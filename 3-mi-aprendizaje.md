Durante la práctica, aprendimos a configurar aplicaciones multi-contenedor utilizando Docker Compose, una de ellas integrando el SonarQube. Aprendimos a implementar `healthchecks` para asegurar que los servicios estuvieran listos antes de depender unos de otros, evitando errores de sincronización. Esto nos permitió comprender cómo orquestar servicios complejos de forma eficiente.

Un desafío clave fue resolver el error "database 'sonar' does not exist", lo que nos llevó a analizar logs, ajustar configuraciones y crear la base de datos manualmente dentro del contenedor de PostgreSQL. Esta experiencia mejoró nuestra capacidad para identificar problemas, implementar soluciones prácticas y comprender la importancia de eliminar volúmenes persistentes cuando se presentan errores en datos previos. Estos aprendizajes nos permiten gestionar entornos contenedorizados con mayor precisión y confiabilidad.

Práctica realizada por Christian Díaz y Joffre Salvador
