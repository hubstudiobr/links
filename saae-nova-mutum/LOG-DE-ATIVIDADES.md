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

## 08 de julho de 2026 (atualização 3) — Claude (Saulo)

### Carrossel Vila União — produção visual das 4 telas concluída + legenda

**Demanda:** Continuação da produção do carrossel Vila União (ver entrada anterior "Carrossel Vila União — comunicação sobre manutenção dos pontos de coleta"). Geração dos prompts de arte para uso em GPT externo de design, revisão crítica de cada tela gerada, e escrita da legenda final.

**Mudança de direção visual (decisão de Pri, durante o processo):**
- Paleta migrada de azul para **verde institucional**, com nova regra de cor por tema: água = azul, resíduos/lixo = verde, esgoto = verde escuro. Regra ainda não aplicada retroativamente a outros materiais — vale para conteúdos futuros sobre resíduos.
- Estilo visual "liquid glass" (painel de vidro fosco/glassmorphism) adotado para o bloco de texto em todas as 4 telas, a pedido de Pri. **Atenção:** essa estética está fora do padrão documentado no guia de direção visual do SAAE (que pede estilo editorial puro, sem elementos de tendência de UI). Decisão tomada por prazo e por preferência estética de Pri, com ressalva registrada pelo Claude sobre risco de datar a peça e destoar do padrão "atemporal" do projeto.
- Logomarca reposicionada para canto inferior, pequena, como assinatura (ver entrada de atualização 2 — já registrada como novo padrão de marca).

**Processo de revisão (etapa por etapa):**
- **Tela 1:** ajustada 2x — primeiro por proporção de fotografia excessiva (55-60% em vez de 30-35%), depois por excesso de azul monocromático (resolvido com a virada para paleta verde + liquid glass).
- **Tela 2:** elemento ilustrativo (lixeira + saco de lixo, line art) inicialmente saiu grande demais e com painel de vidro cortado nas bordas — aprovada mesmo assim por Pri, priorizando prazo.
- **Tela 3:** corrigiu o problema de bordas cortadas da Tela 2. Lista de itens proibidos mantida em texto corrido (não checklist), com apenas um elemento ilustrativo (pneu). Observação registrada: linhas de "movimento/poeira" no pneu destoam do tom neutro institucional — não corrigido, aprovado pelo prazo.
- **Tela 4:** ajuste de conteúdo (adição de texto de apoio para resolver sensação de painel vazio) e correção de erro ortográfico gerado pelo GPT ("seguírá" → "seguirá").

**Legenda final (aprovada):**
Estrutura padrão contexto → explicação → orientação → fechamento, com hashtags. Sem menção a canais de atendimento (WhatsApp) para evitar dependência de terceiros antes da publicação. Sem comparação "antes/depois". Menciona a placa oficial já existente no local como base da orientação sobre itens não aceitos.

**Fotos utilizadas (fornecidas por Pri, originadas do Cristiano/SAAE):**
- Tela 1: foto do caminhão com munck e equipe uniformizada em serviço.
- Tela 4: foto dos contêineres metálicos já organizados/esvaziados.
- Uma terceira foto (da placa oficial fixada no ponto de coleta) foi identificada como valiosa para uso futuro (Stories de apoio ou material de alinhamento interno com Ezaque), mas não utilizada no carrossel do feed.
- Todas as fotos exigiram remoção de carimbo de data/hora/geolocalização visível (aplicado no tratamento via prompt).

**Status:** Carrossel de 4 telas e legenda concluídos e aprovados por Pri. Pronto para publicação.

---

## 08 de julho de 2026 (atualização 2) — Claude (Saulo)

### Nova regra de identidade visual: posicionamento da logomarca SAAE

**Demanda:** Durante a produção da Tela 1 do carrossel Vila União, identificado que a fotografia estava ocupando área maior que a especificada (55-60% em vez de 30-35%), competindo com a tipografia. No ajuste, Pri decidiu também mudar o posicionamento padrão da logomarca.

**Decisão registrada:**
- A logomarca do SAAE passa a ser posicionada no **canto inferior** das artes, em **tamanho pequeno, como assinatura discreta** — não mais no topo em tamanho de destaque.
- Essa mudança não é pontual desta peça: **é o novo padrão de marca para todos os materiais do SAAE daqui em diante.**
- Pendente: avaliar se essa mudança deve ser refletida no arquivo `DESIGN_SYSTEM_SAAE.md` (repositório `hubstudiobr/automacoes-ia`), que documenta as diretrizes visuais completas do projeto.

**Status:** Regra aprovada por Pri. Aplicação no design system ainda não realizada — repositório diferente do utilizado para este log.

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

---

## 18 de junho de 2026 — Gemini (Antigravity)

### Análise de Contrato e Regras de Equilíbrio Contratual

**Demanda:** Análise técnica do Contrato nº 021/2025 e do Termo de Referência (TR nº 040/2025) do SAAE Nova Mutum após questionamentos do cliente sobre a quantidade de publicações entregues em Maio/2026, com formulação de regra e tabela de equilíbrio de compensação produtiva.

**Entregas e Decisões de Equilíbrio Contratual:**
- **Metas contratuais mapeadas:**
  - 10 posts estáticos (incluindo carrosséis)
  - 6 Reels
  - 8 Stories
  - 2 visitas presenciais mensais planejadas
  - 1 visita eventual extra sob demanda
- **Tabela de Equivalência Oficial (aprovada por Pri):**
  - *Faixa Fachada PEV 2 (Grande Porte / CMYK):* Equivale a **4 posts estáticos** (devido à alta resolução, CMYK e complexidade de arquivo para gráfica).
  - *Banner / Backdrop Semana do Meio Ambiente (Médio Porte):* Equivale a **3 posts estáticos**.
  - *Vídeo PEV 2 (Reel Extra produzido e editado):* Equivale a **3 posts estáticos**.
  - *Adesivos Variados Semana do Meio Ambiente:* Equivale a **2 posts estáticos**.
- **Regra de Exclusão:** Visitas e coberturas de campo seguem fluxo e cláusula independente no contrato e **não** entram na compensação de posts.

**Alterações em Arquivos:**
- Atualização do relatório de Maio de 2026 (`saae-nova-mutum/relatorio-maio-2026/index.html`) para incluir a tabela explicativa "Escopo do Contrato vs. Entregas Realizadas", a "Tabela de Equilíbrio Contratual" e a nota metodológica.
- Correção no script de renderização (`gen_pdf.js`) para garantir que os acordeões e as notas fiquem visíveis no PDF final.
- Geração bem-sucedida do novo PDF e PNG (`relatorio-maio-2026-SAAE-V2.pdf` e `relatorio-maio-2026-SAAE-V2.png`).

**Status:** Concluído e enviado ao repositório `links`.

---

## 19 de maio de 2026 — Manu (ChatGPT)

### Roteiros de Gravação e Status do ReCiclo Ep. 3

**Demanda:** Alinhamento do status do vídeo ReCiclo Ep. 3 e planejamento de roteiros para a diária de captação do SAAE de maio.

**Entregas e Decisões:**
- **Status do ReCiclo Ep. 3:** Gravado e em edição com Pri (não necessita de captação na nova diária).
- **Roteiros planejados para a diária:**
  - *Horários do PEV na prática:* Utilidade pública baseada nos horários oficiais do ponto.
  - *ETE (Estação de Tratamento de Esgoto):* Foco institucional de tecnologia urbana.
  - *Sugestões extras:* Planejar mais 2 temas adicionais para totalizar 4 roteiros de captação.

**Status:** Concluído.

---

## 14 de maio de 2026 — Manu (ChatGPT)

### Organização e Hospedagem do Design System

**Demanda:** Criação de estrutura centralizada para documentação visual do SAAE no GitHub e atualização das diretrizes de marca.

**Entregas e Decisões:**
- **Diretório `design-system/` criado:**
  - `design-system-saae.md` (paleta, tipografia, famílias de comunicação e Heróis).
  - `motion-system-saae-complemento.md` (motion graphics, transições e linguagem de Reels).
  - `colors.json` e `typography.json` (design tokens).
- **Mascotes da marca:**
  - Capitão Hydro e Capitã Flora ativos na linha Heróis do Saneamento.
  - Mascote Gotinha descontinuado devido à semelhança com o Zé Gotinha do Ministério da Saúde.
  - Regra de grid rígida (70% estrutura editorial, 30% mascote como isca visual, sem adornos).

**Status:** Concluído.

---

## 12 de maio de 2026 — Manu (ChatGPT)

### Revisão do Planejamento Editorial de Maio

**Demanda:** Correção e revisão do planejamento de conteúdos do mês de maio após identificação de temas redundantes em relação a abril.

**Entregas e Decisões:**
- **Ajuste de eixos editoriais:**
  - Água definida como o ativo institucional e tema central dominante do mês.
  - Saneamento/ETE inserido como tema educativo focado em infraestrutura e na inauguração das novas instalações.
  - ReCiclo Ep. 3 agendado para o Dia Mundial da Reciclagem.
- **Governança:** Estabelecido que o log geral e o do SAAE devem ser atualizados ao final de cada entrega para permitir rastreamento multiplataforma por IAs.

**Status:** Concluído.
