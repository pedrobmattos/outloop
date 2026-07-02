# Criativos — Prompts para SuperGrok (Grok Imagine) | Outloop

Documento de trabalho para geração dos criativos de anúncio (Meta Ads) da Outloop no SuperGrok. Regra de ouro: **a IA gera a cena, nunca o texto** — headlines e CTAs entram depois no Canva/CapCut. Cada criativo abaixo já vem com prompt pronto (em inglês), nota em PT do que ele é, headline de sobreposição e CTA do anúncio correspondente.

---

## 1. Diretrizes visuais da marca

### Paleta oficial Outloop (fixar em todos os criativos)

| Cor | Hex | Uso |
|---|---|---|
| **Azul-noite** | `#0A1826` | Cor primária: fundos, blocos de texto, barra de logo |
| **Verde-loop (neon)** | `#2EE6A0` | Cor de destaque: CTA, ícones, detalhes de luz na cena, sublinhados |
| **Branco-gelo** | `#F4F7F9` | Texto sobre azul, fundos claros alternativos |
| **Grafite** | `#3A4654` | Texto secundário, legendas |
| **Âmbar de alerta** | `#FFB84D` | Uso pontual: só em criativos de "dor" (planilha, papel, caos) |

Regras de aplicação:
- **Headline**: sempre Branco-gelo sobre faixa/bloco Azul-noite, ou Azul-noite sobre área clara da foto. Nunca verde-neon em texto longo (só em 1–2 palavras de destaque).
- **CTA no criativo**: botão/pílula Verde-loop com texto Azul-noite. Um único CTA por peça.
- **Tipografia sugerida** (aplicada no Canva, não na IA): título em *Inter Bold* ou *Poppins SemiBold*; apoio em *Inter Regular*. Não usar mais de 2 pesos por peça.
- **Logo/assinatura**: "outloop" em minúsculas no rodapé ou canto superior, pequeno, sempre no mesmo canto em toda a campanha.

### Estilo visual (o que TODA imagem precisa parecer)

- **Brasileiro de verdade**: pessoas com fenótipos brasileiros diversos (pele parda, negra, branca), roupas de trabalho reais (jaleco, camisa social sem gravata, uniforme de loja), ambientes de PME do interior — recepção de clínica compacta, escritório com ar-condicionado de parede, balcão de loja de rua. **Nada de escritório corporativo gringo de vidro, nada de modelo de banco de imagem sorrindo para a câmera.**
- **Clean e moderno**: composição respirada, poucas cores por cena, luz natural ou luz de tela; toques sutis de verde-neon na iluminação (tela, LED, detalhe) para amarrar a paleta.
- **Fotografia realista** como padrão; cenas conceituais (antes/depois, papel vs. dashboard) podem ser estilizadas, mas nunca cartunescas.
- **Sem texto gerado pela IA**: todo prompt inclui instrução explícita de "no text, no letters, no logos". Telas de computador/celular devem mostrar interfaces genéricas desfocadas ou abstratas.
- **Área limpa para texto**: todo prompt reserva ~1/3 da composição (topo ou base) com fundo simples para a headline.

### Consistência entre criativos

- Repetir a mesma "receita de luz" (luz natural lateral + brilho esverdeado sutil de tela) em todas as fotos da mesma campanha.
- Gerar 3–4 variações de cada prompt e escolher a melhor; manter as pessoas/ambientes coerentes dentro do mesmo conjunto de anúncios.
- Meta pede volume: alvo de **3–5 criativos ativos por conjunto**, trocando quando o CTR cair (fadiga em 2–4 semanas em raio local).

---

## 2. Prompts de IMAGEM (12 — copiar e colar no SuperGrok)

> Formato: 4:5 para feed (padrão), 1:1 para variação de retargeting. Onde o Grok não aceitar proporção no prompt, gerar em 4:5 pelo seletor e manter a instrução de espaço negativo.

### ÂNGULO A — "Automatize sua empresa" (foco: operação rodando sozinha, 24/7)

**IMG-01 — Recepção de clínica com atendimento automático** *(nicho: clínicas)*
> O que é: recepcionista tranquila enquanto o WhatsApp da clínica "se responde sozinho" — a cena vende paz operacional.

```
Realistic editorial photograph, Brazilian dental clinic reception in a mid-size Brazilian city, a Black Brazilian woman receptionist in light blue scrubs smiling calmly while organizing patient files, a smartphone on the counter glowing with a soft green notification light, modern compact clinic interior with white and mint-green tones, natural window light from the left mixed with subtle teal screen glow, shallow depth of field, shot on 50mm lens, candid documentary style, no text, no letters, no logos anywhere, clean uncluttered upper third of the frame with plain wall for text overlay, 4:5 vertical composition
```

- **Headline sobreposta:** "Sua clínica respondendo em segundos. 24/7."
- **Apoio (opcional, menor):** "Agendamento e confirmação no WhatsApp, no automático."
- **CTA do anúncio:** Enviar mensagem (Campanha 1 — Click-to-WhatsApp)
- **Formato:** 4:5 feed (gerar variação 1:1 para retargeting — no remarketing, botão "Fale conosco", Campanha 3)

**IMG-02 — Corretor de imobiliária com lead respondido na hora** *(nicho: imobiliárias)*
> O que é: corretor em movimento, celular respondendo lead de portal sozinho — velocidade de resposta como argumento.

```
Realistic photograph, Brazilian real estate agent, man in his 30s with light brown skin, casual social shirt, walking through a bright new apartment with boxes of keys in hand, holding a smartphone showing a blurred chat interface with a green glow, apartment interior in São Paulo countryside style, late afternoon golden natural light through large window, energetic candid moment, documentary photography style, 35mm lens, no text, no letters, no watermarks, plenty of clean negative space on the plain white wall at the top of the frame for headline overlay, 4:5 vertical composition
```

- **Headline:** "Lead do portal respondido em menos de 1 minuto."
- **Apoio:** "Enquanto o concorrente demora, você já agendou a visita."
- **CTA:** Enviar mensagem (Campanha 1 — Click-to-WhatsApp)
- **Anúncio correspondente:** Anúncio 7 da Campanha 1 (CTWA, botão "Enviar mensagem") — gancho: "O lead do portal esperou 2 horas. O concorrente respondeu em 1 minuto."
- **Formato:** 4:5 feed

**IMG-03 — Conceitual: papel vs. dashboard (antes/depois)** *(uso: todos os nichos)*
> O que é: imagem dividida — caos de papel de um lado, tela limpa com gráficos do outro. Criativo conceitual forte para parar o scroll.

```
Conceptual split-composition photograph, left half: messy stack of paper invoices, sticky notes and a worn spiral notebook on an old office desk under dull warm light; right half: the same desk transformed, minimal and clean, with a laptop showing an abstract blurred analytics dashboard glowing in teal-green tones, dark navy blue ambient background, dramatic contrast between chaos and order, high-end product photography lighting, sharp details, no text, no letters, no numbers, no logos, clean dark band across the top of the frame for text overlay, 1:1 square composition
```

- **Headline:** "Automatize sua empresa."
- **Apoio:** "Do papel ao painel: processos rodando sozinhos."
- **CTA:** Enviar mensagem (Campanha 1 — Click-to-WhatsApp)
- **Formato:** 1:1 (gerar variação 4:5)

**IMG-04 — Dono de comércio local vendo o negócio rodar** *(nicho: comércio/serviços)*
> O que é: dono de loja de rua brasileiro, fim de dia, conferindo no tablet as vendas/atendimentos que aconteceram sem ele digitar nada.

```
Realistic photograph, Brazilian small business owner, man in his 40s with graying hair, wearing a polo shirt, standing behind the counter of a typical Brazilian neighborhood store, relaxed confident posture, holding a tablet with a blurred abstract sales dashboard glowing softly green, shelves with generic unbranded products in the background softly out of focus, warm end-of-day natural light mixed with cool screen glow, documentary lifestyle photography, 35mm lens, no text, no letters, no brand names, no logos, clean and simple lower third of the frame for text overlay, 4:5 vertical composition
```

- **Headline:** "Sua empresa funcionando, mesmo quando você não está."
- **Apoio:** "Cobrança, agenda e atendimento no automático."
- **CTA:** Enviar mensagem (Campanha 1 — Click-to-WhatsApp)
- **Formato:** 4:5 feed

### ÂNGULO B — "Pare com tarefas repetitivas" (foco: dor do trabalho manual)

**IMG-05 — Dono de PME afogado em planilhas à noite** *(uso: geral — a dor universal)*
> O que é: a cena de dor clássica — empresário sozinho no escritório, de noite, digitando planilha. É o criativo de "gancho de dor" principal.

```
Cinematic realistic photograph, tired Brazilian small business owner, woman in her late 30s with brown skin, sitting alone at her desk at night in a small real Brazilian office, face lit only by the cold glow of a laptop screen showing a blurred spreadsheet, coffee mug and scattered papers around, dark moody ambience with deep navy blue shadows, subtle amber desk lamp in background, emotional documentary style, shallow depth of field, 50mm lens, no text, no letters, no logos, dark clean area at the top of the frame for text overlay, 4:5 vertical composition
```

- **Headline:** "Quantas horas da sua semana morrem em planilha?"
- **Apoio:** "Pare com tarefas repetitivas. Automatize."
- **CTA:** Enviar mensagem (Campanha 1 — Click-to-WhatsApp)
- **Formato:** 4:5 feed

**IMG-06 — Advogado/contador soterrado de documentos** *(nicho: advocacia/contabilidade)*
> O que é: profissional liberal cercado de pastas e papel, cobrando documento de cliente manualmente — dor direta do nicho.

```
Realistic photograph, Brazilian lawyer or accountant, man in his 40s wearing a social shirt with rolled-up sleeves, at a traditional law office desk stacked with paper folders and document piles, rubbing his forehead while looking at his phone, bookshelves with generic books in background, warm tungsten office light with a hint of cool daylight from a window, honest tired expression, editorial documentary style, 35mm lens, no text, no readable documents, no letters, no logos, clean neutral wall space in the upper portion of the frame for text overlay, 4:5 vertical composition
```

- **Headline:** "Cobrar documento de cliente não é trabalho de advogado."
- **Apoio:** "A gente automatiza. Você advoga."
- **CTA:** Enviar mensagem (Campanha 1 — Click-to-WhatsApp)
- **Formato:** 4:5 feed (variação para contabilidade: trocar "lawyer" por "accountant" e headline por "Cobrar documento de cliente não é trabalho de contador.")

**IMG-07 — Conceitual: esteira de tarefas repetitivas** *(uso: geral)*
> O que é: metáfora visual — dezenas de post-its e papéis idênticos formando um loop infinito, com um único fluxo verde limpo cortando o caos.

```
Conceptual studio photograph, dozens of identical yellow sticky notes and repeated paper forms arranged in a spiraling endless loop pattern on a dark navy blue surface, one clean glowing teal-green light path cutting straight through the center of the chaos, dramatic top-down flat lay composition, high contrast studio lighting, minimalist and modern, premium advertising photography, no text, no letters, no numbers on the notes, no logos, clean dark space at the bottom third for text overlay, 1:1 square composition
```

- **Headline:** "Pare com tarefas repetitivas."
- **Apoio:** "Um fluxo automático resolve o que hoje toma sua semana."
- **CTA:** Enviar mensagem (Campanha 1 — Click-to-WhatsApp)
- **Formato:** 1:1 (bom para retargeting — nesse uso, botão "Fale conosco", Campanha 3)

**IMG-08 — Recepcionista confirmando consulta uma a uma** *(nicho: clínicas)*
> O que é: a dor específica da clínica — recepcionista ao telefone, agenda de papel aberta, fila de pacientes esperando. Contraponto do IMG-01.

```
Realistic photograph, overwhelmed Brazilian clinic receptionist, young woman in white uniform holding a landline phone between shoulder and ear while writing in a large paper appointment book, small line of patients waiting slightly out of focus in the background, compact aesthetic clinic reception in Brazil, fluorescent mixed with natural light, slightly tense candid moment, documentary photography style, 35mm lens, no text, no readable writing, no letters, no logos, clean light wall area in the upper third for text overlay, 4:5 vertical composition
```

- **Headline:** "Confirmar consulta uma por uma? Em 2026?"
- **Apoio:** "Confirmação automática no WhatsApp reduz falta e libera sua recepção."
- **CTA:** Enviar mensagem (Campanha 1 — Click-to-WhatsApp)
- **Formato:** 4:5 feed

### ÂNGULO C — "Tenha o site e o sistema dos seus sonhos" (foco: aspiração/profissionalização)

**IMG-09 — Site novo abrindo no laptop (hero aspiracional)** *(uso: linha de sites)*
> O que é: cena de produto — laptop em mesa bonita exibindo um site elegante (abstrato/desfocado), estética premium. Criativo "de desejo".

```
Premium product photography, sleek modern laptop on a clean wooden desk in a bright Brazilian coworking space, screen showing an elegant abstract minimalist website layout with dark navy and teal-green accents, slightly blurred so no text is readable, small potted plant and ceramic coffee cup beside it, soft morning natural light with gentle reflections, shallow depth of field, aspirational and clean aesthetic, 50mm lens, no readable text, no letters, no logos, generous clean negative space above the laptop for headline overlay, 4:5 vertical composition
```

- **Headline:** "Tenha o site dos seus sonhos."
- **Apoio:** "Profissional, rápido e pronto para vender."
- **CTA:** "Saiba mais" ou "Fale conosco" (Campanha 2 — landing page)
- **Formato:** 4:5 feed

**IMG-10 — Dona de clínica de estética orgulhosa do site novo** *(nicho: clínicas/estética)*
> O que é: emoção de conquista — a dona vendo o próprio site no celular e sorrindo. Vende o sentimento de "minha empresa parece grande".

```
Realistic lifestyle photograph, proud Brazilian aesthetic clinic owner, woman in her 30s with curly dark hair wearing an elegant white clinic coat, sitting in her beautifully decorated clinic looking at her smartphone with a genuine delighted smile, phone screen glowing softly with a blurred elegant website in teal and white tones, modern Brazilian clinic interior with plants and warm minimal decor, soft golden hour window light, authentic candid emotion, editorial photography, 50mm lens, no text, no letters, no logos, clean softly blurred background area at the top for text overlay, 4:5 vertical composition
```

- **Headline:** "A cara da sua clínica, finalmente à altura do seu trabalho."
- **Apoio:** "Site profissional com entrega rápida."
- **CTA:** "Saiba mais" ou "Fale conosco" (Campanha 2 — landing page)
- **Formato:** 4:5 feed

**IMG-11 — Equipe pequena em volta do sistema sob medida** *(uso: linha de sistemas/CRM)*
> O que é: 2–3 pessoas de uma PME olhando juntas um dashboard/CRM no monitor — vende o "sistema feito para o meu jeito de trabalhar".

```
Realistic photograph, small Brazilian business team of three diverse people (one Black woman, one white man, one brown-skinned man) gathered around a desktop monitor in a modest real office in the Brazilian countryside, pointing at a blurred abstract CRM dashboard with navy blue interface and green data highlights, engaged positive expressions, everyday work clothes, natural daylight from office window mixed with screen glow, collaborative candid moment, documentary style, 35mm lens, no readable text, no letters, no logos, clean wall space in the upper third for headline overlay, 4:5 vertical composition
```

- **Headline:** "Um sistema do jeito que a SUA empresa trabalha."
- **Apoio:** "CRM, painel e portal sob medida — sem pagar por função que você não usa."
- **CTA:** "Saiba mais" ou "Fale conosco" (Campanha 2 — landing page)
- **Formato:** 4:5 feed

**IMG-12 — Conceitual: antes/depois da presença digital** *(uso: linha de sites)*
> O que é: split conceitual — de um lado um celular com "site" datado e escuro; do outro, o mesmo celular com layout limpo e moderno brilhando. Antes/depois sem precisar de cliente real.

```
Conceptual split-composition product photograph, two identical smartphones side by side on a dark navy blue studio surface: the left phone showing a dull, cluttered, outdated abstract webpage layout in gray tones with a cracked dusty feel; the right phone showing a bright, elegant, modern abstract webpage layout in white with teal-green accents, glowing softly like a premium device ad, dramatic studio lighting with strong contrast between the two sides, high-end minimalist advertising photography, no readable text, no letters, no logos, clean dark band at the top of the frame for text overlay, 1:1 square composition
```

- **Headline:** "Seu site hoje ⟶ Seu site com a Outloop."
- **Apoio:** "Entrega rápida, projeto fechado."
- **CTA:** "Saiba mais" ou "Fale conosco" (Campanha 2 — landing page)
- **Formato:** 1:1 (variação 4:5 para feed)

---

## 3. Prompts de VÍDEO curto (6–15s, Reels/Stories 9:16)

> No Grok Imagine, o caminho mais controlável é **imagem→vídeo**: gere primeiro o frame com o prompt de imagem correspondente (adaptado para 9:16) e anime com o prompt de movimento. Alternativa texto→vídeo indicada em cada um. Todos pensados para **loop** (fim parecido com o começo) e **gancho visual nos 3 primeiros segundos**.

### Ângulo A — "Automatize sua empresa"

**VID-01 — Recepção de clínica: mensagens se respondendo sozinhas** *(base: IMG-01 em 9:16)*
> O que é: o celular no balcão recebe notificações e elas "se resolvem" com brilhos verdes, enquanto a recepcionista trabalha tranquila. Prova visual do atendimento 24/7.

```
Animate this scene: slow cinematic push-in toward the smartphone on the clinic reception counter, soft green notification glows pulse on the phone screen one after another and gently fade as if being answered instantly, the receptionist in the background calmly organizes files and smiles slightly, subtle dust particles in the window light, smooth stabilized camera movement, 8 seconds, seamless loop, vertical 9:16, realistic cinematic style, no text on screen
```

- **Duração alvo:** 8s | **Gancho (0–3s):** notificações pulsando em close
- **Texto sobreposto (CapCut):** 0–3s "Sua clínica respondendo em segundos" → 3–6s "Agendamento e confirmação no automático" → 6–8s CTA
- **CTA:** Enviar mensagem (Campanha 1 — Click-to-WhatsApp)

**VID-02 — Conceitual: caos vira painel (transformação)** *(texto→vídeo)*
> O que é: pilha de papéis é "varrida" da mesa e no lugar acende um dashboard limpo — a promessa "automatize sua empresa" em 10 segundos.

```
Cinematic vertical video: a cluttered office desk covered with paper invoices and sticky notes under dull warm light; a smooth gust of motion sweeps the papers away in slow motion; as the desk clears, a laptop screen lights up revealing an abstract glowing analytics dashboard in teal-green on dark navy, camera slowly orbits 20 degrees around the desk, dramatic lighting shift from warm chaos to cool clean tech ambience, 10 seconds, ends on the clean desk composition similar to a loop point, vertical 9:16, premium ad style, photorealistic, no text, no letters, no logos
```

- **Duração alvo:** 10s | **Gancho:** papéis voando em slow motion
- **Texto sobreposto:** 0–3s "Sua operação hoje" → 4–7s "Sua operação com a Outloop" → 8–10s CTA
- **CTA:** Enviar mensagem (Campanha 1 — Click-to-WhatsApp)

### Ângulo B — "Pare com tarefas repetitivas"

**VID-03 — Time-lapse do dono preso na planilha** *(base: IMG-05 em 9:16)*
> O que é: dia vira noite na janela enquanto a empresária digita a mesma planilha — o tempo passa, a tarefa não acaba. Dor pura, altíssimo stop-scroll.

```
Animate this scene as a time-lapse: the Brazilian business owner keeps typing at her desk while the window light behind her shifts rapidly from bright afternoon to deep night, the laptop glow becomes the only light source, papers accumulate slightly on the desk, she pauses and rubs her eyes at the end, subtle camera slow zoom-in throughout, melancholic cinematic mood, 12 seconds, vertical 9:16, photorealistic, no text on screen
```

- **Duração alvo:** 12s | **Gancho:** luz do dia "correndo" na janela
- **Texto sobreposto:** 0–3s "Quantas horas por semana você perde nisso?" → 4–8s "Sua semana tem horas demais no manual." → 9–12s "Pare. Automatize." + CTA
- **CTA:** Enviar mensagem (Campanha 1 — Click-to-WhatsApp)

**VID-04 — Loop infinito de post-its quebrado pelo fluxo verde** *(base: IMG-07 em 9:16)*
> O que é: animação conceitual — o espiral de post-its gira sem fim até um traço de luz verde cortar o caos e organizar tudo. Loop perfeito para Stories.

```
Animate this conceptual scene: the spiral of identical sticky notes slowly rotates like an endless loop on the dark navy surface, top-down camera holds steady, then a bright teal-green light path traces through the center in one smooth continuous stroke, the sticky notes along its path elegantly flip and align into a clean straight row, the rotation calms to stillness, then the cycle subtly restarts, seamless loop, 8 seconds, vertical 9:16, premium minimalist motion design feel, photorealistic materials, no text, no letters
```

- **Duração alvo:** 8s (loop) | **Gancho:** espiral hipnótico girando
- **Texto sobreposto:** 0–3s "Tarefa repetitiva não acaba sozinha." → 4–8s "A gente faz ela acabar." + CTA
- **CTA:** Enviar mensagem (Campanha 1 — Click-to-WhatsApp)

### Ângulo C — "Tenha o site e o sistema dos seus sonhos"

**VID-05 — Reveal do site: laptop abre, site desliza** *(base: IMG-09 em 9:16)*
> O que é: vídeo "de produto" — o laptop abre e um site elegante rola suavemente na tela, com dolly lento. Estética premium para a linha de sites.

```
Animate this scene: the laptop lid opens smoothly revealing an elegant abstract website that scrolls slowly and continuously down the screen, dark navy and teal-green design elements gliding by (all content abstract and unreadable), slow cinematic dolly from left to right around the desk, soft morning light with gentle screen reflections on the wooden surface, calm premium mood, 10 seconds, ends framed like the opening shot for a soft loop, vertical 9:16, photorealistic, no readable text, no logos
```

- **Duração alvo:** 10s | **Gancho:** laptop abrindo com a tela acendendo
- **Texto sobreposto:** 0–3s "O site dos seus sonhos" → 4–7s "Profissional. Rápido. Pronto para vender." → 8–10s CTA
- **CTA:** "Saiba mais" ou "Fale conosco" (Campanha 2 — landing page)

**VID-06 — Antes/depois no celular: swipe de transformação** *(base: IMG-12 em 9:16, texto→vídeo alternativo)*
> O que é: um celular na mão; um deslizar de dedo troca o "site velho" pelo site novo brilhante. Formato nativo de Reels, fácil de entender sem som.

```
Cinematic vertical video: close-up of a Brazilian hand holding a smartphone against a dark navy studio background; the screen shows a dull cluttered outdated abstract webpage; the thumb swipes left and the screen transforms into a bright elegant modern abstract webpage with teal-green accents, a soft glow pulse marks the transformation, slight handheld camera feel for authenticity, the swipe gesture repeats as a natural loop, 7 seconds, vertical 9:16, photorealistic, premium device-ad lighting, no readable text, no letters, no logos
```

- **Duração alvo:** 7s (loop no gesto de swipe) | **Gancho:** o swipe de transformação
- **Texto sobreposto:** 0–3s "Seu site hoje" → no swipe: "Seu site com a Outloop" → 5–7s CTA
- **CTA:** "Saiba mais" ou "Fale conosco" (Campanha 2 — landing page)

> **Complemento recomendado (fora do Grok):** gravar 2–3 vídeos do próprio Pedro falando à câmera (celular, 9:16, 10–15s, gancho de dor nos 3 primeiros segundos) — pela pesquisa, estilo autêntico "dono/especialista" tende a superar produção polida em engajamento (estimativa de mercado na faixa de 20–30%, não uma métrica garantida). Os vídeos de IA acima são o volume; o rosto do fundador é a conversão.

---

## 4. Tabela-resumo: criativo → headline → CTA

| ID | Ângulo | Nicho/uso | Headline | CTA |
|---|---|---|---|---|
| IMG-01 | Automatize | Clínicas | Sua clínica respondendo em segundos. 24/7. | Enviar mensagem (Campanha 1) |
| IMG-02 | Automatize | Imobiliárias | Lead do portal respondido em menos de 1 minuto. | Enviar mensagem (Anúncio 7, Campanha 1) |
| IMG-03 | Automatize | Geral (conceitual) | Automatize sua empresa. | Enviar mensagem (Campanha 1) |
| IMG-04 | Automatize | Comércio local | Sua empresa funcionando, mesmo quando você não está. | Enviar mensagem (Campanha 1) |
| IMG-05 | Tarefas repetitivas | Geral (dor) | Quantas horas da sua semana morrem em planilha? | Enviar mensagem (Campanha 1) |
| IMG-06 | Tarefas repetitivas | Advocacia/contábil | Cobrar documento de cliente não é trabalho de advogado. | Enviar mensagem (Campanha 1) |
| IMG-07 | Tarefas repetitivas | Geral (conceitual) | Pare com tarefas repetitivas. | Enviar mensagem (Campanha 1); retargeting: Fale conosco (Campanha 3) |
| IMG-08 | Tarefas repetitivas | Clínicas | Confirmar consulta uma por uma? Em 2026? | Enviar mensagem (Campanha 1) |
| IMG-09 | Site/sistema dos sonhos | Sites | Tenha o site dos seus sonhos. | Saiba mais / Fale conosco (Campanha 2) |
| IMG-10 | Site/sistema dos sonhos | Clínicas/estética | A cara da sua clínica, finalmente à altura do seu trabalho. | Saiba mais / Fale conosco (Campanha 2) |
| IMG-11 | Site/sistema dos sonhos | Sistemas/CRM | Um sistema do jeito que a SUA empresa trabalha. | Saiba mais / Fale conosco (Campanha 2) |
| IMG-12 | Site/sistema dos sonhos | Sites (conceitual) | Seu site hoje ⟶ Seu site com a Outloop. | Saiba mais / Fale conosco (Campanha 2) |
| VID-01 | Automatize | Clínicas | Sua clínica respondendo em segundos | Enviar mensagem (Campanha 1) |
| VID-02 | Automatize | Geral | Sua operação com a Outloop | Enviar mensagem (Campanha 1) |
| VID-03 | Tarefas repetitivas | Geral (dor) | Quantas horas por semana você perde nisso? | Enviar mensagem (Campanha 1) |
| VID-04 | Tarefas repetitivas | Geral (conceitual) | Tarefa repetitiva não acaba sozinha. | Enviar mensagem (Campanha 1) |
| VID-05 | Site/sistema dos sonhos | Sites | O site dos seus sonhos | Saiba mais / Fale conosco (Campanha 2) |
| VID-06 | Site/sistema dos sonhos | Sites | Seu site hoje → com a Outloop | Saiba mais / Fale conosco (Campanha 2) |

Observações de uso (botões reais do Meta Ads, conforme docs/05-trafego-pago.md):
- Criativos de automação/tarefas repetitivas → **Campanha 1 Click-to-WhatsApp**, botão "Enviar mensagem", com mensagem pré-preenchida ("Quero o diagnóstico gratuito de automação"). Automação NÃO passa por landing page: é CTWA direto para o WhatsApp.
- Criativos de sites/sistemas sob medida ("site e sistema dos seus sonhos") → **Campanha 2** (tráfego para landing page da Outloop com botão de WhatsApp acima da dobra), botões "Saiba mais" ou "Fale conosco".
- Criativos/variações de retargeting → **Campanha 3** (remarketing), botão "Fale conosco".
- Nunca prometer resultado absoluto na headline (nada de "dobre seu faturamento"); manter promessas de processo, como nas headlines acima.
- Para adaptar um prompt a outro nicho, troque apenas o cenário e a profissão (ex.: em IMG-06, "lawyer" → "accountant"; em IMG-01, "dental clinic" → "aesthetic clinic") e mantenha luz, paleta e composição.

---

## 5. Checklist de qualidade antes de publicar

**Na geração (SuperGrok):**
- [ ] A imagem NÃO contém texto, letras, números ou logos gerados pela IA (inclusive em telas, papéis e placas — olhar com zoom). Se contiver, regenerar ou limpar no editor.
- [ ] Mãos, dentes e olhos das pessoas estão anatomicamente corretos (pontos fracos clássicos de IA).
- [ ] A pessoa e o ambiente parecem brasileiros e de PME real — se saiu "escritório de vidro gringo", regenerar reforçando "Brazilian", "modest real office".
- [ ] Existe área limpa de pelo menos 1/3 da imagem para a headline (topo ou base, conforme o prompt).
- [ ] Tons da cena conversam com a paleta (azul-noite/verde nas luzes de tela; âmbar só nos criativos de dor).

**Na montagem (Canva/CapCut):**
- [ ] Headline legível em tela de celular a 1 metro de distância (teste real: olhar no próprio celular, não no monitor).
- [ ] Texto ocupa no máximo ~20% da área da peça (zona segura de texto — melhora entrega no Meta).
- [ ] Um único CTA por peça, em pílula verde-loop `#2EE6A0` com texto azul-noite.
- [ ] Logo "outloop" pequeno, sempre no mesmo canto.
- [ ] Em vídeo: gancho visual + primeira linha de texto nos 3 primeiros segundos; legendas embutidas (maioria assiste sem som); duração 6–15s.
- [ ] Em Stories/Reels 9:16: nada de texto nos 14% superiores e 20% inferiores (área coberta por UI do Instagram).

**Proporções por posicionamento:**
- [ ] Feed (Facebook/Instagram): **4:5** (1080×1350)
- [ ] Stories/Reels: **9:16** (1080×1920)
- [ ] Retargeting/quadrado opcional: **1:1** (1080×1080)
- [ ] Nunca subir 9:16 esticado no feed nem 4:5 no Stories — exportar versão por posicionamento.

**Antes de ativar a campanha:**
- [ ] 3–5 variações de criativo por conjunto de anúncios.
- [ ] Link do anúncio com UTM / link wa.me exclusivo por criativo (atribuição).
- [ ] Headline do criativo coerente com a primeira dobra da landing (mesma promessa, mesmas palavras).
- [ ] Anotar ID do criativo na planilha de controle (ver seção 6) com data de ativação — revisar CTR/fadiga a cada 2 semanas.

---

## 6. Convenção de nomes de arquivo

**Padrão:**

```
OUT-[TIPO]-[ANGULO]-[CENA/NICHO]-[PROPORCAO]-v[N].[ext]
```

**Códigos fixos:**

| Campo | Valores |
|---|---|
| TIPO | `IMG` (imagem) / `VID` (vídeo) |
| ANGULO | `automatize` / `repetitivas` / `sonhos` |
| CENA/NICHO | `clinica`, `imob`, `adv`, `contab`, `comercio`, `conceito-papel`, `conceito-loop`, `site-laptop`, `site-swipe`, `crm-equipe`, `dono-planilha` (curto, sem acento, hífen entre palavras) |
| PROPORCAO | `45` (4:5) / `916` (9:16) / `11` (1:1) |
| vN | versão do criativo (`v1`, `v2`...) — nova versão a cada regeneração/ajuste relevante |

**Exemplos aplicados a este documento:**

- `OUT-IMG-automatize-clinica-45-v1.png` (IMG-01)
- `OUT-IMG-repetitivas-dono-planilha-45-v1.png` (IMG-05)
- `OUT-IMG-sonhos-site-laptop-45-v2.png` (IMG-09, segunda versão)
- `OUT-VID-automatize-conceito-papel-916-v1.mp4` (VID-02)
- `OUT-VID-sonhos-site-swipe-916-v1.mp4` (VID-06)

**Organização de pastas:**

```
/criativos
  /01-brutos-grok        (saída direta do SuperGrok, sem texto)
  /02-finais-feed        (4:5 e 1:1 com texto, prontos para subir)
  /03-finais-stories     (9:16 com texto)
  /04-arquivo            (versões aposentadas por fadiga/CTR baixo)
controle-criativos (planilha: ID, nome do arquivo, ângulo, nicho, headline, CTA, data ativação, CTR, CPL, status)
```

Regra final: criativo aposentado nunca é deletado — vai para `/04-arquivo` com o resultado anotado na planilha. É esse histórico que vai mostrar, em 4–8 semanas de teste, qual ângulo e qual nicho merecem o orçamento.