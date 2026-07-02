# Ofertas e Precificação — Outloop

**Documento de trabalho interno** | Versão 1.0 — julho/2026
Escopo: definição das 3 linhas de serviço, preços de lançamento para Ribeirão Preto e região, oferta de entrada, pacotes, política de pagamento e regras de desconto/garantia.

**Princípios de precificação da Outloop (valem para tudo neste documento):**

1. **Vender resultado, não ferramenta.** O cliente compra "consultas confirmadas sem ninguém digitar" e "resposta ao lead em segundos, 24/7" — não "fluxo de n8n". A stack aparece só como prova de competência.
2. **Toda oferta gera recorrência.** Até site tem plano mensal embutido. Recorrência (MRR) é o que diferencia estúdio de freelancer e o que valoriza o negócio.
3. **Preço na camada "valor", não na "commodity".** A Outloop cobra acima do freelancer avulso e abaixo das agências grandes de IA (que praticam R$ 8.000–20.000 de setup + R$ 1.500–3.000/mês), justificando com diagnóstico estruturado, acesso direto ao especialista sênior, contrato com SLA e suporte contínuo.
4. **Custo variável nunca entra no preço fixo.** API de IA (OpenAI/Anthropic), WhatsApp Business API (cobrada por mensagem-template desde 2025) e VPS ficam na conta do cliente ou são reembolsados com margem administrativa de 15–20%. Isso vai em contrato.
5. **Preço fixo publicado por pacote.** Serviço produtizado encurta o ciclo de venda e evita a armadilha de cobrar por hora.

---

## 1. As 3 linhas de serviço

### 1.1 Automação de processos (carro-chefe — modelo setup + mensalidade)

**Promessa central:** "Pare com tarefas repetitivas. Sua empresa responde clientes em segundos, 24/7."

**Três pacotes produtizados:**

| | **Essencial** | **Operação** | **Escala** |
|---|---|---|---|
| Para quem | PME que quer eliminar 1–2 tarefas manuais específicas | PME cujo gargalo é atendimento/agenda no WhatsApp | PME com volume alto e múltiplos processos |
| O que inclui | 1–2 automações (n8n/Make): ex. planilha → relatório automático, cobrança recorrente, notificação de pedido | Tudo do Essencial + **atendente IA no WhatsApp** (recepção, qualificação, FAQ), confirmação/lembrete de agenda, até 4 fluxos | Tudo do Operação + integração com CRM/sistema do cliente, follow-up automático de leads, dashboards de acompanhamento, fluxos ilimitados dentro do escopo contratado |
| Volume de conversas IA | — | até ~1.000/mês | até ~5.000/mês |
| Suporte / SLA | E-mail/WhatsApp, resposta em até 1 dia útil | Resposta em até 4h úteis + 1 revisão mensal | Resposta em até 2h úteis + revisão mensal + 2h/mês de evolução inclusa |
| **Prazo de entrada em produção** | **até 2 semanas** | **3–4 semanas** | **4–6 semanas** |

**Todo pacote de automação inclui:** diagnóstico e mapeamento do processo (só automatizamos processo que já funciona manualmente — se o processo do cliente estiver mal definido, o ajuste faz parte do setup e é dito com clareza); desenho dos fluxos; engenharia de prompt e curadoria da base de conhecimento (pacotes com IA); testes em ambiente real; treinamento da equipe do cliente; documentação dos fluxos e credenciais entregues ao cliente; monitoramento e ajustes contínuos (mensalidade); revisões nos primeiros 90 dias para garantir adoção.

**O que NÃO inclui:** custos de API de IA, WhatsApp Business API e VPS (repassados — ver Seção 6); criação de conteúdo/marketing; gestão de tráfego pago; alterações de escopo fora do pacote (orçadas à parte); suporte a sistemas de terceiros que não fazem parte da automação.

### 1.2 Sites e landing pages profissionais (projeto fechado, entrega rápida)

**Promessa central:** "Tenha o site dos seus sonhos — no ar em dias, não em meses."

| | **Landing page** | **Site institucional** |
|---|---|---|
| O que inclui | 1 página de alta conversão: copy orientada a resultado, design responsivo mobile-first, botão de WhatsApp com mensagem pré-preenchida, formulário curto, GA4 + Meta Pixel via GTM instalados, SEO on-page básico, carregamento rápido | Até 5 páginas (home, serviços, sobre, contato + 1), design responsivo, integração WhatsApp, formulários, GA4 + Pixel, SEO on-page, Google Meu Negócio configurado/vinculado |
| Rodadas de revisão | 2 | 2 |
| **Prazo de entrega** | **7 dias úteis** após aprovação do conteúdo | **15–20 dias úteis** após aprovação do conteúdo |

**O que NÃO inclui:** redação de blog/conteúdo contínuo; fotografia profissional; e-commerce (loja virtual é orçamento à parte, tratado como sistema); gestão de anúncios; domínio e e-mail corporativo (contratados em nome do cliente — orientamos a compra); SEO contínuo/link building.

**Plano de manutenção mensal (embutido na venda, não opcional "escondido"):** hospedagem gerenciada, backups, atualizações de segurança, pequenos ajustes de conteúdo (até 1h/mês no plano básico), monitoramento de disponibilidade. Mercado pratica R$ 300–1.500/mês; a Outloop entra abaixo para facilitar adesão (ver tabela na Seção 2).

### 1.3 Sistemas sob medida (projeto fechado por faixa de escopo)

**Promessa central:** "O sistema exato que sua operação precisa — sem pagar por 80% de funcionalidades que você nunca vai usar."

| Faixa | Exemplos típicos | Escopo aproximado | **Prazo** |
|---|---|---|---|
| **P — Ferramenta focada** | Dashboard de indicadores, calculadora/orçamentador interno, painel de acompanhamento | 3–8 telas, 1 integração | 3–5 semanas |
| **M — Operação** | CRM simples, portal de clientes, gestão de agendamentos/orçamentos | 8–15 telas, 2–3 integrações, controle de acesso | 6–10 semanas |
| **G — Sistema integrado** | Portal interno completo, CRM + automações + integrações com sistemas existentes | 15+ telas, múltiplas integrações, regras de negócio complexas | 10–16 semanas |

**Todo projeto inclui:** levantamento de requisitos com o dono/equipe; protótipo navegável antes do desenvolvimento; entregas por marcos com critérios de aceite (o cliente valida por etapa, não só no final); código documentado; treinamento da equipe; 30 dias de garantia de correção de bugs pós-entrega; credenciais e documentação entregues ao cliente (neutraliza o risco de "e se o desenvolvedor sumir?").

**O que NÃO inclui:** hospedagem e serviços de terceiros (na conta do cliente); novas funcionalidades fora do escopo aprovado (change requests orçados à parte); migração de dados legados complexa (orçada no diagnóstico se necessária); suporte contínuo sem plano de manutenção contratado.

**Manutenção mensal opcional:** correções, pequenas evoluções (até 4h/mês), monitoramento e atualizações de dependências.

---

## 2. Tabela de preços — mercado vs. preço Outloop de lançamento

Faixas de mercado vêm da pesquisa consolidada (Brasil, 2025/2026). Preços Outloop são a recomendação concreta para começar em Ribeirão Preto: **competitivos, mas deliberadamente acima do piso de freelancer** — preço baixo demais atrai cliente ruim e mata a percepção de "estúdio técnico".

### Sites e landing pages

| Oferta | Faixa de mercado | **Preço Outloop (lançamento)** |
|---|---|---|
| Landing page profissional | R$ 1.200–4.000 (faixa total ~R$ 500–7.100) | **R$ 2.200** fechado |
| Site institucional (até 5 páginas) | R$ 3.000–6.000 (agências); WordPress completo até R$ 20.000 | **R$ 4.500** fechado |
| Manutenção/hospedagem gerenciada | R$ 300–1.500/mês | **R$ 200/mês** (básico) ou **R$ 400/mês** (com até 2h de ajustes de conteúdo) |

**Justificativa:** R$ 2.200 e R$ 4.500 posicionam a Outloop no meio da faixa de agência — acima do freelancer de R$ 1.500 (sinaliza qualidade) e abaixo do teto local (facilita fechamento rápido enquanto não há portfólio extenso). A manutenção a R$ 200–400 é a porta de recorrência: preço fácil de aceitar, e cada site vendido vira MRR.

### Automação de processos

| Pacote | Referência de mercado | **Setup Outloop** | **Mensalidade Outloop** |
|---|---|---|---|
| **Essencial** | Automação n8n avulsa R$ 400–2.500 + manutenção R$ 200–900/mês | **R$ 2.500** | **R$ 400/mês** |
| **Operação** (atendente IA WhatsApp) | Agências: R$ 8.000–20.000 setup + R$ 1.500–3.000/mês; freelancer: R$ 900–2.500 sem suporte | **R$ 6.000** | **R$ 800/mês** |
| **Escala** | Projetos com integração a sistemas internos: R$ 20.000–100.000 | **R$ 10.000** | **R$ 1.400/mês** |

**Justificativa:** o pacote Operação a R$ 6.000 + R$ 800/mês fica dentro da faixa recomendada pela pesquisa para posicionamento solo (R$ 4.000–12.000 + R$ 500–1.500/mês): 30–60% mais barato que as agências grandes, com o argumento "você fala direto com quem constrói, não com o júnior da agência" — e 3–6x acima do freelancer avulso, justificado por diagnóstico, treinamento, SLA e suporte contínuo em contrato. **Piso inegociável de mensalidade: R$ 400.** Mensalidade abaixo disso não paga o custo de atenção do cliente.

### Sistemas sob medida

| Faixa | Referência de mercado | **Preço Outloop** |
|---|---|---|
| **P — Ferramenta focada** | Freelancer: R$ 1.500–5.000 (sem processo); software house: piso ~R$ 40.000 | **R$ 8.000–12.000** |
| **M — Operação** | Faixa realista solo: R$ 8.000–30.000 | **R$ 14.000–20.000** |
| **G — Sistema integrado** | Software house pequeno porte: R$ 40.000–150.000 | **R$ 22.000–35.000** |
| Manutenção mensal opcional | — | **R$ 500–900/mês** conforme faixa |

**Justificativa:** a Outloop ocupa o vazio de mercado entre o freelancer (barato, sem contrato, sem processo, "bus factor 1") e a software house (piso de R$ 40 mil, inacessível para PME). Preço sempre comunicado **por faixa no primeiro contato** e fechado por escopo após o diagnóstico — nunca por hora.

**Nota fiscal e impostos:** todos os preços pressupõem emissão de NFS-e (Outloop como ME no Simples Nacional; ISS de informática em Ribeirão Preto: 2%, recolhido dentro do DAS). Preço é sempre com nota — isso é argumento de venda contra o freelancer informal, não custo escondido.

---

## 3. Oferta de entrada: Diagnóstico Gratuito de Automação (30 min)

É o padrão que funciona no setor — e ofertas de diagnóstico gratuito no anúncio tendem a reduzir bastante o CPL vs. oferta de venda direta (estimativa interna; validar com dados próprios nas primeiras 4–8 semanas). A regra de ouro: **não pode parecer reunião de vendas disfarçada.** Tem escopo definido, duração definida e entregável concreto.

### O que o cliente recebe

1. **Reunião de 30 minutos** (presencial em Ribeirão Preto/região ou vídeo) com o especialista que vai construir a solução — não com um vendedor.
2. **Relatório-diagnóstico em PDF, entregue em até 48h**, contendo:
   - Os **3 maiores gargalos** mapeados na operação do cliente;
   - **Estimativa de horas/semana perdidas** em cada um (estimativas de mercado, sem fonte verificada, apontam algo na casa de 10–15h/semana em tarefas repetitivas — validar no diagnóstico com dados do próprio cliente);
   - **1 "quick win"**: uma melhoria que o cliente pode fazer sozinho, de graça, hoje (gera reciprocidade e prova que o diagnóstico não é isca vazia);
   - **Proposta objetiva**: o que a Outloop automatizaria primeiro, com escopo, prazo e preço fechados.

### Roteiro do diagnóstico (30 min)

| Tempo | Bloco | Perguntas-chave |
|---|---|---|
| 0–3 min | Abertura | Citar a origem do contato; confirmar o objetivo: "sair daqui com um mapa dos seus 3 maiores gargalos — sem compromisso". |
| 3–12 min | Mapeamento da dor | "Qual tarefa consome mais tempo da sua equipe toda semana?" / "Como um cliente novo chega até vocês e o que acontece do primeiro contato até fechar?" / "Onde vocês perdem cliente hoje: demora pra responder, falta de follow-up, no-show?" |
| 12–20 min | Contexto e volume | Segmento e tamanho da equipe; volume (atendimentos/dia, leads/mês, consultas/semana); ferramentas atuais (planilha, agenda, sistema, só WhatsApp?); o que já tentaram. |
| 20–25 min | Priorização | Repetir de volta os 3 gargalos identificados e validar: "Se eu resolvesse só UM desses amanhã, qual mudaria mais o seu mês?" Confirmar urgência e quem decide/assina. |
| 25–30 min | Próximos passos | Explicar o que vem no relatório em 48h; adiantar a faixa de investimento do pacote provável (evita proposta-surpresa); **agendar na hora a conversa de apresentação da proposta, oferecendo 2 horários concretos** — nunca "te chamo depois". |

### Regras de operação do diagnóstico

- **Pré-qualificação antes de agendar** (no WhatsApp, 4 perguntas: segmento → tamanho da equipe → maior gargalo → urgência). Filtra curiosos e protege a agenda.
- **Responder o lead em até 5 minutos em horário comercial** (resposta em 5 min aumenta ~21x a chance de qualificação vs. 30 min; a média das empresas brasileiras passa de 24h — a velocidade já é o produto).
- **Usar a própria operação como demonstração:** o lead que foi qualificado pelo bot da Outloop em segundos já experimentou o serviço. Falar isso explicitamente no diagnóstico: "essa conversa rápida que você teve ao chamar no WhatsApp? Foi automatizada. É isso que eu monto pra você."
- Máximo de diagnósticos/semana definido pelo fundador (sugestão inicial: 5) para não canibalizar horas de entrega.

---

## 4. Pacotes combinados

Combos com desconto embutido (o desconto vive no pacote, não na negociação). Nomes orientados a resultado, alinhados aos nichos prioritários:

| Pacote | Composição | Preço avulso | **Preço combo** | Para quem |
|---|---|---|---|---|
| **Presença Completa** | Landing page + Automação Essencial | R$ 4.700 setup + R$ 600/mês | **R$ 3.900 setup + R$ 500/mês** | Comércio/serviços locais que precisam aparecer e parar de perder mensagem |
| **Atendimento 24/7** | Site institucional + Atendente IA (Operação) | R$ 10.500 setup + R$ 1.200/mês | **R$ 8.900 setup + R$ 1.000/mês** | Clínicas e escritórios: site profissional + agenda confirmada sem secretária digitar nada |
| **Clínica Sem No-Show** | Landing page de captação + Operação com fluxo de agendamento, confirmação e lembrete | R$ 8.200 setup + R$ 1.000/mês | **R$ 6.900 setup + R$ 800/mês** | Odonto/estética/médicas — o combo bandeira do nicho carro-chefe |
| **Lead em 1 Minuto** | Operação configurada para resposta automática a leads de portais + qualificação IA + follow-up | R$ 6.000 setup + R$ 800/mês | **R$ 6.000 setup + R$ 800/mês** (sem desconto — urgência do mercado imobiliário aquecido sustenta preço cheio) | Imobiliárias (RP lidera o estado em lançamentos e vendas em 2025) |
| **Operação Digital** | Sistema faixa M + Automação Operação integrada | a partir de R$ 20.000 + R$ 1.300/mês (R$ 800 da automação + R$ 500 de manutenção do sistema) | **a partir de R$ 17.000 + R$ 1.000/mês** (automação com 50% off no setup: R$ 14.000 + R$ 3.000; a mensalidade combinada sai mais barata que a avulsa) | PME estruturada que quer CRM próprio + atendimento automatizado |

**Regra do combo:** o desconto incide sobre o setup, nunca derruba a mensalidade abaixo do piso (R$ 400) — o MRR é o ativo do negócio.

---

## 5. Política de pagamento

### Projetos fechados (sites, sistemas, setup de automação)

- **Padrão 50/50:** 50% na assinatura do contrato (condição para entrar na fila de produção), 50% na entrega/aceite.
- **Sistemas acima de R$ 14.000 (faixas M e G):** 40% na assinatura / 30% no marco intermediário (protótipo aprovado ou primeira entrega funcional) / 30% no aceite final. Vincular pagamento a marcos protege os dois lados.
- Nenhum projeto entra em produção sem o primeiro pagamento confirmado. Sem exceção — nem para conhecido.

### Mensalidades

- Cobrança recorrente automática, vencimento único (dia 5 ou 10), com nota fiscal.
- Inadimplência: lembrete automático no vencimento e em D+3; suspensão dos serviços recorrentes em D+15; religação sem multa até D+30. (A régua de cobrança da Outloop é automatizada — mais uma vez, a operação é a vitrine do produto.)
- Fidelidade mínima de 3 meses na mensalidade de automação (cobre o custo de estabilização); depois, cancelamento com aviso de 30 dias, sem multa.

### Meios de pagamento e ferramenta

- **Ferramenta recomendada: Asaas** — melhor combinação para o modelo da Outloop: cobrança recorrente nativa, Pix (R$ 1,99/transação, com 100 Pix gratuitos/mês), boleto (R$ 1,99), cartão de crédito (2,99% + R$ 0,49) e API para automatizar a própria régua de cobrança.
- **Pix é o meio preferencial** (custo quase zero; incentivado pela política de desconto abaixo). **InfinitePay** como alternativa/backup pelo Pix a taxa 0%.
- **Cartão de crédito**: aceito para setup e mensalidade; em setups parcelados no cartão (até 6x), a taxa da maquininha/gateway é embutida no preço parcelado — o preço à vista via Pix é sempre o menor.
- **Stripe** apenas se/quando surgir cliente internacional ou cobrança em outra moeda — não usar como padrão nacional.

### Repasse de custos variáveis (cláusula obrigatória em contrato)

- WhatsApp Business API (cobrança por mensagem-template), APIs de IA (OpenAI/Anthropic) e VPS/hospedagem de automação: **contratados em nome do cliente** (preferencial — cliente é dono das próprias contas, o que também neutraliza a objeção de dependência) **ou** pagos pela Outloop e **reembolsados com margem administrativa de 20%**, discriminados na fatura mensal.
- Ordem de grandeza comunicada na proposta para não haver surpresa: VPS R$ 50–200/mês; IA generativa ~R$ 0,02–0,15 por interação; WhatsApp API conforme volume de templates.

---

## 6. Regras de desconto e garantias

### Descontos — quando SIM (lista fechada; fora dela, o preço é o preço)

| Situação | Desconto | Condição |
|---|---|---|
| **Clientes fundadores** (5 primeiros contratos de automação) | 15% no setup | Contrapartida obrigatória em contrato: depoimento + case com números (horas economizadas, tempo de resposta) e autorização de uso do nome/logo. É investimento em prova social local, não desconto. |
| Pagamento 100% antecipado (projetos fechados) | 5% | Via Pix. |
| Mensalidade pré-paga anual | 10% (equivale a ~1 mês grátis) | Pagamento único antecipado. |
| Pacote combinado | Já embutido nas tabelas da Seção 4 | Não acumula com outros descontos de setup. |
| Indicação que fecha contrato | R$ 500 de crédito em mensalidade para quem indicou | Válido para clientes ativos; contadores e agências de marketing parceiros têm programa próprio de comissão recorrente (10% da mensalidade nos 12 primeiros meses do indicado). |

### Descontos — quando NÃO (regras de proteção de margem)

- **Nunca** descontar por pressão de negociação sem contrapartida. Se o cliente não tem orçamento para o pacote, a resposta é **reduzir escopo, não preço** (ex.: começar pelo Essencial em vez do Operação).
- **Nunca** derrubar a mensalidade abaixo de R$ 400. Preferir bonificar setup a tocar no MRR.
- **Nunca** trabalhar "de graça pra fazer portfólio" sem contrato: o programa de clientes fundadores já cumpre esse papel com margem.
- Descontos não são acumuláveis entre si (aplica-se o maior).

### Garantias (neutralizam o risco de contratar um estúdio novo e solo)

1. **Garantia de prazo — sites e landing pages:** entrega no prazo contratado (7 dias úteis para LP, 15–20 para site, contados da aprovação do conteúdo) **ou 10% de desconto por semana de atraso causado pela Outloop**, limitado a 30%. Atrasos por pendência do cliente (conteúdo, aprovações) pausam o relógio — registrado por escrito.
2. **Garantia de produção — automação:** se a automação contratada **não entrar em produção em até 30 dias** após o kickoff por responsabilidade da Outloop, o cliente escolhe entre **reembolso integral do setup** ou continuidade sem custo até a entrega. (Alinhado à prática de mercado de garantias de 7–30 dias — e viável porque o pacote Operação promete 3–4 semanas.)
3. **Garantia de adoção — automação:** revisões mensais incluídas nos primeiros 90 dias; se a equipe do cliente não estiver usando, a Outloop refaz o treinamento sem custo. Entrega e abandono ("instala e some") é o erro nº 1 do setor — a garantia transforma isso em diferencial.
4. **Garantia de correção — sistemas sob medida:** 30 dias de correção gratuita de bugs após o aceite de cada marco.
5. **Garantia de independência (anti-"bus factor"):** todo contrato prevê propriedade intelectual do que foi encomendado para o cliente (regra da Lei 9.609/98, com reserva expressa das bibliotecas e componentes próprios da Outloop), cláusula LGPD com a Outloop como operadora de dados, SLA de resposta por escrito e **entrega de documentação + credenciais**. Argumento de venda explícito: "se amanhã você quiser trocar de fornecedor, tudo é seu e está documentado."

### Como comunicar preço na conversa comercial (script curto)

- No WhatsApp/diagnóstico, informar **faixa** ("um atendente IA como esse fica na faixa de R$ 6 mil de implantação + R$ 800/mês") — nunca esconder preço até a proposta; isso filtra desqualificados cedo e economiza diagnóstico.
- Ancorar sempre contra as alternativas: "agência grande cobra R$ 8 a 20 mil de implantação e você fala com o júnior; freelancer cobra R$ 900 e some depois da entrega; a Outloop fica no meio, com contrato, garantia e o especialista no seu WhatsApp."
- Converter preço em resultado de processo: "R$ 800/mês para responder todo lead em segundos, 24/7, e confirmar 100% das consultas sem ninguém digitar" — nunca prometer resultado absoluto de faturamento.

---

## Anexo — Resumo de bolso (tabela única para consulta rápida)

| Oferta | Setup / Projeto | Mensalidade | Prazo |
|---|---|---|---|
| Landing page | R$ 2.200 | R$ 200–400 (manutenção) | 7 dias úteis |
| Site institucional | R$ 4.500 | R$ 200–400 (manutenção) | 15–20 dias úteis |
| Automação Essencial | R$ 2.500 | R$ 400 | até 2 semanas |
| Automação Operação (IA WhatsApp) | R$ 6.000 | R$ 800 | 3–4 semanas |
| Automação Escala | R$ 10.000 | R$ 1.400 | 4–6 semanas |
| Sistema faixa P | R$ 8.000–12.000 | R$ 500–900 (opcional) | 3–5 semanas |
| Sistema faixa M | R$ 14.000–20.000 | R$ 500–900 (opcional) | 6–10 semanas |
| Sistema faixa G | R$ 22.000–35.000 | R$ 500–900 (opcional) | 10–16 semanas |
| Diagnóstico de automação | Gratuito (30 min + relatório em 48h) | — | agendado em até 5 dias |

**Revisão deste documento:** reavaliar preços após os 5 primeiros contratos fechados (clientes fundadores) ou em 90 dias, o que vier primeiro — usando CPL real das campanhas, taxa de fechamento do diagnóstico e margem efetiva por pacote.