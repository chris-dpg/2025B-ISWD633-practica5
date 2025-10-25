# COMPLETAR  
Comparando sus conocimientos antes de hacer la práctica con sus conocimientos después de hacer la tarea, explicar los principales aprendizajes logrados para beneficio de su formación profesional.  
Si solucionó un problema presentado al realizar la práctica también se debe documentar.

- Entendí cómo se estructura un archivo compose.yaml y para qué sirve cada parte, como los servicios, las redes y los volúmenes.
- Aprendí que la indentación en YAML es muy importante, porque si no se respeta los contenedores no se levantan bien.
- También comprendí cómo los servicios pueden depender uno del otro, como en el caso de WordPress y MySQL, o SonarQube y PostgreSQL, y que se puede usar depends_on con service_healthy para que esperen hasta que el otro esté listo.
- Aprendí a revisar el estado de los contenedores con docker compose ps y a ver los logs cuando algo no arranca bien.
- Tuve un problema al principio porque estaba ejecutando el comando desde el disco C directamente, y me salía el error “project name must not be empty”. Lo solucioné moviendo el archivo a una carpeta con nombre y volviendo a ejecutar el comando desde ahí.
