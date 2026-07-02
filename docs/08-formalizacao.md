# Formalização e Operação Legal — Outloop

Documento de trabalho para o fundador (Pedro). Objetivo: sair da informalidade e operar a Outloop com CNPJ, nota fiscal, contrato e recebimento profissional — do jeito mais barato e rápido possível, sem criar passivo tributário ou jurídico. Referência geográfica: Ribeirão Preto - SP.

---

## 1. MEI ou ME? Resposta direta

**MEI não serve para a Outloop. Ponto final.**

Dois motivos, e o primeiro já encerra a discussão:

1. **Atividade não permitida.** Desenvolvimento de software — sistemas, aplicativos e sites sob encomenda (CNAEs 6201/6204) — **não está na lista de ocupações permitidas ao MEI**. Emitir nota como MEI para esse tipo de serviço é enquadramento irregular, com risco de desenquadramento retroativo e cobrança de impostos como ME.
2. **Teto de faturamento incompatível.** O limite do MEI segue em **R$ 81.000/ano (R$ 6.750/mês)** em 2026, inalterado desde 2019. Há projetos de lei para elevar o teto, mas nada aprovado. Com a meta de tickets de setup + mensalidade da Outloop, esse teto seria estourado rapidamente — e estourar o teto gera recolhimento complementar e dor de cabeça.

**Recomendação: abrir direto uma SLU (Sociedade Limitada Unipessoal), enquadrada como ME, optante do Simples Nacional.** A SLU é a estrutura ideal para fundador solo:

- Não exige sócio;
- Não exige capital social mínimo;
- Separa o patrimônio pessoal do patrimônio da empresa (responsabilidade limitada) — importante quando você assina contratos com cláusula de responsabilidade e acessa dados de clientes.

---

## 2. Passo a passo de abertura

### 2.1 Roteiro

| # | Etapa | Quem faz | Prazo típico |
|---|-------|----------|--------------|
| 1 | Contratar contabilidade online (ver 2.2) | Pedro | 1 dia |
| 2 | Definir CNAEs, endereço fiscal e nome empresarial ("Outloop" como nome fantasia) | Pedro + contador | 1–2 dias |
| 3 | Viabilidade + registro na JUCESP via Redesim/Via Rápida Empresa | Contador | dentro do prazo total |
| 4 | CNPJ + Inscrição Municipal em Ribeirão Preto | Contador | dentro do prazo total |
| 5 | Opção pelo Simples Nacional | Contador | logo após o CNPJ (há prazo legal — não deixar passar) |
| 6 | Certificado digital A1 (faixa típica R$ 150–300/ano, estimativa) | Pedro | 1 dia (videoconferência) |
| 7 | Credenciamento no sistema de NFS-e da prefeitura (ISS.Net) | Pedro + contador | 1–3 dias |
| 8 | Conta PJ + meio de recebimento (ver seção 6) | Pedro | 1–3 dias |

**Prazo total típico: 1 a 3 semanas** (estimativa — depende da fila da JUCESP e da prefeitura).

### 2.2 Custos

- **Contabilidade online:** Contabilizei a partir de ~R$ 195/mês; Agilize a partir de ~R$ 259/mês. Ambas costumam fazer a **abertura sem cobrar honorários** (você paga só as taxas públicas), condicionada à contratação do plano mensal.
- **Custo total de abertura (contabilidade + taxas públicas):** tipicamente entre **R$ 500 e R$ 3.000**. Com contador online, tende a ficar no piso dessa faixa.
- **Certificado digital A1:** R$ 150–300/ano (estimativa).

**Recomendação prática:** contabilidade online resolve bem a fase inicial da Outloop (serviços, sem funcionários, sem estoque). Se preferir alguém local para ter relacionamento — e lembrando que contadores são também um **canal de indicação de clientes** para a Outloop —, um escritório contábil de Ribeirão Preto na mesma faixa de preço é alternativa válida. Não pague mais de ~R$ 400/mês nessa fase.

---

## 3. CNAEs recomendados

| CNAE | Descrição | Papel na Outloop |
|------|-----------|------------------|
| **6201-5/01** (principal) | Desenvolvimento de programas de computador sob encomenda | Sistemas sob medida, automações, sites — o core |
| 6204-0/00 | Consultoria em tecnologia da informação | Diagnóstico de automação, consultoria de processos |
| 6202-3/00 | Desenvolvimento e licenciamento de programas customizáveis | Soluções produtizadas (ex.: pacote de atendente IA replicável) |
| 6209-1/00 | Suporte técnico e manutenção em TI | Mensalidades de manutenção/suporte |

**Atenção ao 7319-0/03 (marketing direto):** só adicione se a Outloop de fato prestar serviço de marketing/prospecção para terceiros. Esse CNAE **não** tem o mesmo tratamento tributário dos CNAEs de TI e pode complicar o enquadramento. Na dúvida, deixe de fora no início — adicionar CNAE depois é uma alteração contratual simples.

---

## 4. Simples Nacional: Anexo III vs Anexo V e o Fator R (explicado sem contabilês)

Os CNAEs de TI da Outloop podem cair em dois "anexos" (tabelas de alíquota) do Simples Nacional:

- **Anexo V:** alíquota inicial de **15,5%** sobre o faturamento. É o padrão se você não fizer nada.
- **Anexo III:** alíquota inicial de **6%**. É onde você quer estar.

O que decide é o **Fator R**:

> **Fator R = folha de salários dos últimos 12 meses (incluindo seu pró-labore + encargos) ÷ receita bruta dos últimos 12 meses.**
>
> - Fator R **≥ 28%** → Anexo III (6% inicial)
> - Fator R **< 28%** → Anexo V (15,5% inicial)

Traduzindo: **se você se pagar um pró-labore de pelo menos ~28% do que a empresa fatura, o imposto da empresa cai de 15,5% para 6% na primeira faixa.**

### Exemplo numérico

Suponha faturamento de **R$ 15.000/mês** (R$ 180.000/ano — teto da primeira faixa do Simples):

| Cenário | Pró-labore | Fator R | Anexo | Imposto (DAS) no ano |
|---------|-----------|---------|-------|----------------------|
| Sem planejamento | R$ 1.518 (salário mínimo, ~10% do faturamento) | < 28% | V (15,5%) | ~R$ 27.900 |
| Com planejamento | R$ 4.200/mês (28% do faturamento) | ≥ 28% | III (6%) | ~R$ 10.800 |

Diferença: **9,5 pontos percentuais, cerca de R$ 17.100/ano** numa receita de R$ 180 mil.

**A pegadinha:** sobre o pró-labore incidem **11% de INSS** e, acima da faixa de isenção, **IRPF**. Ou seja, parte da economia do DAS "volta" como tributo sobre o pró-labore. Na grande maioria dos cenários a conta líquida **ainda compensa muito**, mas o valor ótimo de pró-labore depende do seu faturamento real — **peça ao contador uma simulação Anexo III vs V antes de fixar o valor**, e revise a cada trimestre conforme o faturamento cresce.

**Regra operacional para a Outloop:** fixar pró-labore em ~28% do faturamento bruto médio e monitorar o Fator R mensalmente com o contador (ele é calculado sobre a janela móvel de 12 meses — um mês de faturamento alto pode te derrubar do Anexo III se o pró-labore não acompanhar).

Nota: o **ISS já está incluído dentro do DAS** no Simples — você não paga ISS por fora. A alíquota de referência de Ribeirão Preto para serviços de informática (item 1 da lista) é de **2%** (Decreto 306/2005 — confirmar vigência com o contador).

---

## 5. Emissão de NFS-e em Ribeirão Preto

Toda venda da Outloop (setup, mensalidade, projeto) exige nota fiscal de serviço. Em Ribeirão Preto:

- O sistema é o **ISS.Net (Nota Control)** da Prefeitura, já atualizado ao **padrão nacional da Reforma Tributária**.
- Pré-requisitos: **inscrição municipal** (sai na abertura via Redesim/Via Rápida Empresa) e **certificado digital A1** para autenticação.
- Ao emitir, hoje é obrigatório informar **três classificações**: a atividade municipal (ISS), o **Código de Tributação Nacional** e a **NBS** (nomenclatura de serviços). Configure isso **uma vez, com o contador**, para cada tipo de serviço da Outloop (desenvolvimento, consultoria, suporte/manutenção) e depois só reaproveite.
- Rotina recomendada: emitir a NFS-e **no ato de cada recebimento** (ou na virada do mês para as mensalidades), e nunca receber sem emitir — mensalidade sem nota é o erro clássico que vira problema na primeira fiscalização ou no primeiro cliente que pede a nota retroativa.
- Radar: a **Reforma Tributária (LC 214/2025)** inicia em 2026 a transição do ISS/PIS/COFINS para IBS/CBS. Isso já mudou o layout das notas e vai exigir acompanhamento contábil nos próximos anos — mais um motivo para ter contador ativo, não só "emissor de guia".

---

## 6. Conta PJ e recebimentos

### 6.1 Conta PJ

Abrir conta PJ digital gratuita (as contabilidades online costumam indicar parceiros na própria abertura). Regra de ouro: **nenhum recebimento da Outloop na conta física**. Toda entrada na PJ, pró-labore transferido para a PF mensalmente. Isso protege o Fator R, a contabilidade e a limitação de responsabilidade da SLU.

### 6.2 Ferramenta de cobrança — recomendação

O modelo da Outloop é **setup (valor único) + mensalidade recorrente**, com clientes 100% nacionais. Comparativo:

| Ferramenta | Pix | Boleto | Cartão | Recorrência | Veredito |
|------------|-----|--------|--------|-------------|----------|
| **Asaas** | R$ 0,99 (3 primeiros meses), depois R$ 1,99/transação; 100 Pix grátis/mês | R$ 1,99 | 2,99% + R$ 0,49 | **Forte** (cobrança recorrente nativa, régua de cobrança, API) | **Recomendada como principal** |
| InfinitePay | **0%** | — | débito ~0,75%+, crédito parcelado ~2,6%+ | Limitada | Boa para Pix avulso barato |
| Stripe | 1,19% | — | 3,99% + R$ 0,39 (+2% internacional) | Forte, mas cara no BR | Só se surgir cliente internacional/SaaS |

**Recomendação: Asaas como plataforma principal.** Motivos alinhados ao negócio:

1. **Cobrança recorrente nativa** — a mensalidade da Outloop é o ativo do negócio; o Asaas gera as cobranças mensais automaticamente com régua de lembretes (e reduz inadimplência sem você cobrar ninguém no WhatsApp);
2. **Boleto + Pix + cartão no mesmo lugar** — PME tradicional (clínica, imobiliária, escritório) ainda pede boleto;
3. **API completa** — a Outloop vende automação; automatizar a própria cobrança via API do Asaas vira **case demonstrável** ("a cobrança que você recebeu foi 100% automática — é isso que eu implemento").

Padrão de cobrança sugerido: **setup em 2 parcelas (50% na assinatura do contrato, 50% na entrega/aceite) via Pix ou boleto; mensalidade via cobrança recorrente com vencimento fixo (dia 5 ou 10)**.

---

## 7. Contrato de prestação de serviços — cláusulas essenciais

Um único modelo bom, **revisado uma vez por advogado**, reaproveitado em todos os projetos (com anexo de escopo variável). Isso também neutraliza a objeção clássica contra fornecedor solo ("e se ele sumir?"): contrato com PI, LGPD e SLA é postura de empresa, não de freelancer.

### 7.1 Escopo e mudanças de escopo
- **Anexo de Escopo** por projeto: funcionalidades listadas, especificações, o que está **fora** do escopo (tão importante quanto o que está dentro), e **critérios de aceite objetivos** por entrega ("a automação X dispara a mensagem Y quando ocorre Z").
- **Cláusula de mudança de escopo (change request):** qualquer alteração ou adição é formalizada por escrito (e-mail/WhatsApp vale, se o contrato disser que vale), com novo prazo e novo preço acordados **antes** da execução. Sem isso, todo projeto fechado vira poço sem fundo.

### 7.2 Prazos e marcos
- Cronograma com **marcos de entrega** (ex.: semana 1 diagnóstico/desenho; semana 2–3 implementação; semana 4 homologação e go-live — coerente com o padrão de mercado de setup em 3–4 semanas).
- Prazo de aceite pelo cliente (ex.: 5 dias úteis para homologar; silêncio = aceite tácito) — evita projeto travado esperando o cliente testar.
- Prever que atrasos causados pelo cliente (não enviar acessos, conteúdo, aprovações) suspendem o prazo.

### 7.3 Pagamento
- Valores, forma (Pix/boleto/cartão via Asaas) e **pagamentos vinculados aos marcos** (50/50 no setup é um bom padrão).
- Mensalidade: o que ela cobre (hospedagem, monitoramento, ajustes até X horas/mês, suporte com SLA) e o que é cobrado à parte.
- **Custos variáveis de terceiros ficam fora do preço fixo:** API de IA (OpenAI/Anthropic), WhatsApp Business API (cobrada por mensagem-template desde 2025) e VPS são pagos diretamente pelo cliente **ou** reembolsados com margem administrativa de 15–20%. Absorver custo de API em mensalidade fixa é o erro que corrói margem silenciosamente.
- Multa e juros por atraso; **suspensão do serviço** (automação/hospedagem) após X dias de inadimplência, com aviso prévio.

### 7.4 Propriedade intelectual do código
- **Regra legal (Lei do Software, 9.609/98):** salvo cláusula escrita em contrário, o software desenvolvido sob encomenda **pertence ao contratante**.
- Portanto, o contrato da Outloop deve dizer expressamente: o cliente recebe a titularidade/licença do que foi desenvolvido **especificamente para ele**, mas a Outloop **retém a propriedade de suas bibliotecas, componentes, templates de fluxo (n8n/Make), prompts-base e ferramentas próprias**, licenciando o uso ao cliente. Sem essa cláusula, você juridicamente "doa" seus blocos reutilizáveis a cada projeto — e o modelo de automações-padrão replicáveis por nicho depende deles.
- Entrega de credenciais e documentação ao cliente no encerramento (mata o "bus factor 1" e é argumento de venda).

### 7.5 Confidencialidade
- Mútua, cobrindo dados comerciais, financeiros e técnicos de ambas as partes, vigente durante o contrato e por 2–5 anos após o término.

### 7.6 LGPD — atenção especial ao caso Outloop
Este ponto é crítico e específico do negócio: ao implantar atendente IA no WhatsApp, CRM ou automação de cobrança, **a Outloop acessa dados pessoais dos clientes dos seus clientes** (pacientes de clínica, leads de imobiliária, clientes de escritório). O contrato deve:
- Definir os papéis: **cliente = controlador** dos dados; **Outloop = operadora**, tratando dados somente conforme instruções do controlador;
- Prever medidas de segurança (acesso restrito, credenciais individuais, não usar dados reais em ambiente de teste sem autorização);
- Prever exclusão/devolução dos dados ao término do contrato;
- Vedar uso dos dados para qualquer outra finalidade (inclusive treinar modelos);
- Prever comunicação de incidentes de segurança ao controlador;
- Cuidado extra com **clínicas**: dados de saúde são **dados sensíveis** na LGPD — reforce as salvaguardas nesse nicho, que é justamente o carro-chefe.

### 7.7 Limitação de responsabilidade
- Responsabilidade da Outloop limitada ao valor pago pelo cliente nos últimos 12 meses (ou ao valor do projeto);
- Exclusão de lucros cessantes e danos indiretos;
- Sem garantia de resultado comercial (coerente com o tom da marca: promete-se **processo** — "responder em segundos, 24/7" —, nunca faturamento);
- Ressalva para indisponibilidade causada por terceiros (Meta/WhatsApp, provedores de API, hospedagem).

### 7.8 Garantia, suporte e rescisão
- Garantia pós-entrega delimitada (prazo de garantia de correção de defeitos: **30 dias após o aceite** — padrão comercial Outloop, conforme docs/02; negociável até o máximo de 90 dias em projetos de maior porte, mediante ajuste de preço; defeito ≠ funcionalidade nova);
- SLA de suporte na mensalidade (ex.: primeira resposta em até 1 dia útil);
- Rescisão: aviso prévio de 30 dias para contratos mensais; regras de multa para quebra de projeto fechado no meio; obrigações de transição (entrega de acessos, exportação de dados).

### 7.9 Foro
- **Foro da comarca de Ribeirão Preto - SP** para dirimir controvérsias, com renúncia a qualquer outro. Como a atuação inicial é local/regional, isso é natural e evita litigar fora de casa.

---

## 8. Ordem de execução recomendada (visão geral)

1. Contratar contabilidade online → abrir SLU/ME no Simples (CNAE 6201-5/01 + secundários).
2. Simular e fixar pró-labore ~28% do faturamento (Fator R / Anexo III).
3. Certificado A1 → credenciamento no ISS.Net → emitir uma NFS-e de teste com o contador.
4. Conta PJ + Asaas configurado (cobrança avulsa e recorrente).
5. Modelo de contrato revisado por advogado (uma vez) + modelo de Anexo de Escopo + modelo de proposta.
6. Só então escalar anúncios: **o funil (anúncio → WhatsApp → diagnóstico → proposta) deve desembocar em contrato assinado e nota emitida desde o cliente nº 1.**

---

## 9. Disclaimer

Este documento é um guia operacional baseado em pesquisa de mercado e fontes públicas, com valores e regras vigentes/estimados na data de elaboração. **Ele não substitui a orientação de um contador nem de um advogado.** Tributação (Fator R, anexos do Simples, ISS, Reforma Tributária/IBS-CBS), enquadramento de CNAE e cláusulas contratuais devem ser validados caso a caso por profissionais habilitados antes de qualquer decisão. Faixas de preço e prazos citados são referências de mercado e podem mudar.

---

## 10. Checklist: legal mínimo antes do primeiro contrato

- [ ] **1.** Contabilidade contratada (online ou local, ~R$ 195–400/mês) e responsável definido.
- [ ] **2.** SLU/ME aberta: CNPJ ativo, CNAE principal 6201-5/01 + secundários 6204-0/00, 6202-3/00 e 6209-1/00.
- [ ] **3.** Opção pelo Simples Nacional confirmada dentro do prazo.
- [ ] **4.** Pró-labore definido em ~28% do faturamento projetado (Fator R → Anexo III), com simulação do contador em mãos.
- [ ] **5.** Certificado digital A1 emitido e válido.
- [ ] **6.** Credenciamento no ISS.Net de Ribeirão Preto concluído, com atividade municipal, Código de Tributação Nacional e NBS configurados — e uma NFS-e de teste emitida com sucesso.
- [ ] **7.** Conta PJ aberta e Asaas configurado (cobrança avulsa + recorrente), com regra "todo recebimento na PJ, com nota".
- [ ] **8.** Modelo de contrato revisado por advogado, cobrindo: escopo/mudança de escopo, marcos e prazos, pagamento vinculado a marcos, PI (retenção de componentes próprios), confidencialidade, LGPD (Outloop como operadora), limitação de responsabilidade, garantia/SLA, rescisão e **foro em Ribeirão Preto**.
- [ ] **9.** Cláusula de repasse de custos variáveis (APIs de IA, WhatsApp Business API, VPS) incluída em todo contrato com mensalidade — nada de custo de terceiro dentro do preço fixo.
- [ ] **10.** Modelo de proposta comercial + Anexo de Escopo padronizados, para que todo diagnóstico gratuito termine em proposta formal — e todo fechamento em contrato assinado antes de qualquer linha de código.