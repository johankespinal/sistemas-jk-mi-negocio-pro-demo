# Mi Negocio PRO — demo funcional

Demo de portafolio: panel web de compras, ventas, balance, gráficos de últimos siete días, clientes/retiros, reportes CSV y dictado de voz experimental.

## Uso

Abre `index.html` en el navegador. Para las pruebas de voz se necesita un navegador compatible y normalmente un contexto HTTPS, como GitHub Pages. No hay que instalar Node ni servidor.

## Datos

- Datos de ejemplo iniciales.
- El navegador guarda los registros en `localStorage`. No se comparten entre usuarios o equipos.
- El botón circular **↻** restaura los datos de ejemplo **después de pedir confirmación**.
- Botón **Exportar CSV** en Reportes.

## Voz experimental

Usa Web Speech API si el navegador la soporta: por ejemplo «Registrar venta de 50 soles por dos camisetas». Abre el formulario con el importe y concepto inferidos **para revisión y confirmación humana**; no registra automáticamente. Puede no estar disponible en ciertos navegadores, idiomas o políticas de privacidad. No es un sistema de contabilidad certificado.

## Publicación gratis

1. Crea un repositorio nuevo en GitHub (por ejemplo, `mi-negocio-pro-demo`).
2. Sube `index.html`, `styles.css`, `app.js` y `README.md` a la raíz.
3. En **Settings → Pages**, selecciona **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
4. GitHub mostrará la URL pública de la demostración cuando termine de publicarla.

## Alcance y limitaciones

Proyecto conceptual propio para enseñar diseño y flujo de negocio. No cuenta con backend, usuarios, autenticación, sincronización, facturación tributaria, auditoría, soporte de producción ni copias de seguridad remotas. No introducir información empresarial real o sensible. La versión comercial requeriría validaciones, base de datos, roles y seguridad adecuados.
