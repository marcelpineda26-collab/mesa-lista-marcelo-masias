# Mesa Lista

Aplicación web de demostración para gestionar reservas de Casa Oliva. Construida con React, JSX y Vite; los datos se guardan localmente en el navegador mediante `localStorage`.

## Prototipo de interfaz

[Abrir Mesa Lista en Figma](https://www.figma.com/design/1etvbSIIouey6BuMXAo5t3/Mesa-Lista---Sistema-de-reservas?node-id=3-2&t=wXtp6U56Uw6XDTLV-1)

## Requisitos
- Node.js 20 o superior y npm.

## Instalación y ejecución
1. Abre una terminal en la carpeta del proyecto.
2. Ejecuta `npm install`.
3. Ejecuta `npm run dev` y abre la URL local mostrada por Vite.
4. Para generar la versión de producción, ejecuta `npm run build`; los archivos se crean en `dist/`.

## Funcionalidades
- Agenda diaria y cambio entre fechas.
- Indicadores de reservas activas, comensales, confirmadas y pendientes.
- Búsqueda por cliente/teléfono/mesa y filtro por estado.
- Alta de reservas con fecha, hora, mesa, tamaño del grupo y notas.
- Validación para impedir dos reservas activas de la misma mesa en la misma fecha y hora.
- Confirmar, cancelar y eliminar reservas.
- Diseño adaptable para escritorio y móvil. En pantallas pequeñas la tabla se desplaza horizontalmente.

## Estructura
- `src/App.jsx`: vistas, estado, datos de muestra, validación y componentes.
- `src/styles.css`: estilos adaptables.
- `src/main.jsx`: punto de entrada.

## Datos y alcance
La aplicación es un prototipo funcional de frontend. Incluye datos ficticios de demostración y persistencia en el dispositivo actual. No tiene autenticación, servidor, sincronización entre dispositivos, envío real de confirmaciones ni gestión de aforo concurrente. Para producción se requiere API y base de datos compartida, autenticación y políticas de privacidad.

## Prueba de usabilidad
El informe adjunto propone tareas y registra resultados de una revisión heurística/simulada. No se realizaron entrevistas con usuarios reales; sustituir la sección de resultados por evidencia recogida con participantes antes de presentar como prueba real.
