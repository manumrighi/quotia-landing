# QUOTIA — Landing

Página de presentación de **QUOTIA**, la plataforma B2B de negociación de cotizaciones (RFQ) para corredoras de cereales.

Sitio estático de un solo archivo (`index.html`) con [mermaid](https://mermaid.js.org/) embebido localmente para los diagramas de arquitectura.

## Deploy

Conectado a Vercel — cada push a `main` redeploya automáticamente en https://quotia-gold.vercel.app/

## Estructura

- `index.html` — la landing completa (estilos y scripts inline)
- `mermaid.min.js` — librería de diagramas servida localmente (evita depender de un CDN)
