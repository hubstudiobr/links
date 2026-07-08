# Log de Atividades — SAAE Nova Mutum

Este arquivo registra as atividades de comunicação institucional desenvolvidas para o SAAE Nova Mutum.

## Objetivo

Manter um histórico organizado de estratégias, conceitos, textos, roteiros, legendas, direcionamentos visuais, decisões aprovadas, alterações realizadas e materiais concluídos.

## Regras de atualização

- Registrar as atividades em ordem cronológica decrescente, com as atualizações mais recentes no topo.
- Não apagar registros anteriores.
- Cada entrada deve indicar data, demanda, entregas, decisões, status e, quando houver, arquivos ou páginas relacionadas.
- Diferenciar claramente materiais em desenvolvimento, aprovados, revisados ou concluídos.
- Utilizar linguagem objetiva e descritiva.

---

## 08 de julho de 2026 (atualização)

### Definição do fluxo de atualização do log via Claude

**Demanda:** Alinhar como o Claude (Saulo) atualiza este log diretamente, sem depender de colar manualmente o conteúdo.

**Entregas:**
- Confirmado acesso de leitura e escrita ao repositório `hubstudiobr/links` via Personal Access Token do GitHub, usado diretamente no ambiente do Claude (bash + git).
- Regra de fechamento de conversa estabelecida: ao identificar um encerramento de conversa (ex: "ok obrigada", "por enquanto é isso"), o Claude deve perguntar se a atualização do log é desejada.

**Decisões:**
- Pri optou por token com acesso amplo (classic, escopo `repo`) para uso imediato, com plano de revisar/restringir escopo futuramente conforme o plano de acesso evoluir.
- Recomendação registrada: revogar o token utilizado nesta sessão após uso, por ele ter sido compartilhado em texto simples no chat.
- Push direto ao repositório confirmado como funcional a partir deste momento.

**Status:** Concluído.

---

## 08 de julho de 2026

### Estruturação do log de atividades

**Demanda:** Criar um arquivo central para registrar continuamente as atividades de comunicação do SAAE Nova Mutum.

**Entregas:**
- Criação do arquivo `LOG-DE-ATIVIDADES.md`.
- Definição do objetivo do documento.
- Definição das regras de atualização e do padrão de registro.

**Decisões:**
- O log ficará armazenado em `saae-nova-mutum/LOG-DE-ATIVIDADES.md`.
- As atualizações serão inseridas no topo, preservando todo o histórico.
- O arquivo registrará estratégias, conceitos, textos, legendas, roteiros, direcionamentos visuais, alterações, aprovações e materiais concluídos.

**Status:** Concluído.
