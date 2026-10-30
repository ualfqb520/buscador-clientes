# Buscador de clientes

Encuentra negocios **sin página web** en un radio alrededor de tu ciudad, para ofrecerles tus servicios.

**Abrir la app:** https://ualfqb520.github.io/buscador-clientes/

## Cómo se usa

1. Escribe un sector (peluquería, taller, restaurante…) y una ciudad o calle.
2. Elige el radio en km y pulsa **Buscar**.
3. Pulsa los contadores para filtrar: todos, sin web, o sin web y con teléfono.
4. Usa **Comprobar** para confirmar en Google que de verdad no tiene web, y marca **Contactado**.
5. **Exportar CSV** descarga la lista para Excel.

## Fuentes de datos

- **OpenStreetMap** — gratis, sin clave. Menos negocios y pocos teléfonos.
- **Google Maps** — más completo. Necesita una clave de Google Places API (Google Cloud, con facturación activada; incluye un tramo gratuito mensual). La clave se guarda solo en tu navegador, nunca en este repositorio.

Todo funciona en un único archivo, `index.html`, sin servidor.
