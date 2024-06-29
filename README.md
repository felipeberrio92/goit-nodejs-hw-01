
# Obtenemos y mostramos la lista completa de contactos en forma de tabla (console.table).

node index.js --action list
![Listar todos los contactos disponibles](./static/node1.png)

# Obtenemos un contacto según su id

node index.js --action get --id 05olLMgyVQdWRwgKfg5J6
![Alt text](./static/node2.png)

# Añadimos un contacto

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
![Alt text](./static/node3.png)

# Eliminamos un contacto

node index.js --action remove --id qdggE76Jtbfd9eWJHrssH
![Alt text](./static/node4.png)
