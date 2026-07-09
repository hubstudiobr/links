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

## 09 de julho de 2026 — Claude (Saulo)

### Relatório de Junho/2026 finalizado + Metodologia de Referência publicada + reforma do portal

**Contexto:** Continuação direta da sessão anterior (definição da metodologia de equilíbrio contratual). Nesta sessão, Pri trouxe o histórico completo de discussões sobre relatórios e riscos jurídicos (resumo do ChatGPT desde Janeiro/2026, incluindo o episódio de origem do tráfego pago), o que reforçou a decisão de aplicar a nova metodologia com rigor máximo no relatório de Junho.

**Levantamento de dados de Junho (com correções no processo):**
- Identificados 2 erros de contabilização antes de fechar os números: (1) reel "Anos de Empresa" (trend "quanto tempo de empresa") gravado em Maio mas publicado em 02/06 — não contado em Junho pois o crédito já foi usado no relatório de Maio; (2) reel "Quem Recicla o ReCiclo Ep.3" — confirmado como duplicata do já publicado em Maio, removido da contagem de Junho. Essa correção reduziu os reels válidos de Junho de 4 para 3, o que **mudou o resultado de "compensação integral" para "compensação parcial"**.
- Confirmado por Pri: TR ainda vigente é 10 posts / 6 reels / 8 stories (a mudança para "até 6" discutida com Ezaque **ainda não é oficial**).
- Números finais de Junho: 0 posts estáticos, 3 reels, 11 stories, 2 visitas presenciais (20/06 e 26/06). Materiais extras: 1 adesivo, 1 banner institucional, 2 banners de dinâmica educativa (todos ligados ao 9º Evento Ecológico Todos Pela Natureza).
- Déficit total: 22 créditos. Compensado: 14,5 créditos. **Resultado: compensação parcial**, com saldo de 7,5 créditos (~8 posts) a ser somado à produção de Julho.

**Relatório de Junho — decisões de conteúdo e enquadramento:**
- Resumo executivo reformulado para enquadrar o investimento em tráfego pago concentrado (PEV Palmeiras, custo por ThruPlay R$0,04) como resposta direta a uma reclamação anterior do SAAE ("tem que rodar tráfego mesmo que pouco") — não apenas como estratégia genérica.
- Tabela "Escopo do Contrato vs. Entregas Realizadas" (formato previsto/realizado/diferença) **abolida permanentemente**, substituída por tabela "Produzido no Mês" (só o que foi feito, sem comparação direta com a meta contratual). Decisão de Pri: mostrar "0" explicitamente quando aplicável (não omitir a linha), pois omissão de categoria conhecida gera mais desconfiança do que um número baixo já justificado.
- Parágrafo de justificativa do déficit reescrito e reposicionado para vir **antes** da tabela de produção (para "preparar o terreno" do leitor) e ampliado com duas razões, propositalmente en enquadradas de forma suave: (1) capacidade reservada para demandas sob demanda de curto prazo; (2) cronograma de finalização/edição de materiais já captados. Combinado com a quantificação explícita do saldo a favor de Julho (7,5 créditos).
- Removida a "Nota sobre Visitas Técnicas" (alert-card); visitas presenciais agora aparecem como linha simples na tabela de produção.
- Tabela completa de equivalência (a mesma da Metodologia de Referência) removida do corpo do relatório, substituída por link direto à página de metodologia — relatório mais enxuto, evita duplicação de conteúdo entre documentos.

**Metodologia de Referência (nova página permanente):**
- Criada em `saae-nova-mutum/metodologia-equilibrio/index.html` — documento fixo, sem data de mês, contendo a tabela de equivalência com valores de mercado (pesquisados via web search: post ~R$60, reel ~R$250, peça impressa simples/média/grande, spot de rádio, motion design, vídeo institucional para TV ~R$5.500 — valores ajustados por Pri para a realidade regional de Mato Grosso).
- Linkada no portal do cliente em nova seção "Referência".

**Reforma do Portal do Cliente:**
- Seção "Planejamentos" removida do portal (arquivos mantidos no repositório, apenas não linkados mais).
- Adicionado bloco de headline/contexto abaixo do cabeçalho.
- Portal agora com 2 colunas: Relatórios e Referência (antes 3, incluindo Planejamentos).

**Entregáveis adicionais:**
- PDF do relatório de Junho gerado em duas versões (paginado A4 e "página única"/scroll contínuo) via wkhtmltopdf/wkhtmltoimage, para anexo do Juan junto aos materiais compactados. Limitação registrada: Google Fonts bloqueado no ambiente de geração, then fontes saem como fallback do sistema em vez de Syne/Instrument Sans — para fidelidade visual total, recomendado usar Chrome (Ctrl+P → Salvar como PDF → Gráficos de fundo) a partir do link publicado.

**Pendências:**
- Portal do cliente (`hubstudiobr.github.io/links/saae-nova-mutum/`) continua **público, sem autenticação** — decisão consciente de Pri de aceitar o risco por ora e revisar depois. Agora inclui valores reais de mercado (tabela de preços da Studio Virtually) na página de metodologia.
- Saldo de 7,5 créditos prometido para Julho é um compromisso real que precisa ser cumprido no próximo relatório.

**Status:** Relatório de Junho publicado e completo, sem pendências de dado. Metodologia de Referência publicada. Portal reformado.

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
