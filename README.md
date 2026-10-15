# La Corte dei Sabiìti — sito

Sito statico (HTML + CSS, nessuna build). Hosting: Cloudflare Pages.

- Build command: nessuno
- Output directory: / (root)
- Redirect e link corti: `_redirects` (/ig, /fb, /wa)
- Header di cache e sicurezza: `_headers`
- Redirect www → dominio senza www: regola Cloudflare (Rules → Redirect Rules), non gestibile da `_redirects`
