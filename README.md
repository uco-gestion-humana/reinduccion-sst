# Guardianes de la Vida

Juego interactivo para repasar la inducción en Seguridad y Salud en el Trabajo (SG-SST).
24 retos en 6 rondas: encontrar peligros en una imagen, unir pares, clasificar, ordenar,
completar frases, escribir la respuesta y preguntas de selección. Suma puntos por velocidad y rachas.

## Cómo usarlo

Es un proyecto HTML estático, sin instalación ni dependencias.

- Abre `index.html` en el navegador, o
- publícalo con GitHub Pages (Settings → Pages → Deploy from a branch → `main` / root).

## Cómo editar el contenido

Todo está en `index.html`, dentro de la etiqueta `<script>`:

- `ROUNDS`: rondas y retos (preguntas, opciones, parejas, textos de "Para recordar").
  Tipos de reto: `quiz`, `tf`, `order`, `sort`, `match`, `cloze`, `type` y `hotspot`.
- `HAZ` y `SCENE`: los peligros y el dibujo de la oficina del reto "Encuentra los peligros".
- `IMG_QR`: ruta de la imagen del QR de la pantalla final (por ejemplo `assets/qr.png`).
  Si está vacío, se muestra un recuadro reservado.

## Ranking y panel del administrador

El ranking compartido y el panel de resultados dependen del entorno de Claude (claude.ai)
donde se publicó la versión original. Fuera de ahí, por ejemplo en GitHub Pages, el juego
funciona completo y guarda el mejor puntaje solo en el dispositivo de cada persona,
pero no hay ranking compartido ni panel del administrador.

## Créditos

Contenido basado en la presentación «Inducción SG-SST - Virtual» (Dirección de Gestión Humana).
La imagen `assets/bird.jpg` proviene de esa presentación.
