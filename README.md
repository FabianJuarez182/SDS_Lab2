# SDS_Lab2
 Curso Intensivo de Gen IA

1. ¿Hubo alguna aplicación o caso de uso de los LLMs que le llamó más la atención? ¿Por qué?

        La que me llamo mas la atencion fue la clasificación de texto usando embeddings generados por modelos avanzados como Gemini.
        Porque, al utilizar la API de Gemini para obtener embeddings de textos y entrenar el modelo de Keras me parecio interesante como los LLMs pueden mejorar tareas clásicas del procesamiento del lenguaje natural sin necesidad de entrenar los modelos desde 0, asi reducimos recursos y tiempo computacional.

2. Proponga un caso de ciberseguridad que considere se puede solucionar mediante un LLM y describa de forma general cómo lo resolvería

    ***Problema***

        Cuando las organizaciones enfrentan constantes amenazas cibernéticas en sus redes. Los analistas de seguridad en los SOC deben manejar una cantidad rande de alertas diariamente, lo que los puede llevar a una fatiga por todas ellas, tambien un tiempo de respuesta menor y errores humanos en la toma de decisiones.

    ***Solución General***

        Implementar un LLM que actúe como asistente en un SOC, sugiriendo pasos de mitigación en caso de un ataque, generando reportes detallados y automatizando tareas de respuesta inicial. Este modelo se integraría con plataformas como SIEM, SOAR y EDR para optimizar la detección y gestión de incidentes.

        El LLM procesaría las alertas generadas por el SIEM, filtrando falsos positivos y clasificando las amenazas según su nivel de riesgo. A partir de este análisis, generaría una respuesta y propondría medidas de mitigación, describiendo el incidente y su impacto. Posteriormente, automatizaría acciones de respuesta en el SOAR. Finalmente, funcionaría como asistente para los analistas, respondiendo preguntas sobre amenazas y tácticas de atacantes, apoyando en la investigación de incidentes y generando reportes detallados.
