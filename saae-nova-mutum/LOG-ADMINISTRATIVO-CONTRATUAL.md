# Log Administrativo, Contratual e de Relatórios — SAAE Nova Mutum

Este arquivo registra as atividades administrativas, contratuais e de relatórios desenvolvidas para o SAAE Nova Mutum. É separado do `LOG-DE-ATIVIDADES.md`, que trata de estratégia, conteúdo, roteiros e produção criativa.

## Objetivo

Manter um histórico organizado e enxuto de:
- Análises e alterações do Termo de Referência (TR) e do Contrato Nº 021/2025.
- Questões de renovação contratual.
- Relatórios mensais de desempenho (metodologia, dados utilizados, decisões editoriais).
- Regras de equilíbrio contratual (ex: régua de equivalência entre deliverables contratados e materiais especiais).
- Qualquer decisão com risco jurídico, financeiro ou institucional relacionada ao contrato com o SAAE.

Este log **não** deve conter: textos de posts, roteiros, prompts de arte, ou decisões puramente criativas — esse conteúdo pertence ao `LOG-DE-ATIVIDADES.md`.

## Regras de atualização

- Registrar as atividades em ordem cronológica decrescente, com as atualizações mais recentes no topo.
- Não apagar registros anteriores.
- Cada entrada deve indicar data, demanda, entregas, decisões, status e, quando houver, arquivos ou cláusulas relacionadas.
- Toda entrada deve identificar claramente qual assistente ou ferramenta realizou a atualização (ex: **Claude (Saulo)**, **ChatGPT**, **Antigravity**), já que mais de uma ferramenta pode atualizar este log em sessões diferentes.
- Utilizar linguagem objetiva e descritiva. Dados sensíveis (valores de contrato, disputas com o cliente) devem ser registrados com precisão, sem ambiguidade.

---

## 08/07/2026 — Antigravity (Gemini)

### Análise do Contrato Nº 021/2025 e do Termo de Referência Nº 040/2025

**Contexto da demanda:**
Pri trouxe a questão porque o cliente (SAAE) questionou a quantidade de publicações entregues em Maio/2026. A sessão foi iniciada para entender os limites contratuais e elaborar uma lógica de equilíbrio para justificar materiais extras produzidos fora do escopo padrão.

**Documentos analisados:**
- Contrato Nº 021/2025 (JUAN S. DAMACENO LTDA — Studio Virtually)
- Termo de Referência Nº 040/2025 — Serviço de Comunicação e Marketing Digital

**Metas contratuais mensais identificadas nos documentos:**
- 10 posts estáticos (incluindo carrosséis)
- 6 Reels
- 8 Stories
- 2 visitas presenciais mensais previstas no contrato
- 1 visita eventual extra de emergência, se necessária

**Regra discutida (não aprovada formalmente):**
Foi proposta uma lógica de equivalência para compensar materiais extras produzidos em Maio/2026 que não se encaixam diretamente na contagem padrão de posts. A ideia é que materiais de maior complexidade técnica ou de produção mais longa sejam contabilizados como equivalentes a mais de um post.

**Tabela de equivalência proposta (não é regra aprovada — ainda em discussão):**

| Material extra produzido | Equivalência proposta |
|---|---|
| Faixa/Fachada PEV 2 — Grande Porte, CMYK, alta resolução | 4 posts estáticos |
| Banner / Backdrop Semana do Meio Ambiente — Médio Porte | 3 posts estáticos |
| Vídeo PEV 2 — Reel extra editado | 3 posts estáticos |
| Adesivos variados — Semana do Meio Ambiente | 2 posts estáticos |

> ⚠️ Importante: esses valores foram discutidos e usados como base para o relatório de Maio, mas **não foram formalmente validados ou aprovados por Pri**. A tabela ainda precisa de revisão e aprovação antes de ser tratada como regra definitiva.

**Regra clara definida (essa sim confirmada por Pri):**
Visitas presenciais e coberturas de campo são itens com cláusula independente no contrato e **não entram** na lógica de compensação de posts — nem nas 2 visitas mensais previstas, nem na visita eventual de emergência.

**Relatórios e Entregas Administrativas:**
Foi desenvolvida e mantida uma estrutura dedicada de entregas no repositório `links`:
- **Portal do Cliente SAAE (`saae-nova-mutum/index.html`):** Interface estática e responsiva em glassmorphism que serve como centralizador de acessos para o cliente final (Ezaque/Cristiano). Organiza o acesso rápido para planejamentos e relatórios de desempenho.
- **Relatórios Mensais de Desempenho:**
  - *Relatório de Março/2026 (`saae-nova-mutum/relatorio-marco-2026/index.html`):* Primeiro relatório de métricas entregue no contrato.
  - *Relatório de Abril/2026 (`saae-nova-mutum/relatorio-abril-2026/index.html`):* Dados operacionais e de tráfego de abril.
  - *Relatório de Maio/2026 (`saae-nova-mutum/relatorio-maio-2026/index.html`):* Atualizado na sessão de 18/06 para incluir as tabelas propostas de equivalência quantitativa ("Escopo do Contrato vs. Entregas Realizadas" e "Tabela de Equilíbrio Contratual") e a Nota de Equilíbrio Contratual.
- **Planejamentos de Conteúdo:**
  - *Planejamento de Maio/2026 (`saae-nova-mutum/planejamento-maio-2026/index.html`)*
  - *Planejamento de Junho/2026 (`saae-nova-mutum/planejamento-junho-2026/index.html`)*

**Automação de Exportação (Script PDF):**
- Foi desenvolvido o script local `scratch/gen_pdf.js` utilizando Puppeteer para automatizar a geração do PDF e PNG dos relatórios HTML interativos.
- O script contém uma lógica específica para forçar a abertura de todos os acordeões ocultos em tela (como a Nota Técnica de Equilíbrio Contratual e as tabelas quantitativas) antes de capturar a imagem ou imprimir o PDF. Isso garante que nenhum dado relevante seja omitido na versão impressa entregue ao cliente.
- A última versão local gerada é a `relatorio-maio-2026-SAAE-V2.pdf`.

**Pendências e questões em aberto:**
- A tabela de equivalência ainda não foi aprovada por Pri — precisa de revisão antes de qualquer uso oficial.
- Não está definido se/como essa tabela será comunicada ao cliente.
- Não foi discutido se a metodologia de equivalência vai ser aplicada retroativamente a outros meses ou apenas a Maio.
- Não foi decidido onde o relatório final será entregue ao cliente (painel, e-mail, PDF direto).

**Relato do Usuário (Dúvidas, Questionamentos e Pedidos de Ajuda):**
Durante a sessão, o usuário expressou as seguintes dores, questionamentos e pedidos de ajuda:
1. **Dificuldade na Localização de Documentos:** O usuário não lembrava onde havia salvo o Termo de Referência baixado e solicitou uma varredura no computador por palavras-chave para encontrá-lo. Posteriormente, localizou no celular e enviou o caminho do arquivo RTF.
2. **Contexto de Pressão por Cobrança do Cliente (SAAE):** O usuário relatou que o SAAE tem dificultado o fluxo de pagamento mês a mês, intensificando a fiscalização de entregas e questionando se a quantidade produzida bate com o previsto em contrato. A dúvida central era como justificar de forma clara, em formato de tabela de equilíbrio contratual, a compensação com materiais extras gerados fora do escopo clássico de redes sociais.
3. **Dúvida sobre Regras do Contrato (Visitas):** O usuário questionou se visitas presenciais e coberturas de eventos deveriam ser incluídas na tabela de compensação de posts extras, definindo posteriormente que elas seguem regras próprias e não devem ser misturadas com posts estáticos e Reels.
4. **Problema de Visualização de Arquivos Locais:** O usuário relatou que não estava conseguindo visualizar o material gerado (relatório em PDF/PNG), demandando suporte para garantir que a renderização estivesse correta e visível.
5. **Dúvidas de Governança de Logs de IA:** O usuário levantou a dúvida se deveriam ser criados logs separados para planejamentos vs. demandas operacionais no GitHub.
6. **Alinhamento de Autonomia da IA:** O usuário trouxe um questionamento crítico importante: chamou a atenção sobre a IA ter realizado ações diretas de escrita e commit no GitHub sem sua validação prévia. Reforçou que a IA deve apenas realizar análises e aguardar confirmações explícitas antes de efetivar alterações nos arquivos de histórico operacional do projeto.

**Status:** Sessão de análise concluída. Nenhuma decisão foi formalizada. Tudo ainda em aberto para revisão e aprovação de Pri.

**Arquivos relacionados (locais, não publicados):**
- `relatorio-maio-2026-SAAE.pdf` — disponível no ambiente do Antigravity
- Contrato e TR foram lidos e analisados diretamente dos arquivos originais fornecidos por Pri



