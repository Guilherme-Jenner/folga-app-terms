# folga-site

Páginas estáticas do Folga, publicadas pelo GitHub Pages. Cada tela é um arquivo HTML:

| Arquivo | Conteúdo |
|---|---|
| `index.html` | Página inicial (o que o app faz e não faz) |
| `termos.html` | Termos de Uso |
| `privacidade.html` | Política de Privacidade |
| `style.css` | Estilo comum (cores do design system do app) |

Sem build: é só HTML e CSS. `.nojekyll` desliga o Jekyll do Pages.

## Antes de publicar

- Trocar `CONTATO@EXEMPLO.COM` (em `termos.html` e `privacidade.html`) pelo e-mail de contato real.
- Os textos descrevem o app como ele é hoje (dados sensíveis só no aparelho; servidor guarda conta e quais cartões). Se isso mudar no app, atualizar aqui. **Ainda sem revisão jurídica.**

## Publicar

Settings → Pages → Deploy from a branch → `main` / `(root)`.
