<h1 align="center">Actividad teórica 4 (DCU y Accesibilidad)</h1>

## 1. Las técnicas y métodos de usabilidad sirven para relevar, estudiar, investigar y confeccionar los requerimientos a nivel de la interfaz del usuario, y así poder converger y plantear un buen diseño de la misma que permita experiencias digitales de calidad. Estas técnicas pueden ser replanteadas y adaptadas de acuerdo al caso, y ser utilizadas en distintas etapas metodológicas. Revise el siguiente material e indique las técnicas de DCU utilizadas y con qué finalidad.

### [Del telegrama a los tweets - Capítulo 5](https://drive.google.com/file/d/1NOPRbrajJVIycNVZhjY4Js7iTW8HDDhW/view?usp=sharing)

Primero se usaron **encuestas y entrevistas** con la finalidad de obtener info sobre el perfil de los usuarios participantes, como su nivel educativo, a qué se dedican y por qué les interesa usar redes sociales como Facebook y Twitter, además de indagar sobre conocimientos previos relacionados a estos dos sitios. La encuesta se llevó a cabo tanto digitalmente (Google Forms) como físicamente en papel.

Luego se realizaron dos **testeos de usabilidad** que tuvieron como objetivo analizar cómo interactúan las personas ancianas con Facebook y Twitter, analizando la eficiencia, eficacia y grado de satisfacción. Básicamente, se les asignó a cada participante mayor 10 actividades a llevar a cabo en Facebook y 5 en Twitter, mientras las personas que llevaban a cabo el testeo las observaban directamente y tomaban notas.

Después se llevó a cabo un **Cuestionario SUS (System Usability Scale)** con la finalidad de obtener medidas de usabilidad percibidas por los participantes y sus grados de satisfacción frente a las interacciones llevadas a cabo en los dos testeos anteriores.

Más adelante se utilizó la técnica de **Card Sorting** vía un software llamado OptimalSort, con el objetivo de que los adultos mayores pudieran convertir sus críticas sobre la sobrecarga y desorganización de Facebook en propuestas constructivas de rediseño, involucrándolos así en la reorganización funcional y mejor jerarquización de la información del sitio mencionado.

Finalmente, se usó un **juego interactivo** desarrollado en Python que tuvo como propósito evaluar de forma concreta y transparente los conocimientos sintácticos previos y de uso que los participantes tenían sobre Facebook, pidiendoles localizar opciones en una interfaz simulada. Todo esto se hizo proque en las encuestas y entrevistas iniciales se detectaron ambiguedades: muchos encuestados decían que sabían poco y nada de cómo usar el sitio pero se contradecían diciendo también que tenían una cuenta y que usaban el sitio frecuentemente; otros afirmaban que sabían usar bien la aplicación pero cuando empezaban a utilizarla se perdían o necesitaban mucha ayuda.

### [Del telegrama a los tweets - Capítulo 4](https://drive.google.com/file/d/19yJGqQb-Mae0Hzuz4CtfQtqOQUVpSdmN/view?usp=sharing)

Primero se usó el método de **inspección y evaluación heurística** que consiste en una examinación formal y objetiva de las interfaces de usuario, en este caso Facebook, Twitter, Google Docs, Google Drive, que es llevada a cabo por un experto en HCI. El objetivo fundamental es determinar el grado de usabilidad y accesibilidad de las aplicaciones y detectar errores, comprobando si estas páginmas habían sido diseñadas teniendo en cuenta a las personas mayores. Para lograr esto, se adaptó y construyó un conjunto de 65 heurísticas creadas específicamente para medir aplicaciones web colaborativas considerando el perfil de los adultos mayores. Estas heurísticas se diseñaron teniendo en cuenta los aportes fundamentales de Nielsen, Montero y Fernandez, Leavitt y Shneiderman, NIA, W3C, WCAG, entre otros.

Luego se realizó una **evaluación automática de accesibilidad web** usando el validador WAVE que tuvo como finalidad principal analizar el código HTML de los cuatro sitios y evaluar de forma rigurosa el cumplimiento o no de las normativas de accesibilidad WCAG 2.0 que la W3C recomienda encarecidamente. Esto permitió entender el estado técnico de las aplicaciones y anticipar cómo el código inaccesible afectarían a la interacción de las personas grandes con el sitio.

### [Martín - Test Escenario 1](https://drive.google.com/file/d/18KC1uhFELEk5uy0tQrrwsAxd7dy0aBs-/view?usp=sharing) (participó una persona sorda)

El video muestra un ejemplo claro de **testeo de usabilidad**, donde se busca que una persona sorda muestre detalladamente y paso a paso cómo intenta usar determinada página para realizar una determinada acción, en este paso comprar una crema para manos de la página Natura. El video muestra lo difícil e inconveniente que es el proceso debido a que el sitio no es para nada accesible.

### [Benchmark + métricas ISO](https://drive.google.com/file/d/1r-FzhhnMUHBWGM5aDGx8R0otwfDIaJ15/view?usp=sharing)

La técnica utilizada es la de **reportes benchmark**, donde se compara el rendimiento de un sitio web (bunches.co.uk) frente a su competidor principal, pidiendole a un grupo de participantes que completen una serie de tareas en ambos sitios. Esta técnica se utiliza con el propósito de medir qué tan bien se desempeña una interfaz contra otra utilizando las tres métricas típicas: eficacia, eficiencia, satisfacción.

### [Carrefour - Diagnóstico accesibilidad de redes sociales](https://drive.google.com/file/d/1FF7QSn7ruCSM19Dtbur0-ngjqzug7afU/view?usp=sharing)

Se usó la técnica de **inspección de accesibilidad web** desde la perspectiva del usuario, con el objetivo de hallar falencias típicas que dañan la inclusividad e accesibilidad, como imágenes sin texto alternativo, videos sin subtítulos/descripción o con problemas de contraste, contenido imposible de procesar para personas no videntes, malos contrastes en letras, fondos o elementos, uso cuestionable de tipografía, ruido visual, entre otros.

### Indique qué técnicas de usabilidad utilizaría en sus desarrollos, en qué etapa metodológica la incluiría, y por qué.

En la etapa inicial de análisis de requerimientos haría uso de entrevistas y/o cuestionarios para entender las necesidades de los usuarios. Me aseguraría de que el grupo de usuarios que participen en esta etapa sea lo más diverso posible. Además, sería útil usar Card Sorting para entender cómo estos mismos usuarios interpretan se debería agrupar la información de la aplicación de la forma más intuitiva.

En la etapa de diseño y prototipado de la aplicación usaría testeos de usabilidad para ver con claridad cómo las personas interactúan con este prototipo y detectar errores o cosas no intuitivas en la app. También usaría mapas de calor y seguimiento ocular (si es posible) o seguimiento de clicks para optimizar las zonas que menos atención reciben y entender qué zonas son las más atractivas y por qué motivos.

Una vez la aplicación está terminada y en producción, usaría tests A/B para probar nuevas versiones de la app con posibles mejoras, para cerciorarme de que las mismas realmente valen la pena o no. Adicionalmente, llevaría a cabo reportes benchmark para comparar nuestra app con alguna similar a la nuestra y ver en qué detalles aún podemos mejorar vs la competencia.

## 2. Realice una entrevista o encuesta sobre UX y discapacidad, a una persona con discapacidad. Se quiere indagar en base a sus experiencias digitales sobre cuestiones emocionales y factores humanos antes, durante o después de usar alguna app, sitio o software informático. Incluya el enlace a un video donde haya podido contar tal experiencia o a una evidencia que haya compartido la persona.

No pude concretar una entrevista con alguna persona con discapacidades.

## 3. Analice [esta publicación](https://webaim.org/projects/million/lookup) y realice una encuesta a colegas informáticos (mínimo 5) que se encuentren trabajando en el desarrollo de software sobre si en su equipo hay perspectiva de inclusión. Si dentro de la ingeniería de software aplican conceptos de accesibilidad. Indagar desde qué etapas, cómo, quiénes la impulsan, impacto dentro del grupo y de los usuarios. Detallar el instrumento de indagación empleado, método, resultados obtenidos, análisis de los mismos y conclusiones.

No conozco a nadie que esté trabajando como desarrollador.

## 4. Investigue qué herramientas sobre accesibilidad (como por ejemplo pa11y) se pueden incluir en repositorios y plataformas de almacenamiento de código y su relación con CI (Continuous Integration)

En repositorios y plataformas de almacenamiento de código como GitHub/GitLab/Bitbucket, se pueden incluir herramientas que permiten verificar la accesibilidad de la aplicación de forma automatizada. Esto permite detectar problemas de accesibilidad en el código cada vez que se realizan cambios nuevos, evitando que éstos lleguen a producción y afecten a los usuarios finales. Algunas de estas herramientas son:

- pa11y: Analiza páginas web según las pautas WCAG y genera reportes de accesibilidad.
- axe-core: Motor de accesibilidad desarrollado por Deque. Es una de las herramientas más usadas y sirve de base para otras soluciones.
- Lighthouse: Herramienta de Google que evalúa rendimiento, SEO, buenas prácticas y accesibilidad.

La relación con CI (Continuous Integration) es que CI consiste en ejecutar automáticamente tareas de validación cada vez que un developer realiza un cambio en el repositorio, por ejemplo al crear un pull request o hacer un commit. Al integrar herramientas de accesibilidad en el pipeline de CI, se puede garantizar que cada cambio en el código, por más pequeño que sea, sea analizado por estas herramientas automáticamente y se generen reportes con los problemas de accesibilidad detectados en dicho código.

El flujo básico sería: un developer hace un commit -> el pipeline de CI se ejecuta -> las herramientas de accesibilidad analizan el código -> se generan reportes -> si hay problemas, el pipeline falla y el cambio no se aprueba hasta que esos errores no sean corregidos.

Esto asegura que la accesibilidad no sea ignorada y los estándares de accesibilidad se mantengan firmes.
