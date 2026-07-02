# Tasklist de Lançamento — Outloop

> **Status (atualizado):** empresa aberta e contador contratado ✔ · landing page da campanha construída em código (pasta `/site`) ✔ · kit de WhatsApp, proposta-modelo, minuta de contrato e planilha de CRM prontos (pasta `/operacional`) ✔ — próximos passos: publicar o site no domínio, configurar WhatsApp Business e Meta Pixel.

Checklist mestre de lançamento da Outloop (estúdio de tecnologia — automação, sites e sistemas sob medida para PMEs de Ribeirão Preto e região). Marque cada item apenas quando estiver **feito e verificável** (documento salvo, conta ativa, campanha publicada, etc.). Prazos são alvo a partir da data de início — se atrasar uma fase, não pule etapas: as fases 0–2 são pré-requisito para ligar tráfego.

---

## Esta semana — as 10 primeiras tarefas, na ordem exata

1. - [ ] Configurar o **WhatsApp Business** no número comercial da Outloop: perfil, saudação, respostas rápidas e as 8 etiquetas — todos os textos prontos para colar em `operacional/whatsapp-kit.md`.
2. - [ ] Definir a identidade visual mínima: logo simples e 2 fontes — a paleta oficial já está fixada em `docs/06` (azul-noite `#0A1826` + verde-loop `#2EE6A0`); salvar tudo em um arquivo de referência único (`brand-outloop`).
3. - [ ] Abrir **conta PJ digital** (Asaas, Inter PJ ou similar) e configurar a ferramenta de cobrança (Asaas: Pix, boleto e recorrência) — criar os planos de mensalidade como cobranças recorrentes desde já.
4. - [ ] Validar com o contador o credenciamento de **NFS-e em Ribeirão Preto** (certificado A1 + ISS.Net) e emitir uma NF de teste.
5. - [ ] Enviar a minuta `operacional/contrato-modelo.md` para **uma revisão única de advogado** e congelar a versão 1.0.
6. - [ ] Preencher os placeholders da **landing page pronta** (checklist em `site/README.md`: número do WhatsApp, CNPJ, foto do fundador) e publicar na Vercel apontando o domínio — a landing pode ser o site v1 na raiz do domínio.
7. - [ ] Instalar **Meta Pixel + GA4 via Google Tag Manager** na landing (blocos já preparados no código) e testar o evento de clique no WhatsApp de ponta a ponta.
8. - [ ] Criar o **Google Business Profile** da Outloop em Ribeirão Preto e enviar a verificação.
9. - [ ] Escrever os 3 **estudos de caso do portfólio** (sistemas da Lokok + projetos pessoais), com autorização por escrito da Lokok para citar nome e números.
10. - [ ] Ensaiar em voz alta o **script de qualificação** e o **roteiro do diagnóstico gratuito** (prontos em `operacional/whatsapp-kit.md` e `docs/07`).

> Regra da semana: nada de tráfego pago antes de os itens 1, 6, 7 e 10 estarem prontos. Anúncio sem funil atrás só queima verba.

---

## Fase 0 — Fundação (semana 1–2)

### Formalização

- [x] Contratar contabilidade online e assinar a proposta de abertura da empresa. *(já feito — empresa aberta e contador contratado)*
- [x] Abrir a empresa optante do Simples Nacional. *(já feito — empresa aberta e contador contratado)*
- [x] Registrar os CNAEs adequados. *(já feito — conferir com o contador se o CNAE principal é o 6201-5/01 e se há os secundários 6204-0/00, 6202-3/00 e 6209-1/00; ajustar é simples se precisar)*
- [ ] Definir com o contador o valor do pró-labore para atingir **Fator R ≥ 28%** (Anexo III), já considerando os 11% de INSS e eventual IRPF na conta líquida.
- [ ] Abrir **conta PJ digital** assim que sair o CNPJ (Asaas, Inter PJ ou similar) e separar 100% das finanças da empresa das pessoais.
- [ ] Comprar **certificado digital A1** (faixa típica de R$ 150–300/ano) após obter CNPJ e inscrição municipal.
- [ ] Credenciar a empresa no sistema de NFS-e de Ribeirão Preto (**ISS.Net / Nota Control**), configurando item 1 da lista de serviços (informática — ISS de 2% pelo Decreto 306/2005, confirmar vigência com o contador), Código de Tributação Nacional e NBS.
- [ ] Emitir **uma NF de teste** (valor simbólico ou cancelável) para validar o credenciamento antes do primeiro cliente real.
- [ ] Configurar ferramenta de cobrança: **Asaas** para boleto/Pix/recorrência (Pix R$ 1,99/transação com 100 gratuitos/mês; cartão 2,99% + R$ 0,49) — criar os planos de mensalidade como cobranças recorrentes desde já.

### Contrato-modelo

- [x] Redigir o contrato-modelo de prestação de serviços com as cláusulas essenciais. *(minuta completa pronta em `operacional/contrato-modelo.md` — escopo/aceite, marcos, pagamento, PI com reserva de componentes próprios, confidencialidade, LGPD, garantia, SLA, limitação de responsabilidade, rescisão e foro)*
- [x] Incluir cláusula de **repasse de custos variáveis** (API de IA, WhatsApp Business API, VPS). *(incluída — cláusula 4.3 da minuta)*
- [ ] Pagar **uma revisão única de advogado** no contrato-modelo e congelar a versão 1.0 para reaproveitar em todos os projetos.
- [x] Criar o anexo padrão de **entrega de documentação e credenciais** ao cliente. *(coberto pelas cláusulas 5.1 e 12.4 e pelo Anexo de Escopo da minuta)*

### Identidade visual mínima

- [ ] Criar logo (versões horizontal, ícone e monocromática) e exportar em PNG/SVG.
- [ ] Definir paleta (2–3 cores) e tipografia (2 fontes) e registrar tudo em um mini-guia de 1 página.
- [ ] Aplicar a identidade em: foto/capa do WhatsApp Business, template de proposta, assinatura de e-mail e avatar do Instagram.

### WhatsApp Business configurado

- [ ] Preencher o perfil comercial completo: nome, descrição ("Automação, sites e sistemas para PMEs de Ribeirão Preto"), endereço/região, horário e link do site.
- [ ] Configurar **mensagem de saudação automática** com a primeira pergunta de qualificação embutida (assim nenhum lead fica sem resposta imediata, mesmo fora do teclado).
- [ ] Criar 6 **respostas rápidas**: /diagnostico (o que é e como agendar), /servicos (3 linhas de serviço), /precos (faixas e "depende do escopo — o diagnóstico define"), /cases (links do portfólio), /proposta (próximos passos), /obrigado (pós-reunião).
- [ ] Criar **etiquetas** de funil espelhando o pipeline canônico do CRM: Lead novo, Qualificado, Diagnóstico agendado, Diagnóstico feito, Proposta enviada, Fechado, Perdido, Indicação/Parceiro.
- [ ] Gerar links **wa.me distintos por canal** (site, landing, Instagram, Google Business, prospecção) com mensagens pré-preenchidas diferentes, para atribuir origem de cada lead.

**Critério de saída da Fase 0:** empresa aberta ✔ (feito), contrato-modelo v1.0 salvo, WhatsApp pronto para receber lead hoje.

---

## Fase 1 — Presença digital (semana 2–3)

### Site institucional (domínio próprio da Outloop)

- [ ] Publicar o site da Outloop no domínio próprio com: home (proposta de valor + 3 serviços), página por serviço (automação / sites / sistemas), portfólio, sobre (Pedro, experiência real em sistemas em produção) e contato via WhatsApp.
- [ ] Escrever a home usando os ângulos obrigatórios da marca: **"Automatize sua empresa"**, **"Pare com tarefas repetitivas"**, **"Tenha o site e o sistema dos seus sonhos"** — tom direto, sem jargão técnico, sem promessas absolutas (usar promessas de processo: "responda clientes em segundos, 24/7").
- [ ] Garantir mobile-first e carregamento rápido (testar no PageSpeed; a maioria dos donos de PME vai abrir pelo celular vindo do Instagram).
- [ ] Publicar em stack gratuita/barata (Vercel/Netlify ou equivalente) — o site é vitrine e prova de competência, não projeto de 3 semanas.

### Landing page da campanha

- [x] Construir a landing com a estrutura completa (hero, dores, serviços, como funciona, prova, fundador, FAQ, CTA final). *(construída — `site/index.html`, com a copy do docs/04; falta publicar no domínio e preencher os placeholders do `site/README.md`)*
- [x] Remover menu de navegação e links externos da landing (uma página, uma ação). *(feito na página construída)*
- [x] Usar **botão de WhatsApp com mensagem pré-preenchida** como CTA principal, com token `#origem` por seção. *(feito — todos os botões configuráveis num único lugar do código)*
- [x] Descrever a oferta de entrada com escopo explícito: **"Diagnóstico gratuito de automação (30 min): mapeamos seus 3 maiores gargalos e você sai com um plano por escrito"**. *(feito — seção "Como funciona" da página)*

### Rastreamento (antes de qualquer anúncio)

- [ ] Instalar **Google Tag Manager** no site e na landing; dentro dele, GA4, Meta Pixel e tag do Google Ads.
- [ ] Configurar a **API de Conversões da Meta** além do Pixel.
- [ ] Criar evento de conversão "clique no botão de WhatsApp" e testar de ponta a ponta (Test Events da Meta + DebugView do GA4).
- [ ] Padronizar **UTMs** em todos os links (anúncio → landing) e manter a tabela de links wa.me por origem.
- [ ] Criar planilha (ou CRM) com campo obrigatório "origem do lead" — sem isso não dá para comparar canais ao fim do teste de 4–8 semanas.

### Instagram profissional

- [ ] Criar/converter o perfil para conta profissional com bio direta (o que faz + para quem + cidade + link com wa.me rastreado).
- [ ] Publicar os **9 posts iniciais**: 3 de dor/solução (um por nicho prioritário: clínica que perde consulta por no-show, imobiliária que demora a responder lead, escritório que cobra documento no braço), 3 de prova (mini-cases Lokok/projetos com número concreto), 1 "quem é a Outloop/Pedro", 1 explicando o diagnóstico gratuito, 1 explicando os 3 serviços.
- [ ] Gravar 1 vídeo curto vertical (9:16, 6–15s) de apresentação com Pedro falando à câmera — o formato autêntico supera produção polida e vira criativo de anúncio depois.
- [ ] Conectar o Instagram à conta do WhatsApp Business (botão de mensagem no perfil).

### Google Business Profile

- [ ] Criar o perfil em Ribeirão Preto com categoria adequada (ex.: "consultor de TI" / "desenvolvedor de software"), área de atendimento (RP + raio ~40km), serviços cadastrados e link wa.me próprio.
- [ ] Concluir a verificação e publicar 3 fotos + 1 post inicial.
- [ ] Pedir as 2–3 primeiras avaliações a contatos profissionais reais (Lokok, colegas que conhecem o trabalho).

### Portfólio

- [ ] Obter **autorização por escrito** da Lokok para citar nome, contexto e resultados dos sistemas internos.
- [ ] Escrever cada case no formato problema → solução → resultado com número (horas/semana economizadas, erros eliminados, tempo de resposta) — sem jargão: "planilha que se atualiza sozinha", não "pipeline ETL".
- [ ] Publicar os cases no site e fixar os posts correspondentes no Instagram.

**Critério de saída da Fase 1:** um desconhecido consegue achar a Outloop no Google, entender o serviço em 30 segundos e chamar no WhatsApp — e você consegue ver de onde ele veio.

---

## Fase 2 — Máquina de vendas (semana 3–4)

### CRM

- [ ] Configurar CRM gratuito (HubSpot free ou planilha estruturada) com as etapas: Lead novo → Qualificado → Diagnóstico agendado → Diagnóstico feito → Proposta enviada → Fechado / Perdido, mais a etiqueta extra "Indicação/Parceiro". *(planilha inicial pronta em `operacional/crm-pipeline.csv` — importar no Google Sheets ou migrar para o HubSpot free antes dos 10 primeiros leads)*
- [ ] Registrar em cada lead: origem (UTM/link wa.me), nicho, tamanho da empresa, dor principal e próximo passo com data.
- [ ] Definir as 3 métricas de funil a acompanhar desde o lead nº 1: **conversa → diagnóstico** (meta: 20–40%), **diagnóstico → proposta**, **proposta → fechamento** (referência de mercado: 15–25% das oportunidades) — ou seja, planejar ~15–40 conversas iniciadas por cliente fechado.

### Script de qualificação no WhatsApp

- [x] Finalizar o script de 4 perguntas: saudação citando a origem → segmento → tamanho/volume → dor principal → urgência e quem decide. *(pronto — `operacional/whatsapp-kit.md`, seção 5)*
- [x] Fechar o script **sempre oferecendo 2 horários concretos** para o diagnóstico. *(incluído no script pronto)*
- [ ] Salvar o script como respostas rápidas no WhatsApp Business para responder em segundos.
- [ ] Definir critério de lead qualificado (empresa com CNPJ ativo, dor clara, decisor na conversa) e o que fazer com desqualificados (etiqueta "futuro" + conteúdo do Instagram).

### Roteiro do diagnóstico gratuito (30 min)

- [x] Escrever o roteiro em blocos: contexto → mapeamento dos 3 maiores gargalos → estimativa de horas → próximos passos. *(roteiro minuto a minuto pronto em `docs/07`, seção 3.2)*
- [ ] Criar o **entregável padrão**: mini-relatório em PDF (1–2 páginas) com os 3 gargalos, estimativa de horas economizadas e recomendação — enviado em até 48h após a reunião.
- [ ] Incluir no roteiro a frase de prova viva: "essa resposta rápida e organizada que você recebeu no WhatsApp é exatamente o que eu monto para a sua empresa".
- [ ] Só recomendar automação de processo que **já funciona manualmente** — se o processo do cliente é bagunçado, a proposta inclui a etapa de arrumar o processo (isso justifica o setup fee e evita projeto fracassado).

### Template de proposta comercial

- [x] Criar template de proposta de 1–2 páginas: resumo do diagnóstico → solução proposta → escopo e prazo → investimento → garantia → próximos passos. *(pronto — `operacional/proposta-modelo.md`, com anexo interno de preços de referência)*
- [ ] Fixar a tabela de preços de referência (camada "resultado", não "commodity"; ajustar por escopo, manter coerência):
  - Automação/atendente IA no WhatsApp: **Essencial R$ 2.500 de setup + R$ 400/mês**, **Operação (atendente IA no WhatsApp) R$ 6.000 + R$ 800/mês**, **Escala R$ 10.000 + R$ 1.400/mês** (abaixo das agências grandes de R$ 8–20 mil + R$ 1,5–3 mil/mês, bem acima do freelancer avulso).
  - Sites: **R$ 4.500** (institucional) / landing page **R$ 2.200 (valor fechado)**, sempre com plano de manutenção/hospedagem de **R$ 200–400/mês** embutido na oferta.
  - Sistemas sob medida (CRM simples, dashboard, portal): **R$ 8.000–35.000** por escopo, com manutenção mensal opcional.
- [ ] Estruturar 3 pacotes de automação (ex.: **Essencial / Operação / Escala**) por número de automações, volume de conversas e SLA — serviço produtizado encurta a venda.
- [ ] Incluir na proposta: garantia explícita (ex.: reembolso do setup se a automação não entrar em produção em X dias), cláusula de repasse de custos de API/VPS, e o bloco "por que um estúdio boutique": acesso direto ao especialista sênior, documentação e credenciais entregues, contrato com PI/LGPD/SLA.

### Criativos (SuperGrok / Grok Imagine)

- [ ] Gerar **10–20 variações de criativo** para a campanha Advantage+ (3–5 por conjunto em campanhas manuais): prioridade para vídeo vertical 9:16 de 6–15s com gancho de dor nos 3 primeiros segundos.
- [ ] Produzir 1 conjunto de criativos por nicho prioritário com dor específica: clínicas ("Sua agenda ainda depende de alguém digitando confirmação?"), imobiliárias ("O lead do portal esperou 2 horas. O concorrente respondeu em 1 minuto."), advocacia/contabilidade ("Quantas horas sua equipe perde cobrando documento de cliente?"), comércio/serviços local ("Cliente no WhatsApp sem resposta é venda perdida").
- [ ] Usar os ângulos da marca nas headlines: "Automatize sua empresa", "Pare com tarefas repetitivas", "Tenha o site e o sistema dos seus sonhos".
- [ ] Gerar estáticos 1:1/4:5 para retargeting.
- [ ] Escrever as copies com **1 único CTA por anúncio** ("Chame no WhatsApp" / "Agende um diagnóstico gratuito") e oferta de valor, não venda direta — diagnóstico gratuito reduz CPL em 40–60% vs pedir a venda no anúncio (estimativa de mercado; validar com nossos dados).

### Campanhas em rascunho

- [ ] Montar no Gerenciador da Meta a campanha **Click-to-WhatsApp** (canal principal): Advantage+ Audience com sinais (lista de contatos, lookalike quando houver), segmentação Ribeirão Preto + raio, exclusão de quem já converteu — salvar em rascunho.
- [ ] Montar campanha Meta secundária de tráfego para a landing (para comparar CPL bruto vs qualificado).
- [ ] Montar no Google Ads a campanha de **Search local**: correspondência de frase/exata em termos de alta intenção ("criação de site para empresa", "automação de processos", "sistema para clínica ribeirão preto", "atendente virtual whatsapp"), localização por **presença** (não interesse), lista de negativação (grátis, curso, vaga, emprego, download) — salvar em rascunho.
- [ ] Validar CPCs reais no **Planejador de Palavras-chave** com geografia local antes de fixar metas (referências de mercado: "criação de sites" R$ 3–10; "automação de processos" R$ 4–12; "sistema para clínica" R$ 5–15; interior tende ao piso).
- [ ] Definir orçamento de validação: **Meta R$ 50–70/dia (R$ 1.500–2.100/mês) + Google Search R$ 30–50/dia (R$ 900–1.500/mês)**, janela de teste de 4–8 semanas; se a verba for curta para os dois, começar só pelo Meta CTWA.
- [ ] Fixar metas de referência com folga (mercado): CPL bruto R$ 15–60; lead qualificado 2–4x isso; primeiras 2 semanas rodam 25–40% mais caras (fase de aprendizado) — **não julgar o canal antes da semana 4**.

**Critério de saída da Fase 2:** se um lead chegar agora, existe script, agenda de diagnóstico, proposta e contrato prontos — e as campanhas estão a um clique de publicar.

---

## Fase 3 — Tráfego ligado (semana 4+)

### Publicação

- [ ] Publicar primeiro a campanha **Meta CTWA**, com rastreamento conferido (lead de teste do próprio celular percorrendo o funil inteiro) — verba inicial de R$ 1.500–2.100/mês somente em Meta Ads.
- [ ] Ativar a campanha **Google Search** (já montada em rascunho) apenas quando a verba total puder atingir R$ 2.400–3.600/mês **ou** no mês 4–6, o que vier primeiro — não publicar os dois canais no mesmo dia.
- [ ] Anotar data de publicação e orçamento no CRM/planilha de métricas — a régua do teste de 4–8 semanas começa aqui.

### Rotina diária (dias úteis, ~45 min + respostas ao longo do dia)

- [ ] Responder **todo lead em menos de 5 minutos em horário comercial** (responder em 5 min aumenta ~21x a chance de qualificar vs 30 min; a média das empresas passa de 24h — a velocidade é a primeira vantagem competitiva da Outloop).
- [ ] Configurar resposta automática do WhatsApp para fora do horário comercial, já com a primeira pergunta de qualificação.
- [ ] Atualizar o CRM ao fim do dia: cada lead com etiqueta, origem e próximo passo datado.
- [ ] Fazer follow-up de leads parados: D+1 e D+3 para quem não respondeu; proposta sem resposta recebe follow-up em 48h e depois em 7 dias.
- [ ] Conferir gasto diário das campanhas (5 min): sem anomalia de gasto, sem anúncio reprovado.

### Rotina semanal de otimização (1 bloco fixo de 1–2h, ex.: sexta de manhã)

- [ ] Registrar na planilha: gasto, leads, CPL bruto, **CPL qualificado** (lead que virou conversa real/diagnóstico), diagnósticos agendados e realizados, propostas, fechamentos — por canal.
- [ ] Pausar criativos com CTR em queda e subir variações novas (em raio local pequeno, a fadiga aparece em 2–4 semanas — manter esteira de criativos no SuperGrok).
- [ ] Comparar Meta vs Google pelo CPL **qualificado**, não pelo bruto; se o WhatsApp encher de curioso, migrar parte da verba para a landing ou ativar formulário de maior intenção.
- [ ] Revisar termos de pesquisa no Google Ads e negativar o que não é comprador.
- [ ] Publicar 2–3 conteúdos no Instagram (1 dor/solução, 1 prova/bastidor, 1 CTA para diagnóstico) e 1 post no Google Business Profile.

### Prospecção ativa paralela (não depender só de anúncio)

- [ ] Montar lista de 100 alvos nos nichos prioritários (clínicas odonto/estética/médicas, advocacia, contabilidade, imobiliárias, comércio local com WhatsApp ativo) usando Google Maps + Instagram + Observatório Sebrae/Econodata por CNAE.
- [ ] Executar **20 abordagens por semana** (WhatsApp/Instagram/e-mail), personalizadas com uma observação real sobre o negócio ("vi que o agendamento de vocês é por DM…") + convite para o diagnóstico gratuito — registrar todas no CRM.
- [ ] Priorizar **imobiliárias enquanto o ciclo está quente** (Ribeirão Preto liderou o estado em lançamentos e vendas em 2025): oferta específica de resposta a lead de portal em menos de 1 minuto + qualificação + follow-up automático.
- [ ] Abordar **escritórios de contabilidade como canal, não só como cliente**: propor automação do onboarding/cobrança de documentos deles + parceria de indicação formal (cada contador atende dezenas de PMEs).
- [ ] Testar parceria com 2–3 agências de marketing locais (nicho de entrada mais fácil do setor: já entendem o valor e indicam os próprios clientes).

### Networking local

- [ ] Associar-se à **ACIRP** e agendar presença em 1 evento da agenda no primeiro mês.
- [ ] Visitar um capítulo **BNI** da região e pleitear a vaga da categoria "automação/IA" (exclusividade por categoria — garantir antes de um concorrente).
- [ ] Acompanhar mensalmente a agenda do **Sebrae-SP Regional Ribeirão Preto** e as **Rodadas de Negócios do CIESP**; inscrever-se na próxima edição disponível.
- [ ] Participar de 1 evento do **Supera Parque** (ex.: Startup Day) para credibilidade técnica e parcerias — lembrando que o diferencial da Outloop vs as ~359 startups regionais é o atendimento local e próximo à PME tradicional.
- [ ] Definir meta de networking verificável: **2 eventos/mês e 5 conversas qualificadas por evento** registradas no CRM.

**Critério de saída da Fase 3:** ao fim de 4–8 semanas, planilha respondendo com dados: CPL por canal, custo por diagnóstico, custo por cliente — e decisão tomada de onde dobrar a verba.

---

## Fase 4 — Entrega e escala (mês 2+)

### Onboarding de cliente (padronizar no 1º cliente)

- [ ] Criar o checklist de onboarding: contrato assinado → pagamento do marco 1 → reunião de kickoff (30 min) → coleta de acessos e materiais (com prazo dado ao cliente) → cronograma com marcos compartilhado → grupo/canal de comunicação definido.
- [ ] Enviar mensagem-padrão de boas-vindas com o que acontece nas próximas 2 semanas e o que a Outloop precisa do cliente até quando.
- [ ] Incluir **treinamento da equipe do cliente** no escopo de toda entrega de automação/sistema (adoção é o que renova mensalidade).

### Checklist de entrega por serviço

- [ ] **Automação/atendente IA:** fluxos testados com casos reais → cliente aprovou em homologação → custos de API/VPS na conta do cliente (ou repasse contratado) → monitoramento de erros configurado → equipe treinada → documentação e credenciais entregues → revisões mensais agendadas nos primeiros 90 dias.
- [ ] **Site/landing:** revisão de conteúdo aprovada pelo cliente → mobile e velocidade testados → domínio, SSL e e-mail configurados → GA4/Pixel instalados → tutorial curto de edição gravado → plano de manutenção mensal ativado na cobrança recorrente.
- [ ] **Sistema sob medida:** critérios de aceite do contrato verificados um a um com o cliente → dados migrados e conferidos → usuários criados e treinados → backup automático ativo → documentação entregue → termo de aceite assinado → oferta de manutenção mensal formalizada.

### Depoimento e indicação (embutir no processo, não deixar para "quando der")

- [ ] Pedir **depoimento com nome, empresa e número concreto** entre 2 e 4 semanas após a entrega, quando o resultado já é visível ("economizamos X horas/semana", "respondemos em segundos") — modelo de 3 perguntas pronto para facilitar.
- [ ] Transformar cada projeto entregue em case no site + post no Instagram (com autorização).
- [ ] Pedir 1–2 indicações a todo cliente satisfeito, com mensagem-padrão; avaliar recompensa de indicação (ex.: desconto na mensalidade).
- [ ] Pedir avaliação no Google Business Profile a todo cliente entregue.

### Revisão mensal (bloco fixo de 2h, todo início de mês)

- [ ] Revisar o funil completo do mês: investimento total, leads, CPL qualificado, diagnósticos, propostas, taxa de fechamento, ticket médio, **MRR** e churn de mensalidades.
- [ ] Comparar as taxas reais com as referências (conversa→diagnóstico 20–40%; proposta→fechamento 15–25%) e atacar **o pior gargalo** do funil no mês seguinte — um por vez.
- [ ] Revisar preços: se a taxa de fechamento passar de ~40–50% com agenda cheia, subir preço/setup no próximo pacote; medir também horas gastas por entrega vs valor cobrado.
- [ ] Revisar mix de serviços: qual linha traz mais MRR por hora trabalhada — priorizar automação com mensalidade (é o que diferencia estúdio de freelancer e valoriza o negócio).
- [ ] Decidir realocação de verba de tráfego com base no custo por cliente por canal (não por lead).
- [ ] Verificar com o contador: faturamento acumulado vs faixas do Simples, Fator R do trimestre e novidades da Reforma Tributária (transição IBS/CBS a partir de 2026).
- [ ] Planejar a evolução do stack conforme volume de leads: fase manual (0–10 leads/mês) → **Typebot + Evolution API em VPS (~R$ 30–60/mês)** para qualificação 24/7 (10–50/mês) → CRM com inbox WhatsApp integrado (50+/mês) — usar a própria automação como vitrine de venda.
- [ ] Revisar a lista de nichos: dobrar esforço no nicho com melhor taxa de fechamento e criar o **pacote produtizado do nicho campeão** (ex.: clínicas — confirmação de consulta + redução de no-show + agenda, preço fixo publicado).
- [ ] Agendar (trimestral): visita de prospecção a feiras e eventos do agro da região mirando a **Agrishow 2027** como território de prospecção B2B (revendas e serviços agro precisam de CRM, orçamento e pós-venda automatizados — ir como comprador/networker, não como expositor).

**Critério de saída da Fase 4 (contínua):** todo cliente entregue vira case + depoimento + indicação, e a revisão mensal decide preço, verba e nicho com base em número, não em achismo.

---

## Painel de metas de referência (colar na parede)

| Indicador | Faixa-alvo (referência de mercado) |
|---|---|
| CPL bruto (Meta CTWA) | R$ 15–60 |
| CPL qualificado | 2–4x o CPL bruto |
| Conversa → diagnóstico | 20–40% |
| Proposta → fechamento | 15–25% |
| Conversas por cliente fechado | ~15–40 |
| SLA de resposta a lead | < 5 min (horário comercial) |
| Orçamento de teste | Meta R$ 1.500–2.100/mês + Google R$ 900–1.500/mês, por 4–8 semanas |
| Prospecção ativa | 20 abordagens/semana |
| Networking | 2 eventos/mês |

*Faixas baseadas em benchmarks públicos 2025/2026 — validar com os números reais da Outloop a partir da semana 4 e substituir esta tabela pelos seus próprios dados na primeira revisão mensal.*