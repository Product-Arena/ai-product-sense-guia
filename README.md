# Guia do aluno — AI Product Sense

Site estático do guia de sala (Product Arena). Think → Augment → Connect → Build.

**Repositório:** [Product-Arena/ai-product-sense-guia](https://github.com/Product-Arena/ai-product-sense-guia)  
**Produção:** o deploy vai para a Vercel a cada push em `main`.

Cópia de trabalho no workspace do Lucas: `learning/ai-product-sense/guia-do-aluno/`.  
Não edite o guia do [Cursor na prática](https://github.com/Product-Arena/cursor-para-pms).

## Local

```bash
./serve-local.sh --open
```

URL: [http://127.0.0.1:8846/](http://127.0.0.1:8846/)

Sempre sirva por HTTP. Abrir `index.html` com `file://` quebra os partials.

## Deploy (Vercel)

O projeto na Vercel está ligado a este repositório. Fluxo:

1. Commit na pasta deste guia
2. `git push origin main`
3. A Vercel publica sozinha

Não use `vercel deploy` no dia a dia.

## Conteúdo que entra no Git

HTML, CSS, JS, logos, fotos dos instrutores e os ZIPs dos cases Arena. Vídeos e prints do curso Cursor na prática ficam só na máquina (`.gitignore`).
