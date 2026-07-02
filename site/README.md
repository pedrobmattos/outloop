# Site da campanha — Outloop

Landing page estática da campanha (copy do `docs/04-landing-page.md`), pronta para publicar. Zero dependências, zero build — são só 2 arquivos HTML.

## Antes de publicar — checklist de placeholders

Tudo que precisa ser preenchido está marcado com `TODO` ou `[COLCHETES]` nos arquivos:

1. **`index.html` → `OUTLOOP_CONFIG.whatsappNumber`** (fim do arquivo): trocar `"55SEUNUMERO"` pelo número comercial com DDI+DDD, só dígitos (ex.: `"5516991234567"`). **É o único campo obrigatório** — todos os botões da página apontam para ele.
2. **`index.html` → Open Graph** (`<head>`): trocar `https://SEUDOMINIO` pelo domínio real e gerar a imagem OG 1200×630 no SuperGrok (prompt no `docs/06`).
3. **`index.html` → rodapé**: preencher o CNPJ real; descomentar o link do Instagram quando estiver ativo.
4. **`index.html` → foto do fundador**: trocar o placeholder da seção "Quem constrói é quem atende" por uma foto real (WebP, ~600px de largura).
5. **`privacidade.html`**: preencher CNPJ, e-mail, WhatsApp e a data de publicação.
6. **Rastreamento** (fazer antes do primeiro real de mídia): criar contêiner no [Google Tag Manager](https://tagmanager.google.com), trocar `GTM-XXXXXXX` e **descomentar** os dois blocos do GTM (head e noscript). Dentro do GTM, adicionar Meta Pixel + GA4. Os eventos já são disparados pela página:
   - `Contact` (Meta) com `content_name` = seção do botão, em todo clique de WhatsApp;
   - `whatsapp_click` no dataLayer (usar como gatilho no GTM);
   - `Lead` (Meta) + `lead_form` no envio do formulário.
7. **Formulário (opcional)**: por padrão fica oculto e a página é 100% WhatsApp (recomendado no início). Para ativar, criar um form no [Formspree](https://formspree.io) (grátis) e colar a URL em `OUTLOOP_CONFIG.formEndpoint`.

## Publicar na Vercel (grátis, ~10 min)

1. Criar conta em [vercel.com](https://vercel.com) com o GitHub.
2. **Add New → Project → importar este repositório.**
3. Em *Root Directory*, apontar para `site/`. Framework preset: **Other**. Deploy.
4. **Settings → Domains → adicionar o domínio da Outloop** e seguir as instruções de DNS (apontar o registro `A`/`CNAME` no painel onde o domínio foi comprado).
5. Testar no celular: velocidade, todos os botões abrindo o WhatsApp com a mensagem certa e o token `#origem` no fim.

Alternativas igualmente válidas: Netlify (arrastar a pasta `site/` em app.netlify.com/drop) ou Cloudflare Pages.

## Teste antes de ligar tráfego

- [ ] Abrir no celular (4G, não Wi-Fi) — a página deve carregar em ~2s.
- [ ] Clicar TODOS os botões e conferir a mensagem pré-preenchida + `#origem` de cada um (`#lp-hero`, `#lp-auto`, `#lp-site`, `#lp-sistema`, `#lp-passos`, `#lp-fundador`, `#lp-final`, `#lp-flutuante`).
- [ ] Conferir o evento `Contact` no [Gerenciador de Eventos da Meta](https://business.facebook.com/events_manager) usando a extensão Meta Pixel Helper.
- [ ] Rolar a página: o botão flutuante 💬 deve aparecer depois do hero.
- [ ] Testar o FAQ (abre/fecha) e o link da Política de Privacidade.
