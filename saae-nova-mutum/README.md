# Protocolo de Atualização — SAAE Nova Mutum

Este documento serve como diretriz padrão para qualquer agente de IA ou desenvolvedor que realizar atualizações nas páginas do cliente **SAAE Nova Mutum** neste repositório.

---

## 📋 Regras de Atualização e Histórico

1. **Preservação do Histórico**:
   - **NUNCA** altere, apague ou sobrescreva planejamentos ou relatórios de meses anteriores, a menos que solicitado explicitamente pelo usuário.
   - Ao adicionar novos itens, crie uma nova pasta com o nome padronizado (ex: `planejamento-julho-2026` ou `relatorio-junho-2026`) e coloque o respectivo arquivo `index.html` dentro dela.

2. **Organização do Portal (`saae-nova-mutum/index.html`)**:
   - Todos os novos planejamentos e relatórios devem ser cadastrados no portal do cliente.
   - Insira o novo link no topo da respectiva lista (ordem cronológica decrescente: o mais novo sempre fica acima).

3. **Formato dos Links**:
   - Todos os links devem apontar diretamente para o arquivo `index.html` da pasta (ex: `href="planejamento-junho-2026/index.html"` em vez de `href="planejamento-junho-2026/"`).
   - Isso garante que o navegador renderize o arquivo diretamente sob o protocolo local `file://` sem exibir listagens de diretórios.

---

## 🎨 Padrão Visual do Portal (Style Guide)

O portal utiliza uma identidade visual escura e moderna para valorizar as cores da marca. Mantenha os seguintes estilos:

*   **Fundo da Página**: Gradiente azul escuro profundo (`linear-gradient(135deg, #0F172A 0%, #0C2340 60%, #083358 100%)`).
*   **Cabeçalho**: Translúcido (glassmorphism) com fundo escuro e a logo oficial do SAAE (`logo.png`) visível no canto superior esquerdo.
*   **Cards (Blocos)**: Gradiente verde vibrante do SAAE (`linear-gradient(135deg, #004d26 0%, #007D43 50%, #10B981 100%)`) com borda iluminada verde e sombra com efeito *neon/glow*.
*   **Tipografia dos Cabeçalhos**: Os títulos dos blocos (ex: `PLANEJAMENTOS` e `RELATÓRIOS`) devem usar a fonte **Montserrat** em caixa alta (uppercase), com espaçamento entre letras aumentado (`letter-spacing: 0.06em`), **sem emojis**.
*   **Links de Acesso**: Estilo botão translúcido sobre o fundo verde, com efeito hover de deslocamento horizontal e seta indicadora (`→`).

---

## 🚀 Protocolo de Deploy (Git / GitHub Pages)

Toda alteração deve ser enviada para o ambiente de produção via Git:

1. **Atualizar Repositório Local**:
   ```bash
   git pull --rebase origin main
   ```
2. **Adicionar Arquivos Modificados/Novos**:
   ```bash
   git add saae-nova-mutum/
   ```
3. **Criar Commit Descritivo**:
   ```bash
   git commit -m "feat(saae): upload [Mês/Ano] [Relatório/Planejamento] e atualizar portal"
   ```
4. **Fazer Push**:
   ```bash
   git push origin main
   ```
   *(Aguardar 1-2 minutos para que o GitHub Pages compile a nova versão)*
