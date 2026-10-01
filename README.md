# AVEC - Maqueta académica

## Descripción
AVEC es una maqueta web navegable de una tienda de productos electrónicos. Integra un chatbot simulado para consultar catálogo, precios, inventario, pedidos y orientación de compra. Todos los datos son locales y no existe conexión con bases de datos, pasarelas de pago ni servicios de inteligencia artificial.

## Objetivo académico
Demostrar competencias de HTML5 semántico, CSS3 responsivo, JavaScript, usabilidad, accesibilidad web y despliegue de un sitio estático dentro del programa de Análisis y Desarrollo de Software.

## Tecnologías utilizadas
- HTML5 semántico
- CSS3 con diseño responsivo
- JavaScript puro
- localStorage para conservar el carrito
- GitHub Pages para publicación estática

## Estructura
```text
avec-maqueta/
├── index.html
├── css/
│   └── estilos.css
├── js/
│   └── app.js
├── img/
│   └── productos/
│       └── .gitkeep
└── README.md
```

## Funciones principales
- Catálogo de ocho productos con búsqueda y filtros.
- Control de cantidades según inventario y límite máximo de 12.
- AVEC Bot con respuestas simuladas y espera de consulta de inventario.
- Carrito persistente con subtotal y total.
- Resumen de compra, formulario validado y simulación de pago.
- Recuperación tras pago rechazado sin perder el carrito.
- Pedido simulado y línea de progreso.
- Menú móvil, diálogos accesibles y regiones `aria-live`.

## Ejecución local
1. Descarga o copia la carpeta completa.
2. Abre la carpeta `avec-maqueta` en Visual Studio Code.
3. Abre `index.html` directamente en un navegador o utiliza la extensión Live Server.
4. No se requiere npm, servidor, API key ni instalación adicional.

## Publicación
1. Crea un repositorio público llamado `avec-maqueta-html`.
2. Sube el contenido de esta carpeta, dejando `index.html` en la raíz.
3. En **Settings > Pages**, elige **Deploy from a branch**.
4. Selecciona la rama `main`, la carpeta `/(root)` y guarda.
5. Espera la publicación y abre `https://NOMBRE-DE-USUARIO.github.io/avec-maqueta-html/`.

## Autor
**Manuel Rodrigo Montenegro Rivera**

**Programa:** Análisis y Desarrollo de Software

> Maqueta académica con fines educativos. No procesa pagos ni datos reales.
