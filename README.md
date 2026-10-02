# ConsultorIA

Aplicación web de un solo fichero que da **feedback estratégico** sobre las prácticas de estudiantes de **periodismo y comunicación audiovisual** (y áreas afines). Lee la entrega, comprueba los requisitos de la actividad con evidencias reales y redacta un feedback con fortalezas, oportunidades de mejora y un *insight* final. **No pone notas.**

**Usar la app:** https://fborrasumh.github.io/consultoria/

## Origen de la idea

ConsultorIA generaliza el ejercicio **«Evaluación de prácticas con IA»** de **José Alberto García Avilés** (Universidad Miguel Hernández de Elche, Máster en Innovación en Periodismo): un cuaderno que, a partir del enunciado y los criterios de una práctica, genera para cada estudiante un feedback estratégico con fortalezas y logros, debilidades y oportunidades de mejora, y una conclusión inspiradora.

## Qué hace

- **Actividades:** 14 plantillas de periodismo, comunicación y audiovisual (noticia, reportaje, entrevista, podcast, guion, storyboard, plan de comunicación, pitch de innovación, análisis de medios, verificación, newsletter, memoria de prácticas, pieza multimedia y la práctica original de análisis de comunidades). También se puede importar un enunciado en Word o PDF y extraer criterios y requisitos con IA.
- **Entregas:** Word, PDF, PowerPoint (con notas del ponente), texto, imágenes (también las incrustadas en Word y PowerPoint), audio y vídeo. El audio se extrae en el navegador y se transcribe con OpenAI o Gemini.
- **Requisitos verificados:** cada requisito se comprueba con citas literales de la entrega. Los recuentos («al menos 4 metodologías») los hace el código: si la IA da por cumplido un requisito pero faltan elementos con evidencia, el estado se corrige. Las citas que no aparecen en la entrega se descartan.
- **Feedback sin notas:** estructura fija (fortalezas y logros · debilidades y oportunidades de mejora · conclusión: el insight), con tono, extensión e idioma ajustables. Si el texto contiene porcentajes o puntuaciones, se reescribe.
- **Grupo:** cumplimiento de requisitos en toda la clase y síntesis de patrones comunes, con datos anonimizados.
- **Salidas:** un Word por estudiante, ZIP, CSV de requisitos.
- **Modo alumnado:** genera una página con la actividad cargada para que cada estudiante pida feedback de su borrador antes de entregar. Usa la clave de cada estudiante; la herramienta nunca incluye ninguna clave en los ficheros que genera.

## Cómo se usa la IA

Con la propia clave de **OpenAI, Google Gemini o Anthropic Claude** (con visión para las imágenes). Para transcribir audio se necesita OpenAI o Gemini. La clave se guarda solo en el navegador. No hace falta servidor.

## Privacidad

Las entregas se guardan en el navegador. Al generar, el texto sale hacia el proveedor de IA con el nombre del estudiante y los datos personales enmascarados, y antes del primer envío se muestra una muestra de lo que sale. **Las imágenes no se pueden enmascarar**: hay que comprobar que no muestran caras o datos que no deban enviarse.

## Límites

- De audio y vídeo solo se analiza la transcripción: no se valora la calidad técnica de la imagen, el sonido ni el montaje, y el feedback lo indica.
- En los PDF no se detectan las imágenes incrustadas y no se hace OCR de texto, salvo enviar las primeras páginas como imágenes si el PDF no tiene texto.
- La IA puede equivocarse: el feedback es una propuesta que el profesorado debe leer y editar. La valoración final es suya.

## Autoría

Fernando Borrás Rocher y José Alberto García Avilés · Universidad Miguel Hernández de Elche.

## Cómo citar

Borrás Rocher, F. y García Avilés, J. A. (2026). *ConsultorIA* (v1.0.0) [Software]. Universidad Miguel Hernández de Elche. (DOI en trámite)

## Licencia

MIT. Véase [LICENSE](LICENSE).
