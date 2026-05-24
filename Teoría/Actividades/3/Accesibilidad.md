<h1 align="center">Actividad teórica 3 (Accesibilidad)</h1>

## 1. Videos accesibles

### Observe las siguientes versiones de videos e identifique los elementos de accesibilidad que tiene y las mejoras realizadas.

### Video 1:

#### [Versión 1](https://www.youtube.com/watch?v=Ob0Lfvsf6ww&feature=emb_logo)

#### [Versión 2](https://www.youtube.com/watch?time_continue=2&v=fB8nCC5PrmI&feature=emb_logo)

#### [Versión 3](https://www.youtube.com/watch?v=O_Wz_Qv1PNI&feature=emb_logo)

Los elementos de accesibilidad que idealmente debería tener todo video según la teoría son:

1. Subtitulado
2. Transcripción en formato texto
3. Audiodescripción
4. Lenguaje de señas

La primer versión del video solo tiene subtitulado, el cual se ve claramente por tener un fondo gris detrás del texto y color de letra blanco. En ningún momento se dificulta la lectura de los subtítulos, por lo que es un elemento bien implementado. Sin embargo, no hay transcripción en formato texto en la descripción del video, no hay audiodescripción con voz en off y tampoco hay lenguaje de señas.

La segunda versión tiene el mismo subtitulado que la primera versión, pero además tiene audiodescripción con voz en off. Sin embargo, nuevamente no hay transcripción en formato texto ni tampoco lenguaje de señas.

La tercer y última versión tiene el mismo subtitulado y audiodescripción que las versiones anteriores y además suma una transcripción completa en formato texto en la descripción, así como también lenguaje de señas con una persona que hace la interpretación en la parte inferior derecha del video durante toda la duración del mismo.

Resumiendo:

| Video     | Subtitulado | Transcripción | Audiodescripción | Lenguaje de señas |
| --------- | ----------- | ------------- | ---------------- | ----------------- |
| Versión 1 | ✅          | ❌            | ❌               | ❌                |
| Versión 2 | ✅          | ❌            | ✅               | ❌                |
| Versión 3 | ✅          | ✅            | ✅               | ✅                |

### Video 2:

#### [Versión 1](https://drive.google.com/file/d/11chRNeRkKanh_SzeKaRJR80yrTyRwkuw/view?usp=sharing)

#### [Versión 2](https://drive.google.com/file/d/1K2gENTK5EBoX1Nh4qDtxEAk-aKT67PYk/view?usp=sharing)

La primer versión del video no tiene ningún elemento de accesibilidad: no hay subtítulos, no hay transcripción en formato texto, no hay audiodescripción y no hay lenguaje de señas.

La segunda versión del video sí tiene subtítulos, los cuales nuevamente son faciles de leer. Además tiene audiodescripción y lenguaje de señas, pero no tiene transcripción en formato texto.

Resumiendo:

| Video     | Subtitulado | Transcripción | Audiodescripción | Lenguaje de señas |
| --------- | ----------- | ------------- | ---------------- | ----------------- |
| Versión 1 | ❌          | ❌            | ❌               | ❌                |
| Versión 2 | ✅          | ❌            | ✅               | ✅                |

## 2. Observe los siguientes videos y responda los ítems a. al d.

### a. Situación de la persona y qué producto digital quería acceder.

### b. Con qué problemas de accesibilidad se encontró. Qué información/funciones fueron inaccesibles.

### c. Qué criterios de accesibilidad de WCAG 2 infringe?

### d. Qué solución recomendaría.

### [Video 1](https://www.youtube.com/watch?time_continue=4&v=G5kGRE07CvI&feature=emb_logo)

1. La persona es una mujer ciega y quería acceder a un email que recibió del Banco Patagonia sobre una renovación de ambientes en 12 cuotas sin interés.
2. Se encontró con el problema de que el email no tenía una estructura semántica clara, lo que dificultaba la navegación con su lector de pantalla. En particular:
   1. Algunos enlaces no están etiquetados correctamente, por lo que el lector los interpreta como códigos numéricos sin ningún sentido.
   2. Se ofrece descargar dos archivos que no tienen nombre, por lo que el lector no lo puede interpretar y la persona ciega no tendría idea de qué es.
   3. Varios gráficos no tienen texto alternativo/descripción, por lo que el lector de pantalla no tiene manera de describirlos.
3. Infringe los criterios [2.4.4 Link Purpose (In Context)](https://www.w3.org/WAI/WCAG22/quickref/#link-purpose-in-context), [4.1.2 Name, Role, Value](https://www.w3.org/WAI/WCAG22/quickref/#name-role-value) y [1.1.1 Non-text Content](https://www.w3.org/WAI/WCAG22/quickref/#non-text-content).
4. Recomendaría que el email tenga una estructura semántica clara, con encabezados, párrafos y enlaces etiquetados correctamente. Además, los archivos adjuntos deberían tener nombres descriptivos y los gráficos deberían tener siempre un texto alternativo que describa con precisión su contenido.

### [Video 2](https://drive.google.com/file/d/1K32_1efM52tHfo7gvMqw7ixvUd0kHv9s/view?usp=sharing)

1. La persona es una mujer ciega y quería acceder al sitio de aulas web con información relevante a la cursada, horarios, bibliografía, etc.
2. Se encontró con el problema de que el recorrido con teclado es difícil en los foros, y hay problemas en archivos PDF que se suben a la plataforma, ya que algunos poseen contenido escaneado que el lector no tiene forma de interpretar.
3. Infringe los criterios [2.1.1 Keyboard](https://www.w3.org/WAI/WCAG22/quickref/#keyboard) y [1.1.1 Non-text Content](https://www.w3.org/WAI/WCAG22/quickref/#non-text-content).
4. Recomendaría que el sitio de aulas web tenga una estructura semántica bien hecha para que todo elemento sea accesible con el teclado. Además, los archivos PDF que se suban a la plataforma deberían ser siempre en formato texto o si no hay manera de evitar subir archivos escaneados, deberían tener una descripción alternativa que explique su contenido.

### [Video 3](https://drive.google.com/file/d/15UhhOETWuL4iOgZBbKVAl0ujRURI-EyE/view?usp=drive_link)

1. La persona es un hombre que pretende ser ciego para probar la accesibilidad del sitio de login del banco ICBC.
2. Se encontró con que la experiencia es mala, para empezar porque el lector de pantalla lee muchos elementos "en blanco" que no tienen ningún sentido, lo cual se debe a que el sitio no tiene una estructura semántica clara. Además, el campo de password en el formulario no tiene ninguna etiqueta, por lo que el lector de pantalla no puede identificarlo correctamente y la persona ciega no tiene forma de saber qué es lo que está ingresando/editando. Para peor, una vez la persona intenta ingresar y las credenciales no son válidas, el mensaje de error cuando es leído por el lector contiene textos irrelevantes.
3. Infringe los criterios [2.1.1 Keyboard](https://www.w3.org/WAI/WCAG22/quickref/#keyboard), [4.1.2 Name, Role, Value](https://www.w3.org/WAI/WCAG22/quickref/#name-role-value) y [3.3.1 Error Identification](https://www.w3.org/WAI/WCAG22/quickref/#error-identification).
4. Recomendaría que el sitio mejore su estructura para ser más semántica, de manera que el lector de pantalla pueda interpretar correctamente cada elemento y así se pueda navegar con teclado sin problemas. Además, el campo de password debería tener una etiqueta clara para que el lector pueda identificarlo correctamente. Por último, el mensaje de error debería ser claro y contener solo la información relevante para que el usuario pueda entender qué es lo que hizo mal.

### [Video 4](https://drive.google.com/file/d/1ksMNv_L8x3QeTehVO_RMjw1sDt-5qAS2/view?usp=sharing)

1. La persona es un hombre ciego que quería acceder al sistema SUBE en la computadora.
2. Se encontró con que la pantalla principal que aparece al abrir el programa tiene 4 botones de los cuales ninguno está etiquetado por lo que al recorrerlos con el tab en el teclado, el lector de pantalla no dice nada sobre ellos y la persona no tiene idea de dónde "está parada" ni qué hace cada botón.
3. Nuevamente infringe el criterio [4.1.2 Name, Role, Value](https://www.w3.org/WAI/WCAG22/quickref/#name-role-value) y el [2.1.1 Keyboard](https://www.w3.org/WAI/WCAG22/quickref/#keyboard).
4. Recomendaría que cada botón tenga una etiqueta clara para que el lector de pantalla pueda identificarlo correctamente y así la persona ciega pueda navegar sin problemas con el teclado.

### [Video 5](https://drive.google.com/file/d/12rMn-J12AUiOrXRB7Cj4fzAxDzzlq3Tg/view?usp=sharing)

1. La persona es una mujer ciega que quería acceder a la página de inicio del sitio del BNA.
2. Se encontró con que si bien al navegar con teclado se puede acceder a todos los elementos, los nombres de los mismos no son claros, ya que omiten información que sí está presente visualmente. Por ejemplo, el botón de "Quiero abrir mi cuenta" es leído por el lector de pantalla como "Quiero abrir" y luego de otro tab se lee "mi cuenta", lo cual es confuso y molesto.
3. Se viola el criterio [2.4.6 Headings and Labels](https://www.w3.org/WAI/WCAG22/quickref/#headings-and-labels).
4. Recomendaría que se revise el código HTML, en particular el uso de los headers, porque está mal organizado y eso hace que el lector de pantalla no los pueda interpretar bien.

## 3. Ingrese al [enlace de w3 sobre accesibilidad](https://www.w3.org/WAI/demos/bad/)

### a. Evalúe utilizando un validador automático de accesibilidad los sitios

#### i) [Before](https://www.w3.org/WAI/demos/bad/before/home.html)

Usando el validador automático de accesibilidad [WAVE](https://wave.webaim.org/extension/) se encontraron 37 errores, la gran mayoría de ellos relacionados a la falta de texto alternativo en etiquetas HTML. Además se encontraron 35 alertas, la mayoría relacionadas a estructura del sitio dudosa. El puntaje AIM es de 3.5/10.

#### ii) [After](https://www.w3.org/WAI/demos/bad/after/home.html)

Usando el mismo validador se encontraron 0 errores y 7 alertas de detalles menores. El puntaje AIM es de 9.5/10.

### b. A nivel visual qué diferencias nota?

Noto varias diferencias:

1. La versión mejorada tiene links mucho más claros, con textos descriptivos que indican exactamente a dónde llevan, mientras que la versión original tiene links con textos genéricos como "Click here" o "Read more".
2. La versión mejorada tiene una fuente más clara, moderna y fácil de leer que la original.
3. En la versión original hay una imagen al final de la página con un número de telefono que es dificil de leer, mientras que en la versión mejorada el número de teléfono está escrito en texto y es totalmente legible.
4. Los links en la versión mejorada son mucho más claros al estar en color rojo y subrayados, mientras que en la versión original son de color celeste y sin subrayar, lo que es malo para el contraste.
5. Las imagenes están mejor centradas en la versión mejorada, mientras que en la original están un poco alineadas hacia la izquierda.

### c. Dónde están las diferencias realmente?

La mayoría de las diferencias están en el código HTML, ya que la versión mejorada tiene una estructura semántica clara, con encabezados, párrafos y enlaces etiquetados correctamente. Como se dijo en el primer punto, la mayoría de las mejoras vienen de agregar texto alternativo claro y descriptivo a todo tag que lo permita, lo que hace que el sitio sea mucho más accesible para personas con discapacidad visual que utilizan lectores de pantalla. Además, la versión mejorada tiene un mejor contraste de colores y una fuente más legible, lo que también mejora la accesibilidad para personas con visión disminuida.

### d. Cuál es la mejor versión? Por qué?

Claramente la mejor versión es la "After", ya que no solo es más accesible para personas con discapacidades visuales sino que también es más legible, fácil de navegar y agradable visualmente para prácticamente cualquier usuario.

## 4. Sobre WAI - ARIA

### Indique para qué sirve respecto al desarrollo accesible el estándar WAI ARIA Accessible Rich Internet Application y qué novedades introduce la última versión 1.2. Muestre ejemplos de código donde se aplique.

El estándar WAI ARIA (Accessible Rich Internet Application) es una especificación del W3C que permite que los sitios y aplicaciones web sean más accesibles para personas con discapacidades, especialmente aquellas que usan tecnologías de asistencia como lectores de pantalla. Básicamente proporciona funcionalidades extra al HTML para mejorar la accesibilidad en los casos donde el HTML semántico, el texto alternativo, etc no alcanzan para hacer que un sitio sea completamente accesible.

Se compone de tres elementos:

1. Roles: definen qué es cada elemento HTML, por ejemplo si es un botón, un menú de navegación, otra pestaña, etc.
2. Propiedades: permiten agregar información adicional a los elementos HTML, como por ejemplo si un elemento está obligatoriamente vacío, si está desplegado o no, o cual es su posición actual.
3. Estados: indican la condición actual de un elemento HTML en tiempo real, por ejemplo si un botón está deshabilitado o no, o si un elemento está actualmente con foco o no.

## 5. Sobre herramientas para accesibilidad

### Indique herramientas para validar o comprobar accesibilidad que puede incorporar:

#### En diseño

Las herramientas principales para esto son plugins de accesibilidad que se pueden integrar a las herramientas de diseño como Figma. Ejemplos: [Stark](https://www.figma.com/community/plugin/732603254453395948) y [Able](https://www.figma.com/community/plugin/734693888346260052).

#### Como complementos en el navegador

La más usada es la que usé en el punto 3: el validador automático de accesibilidad [WAVE](https://wave.webaim.org/extension/), que se puede instalar como extensión tanto en Chrome como Firefox como Edge.

Otra popular es [axe DevTools](https://www.deque.com/axe/devtools/), que también se puede instalar como extensión en los navegadores más populares.

#### Como herramientas para el desarrollador en el navegador

En Chrome tenemos el DevTools Accessibility Panel y en Firefox el Firefox Accessibility Inspector. Ambos permiten analizar la accesibilidad de un sitio web en tiempo real, ayudando a los desarrolladores a identificar problemas de accesibilidad y a entender cómo los usuarios con discapacidades interactúan con su sitio.

#### Dentro de GitHub

En GitHub se pueden usar GitHub Actions que permiten integrar validadores de accesibilidad en el proceso de desarrollo, de manera que cada vez que se haga un commit o se abra un pull request, se ejecute automáticamente una revisión de accesibilidad y se informe a los desarrolladores sobre cualquier problema encontrado. Ejemplos: [axe Linter](https://github.com/marketplace/axe-linter), [GitHub Accessibility Scanner](https://github.com/github/accessibility-scanner) o [AI WCAG Code Review Action](https://github.com/marketplace/actions/ai-wcag-code-review-action)
