# Processo de Vendas e Atendimento — Outloop

**Documento de trabalho interno.** Cobre todo o caminho do lead: da primeira mensagem no WhatsApp até o pós-venda e a indicação. Objetivo: nenhum lead sem resposta em 5 minutos, nenhuma conversa sem próximo passo, nenhum cliente entregue sem pedido de depoimento.

**Regra de ouro da operação:** responder um lead em até 5 minutos aumenta em ~21x a chance de qualificá-lo (vs. 30 minutos), e a média das empresas brasileiras passa de 24h. Velocidade de resposta é, sozinha, nossa primeira vantagem competitiva — e é prova viva do que vendemos.

---

## 1. SLA e setup do WhatsApp Business

### 1.1 SLA de atendimento

| Situação | Prazo de resposta |
|---|---|
| Lead novo de anúncio (horário comercial, seg–sex 8h–18h) | **Até 5 minutos** |
| Lead novo fora do horário comercial | Saudação automática imediata + resposta pessoal até 9h do próximo dia útil |
| Lead em conversa ativa | Até 30 minutos |
| Cliente ativo (suporte) | Até 4h úteis (ou conforme SLA do contrato) |

Enquanto a operação for solo: notificações do WhatsApp Business sempre ativas no horário comercial. Se estiver em reunião, a saudação automática segura o lead e a primeira pergunta de qualificação já começa a conversa.

### 1.2 Mensagem de saudação automática (fora do horário ou ausente)

> Olá! Aqui é o Pedro, da Outloop. Obrigado pela mensagem.
>
> A gente ajuda empresas de Ribeirão Preto e região a parar de perder tempo com tarefas repetitivas: automação de processos, atendente com IA no WhatsApp, sites e sistemas sob medida.
>
> Já vou te responder pessoalmente. Enquanto isso, me adianta uma coisa: **qual é a tarefa manual que mais toma tempo na sua empresa hoje?**

Por que assim: apresenta a empresa em 1 linha, promete resposta humana e já dispara a primeira pergunta de qualificação — o lead chega "pré-aquecido" quando você retomar.

### 1.3 Respostas rápidas (atalhos do WhatsApp Business)

**/precos**

> Boa pergunta — o valor depende do que faz sentido pro seu caso, mas pra você ter referência, nossas faixas são:
>
> - **Landing page:** R$ 2.200 (projeto fechado).
> - **Site institucional:** R$ 4.500 (projeto fechado).
> - **Automação:** a partir de R$ 2.500 de implantação + R$ 400/mês.
> - **Atendente IA no WhatsApp:** R$ 6.000 de implantação + R$ 800/mês.
> - **Sistema sob medida (CRM simples, dashboard, portal):** projeto fechado por escopo, de R$ 8 mil a R$ 35 mil conforme escopo.
>
> Antes de falar de número exato, eu faço um **diagnóstico gratuito de 30 minutos**: mapeamos seus maiores gargalos e você sai com um plano concreto (com estimativa de horas economizadas), mesmo que não feche nada com a gente. Quer agendar? Tenho horário **[dia] às [hora]** ou **[dia] às [hora]**.

**/diagnostico**

> O **Diagnóstico Gratuito de Automação** funciona assim:
>
> 1. Conversa de 30 minutos (vídeo ou presencial, se você estiver em Ribeirão e região).
> 2. Mapeamos juntos os 3 maiores gargalos da sua operação.
> 3. Você recebe em até 48h um resumo em PDF com o plano de automação, estimativa de horas economizadas e proposta com escopo, prazo e investimento.
>
> Sem compromisso e sem enrolação: se automação não fizer sentido pro seu caso, eu falo isso na reunião.
>
> Tenho horário **[dia] às [hora]** ou **[dia] às [hora]**. Qual prefere?

**/portfolio**

> Claro! Alguns exemplos do que já construí:
>
> - Sistemas internos em produção para a Lokok (gestão de operação do dia a dia) — uso real, todos os dias.
> - Automações de integração entre ferramentas (planilhas, relatórios, cobranças) com n8n/Make.
> - Atendente com IA no WhatsApp: responde, qualifica e agenda 24/7.
> - Sites e landing pages: veja o próprio site da Outloop — foi feito por nós, do jeito que entregamos: **[link do site da Outloop]**.
>
> Aliás, um detalhe: parte desta conversa que você está tendo comigo já passa pela nossa própria automação. É assim que funciona na prática.
>
> Quer ver como ficaria no seu negócio? O diagnóstico de 30 min é gratuito.

Outros atalhos úteis para criar desde o dia 1: **/pix** (dados de pagamento), **/contrato** (explicação curta do contrato + LGPD), **/endereco** (para reunião presencial).

### 1.4 Etiquetas de funil no WhatsApp Business

Espelham o pipeline do CRM (seção 7). Toda conversa recebe etiqueta na hora:

1. `01 Lead novo` — chegou e ainda não foi qualificado
2. `02 Qualificado` — respondeu as perguntas, tem fit
3. `03 Diagnóstico agendado` — reunião marcada
4. `04 Diagnóstico feito` — reunião realizada, proposta em preparação
5. `05 Proposta enviada` — aguardando decisão
6. `06 Fechado` — virou cliente
7. `07 Perdido` — descartado ou sumiu após cadência completa
8. `08 Indicação/Parceiro` — contadores, agências, parceiros de indicação

Rotina diária (10 min, fim do dia): revisar `01` (ninguém sem resposta), `03` (confirmar reuniões de amanhã) e `05` (quem entrou na cadência de follow-up hoje).

---

## 2. Script de qualificação no WhatsApp

### 2.1 Primeira resposta ao lead de anúncio (em até 5 min)

O lead clicou no anúncio e mandou a mensagem pré-preenchida (ex.: "Quero o diagnóstico gratuito de automação"). Resposta:

> Oi, [nome]! Pedro aqui, da Outloop. Vi que você veio pelo nosso anúncio — obrigado pelo interesse.
>
> Pra eu já te ajudar com algo concreto (e não te fazer perder tempo), me conta rapidinho: **qual é o ramo da sua empresa e qual tarefa repetitiva mais consome o tempo de vocês hoje?**

Regras: sempre usar o nome; citar a origem ("veio pelo anúncio"); **uma pergunta por mensagem**, nunca um questionário em bloco; mensagens curtas — é WhatsApp, não e-mail.

### 2.2 As 4 perguntas de qualificação

Fazer em conversa natural, uma de cada vez, reagindo ao que o lead responde. Meta: qualificar em ~5 minutos de troca.

**P1 — Segmento e contexto** (geralmente já vem na primeira resposta):
> Qual é o ramo da empresa e como funciona o atendimento de vocês hoje — é tudo pelo WhatsApp?

**P2 — Tamanho e volume:**
> E quantas pessoas trabalham aí hoje? Vocês recebem mais ou menos quantos contatos/atendimentos por dia?

**P3 — Dor principal:**
> Se você pudesse eliminar UMA tarefa manual amanhã, qual seria? (Ex.: confirmar agendamento, responder as mesmas perguntas, montar relatório, cobrar cliente...)

**P4 — Urgência e decisão:**
> Isso é algo que vocês querem resolver agora ou estão só pesquisando por enquanto? E a decisão é sua ou tem mais alguém envolvido?

**Leitura rápida do fit:**

| Sinal | Ação |
|---|---|
| Nicho prioritário (clínica, advocacia/contábil, imobiliária, comércio local), 2+ pessoas, dor clara, quer resolver agora | **Quente** — convidar para o diagnóstico na mesma conversa |
| Dor clara mas "sem pressa" | Convidar para o diagnóstico mesmo assim ("é gratuito e você sai com um plano pronto pra quando decidir") |
| MEI sozinho sem verba, curioso, quer "só o preço" de algo indefinido | Enviar /precos, deixar a porta aberta, etiquetar `07 Perdido` se não avançar |
| Pedindo emprego, vendendo serviço, fora da região sem fit | Responder com educação e encerrar |

### 2.3 Condução para o diagnóstico

Assim que a dor aparecer (não precisa esperar as 4 perguntas se o lead já se abriu):

> Entendi, [nome]. Esse é exatamente o tipo de coisa que a gente resolve — [1 frase conectando a dor à solução, ex.: "dá pra confirmar consulta automaticamente pelo WhatsApp, sem ninguém digitar nada"].
>
> O próximo passo é o nosso **diagnóstico gratuito de 30 minutos**: eu mapeio com você os 3 maiores gargalos aí e te entrego um plano com estimativa de horas economizadas — por escrito, em até 48h depois da conversa. Sem compromisso.
>
> Tenho **quarta às 10h** ou **quinta às 16h**. Qual funciona melhor pra você?

Regras: **sempre oferecer 2 horários concretos**, nunca "qualquer dia". Se nenhum servir, oferecer mais dois. Confirmar por escrito: data, hora, formato (Meet ou presencial) e o que a pessoa deve ter em mãos (ver seção 3.1). Registrar no CRM e mover a etiqueta para `03`.

### 2.4 Respostas prontas para as 8 objeções mais comuns

**1. "Quanto custa?" (cedo demais, antes de qualquer contexto)**

> Justo perguntar isso logo — te dou as faixas pra você ter referência: landing page R$ 2.200; site institucional R$ 4.500 (projeto fechado); automação a partir de R$ 2.500 de implantação + R$ 400/mês; atendente IA no WhatsApp R$ 6.000 + R$ 800/mês; sistema sob medida de R$ 8 mil a R$ 35 mil, conforme escopo.
>
> Mas o número certo pro SEU caso depende do que vamos automatizar — por isso o diagnóstico gratuito existe: você sai dele com preço exato, escopo e prazo, sem compromisso. Posso te mostrar **[dia] às [hora]** ou **[dia] às [hora]**?

Princípio: nunca esconder preço (gera desconfiança), nunca cravar preço sem escopo (gera âncora errada). Faixa + convite.

**2. "Vou pensar"**

> Claro, decisão de negócio se pensa mesmo. Só me ajuda com uma coisa pra eu não te atrapalhar: o que ficou faltando pra você decidir — é o valor, o momento, ou ficou dúvida se funciona pro seu caso?

(A resposta revela a objeção real. Se for valor → objeção 3. Se for momento → cadência de follow-up. Se for dúvida técnica → oferecer mostrar um exemplo funcionando na própria conversa.)

**3. "Tá caro"**

> Entendo. Deixa eu colocar em perspectiva com os seus números: você me disse que [pessoa/equipe] gasta cerca de [X horas/semana] com [tarefa]. Isso dá umas [X×4] horas por mês — tempo que hoje custa salário e não gera receita. A automação se paga quando devolve essas horas pra atividade que traz cliente.
>
> E dá pra começar menor: em vez do pacote completo, a gente implanta só [módulo da dor nº 1] primeiro, por [valor menor], e expande quando você ver funcionando. Faz mais sentido assim?

Princípio: nunca dar desconto seco. Reduzir escopo, não preço. Desconto sem contrapartida ensina o cliente a pechinchar.

**4. "Já tenho site"**

> Ótimo — aí talvez site nem seja o que você precisa. A maioria dos nossos clientes não contrata site: contrata automação (atendente IA no WhatsApp, confirmação de agenda, cobrança automática, relatórios). O site só entra quando ele não está trazendo cliente ou não conversa com o WhatsApp.
>
> Me conta: hoje, quem chega pelo site de vocês cai onde? Alguém responde na hora?

Princípio: a objeção "já tenho site" quase sempre esconde a venda real, que é automação. Redirecionar, não discutir o site atual.

**5. "Não entendo de tecnologia"**

> Perfeito — você não precisa entender. É exatamente pra isso que a gente existe. Você continua usando o que já usa (WhatsApp, planilha, agenda); a tecnologia trabalha por trás, e eu cuido dela. Você não vai "mexer em sistema": vai receber cliente respondido, consulta confirmada e relatório pronto.
>
> No diagnóstico eu te mostro tudo em português claro, sem sigla. Se em algum momento eu falar algo que você não entendeu, a culpa é minha, não sua.

**6. "Me manda por email"**

> Mando sim — me passa o email que eu envio um resumo hoje ainda.
>
> Só uma sugestão sincera: material genérico por email diz pouco, porque cada empresa tem um gargalo diferente. Em 30 minutos de conversa eu te entrego um plano específico pro seu caso, por escrito. Que tal a gente marcar o diagnóstico e o email vai junto com o resumo personalizado? Tenho **[dia] às [hora]** ou **[dia] às [hora]**.

(Se insistir só no email: enviar 1 página objetiva + link do site, etiquetar `02` e entrar na cadência de follow-up.)

**7. "Depois te chamo"**

> Combinado, [nome]. Pra eu não ficar te enchendo: posso te mandar uma mensagem na **[dia da semana, D+7]** pra ver se é um bom momento? Se antes disso a [dor citada] apertar, é só chamar aqui — esse número é direto comigo.

Princípio: pedir permissão para o follow-up transforma "cobrança" em "combinado". Registrar a data no CRM e cumprir.

**8. "Faz um teste grátis?"**

> O trabalho é sob medida, então não tem "teste" no sentido de software de prateleira — mas tem duas coisas melhores:
>
> 1. O **diagnóstico gratuito**: você sai com o plano completo por escrito antes de pagar qualquer coisa.
> 2. Nossa **garantia em contrato**: se a automação combinada não entrar em produção funcionando no prazo acordado, você não paga a implantação. O risco fica comigo, não com você.
>
> E tem um teste que você já está fazendo agora sem perceber: a velocidade e a qualidade deste atendimento aqui é o produto funcionando. Quer ver isso rodando na sua empresa?

---

## 3. Roteiro do Diagnóstico Gratuito de Automação (30 min)

Formato: Google Meet ou presencial (Ribeirão Preto e região, ~40 km). Presencial tem prioridade para leads quentes de ticket alto — aperto de mão ainda fecha negócio no interior.

### 3.1 Antes da reunião (preparação, 15 min)

- Reler a conversa do WhatsApp e anotar: segmento, tamanho, dor citada, urgência.
- Olhar Instagram, Google Maps e site do lead: como respondem? Têm avaliações reclamando de demora? Site desatualizado?
- Preparar 1 exemplo pronto do nicho dele para mostrar na tela (ex.: fluxo de confirmação de consulta para clínica).
- Mensagem de confirmação na véspera:

> Oi, [nome]! Confirmando nosso diagnóstico amanhã, **[dia] às [hora]**, por **[Meet/presencial]**. Pra render mais, tenha em mente: (1) as 3 tarefas que mais tomam tempo aí, (2) quantas pessoas mexem nelas e (3) as ferramentas que vocês usam hoje (agenda, planilha, sistema). Até amanhã!

### 3.2 Minuto a minuto

**0–3 min | Abertura e enquadramento**
Quebra-gelo curto (1 referência local ajuda: bairro, região). Depois:

> Nosso combinado pros próximos 30 minutos: eu vou te fazer perguntas sobre a operação, a gente vai mapear juntos os 3 maiores gargalos, e eu já te mostro ao vivo como eles ficariam automatizados. No final, você me diz se quer receber a proposta — que eu mando por escrito em até 48h, com escopo, prazo e valor. Não vou te empurrar nada hoje. Fechado?

Isso mata a resistência de "reunião de vendas disfarçada" e já semeia o fechamento.

**3–13 min | Descoberta (a parte mais importante — falar 20%, ouvir 80%)**
Perguntas de descoberta, adaptando ao nicho:

1. "Me descreve um dia normal aí: o cliente chega por onde, e o que acontece do primeiro contato até o pagamento?"
2. "Dessa jornada toda, qual pedaço é feito na mão, por pessoa, hoje?"
3. "Quanto tempo por dia/semana isso consome? Quem faz?"
4. "O que acontece quando essa pessoa falta, ou quando chega mensagem fora do horário / no fim de semana?"
5. "Já perderam cliente por demora na resposta ou por esquecimento de follow-up? Com que frequência?" *(clínica: "quantos pacientes faltam sem avisar por mês?"; imobiliária: "em quanto tempo vocês respondem um lead de portal?")*
6. "Que ferramentas vocês usam? Agenda de papel, planilha, algum sistema?"
7. "Se nada mudar, como isso fica daqui a 6 meses com mais volume?"

Anotar **números** sempre que aparecerem (horas, faltas, leads perdidos) — eles viram o argumento da proposta.

**13–22 min | Mapeamento ao vivo dos 3 maiores gargalos automatizáveis**
Compartilhar tela (ou papel, se presencial) e desenhar com o lead:

> Deixa eu desenhar o que você me contou: [cliente chama no WhatsApp] → [secretária responde quando dá] → [agenda no caderno] → [ninguém confirma] → [20% faltam]. Agora o mesmo fluxo automatizado: [cliente chama] → [atendente IA responde em segundos, 24/7] → [agenda direto] → [confirmação automática 1 dia antes] → [quem não confirma recebe reoferta de horário].

Para cada gargalo mapeado, verbalizar o trio: **o que muda + horas devolvidas + o que a pessoa passa a fazer com esse tempo**. Priorizar com o lead: "desses 3, qual dói mais?" — o escolhido vira a fase 1 da proposta.

Importante (aprendizado do setor): **só prometer automatizar processo que já funciona manualmente**. Se o processo do lead for bagunçado, dizer com franqueza: "antes de automatizar, a gente organiza esse fluxo — isso faz parte da implantação". Isso evita projeto fracassado e justifica o valor do setup.

**22–27 min | Recapitulação e teste de temperatura**

> Resumindo: os dois maiores ganhos aqui são [processo A] e [processo B], que hoje consomem cerca de [X horas/semana]. A implantação leva tipicamente de 3 a 4 semanas, no modelo de projeto de implantação + mensalidade de operação. Faz sentido pra você o que a gente desenhou?

Deixar o lead reagir. Se surgir objeção, tratar aqui (seção 2.4) — é mais barato tratar agora do que no follow-up.

**27–30 min | Fechamento com compromisso**

> Então o combinado é: **em até 48h você recebe no WhatsApp a proposta em PDF** — o resumo deste diagnóstico, o plano de automação, prazo e investimento, com o valor travado por 15 dias. Você olha com calma e a gente conversa **[dia, D+2] às [hora]** pra eu tirar dúvidas. Pode ser?

Sempre sair com **data e hora da próxima conversa marcadas**. Proposta sem retorno agendado é proposta que morre na caixa de entrada.

### 3.3 Depois da reunião (mesmo dia)

- Registrar tudo no CRM (dores, números, processos priorizados, objeções).
- Montar e enviar a proposta em **até 48h** (template na seção 4) — cumprir esse prazo é parte da demonstração de competência.

---

## 4. Template da proposta comercial (1–2 páginas, PDF)

Enviar como PDF com identidade visual da Outloop, pelo WhatsApp, com mensagem curta:

> [Nome], conforme combinado: sua proposta está aí, em 2 páginas, sem letra miúda. Qualquer dúvida me chama — e nos falamos [dia] às [hora].

---

> # Proposta — [Nome da empresa cliente]
> **Outloop | Automação, sites e sistemas sob medida — Ribeirão Preto/SP**
> Preparada por Pedro [sobrenome] · [data] · Válida por 15 dias
>
> ## 1. O problema (o que vimos no diagnóstico)
> No diagnóstico de [data], mapeamos juntos os processos que mais consomem tempo na [empresa]:
> - **[Processo A]** — hoje feito manualmente por [pessoa/função], consumindo cerca de **[X horas/semana]**. Consequência: [demora na resposta / faltas sem aviso / cobranças esquecidas].
> - **[Processo B]** — [mesma estrutura, com o número citado pelo cliente].
>
> Mantido como está, isso significa aproximadamente **[X×4 horas/mês]** de trabalho repetitivo — tempo que não atende cliente nem gera receita.
>
> ## 2. A solução proposta
> Implantar **[nome direto da solução, ex.: "atendente com IA no WhatsApp + confirmação automática de agenda"]**, para que a [empresa]:
> - Responda clientes **em segundos, 24 horas por dia, 7 dias por semana**;
> - Elimine [tarefa A] da rotina da equipe;
> - Tenha [relatório/visão] pronto automaticamente, sem digitação.
>
> ## 3. Escopo da implantação
> **Fase 1 — [Processo prioritário]** *(o que está incluído, em linguagem clara)*
> - [Item 1 — ex.: fluxo de atendimento e qualificação no WhatsApp, com transbordo para humano]
> - [Item 2 — ex.: confirmação automática de agendamento com lembrete em D-1]
> - [Item 3 — ex.: painel simples com os números do atendimento]
> - Treinamento da equipe + documentação de tudo que for construído (acessos e credenciais ficam com você)
>
> **Não incluído nesta fase:** [deixar explícito — ex.: integração com sistema X, site novo]. Pode ser contratado depois como Fase 2.
>
> ## 4. Prazo
> **[3 a 4] semanas** a partir do aceite e do acesso às ferramentas, em 3 marcos: (1) desenho e aprovação dos fluxos, (2) construção e testes com você, (3) virada em produção + treinamento.
>
> ## 5. Investimento
> | Item | Valor |
> |---|---|
> | Implantação (projeto fechado, Fase 1) | **R$ [valor]** — 50% no aceite, 50% na entrega em produção |
> | Mensalidade de operação (monitoramento, ajustes, suporte, evolução) | **R$ [valor]/mês**, a partir da virada em produção — compromisso mínimo de 3 meses (período de estabilização); depois, cancelamento com aviso de 30 dias, sem multa |
>
> Custos variáveis de terceiros (API do WhatsApp/IA, servidor) são repassados de forma transparente — estimativa para seu volume: **R$ [faixa]/mês**.
>
> **Garantia:** se a automação descrita na Fase 1 não entrar em produção funcionando conforme este escopo, a implantação é devolvida. Contrato com cláusulas de confidencialidade, LGPD e propriedade do que for desenvolvido para você.
>
> ## 6. Próximos passos
> 1. Você aprova esta proposta (basta responder no WhatsApp);
> 2. Envio o contrato para assinatura digital + dados de pagamento da 1ª parcela;
> 3. Agendamos o kickoff de 30 min e a Fase 1 começa na mesma semana.
>
> *Dúvidas? Me chame direto: [WhatsApp] · [email] · [site da Outloop]*

---

Notas de uso do template:
- A seção 1 deve usar **os números que o próprio cliente falou** no diagnóstico — é isso que faz a proposta parecer feita sob medida (porque é).
- Uma única opção principal de escopo; no máximo mencionar a Fase 2 como expansão. Proposta com 3 pacotes funciona no site; na proposta pós-diagnóstico, escolha por ele.
- Validade de 15 dias cria urgência honesta e dá gancho para o follow-up.

---

## 5. Cadência de follow-up (após envio da proposta)

Dia 0 = envio da proposta, já com conversa de retorno marcada para D+2. Se o lead sumir ou adiar, entra a cadência:

**D+1 — Confirmação de recebimento (curta, sem pressão)**

> Oi, [nome]! Só confirmando que a proposta chegou direitinho. Se bater qualquer dúvida antes da nossa conversa de [dia], me chama — respondo rápido por aqui.

**D+3 — Valor, não cobrança (trazer algo novo, nunca só "e aí?")**

> [Nome], lembrei de você: [conteúdo relevante — ex.: "um cliente do mesmo ramo reduziu bastante as faltas só com a confirmação automática em D-1" / "vi que vocês receberam mais uma avaliação reclamando de demora no retorno — é exatamente o que a Fase 1 resolve"]. Conseguiu olhar a proposta? Posso te ligar 10 min hoje ou amanhã pra fechar as dúvidas?

**D+7 — Pergunta direta + lembrete da validade**

> Oi, [nome]. Sendo direto, como você me pediu que eu fosse: a proposta segue de pé até [data]. Existe algo nela que está te travando — valor, prazo, ou o momento? Se for algum desses, me fala que eu vejo como ajustar. Se a resposta for "agora não", também está tudo bem — só me diz pra eu não ficar te incomodando.

**D+14 — Última mensagem da cadência (break-up educado)**

> [Nome], essa é minha última mensagem sobre a proposta, prometo. Vou entender seu silêncio como "agora não é o momento" — acontece, e tá tudo certo. Vou deixar seu plano guardado aqui: quando a [dor citada] voltar a apertar, é só me chamar que a gente retoma do ponto em que parou (só reviso o valor se os custos tiverem mudado). Obrigado pela conversa e sucesso aí!

### Regras da cadência

- **Sempre alternar o conteúdo**: confirmação → valor → pergunta direta → despedida. Nunca 4 mensagens de "e aí, viu a proposta?".
- Se o lead responder "me procura em [mês]": marcar no CRM, sair da cadência e **cumprir a data** — follow-up combinado tem taxa de resposta muito maior.
- **Marcar como Perdido quando:** (a) completou a cadência D+14 sem resposta; (b) disse "não" explícito; (c) fechou com concorrente; (d) sumiu antes mesmo do diagnóstico após 3 tentativas de contato. Registrar sempre o **motivo** (preço / momento / concorrente / sem fit / sumiu) — esse dado corrige anúncio, qualificação e preço.
- Perdido não é lixo: leads perdidos por "momento" entram numa lista para um toque leve a cada ~90 dias (novidade, case novo, conteúdo útil).

---

## 6. Pós-venda

### 6.1 Onboarding do cliente novo

**No aceite (mesmo dia):**

> [Nome], fechado — bem-vindo à Outloop! Próximos passos: (1) contrato chega hoje por assinatura digital, (2) junto vai o link de pagamento da 1ª parcela, (3) assim que assinar, a gente marca o kickoff de 30 min pra levantar acessos e começar. Bora?

**Kickoff (30 min, até 3 dias úteis após assinatura):**
1. Reapresentar escopo e os 3 marcos com datas (alinhamento de expectativa evita 90% dos atritos);
2. Levantar acessos necessários (WhatsApp, agenda, planilhas, sistema, domínio) — usar checklist padrão por tipo de projeto;
3. Definir o canal oficial: **grupo de WhatsApp "Outloop × [Cliente]"** com os envolvidos do cliente — pedidos e aprovações passam por ali (nada de escopo combinado em áudio perdido);
4. Combinar ritual: update curto de progresso **toda sexta** no grupo, mesmo que seja "em construção, no prazo";
5. Explicar o que acontece na virada: treinamento da equipe + entrega da documentação e credenciais (reforçar: "tudo que eu construir é seu e fica documentado" — isso mata a objeção do fornecedor solo).

**Primeiros 90 dias (clientes com mensalidade):** 1 revisão por mês de 20–30 min — o que rodou, números (conversas atendidas, horas economizadas, faltas evitadas), ajustes e oportunidades de expansão (Fase 2). Adoção é o que renova mensalidade e gera case.

### 6.2 Pedido de depoimento (na entrega / primeiro resultado)

Pedir no pico de satisfação: na virada em produção ou na primeira revisão mensal com número bom na mesa.

> [Nome], que bom que [resultado concreto: "o atendente já respondeu X conversas sozinho" / "as faltas caíram de X pra Y"]. Posso te pedir uma coisa que me ajuda demais? **Um depoimento curto, de 2 ou 3 frases**, contando como era antes e como ficou. Pode ser por escrito aqui mesmo ou um áudio/vídeo de 30 segundos pelo celular — do jeito que for mais fácil. Eu uso no site e nos materiais da Outloop, com seu nome e o da [empresa]. Topa?

Boas práticas: pedir **autorização explícita** de uso de nome/empresa (guardar a mensagem de autorização); facilitar com 3 perguntas-guia ("como era antes? o que a Outloop fez? o que mudou em número ou tempo?"); pedir também avaliação no Google da Outloop. Meta: **todo cliente entregue = 1 depoimento + 1 avaliação Google**.

### 6.3 Programa de indicação (simples de operar e de explicar)

**Regra:** cliente que indicar uma empresa que **fechar** com a Outloop ganha **R$ 500 de crédito em mensalidade por indicação fechada** (clientes só de projeto, sem mensalidade: R$ 500 de crédito em serviços). Sem limite de indicações; crédito aplicado na fatura seguinte ao fechamento.

**Como divulgar (na revisão mensal ou após um resultado bom):**

> Aliás, [nome]: se você conhecer outro [dono de clínica/advogado/imobiliária] penando com [dor], me apresenta? Funciona assim: se a indicação fechar, **você ganha R$ 500 de crédito na sua mensalidade** — e a pessoa entra direto pro diagnóstico gratuito, sem compromisso. Basta me mandar o contato dela ou encaminhar meu número.

**Operação:** registrar o indicador no CRM no campo "origem"; avisar o indicador quando a indicação fechar (e agradecer); aplicar o crédito sem a pessoa precisar cobrar. Canal paralelo: **contadores e agências de marketing como parceiros de indicação recorrente** (etiqueta `08`) — cada contador atende dezenas de PMEs; oferecer a eles a mesma mecânica ou comissão combinada caso a caso.

---

## 7. CRM: pipeline e ferramenta

### 7.1 Pipeline de estágios

| # | Estágio | Entra quando... | Sai quando... | Ação obrigatória no estágio |
|---|---|---|---|---|
| 1 | **Lead novo** | Primeira mensagem recebida | Respondeu as perguntas de qualificação | Responder em ≤5 min; registrar origem (campanha/UTM) |
| 2 | **Qualificado** | Tem fit (nicho, tamanho, dor, urgência) | Diagnóstico marcado ou descartado | Oferecer 2 horários para o diagnóstico |
| 3 | **Diagnóstico agendado** | Data e hora confirmadas | Reunião realizada (ou no-show) | Confirmar na véspera; preparar exemplo do nicho |
| 4 | **Diagnóstico feito** | Reunião realizada | Proposta enviada | Registrar dores, números e gargalos priorizados no CRM; montar a proposta (permite medir comparecimento vs. agendado) |
| 5 | **Proposta enviada** | Proposta enviada (≤48h após diagnóstico) | Aceite ou fim da cadência D+14 | Conversa de retorno marcada; cadência D+1/3/7/14 |
| 6a | **Fechado** | Aceite + contrato assinado | — | Kickoff em até 3 dias úteis; iniciar onboarding |
| 6b | **Perdido** | "Não", sumiço pós-cadência ou sem fit | — | Registrar motivo; agendar toque em ~90 dias se for "momento" |

**Métricas a acompanhar desde o dia 1** (referências de mercado para calibrar expectativa): conversas → diagnóstico agendado (referência: 20–40% para inbound bem atendido), diagnóstico → fechamento (referência: 15–25% das oportunidades), CPL por canal e tempo médio de primeira resposta. Regra prática derivada dos benchmarks: **1 cliente novo a cada ~15–40 conversas iniciadas** — planejar verba de anúncio com isso em mente.

### 7.2 Ferramenta recomendada

**Começar com o HubSpot CRM gratuito** (recomendação da pesquisa): pipeline visual com os estágios acima, contatos ilimitados no essencial, campos personalizados (origem, nicho, dor, motivo de perda) e custo zero. Alternativa mínima aceitável na primeiríssima semana: planilha estruturada com as mesmas colunas — mas migrar para o CRM antes dos 10 primeiros leads, porque follow-up sem lembrete automático se perde.

Complementos desde o dia 1 (todos gratuitos): etiquetas do WhatsApp Business espelhando o pipeline (seção 1.4); links `wa.me` distintos por canal/campanha (ou mensagem pré-preenchida diferente) para atribuição de origem; GA4 + Meta Pixel via Google Tag Manager na landing. Evolução por volume: até ~10 leads/mês, tudo manual + HubSpot; de 10 a 50/mês, qualificação automática com Typebot + Evolution API em VPS (~R$ 30–60/mês); acima de 50/mês, CRM com inbox de WhatsApp integrada (Kommo ou RD Station CRM).

**Disciplina mínima inegociável:** todo lead entra no CRM no dia em que chega, com origem preenchida; nenhum card fica sem "próxima ação + data". Um pipeline com 20 cards atualizados vale mais do que qualquer ferramenta paga com dados velhos.