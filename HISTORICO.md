# Histórico do Projeto — Perfil GitHub (`raphael-c-martins`)

> **Diretriz de Preservação:** Este repositório não utiliza banco de dados nem logs persistentes de aplicação. Em futuras manutenções, nunca apagar a branch `output` manualmente sem regenerar os SVGs pela Action e nunca commitar tokens ou credenciais.

## 13/11/2026 — Criação do README de Perfil e Automação da Cobrinha
- Criado repositório especial `raphael-c-martins/raphael-c-martins` para exibição do README na página principal do perfil no GitHub.
- Estruturado `README.md` em PT-BR com visual sóbrio e técnico:
  - Apresentação objetiva alinhada ao portfólio (`raphael-c-martins.github.io`).
  - Badges de contato (Portfólio, LinkedIn, E-mail).
  - Grade de ícones via `skillicons.dev` com troca automática entre tema claro e escuro (`<picture>`), complementada por badges de Playwright E2E, Proxmox VE, Windows Server & AD e Kaspersky EDR & Hardening.
  - Tabela de destaque dos repositórios públicos principais (`Otimizador-Windows-10-11`, `i-love-security`, `media-studio` e `raphael-c-martins.github.io`).
  - Animação da cobrinha no gráfico de contribuições com suporte a tema claro e escuro.
- Adicionado `.github/workflows/snake.yml` com `Platane/snk/svg-only@v3` e `crazy-max/ghaction-github-pages@v5` para atualização diária na branch `output`.
- Adicionado `.github/workflows/ci.yml` com `gitleaks/gitleaks-action@v2` para busca contínua de segredos.
