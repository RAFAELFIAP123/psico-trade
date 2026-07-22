# Ecossistema de Performance para Traders

> O trader já sabe o que precisa fazer — falta ele enxergar o que está fazendo.

Um produto de tecnologia que transforma comportamento em dado. Não ensina, não aconselha, não faz terapia. **Espelha.**

---

## O Produto em 3 Camadas

| Camada | Função | Fase |
|---|---|---|
| **Diário Inteligente** | Registro estruturado de operações + contexto emocional | MVP (v1) |
| **Circuit Breaker** | Trava de proteção contra comportamento impulsivo | v2 |
| **Score de Saúde** | Métrica de disciplina e processo, independente do P&L | v3 |

📄 Detalhamento completo em [`docs/05-ecossistema-de-performance.md`](docs/05-ecossistema-de-performance.md)

---

## Documentação do Processo

| # | Documento | Descrição |
|---|---|---|
| 01 | [`Dores do Trader no Brasil`](docs/01-dores-do-trader-brasil.md) | Levantamento amplo de dores + decisão de foco |
| 02 | [`Aspectos Emocionais e Psicológicos`](docs/02-aspectos-emocionais-e-psicologicos.md) | Destrinchamento da dor selecionada em 9 componentes |
| 03 | [`Soluções por Produto/Serviço`](docs/03-solucoes-produto-servico.md) | 6 soluções levantadas, o que avançou e o que foi descartado |
| 04 | [`Mapeamento Dores × Soluções`](docs/04-mapeamento-dores-solucoes.md) | Estrutura do diagrama visual + matriz de conexões |
| 05 | [`Ecossistema de Performance`](docs/05-ecossistema-de-performance.md) | Filosofia, 3 camadas, tese do registro, estratégia de build |

---

## Frentes de Ação

### Frente 1 — Validação com o Mercado

Confirmar que a dor é real e compartilhada por traders suficientes para sustentar um produto.

| Tarefa | Status |
|---|---|
| Elaborar formulário de pesquisa com perguntas-chave | ⬜ Não iniciado |
| Mapear comunidades-alvo para distribuição (Reddit, Telegram, X/FinTwit BR) | ⬜ Não iniciado |
| Distribuir pesquisa e coletar respostas (meta: 50+) | ⬜ Não iniciado |
| Selecionar 15-20 traders para entrevista qualitativa (iniciante, intermediário, consistente) | ⬜ Não iniciado |
| Realizar entrevistas e documentar achados | ⬜ Não iniciado |
| Mapear o que traders já usam hoje para registro (planilha, caderno, app, nada) | ⬜ Não iniciado |
| Levantar disposição de pagamento (quanto pagariam, modelo preferido) | ⬜ Não iniciado |
| Consolidar relatório de validação com conclusões | ⬜ Não iniciado |

---

### Frente 2 — Análise Competitiva

Mapear o que já existe, onde funciona, onde falha e onde está o espaço vazio.

| Tarefa | Status |
|---|---|
| Listar concorrentes diretos internacionais (TraderSync, Tradervue, Edgewonk) | ⬜ Não iniciado |
| Listar concorrentes diretos nacionais (Trademetria, outros) | ⬜ Não iniciado |
| Testar cada produto (criar conta, usar como trader real) | ⬜ Não iniciado |
| Mapear features de cada um (registro, emocional, analytics, integrações) | ⬜ Não iniciado |
| Identificar pontos fracos e reclamações recorrentes (reviews, fóruns) | ⬜ Não iniciado |
| Analisar modelos de preço e monetização de cada concorrente | ⬜ Não iniciado |
| Identificar diferencial: por que traders ainda usam planilha se esses produtos existem? | ⬜ Não iniciado |
| Documentar análise comparativa com matriz de features | ⬜ Não iniciado |

---

### Frente 3 — Definição do MVP do Diário

Definir o escopo mínimo que entrega valor real. Cortar até doer.

| Tarefa | Status |
|---|---|
| Definir campos obrigatórios do registro de operação (ativo, entrada, saída, resultado) | ⬜ Não iniciado |
| Definir campos do registro emocional (escala, sim/não, campo aberto limitado) | ⬜ Não iniciado |
| Decidir entrada de dados v1: manual ou integração com corretora | ⬜ Não iniciado |
| Definir output mínimo: o que o trader vê depois de registrar (resumo diário, semanal) | ⬜ Não iniciado |
| Especificar os primeiros padrões que o sistema deve detectar e mostrar | ⬜ Não iniciado |
| Escrever user stories do fluxo principal (registrar → revisar → aprender) | ⬜ Não iniciado |
| Definir o que NÃO entra no MVP (lista de exclusão explícita) | ⬜ Não iniciado |
| Documentar especificação funcional do MVP | ⬜ Não iniciado |

---

### Frente 4 — Arquitetura Técnica e Stack

Fundação técnica que suporte as 3 camadas sem retrabalho.

| Tarefa | Status |
|---|---|
| Decidir plataforma: web, mobile nativo, PWA ou híbrido | ⬜ Não iniciado |
| Definir stack de frontend | ⬜ Não iniciado |
| Definir stack de backend e API | ⬜ Não iniciado |
| Escolher banco de dados (relacional, NoSQL, ou combinação) | ⬜ Não iniciado |
| Modelar dados: operações, registros emocionais, regras de circuit breaker, score | ⬜ Não iniciado |
| Pesquisar APIs de corretoras brasileiras (quais têm API aberta, viabilidade CEI/B3) | ⬜ Não iniciado |
| Definir infraestrutura cloud e estimativa de custo inicial | ⬜ Não iniciado |
| Definir estratégia de autenticação e segurança de dados financeiros | ⬜ Não iniciado |
| Documentar ADRs (Architecture Decision Records) das escolhas feitas | ⬜ Não iniciado |

---

### Frente 5 — Prototipagem Visual

Desenhar antes de codar. Reduzir retrabalho e alinhar visão entre fundadores.

| Tarefa | Status |
|---|---|
| Definir fluxo principal do usuário (user flow completo) | ⬜ Não iniciado |
| Criar wireframes de baixa fidelidade das telas principais | ⬜ Não iniciado |
| Criar protótipo navegável (Figma ou equivalente) | ⬜ Não iniciado |
| Testar protótipo com 5-10 traders reais ("você usaria isso?") | ⬜ Não iniciado |
| Iterar com base no feedback | ⬜ Não iniciado |
| Definir identidade visual básica (cores, tipografia, tom) | ⬜ Não iniciado |
| Documentar decisões de UX e feedback coletado | ⬜ Não iniciado |

---

### Frente 6 — Modelo de Negócio e Monetização

Como o produto se sustenta. Influencia decisões técnicas e de produto.

| Tarefa | Status |
|---|---|
| Definir modelo principal: freemium, assinatura fixa, por volume, ou híbrido | ⬜ Não iniciado |
| Definir o que é gratuito vs. o que é pago | ⬜ Não iniciado |
| Avaliar viabilidade B2B: corretoras como canal de distribuição | ⬜ Não iniciado |
| Pesquisar disposição de pagamento do público-alvo (cruza com Frente 1) | ⬜ Não iniciado |
| Estimar custos operacionais mensais (infra, manutenção, suporte) | ⬜ Não iniciado |
| Projetar cenários de receita (pessimista, base, otimista) | ⬜ Não iniciado |
| Documentar modelo de negócio (canvas ou similar) | ⬜ Não iniciado |

---

### Frente 7 — Conteúdo e Posicionamento

Construir autoridade antes do produto existir. Captar early adopters.

| Tarefa | Status |
|---|---|
| Definir canal principal (blog, newsletter, X/Twitter, Instagram, ou combinação) | ⬜ Não iniciado |
| Definir tom de voz e posicionamento editorial | ⬜ Não iniciado |
| Criar calendário inicial de conteúdo (4-8 semanas) | ⬜ Não iniciado |
| Produzir primeiros conteúdos sobre psicologia do trader e poder do registro | ⬜ Não iniciado |
| Criar landing page de captura (email de early adopters) | ⬜ Não iniciado |
| Medir engajamento e ajustar mensagem com base no que ressoa | ⬜ Não iniciado |
| Documentar aprendizados de posicionamento | ⬜ Não iniciado |

---

## Progresso Geral

| Frente | Tarefas | Concluídas | Status |
|---|---|---|---|
| 1. Validação com o Mercado | 8 | 0 | 🔲 Não iniciado |
| 2. Análise Competitiva | 8 | 0 | 🔲 Não iniciado |
| 3. Definição do MVP | 8 | 0 | 🔲 Não iniciado |
| 4. Arquitetura Técnica | 9 | 0 | 🔲 Não iniciado |
| 5. Prototipagem Visual | 7 | 0 | 🔲 Não iniciado |
| 6. Modelo de Negócio | 7 | 0 | 🔲 Não iniciado |
| 7. Conteúdo e Posicionamento | 7 | 0 | 🔲 Não iniciado |
| **Total** | **54** | **0** | — |
