# Explicación de conceptos del HTML

Este documento resume los conceptos y etiquetas HTML que se explican en los comentarios del archivo `index.html` del proyecto. Está dirigido a estudiantes de frontend para ayudar a comprender el propósito y uso de cada sección.

---

## 1. Inclusión de hojas de estilo externas (CSS Frameworks)
En la cabecera (`<head>`) del HTML se muestran ejemplos de cómo agregar hojas de estilo externas, como Milligram, Pico CSS y Water CSS. Estas hojas de estilo permiten mejorar la apariencia de la página rápidamente usando estilos predefinidos.

**Ejemplo:**
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/water.css@2/out/light.css" />
```

---

## 2. Etiqueta `<audio>`
Permite agregar audio a la página web. Con los atributos `controls` y `autoplay`, el usuario puede controlar la reproducción o que el audio inicie automáticamente.

**Ejemplo:**
```html
<audio controls autoplay src="./audio/batman-series-tv-.mp3"></audio>
```

---

## 3. Uso de `<table>` para mostrar datos
Las tablas permiten organizar información en filas y columnas. En el ejemplo, se muestra una tabla de notas de alumnos usando `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, y `<td>`.

---

## 4. `<details>` y `<summary>` para FAQs
Estas etiquetas permiten crear secciones desplegables, ideales para preguntas frecuentes (FAQ). El usuario puede hacer clic en el resumen para ver más información.

**Ejemplo:**
```html
<details>
  <summary>¿Cuáles son los requisitos de ingreso?</summary>
  <ul>
    <li>Ser mayor de edad</li>
    ...
  </ul>
</details>
```

---

## 5. Popovers (Elementos emergentes)
Los popovers son elementos que muestran información adicional al usuario cuando realiza una acción, por ejemplo, hacer clic en un botón. Se usan los atributos `popover` y `popovertarget`.

**Ejemplo:**
```html
<button popovertarget="info-popover">Mostrar Info Adicional</button>
<div id="info-popover" popover>
  ...
</div>
```

---

## 6. Botones
Los botones (`<button>`) permiten al usuario interactuar con la página, por ejemplo, para guardar, cancelar o eliminar información.

---

## 7. URL Schemes
Permiten crear enlaces que abren aplicaciones externas, como hacer una llamada telefónica, enviar un correo o abrir WhatsApp.

- `tel:` abre la app de llamadas
- `mailto:` abre el cliente de correo
- Enlace de WhatsApp abre una conversación predefinida

**Ejemplo:**
```html
<a href="tel:+1134567890">Llama a la empresa</a>
<a href="mailto:ing.fabio.arg@gmail.com">Enviar correo</a>
<a href="https://web.whatsapp.com/send?...">Enviar whatsapp</a>
```

---

## 8. Uso de `<iframe>` para mapas, videos y sitios externos
La etiqueta `<iframe>` permite incrustar contenido de otras páginas web, como mapas de Google, videos de YouTube o sitios externos.

**Ejemplo:**
```html
<iframe src="https://www.google.com/maps/embed?..." width="100%" height="500"></iframe>
<iframe src="https://www.youtube.com/embed/..." width="560" height="315"></iframe>
```

---

Cada uno de estos conceptos es fundamental para el desarrollo de páginas web modernas y enriquecidas. ¡Explora el código y prueba modificar los ejemplos para aprender más!
