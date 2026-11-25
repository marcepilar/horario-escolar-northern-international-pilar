# Horario Escolar — Northern International School V1.0.1 DE PRUEBA

Nueva identidad visual con banner azul/turquesa y escudo **recreado**, basado en referencias públicas a un símbolo N/I/S. **No es el escudo oficial ni implica aprobación de Northern International School.**

Modificaciones V1.0.1: banner y los íconos, actualización de versión, caché y HTML interactivo. Mantiene los seis idiomas, los tres temas, los doce cursos de demostración, horarios ficticios para 2027 y funciones de compartir.

## GitHub Pages

Repositorio previsto: `marcepilar/horario-escolar-northern-international-pilar`.

Descomprimir y cargar **todos los archivos en la raíz de `main`**; GitHub Pages se configura con `main / (root)`. La aplicación genera su QR real al abrirse en su dirección HTTPS.

**No publicar ni declarar estable sin aprobación del usuario.** Verificar instalación en Samsung A71, service worker y recarga de preferencias en HTTPS.

## Pruebas realizadas
- Chromium automatizado con HTML autónomo: anchos de 320, 360 y 412 px; sin desbordes ni errores JavaScript detectados.
- Temas Dark Blue, Claro y Dark a 360 px.
- Seis idiomas: título, marca ✓, apertura de lunes y traducción de materias y recreos.
- Comparación de fuente: mismos horarios y lógica que V1.0.0; solo banner, íconos, CSS y versión cambiados.
- Pendientes: instalación física, persistencia con origen HTTPS y actualización real del service worker.
