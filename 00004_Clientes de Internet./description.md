Los nodos desde los que se solicitan datos, usualmente también lo hacen a partir de otro tipo de programas que se llaman **clientes**, que principalmente ahorran el trabajo de tener que escribir código :pencil: cada vez que se quiere consultar un servidor.

Lo más común es que hagamos _consumo_ de datos a través de _clientes_, y que la mayoría de los _sitios_ que visitamos estén alojados en _servidores_. Esa relación es lo que se llama **arquitectura cliente-servidor**, donde la gestión de envío de datos (a qué nodo y con qué prioridad) queda del lado del servidor, mientras que el rol del cliente es más pasivo y solo se limita a pedir y recibir información.

Puede parecer confuso, pero es sencillo.  ¿Cuál de estos ejemplos sería el correcto?

Cliente consulta servidor, servidor gestiona y envía datos. (correcto)
Cliente consulta servidor, cliente gestiona y envía datos.
Servidor consulta cliente, cliente gestiona y envía datos.
Servidor consulta cliente, servidor gestiona y envía datos.
