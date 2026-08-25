# Negocio Digital

Sitio estático (3 páginas, sin dependencias externas más allá de Google Fonts).

- `index.html` — home
- `privacidad.html` — política de privacidad
- `condiciones.html` — condiciones del servicio
- `CNAME` — dominio agentecero.cloud

## Publicar con GitHub Pages

1. Sube el contenido de esta carpeta a la raíz de la rama `main` del repositorio.
2. Settings → Pages → Source: *Deploy from a branch*, rama `main`, carpeta `/ (root)`.
3. Settings → Pages → Custom domain: `agentecero.cloud` y marca *Enforce HTTPS*.
4. En tu proveedor de DNS:
   - `A` @ → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `CNAME` www → hvillalonga94-code.github.io
