# Gestión de la implantación de redes telemáticas (MF0229_3) — Banco de Tests 📚

Tests interactivos para repasar **UF1877 – Planificación** y **UF1878 – Ejecución** del programa “Redes departamentales”.
Cada intento baraja las preguntas y **muestra 10 por página**, con botón “Comprobar” por pregunta, resultado final y reinicio.  
Total actual: **150+ preguntas** (bloques por unidad + finales).

**➡️ Demo:** https://github.com/alejo7774/test_unidad_II_redes_departamentales/

## ✨ Características
- UI agradable, emojis, dark mode y 100% responsive (móvil, tablet y desktop).
- Letras **a) b) c) d)** en las opciones.
- **Comprobar** por pregunta: marca correcta/incorrecta y muestra solución.
- **Paginación 10×10**, **barajado aleatorio** de preguntas.
- Resultado final con aprobado/no aprobado, conteos y botón **Reiniciar**.

## 🧩 Estructura
- `index.html`: todo el HTML+CSS+JS en un archivo (sin dependencias).
- `QUESTION_BANK` en el JS: pega ahí tus bloques de preguntas (objeto por pregunta con `text`, `options[]`, `answerIndex` y `explanation`).

## ➕ Añadir más preguntas
1. Abre `index.html`.
2. Busca `const QUESTION_BANK = [ ... ]`.
3. Pega tus objetos de pregunta al final del array y **guarda**.
4. Sube cambios (ver “Despliegue” abajo). GitHub Pages se actualiza solo.

## 🧪 Ejecutar en local
- Basta con abrir `index.html` en el navegador.  
- O levanta un servidor simple:
  - Python 3: `python -m http.server 8000` y abre http://localhost:8000

## 🚀 Despliegue (GitHub Pages)
Este repo se publica como **sitio estático**. Tras el primer push:
1. Settings → **Pages** → *Build and deployment* → **Source: Deploy from a branch**.
2. **Branch:** `main` • **Folder:** `/ (root)` → **Save**.
3. Espera ~1 min. Tu URL será: `https://TU_USUARIO.github.io/test_unidad_II_redes_departamentales/`.

## 🤝 Contribuir
- Pull Requests con más bloques de preguntas o mejoras de UI/UX son bienvenidos.
- Sigue *Conventional Commits*: `feat:`, `fix:`, `docs:`, etc.

## 📄 Licencia
[MIT](./LICENSE)
