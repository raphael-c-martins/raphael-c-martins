# Histórico do Projeto — Perfil GitHub (`raphael-c-martins`)

> **Diretriz de Preservação:** Este repositório não utiliza banco de dados nem logs persistentes de aplicação. Em futuras manutenções, nunca apagar a branch `output` manualmente sem regenerar os SVGs pela Action e nunca commitar tokens ou credenciais.

## 13/11/2026 — Remoção de OpenCV e Ubuntu da grade
- Removidos `OpenCV` e `Ubuntu` (mantendo apenas `Linux` de forma abrangente), resultando em 23 ícones com `perline=8`.

## 13/11/2026 — Remoção de tecnologias fora da dominância principal
- Removidos da grade `.NET`, `Vite`, `PostgreSQL`, `Debian` e `Nginx` por solicitação do usuário, mantendo `SQLite` e ajustando a exibição para 25 ícones (`perline=9`).

## 13/11/2026 — Correção do srcset da grade e ampliação das tecnologias
- Corrigida a URL do `skillicons.dev` dentro de `<source srcset>` substituindo `,` por `%2C` (vírgulas sem codificação eram quebradas pelo parser HTML de `srcset`, exibindo apenas o primeiro ícone).
- Expandida a grade para 30 ícones em 3 linhas (`Python`, `PowerShell`, `Bash`, `C#`, `.NET`, `TypeScript`, `JavaScript`, `HTML5`, `CSS3`, `React`, `Next.js`, `Vite`, `Tailwind`, `FastAPI`, `Node.js`, `Prisma`, `PostgreSQL`, `SQLite`, `Supabase`, `OpenCV`, `Linux`, `Ubuntu`, `Debian`, `Windows`, `Docker`, `Nginx`, `Git`, `GitHub`, `GitHub Actions`, `VS Code`) e adicionados badges de `Hyper-V` e `CI/CD & Gitleaks`.

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
