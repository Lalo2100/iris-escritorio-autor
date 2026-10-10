I.R.I.S. — Escritorio de autor (versión actualizada)

Contenido
- index.html: aplicación web estática.

Novedades
- Importación de archivos .docx mediante Mammoth.js y de TXT/MD. Requiere conexión a internet para cargar la biblioteca Mammoth desde CDN.
- Impresión del manuscrito y opción del navegador para Guardar como PDF.
- Exportación de cada manuscrito como HTML autónomo listo para compartir o alojar en una web, y exportación TXT.
- Formulario de prueba de envíos de autores, con archivos y metadatos guardados solo en el navegador actual.
- Reparto de ingresos editable de ejemplo (por defecto 60% plataforma/creador y 40% autor). No procesa pagos reales.

IMPORTANTE
Esta versión es un prototipo estático. Para ofrecer libros públicamente a todos los usuarios y repartir ganancias reales se necesita backend/base de datos, autenticación, almacenamiento de archivos, revisión de derechos y una integración de pagos. No sube automáticamente los libros a internet.

Publicación en Vercel
1. Descomprimí el ZIP.
2. Subí index.html a un repositorio propio.
3. Importá ese repositorio en Vercel y usá el preset Other; no hace falta comando de build.
4. Para un sitio de producción, agregá servicios de servidor antes de habilitar ventas o cuentas de autor.

Los textos de los libros se guardan localmente en el navegador. Descargá una copia de seguridad con frecuencia.
