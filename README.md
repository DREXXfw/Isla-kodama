# ISLA KODAMA — prototipo Android

## Qué contiene
- Isla 3D generada proceduralmente.
- Cámara en tercera persona y controles táctiles.
- Joystick virtual, movimiento por teclado para pruebas.
- Recolección básica de madera, piedra, fibra y bayas.
- Hambre, energía y vida.
- Construcción de primer refugio y fogata.
- Animales ambientales sencillos.
- Ciclo de días y estaciones simplificado.
- Guardado local de datos básicos.
- Contador FPS visible.

## Importante
Esta entrega es un prototipo integrado optimizado, no el juego comercial terminado ni las ocho fases avanzadas completas. Los aldeanos reclutables, rutinas complejas, combate completo, inventario avanzado, clima detallado, festivales, sonido y animaciones finales aún requieren desarrollo.

## Ejecutar en Replit
1. Crea un proyecto web Node.js/Vite.
2. Sube el contenido de esta carpeta conservando `src/` y `index.html`.
3. En la consola ejecuta `npm install`.
4. Ejecuta `npm run dev -- --host 0.0.0.0`.
5. Abre la vista previa.

## Rendimiento
- Pixel ratio limitado a 1.35.
- Antialias desactivado.
- Sombras en tiempo real desactivadas.
- Geometrías low-poly y materiales compartidos donde es posible.
- Número limitado de objetos y animales.
- Sin partículas permanentes ni efectos de postprocesado.

El contador FPS mide los fotogramas por segundo aproximados de renderizado. El rendimiento dependerá del dispositivo, navegador y temperatura.
