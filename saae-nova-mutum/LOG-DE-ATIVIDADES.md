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
- Toda entrada deve identificar claramente qual assistente realizou a atualização (ex: **Claude (Saulo)** ou **ChatGPT**), já que ambos podem atualizar o mesmo log em sessões/demandas diferentes.

---

## 08 de julho de 2026 — Claude (Saulo)

### Carrossel Vila União — comunicação sobre manutenção dos pontos de coleta

**Demanda:** Demanda solicitada pelo Cristiano/Ezaque (SAAE) via áudio transcrito, repassada por Pri: criar postagem (Feed + Story) sobre o serviço de limpeza realizado nos pontos de coleta da Vila União, orientando a população sobre descarte correto. Demanda iniciada em outro chat (ChatGPT), migrada para o Claude por limite de tamanho da conversa.

**Contexto herdado do chat anterior:**
- Já existia uma primeira arte pronta (Tela 1 "Manter a Vila União limpa é um compromisso de todos"), com prompt de direção de arte completo já validado (fotografia 30-40% da composição, tipografia protagonista, paleta institucional SAAE).
- Discussão prévia sobre estrutura de carrossel (4 telas) entre Pri e ChatGPT, com proposta de narrativa "curiosidade → problema → orientação → responsabilidade compartilhada".

**Entregas (Claude):**
- Revisão crítica da proposta de 4 telas do ChatGPT — identificado risco institucional: a Tela 3 (destinos de descarte) dependia de confirmar fluxo oficial não verificado (destino de pneu/móveis).
- Desenvolvimento de caminho alternativo de conteúdo, evitando exibir "erros" da comunidade (fotos de descarte irregular) e ancorando a comunicação em identidade/norma social positiva, em vez de repreensão.
- Ajuste de tom da Tela 1 (de mais comercial/anúncio para mais institucional/neutro), a pedido de Pri.
- Identificado, a partir de releitura da transcrição do Ezaque, que já existe placa oficial fixada no ponto de coleta com regras de proibição (móveis, entulho, galho, animal). Essa informação permitiu resolver o risco da Tela 3 sem depender de confirmação externa: em vez de indicar destino de descarte, a peça informa o que **não é aceito** no ponto, com base em informação já oficial e pública.
- Fechada versão final das 4 telas (texto), sem dependência de validação externa, priorizando publicação ainda hoje (demanda atrasada).

**Versão final aprovada (texto):**
1. Fato + gancho: "Os pontos de coleta da Vila União passaram por manutenção." / "Saiba como você pode ajudar a manter a Vila União organizada." / CTA "Arraste para ver."
2. Regra única: "Manter limpo começa com um cuidado simples." / "Lixo doméstico sempre ensacado e dentro da lixeira."
3. Proibições do ponto (base: placa oficial existente): "Nem tudo pode ser descartado nos pontos de coleta." / "Móveis, entulho, galhos, pneus e animais não são aceitos — apenas resíduos domésticos, devidamente ensacados."
4. Fechamento institucional: "A Vila União organizada é resultado do trabalho de todos."

**Pendências:**
- Prompts de arte para as 4 telas ainda não gerados (próximo passo).
- Legenda do post ainda não escrita.
- Fotos reais do descarte irregular (arquivo compactado enviado pelo Cristiano) já estão com Pri, ainda não repassadas ao Claude para uso no material.

**Status:** Textos das 4 telas aprovados e fechados. Produção visual em andamento.

---

## 08 de julho de 2026 (atualização) — Claude (Saulo)

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
