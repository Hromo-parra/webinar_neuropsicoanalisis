# El cerebro que no sabe que sabe

Material interactivo en español del webinar de Héctor Romo-Parra. Sitio estático con HTML, CSS y JavaScript puros: no requiere compilación, instalación, backend ni paquetes.

## Usar localmente

Para abrir o copiar un solo archivo, usa `webinar_completo.html`: incluye los estilos y la lógica de los cinco módulos. Para usar la versión separada, conserva `index.html`, `styles.css` y `app.js` juntos en la misma carpeta y abre `index.html` en un navegador moderno. También puedes servir esta carpeta con cualquier servidor estático. Google Fonts requiere conexión; las tipografías del sistema son el respaldo.

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub y coloca `index.html`, `styles.css`, `app.js` y `.github/workflows/pages.yml` en la raíz del repositorio. Conserva el workflow dentro de su directorio.
2. Usa `main` como rama principal. Si usas otra rama, modifica `branches: [main]` en el workflow.
3. En **Settings → Pages → Build and deployment → Source**, selecciona **GitHub Actions**.
4. Sube un commit a `main`, o ejecuta **Actions → Publicar en GitHub Pages → Run workflow**.
5. Cuando termine el workflow, abre la URL indicada en el entorno `github-pages` o en Settings → Pages. Normalmente será `https://TU_USUARIO.github.io/TU_REPOSITORIO/`.

Las rutas relativas funcionan tanto en Pages de proyecto como en Pages de usuario. El workflow publica únicamente los tres archivos del sitio, no el README ni otros archivos del repositorio. Este proyecto no ha sido publicado automáticamente.

## Actividades

- Leer en espejo: cinco rondas cronometradas desde la aparición de la palabra hasta una respuesta correcta. Gráfica SVG y tabla equivalente, sin forzar una mejora.
- ¿B o 13?: dos contextos con exactamente el mismo trazo SVG; admite una respuesta indecisa.
- Señal borrosa: cuatro frases, comparación explícita entre expectativas confirmadas y continuaciones inesperadas. Control operable con flechas y revelación textual al 100 %.
- ¿Qué sabemos y qué suponemos?: ejemplo inicial y doce afirmaciones para distinguir datos, modelos e hipótesis sobre el caso.
- Expediente de Lucía: cuatro datos de un personaje ficticio, hipótesis libre y contraste de una hipótesis provisional explícita.

## Privacidad y accesibilidad

No se usa almacenamiento persistente, cookies, analítica, formularios remotos ni peticiones de envío. Respuestas y tiempos solo existen en memoria durante la actividad. Cambiar de módulo reinicia la actividad; recargar elimina todas las respuestas. No escribas datos personales.

Google Fonts es una petición externa de recursos tipográficos y puede recibir metadatos habituales de conexión. No recibe respuestas de la aplicación. Para uso completamente desconectado, elimina los enlaces de Google Fonts de `index.html`; las fuentes de respaldo seguirán funcionando.

Idioma declarado, texto mínimo de 18 px, enlaces de salto, foco visible, formularios etiquetados, estados anunciados y navegación por teclado. Texto principal #1D2433 sobre #F6F3EC; botones Dato con texto blanco sobre #2B5F9E; Modelo con texto oscuro sobre #E2A34A; Apuesta con texto blanco sobre #6B2D6B. El color nunca es el único indicador de una categoría. Las tareas visuales no ofrecen una medición equivalente con lector de pantalla: se explicita esta limitación y se ofrecen explicaciones y datos textuales.

## Alcance didáctico

Aviso visible: «Material didáctico; no es una herramienta diagnóstica». Las actividades no evalúan capacidades clínicas ni demuestran mecanismos cerebrales individuales. La lectura en espejo no incluye una prueba de recuerdo; los tiempos combinan lectura y escritura. La conclusión describe cambios de desempeño sin asumir una mejora ni atribuirlos a memoria implícita. Cinco rondas sin evaluar recuerdo explícito no reproducen el estudio de Cohen y Squire.

Referencia: Cohen, N. J. y Squire, L. R. (1980). *Preserved learning and retention of pattern-analyzing skill in amnesia: dissociation of knowing how and knowing that*. Science, 210(4466), 207–210. https://pubmed.ncbi.nlm.nih.gov/7414331/

El quiz distingue tipos de afirmación y no equipara «modelo» con ausencia de evidencia. Las hipótesis sobre un caso no se etiquetan automáticamente como neuropsicoanalíticas.

## Comprobación manual

Recorre todas las actividades con Tab, Shift+Tab, Enter y las flechas del control de claridad. Completa cinco rondas; comprueba errores y resultados sin descenso. Responde los dos contextos SVG. Revela las cuatro frases, completa las doce preguntas y contrasta las tres opciones del caso. Comprueba el diseño en móvil y la tabla de tiempos con lector de pantalla. Comprueba que recargar reinicia todo y que no aparecen peticiones con respuestas en la pestaña Network.
