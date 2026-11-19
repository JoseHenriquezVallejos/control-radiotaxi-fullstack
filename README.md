# Embudo de Diagnóstico Interactivo (Precalificación Mobile-First)

Aplicación web interactiva sin fricción diseñada para profesionales independientes, permitiendo precalificar prospectos antes de iniciar una conversación directa en WhatsApp.

## Demo en Vivo
[Ver Demo Interactiva](https://JoseHenriquezVallejos.github.io/embudo-diagnostico-interactivo/)

## Problema de Negocio y Enfoque Analítico
Los profesionales independientes (psicólogos, consultores, clínicas) pierden tráfico móvil de alta intención debido a páginas tradicionales saturadas de texto y formularios largos.

**La Solución:** Un embudo visual guiado por estado y de un solo toque (*single-tap*) que lleva al usuario mediante micro-compromisos progresivos, captura sus respuestas dinámicamente y construye un resumen estructurado prellenado directo en WhatsApp.

## Arquitectura y Aspectos Técnicos
* **Experiencia Móvil Sin Fricción:** Diseñado estrictamente bajo enfoque *mobile-first* con transiciones instantáneas de estado y cero recargas de página para eliminar el abandono.
* **Arquitectura Serverless Ligera:** Alojado de forma estática en GitHub Pages para tiempos de carga inferiores a un segundo, utilizando entrega de activos optimizados (`.webp`) y codificación dinámica de parámetros en URL.
* **Enrutamiento Automatizado de Prospectos:** Compila dinámicamente las selecciones del usuario en una carga útil estructurada enviada mediante la API de WhatsApp (`wa.me`), reduciendo el tiempo de triaje manual para el profesional.

## Stack Tecnológico
* **Frontend:** HTML5, CSS3 (Grid/Flexbox Responsivo), JavaScript Vanilla (ES6+ Manejo de Estado)
* **Infraestructura y Activos:** GitHub Pages, Cloudflare R2 (optimización multimedia `.webp`)
