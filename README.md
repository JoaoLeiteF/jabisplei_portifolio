# Gustavo Hikaru — Portfólio (site estático)

Site em HTML/CSS puro, pensado para hospedar no **GitHub** e publicar na **Vercel** (ou GitHub Pages) sem WordPress.

## Conteúdo do repositório

| Item | Descrição |
|------|-----------|
| `index.html` | Página única: sobre, grid de projetos, iframes Bunny/Vimeo |
| `media/` | Imagens de capa (thumbnails) |

## Rodar localmente

Abra `index.html` no navegador ou use um servidor estático, por exemplo:

```bash
npx serve .
```

## Vercel

1. Importe este repositório na Vercel.
2. **Framework Preset:** Other (ou detecção automática).
3. **Root Directory:** deixe vazio se a raiz do repo for esta pasta (onde está o `index.html`).

## Editar

- Textos, links e ordem dos projetos: edite `index.html`.
- Novas capas: adicione arquivos em `media/` e atualize os caminhos `./media/...` no HTML.

## Origem

Conteúdo migrado a partir de um backup WordPress (tema Minimalio + Bunny Stream / Vimeo).
