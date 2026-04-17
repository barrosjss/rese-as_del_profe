# 🍎 Actividad: Muro de Reseñas del Profe

¡Bienvenidos a esta actividad de colaboración en tiempo real! El objetivo de hoy es doble:
1. **Dominar el flujo de trabajo en Git/GitHub**: Aprenderemos a colaborar en un mismo repositorio utilizando ramas (branches) y Pull Requests (PR).
2. **HTML y CSS Inline**: Practicaremos la creación de tarjetas visualmente atractivas usando únicamente estilos en línea (`style=""`), lo que nos obliga a entender cómo funcionan las propiedades de CSS directamente sobre los elementos.

---

## 🚀 Instrucciones para Estudiantes

Sigue estos pasos cuidadosamente para agregar tu reseña al muro:

### 1. Preparación (Fork y Clona)
*   Haz un **Fork** de este repositorio a tu propia cuenta de GitHub.
*   Clona tu fork a tu computadora local.

### 2. Crea una Rama (Importante)
Para mantener el orden, **no trabajaremos en `main`**. Crea una rama con tu nombre:
```bash
git checkout -b reseña-tu-nombre
```

### 3. Edita el Archivo `index.html`
*   Abre el archivo `index.html`.
*   Busca la sección que dice `<!-- INICIO DE TARJETAS DE ESTUDIANTES -->`.
*   Copia la **Tarjeta Base de Referencia** y pégala al final de la lista.
*   **Personalízala**:
    *   Cambia el nombre, la institución y el mensaje.
    *   Modifica los colores de fondo (`background`), bordes (`border`), sombras (`box-shadow`) y fuentes.
    *   ¡Usa tu creatividad! Recuerda usar solo el atributo `style`.

### 4. Sube tus cambios
```bash
git add index.html
git commit -m "Agregada reseña de [Tu Nombre]"
git push origin reseña-tu-nombre
```

### 5. Crea el Pull Request
*   Ve a la página principal del repositorio original del profesor.
*   Verás un botón verde que dice **"Compare & pull request"**. Haz clic ahí.
*   Escribe un breve mensaje explicando qué personalización hiciste y envía el PR.

---

## 👨‍🏫 Guía para el Profesor (Control y Gestión)

Para mantener el control del repositorio y evitar un caos de conflictos:

1. **Revisión de PRs**: No fusiones (merge) inmediatamente. Revisa que el código sea correcto y que el estudiante solo haya modificado su parte.
2. **Estrategia de Branching**: Al obligar a los estudiantes a usar ramas, evitas que todos intenten empujar a `main` al mismo tiempo.
3. **Resolución de Conflictos**: Como todos editan el mismo archivo, GitHub podría detectar conflictos si dos personas editan líneas muy cercanas. 
    *   *Tip:* Pide a los estudiantes que dejen un par de líneas en blanco entre tarjetas para minimizar esto.
4. **Visualización**: Puedes activar **GitHub Pages** en la configuración del repositorio para que todos vean el muro final publicado en una URL.
5. **Control de Calidad**: Si un estudiante "rompe" el layout general, puedes pedirle cambios en el PR antes de aceptarlo.

---

## 🎨 Tipos de Estilos Sugeridos
Para que tu tarjeta destaque, intenta usar:
*   `border-radius`: Para esquinas redondeadas.
*   `box-shadow`: Para dar profundidad.
*   `transform: rotate(-2deg)`: Para un efecto de "pegatina" o nota física.
*   `linear-gradient`: Para fondos degradados modernos.

---
*¡Buena suerte y que gane la mejor reseña!*
