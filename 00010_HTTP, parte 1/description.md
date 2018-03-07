Los 4 comandos que mencionamos se usan para hacerle distintos tipos de peticiones al servidor. 

El más común es `GET`, y se utiliza para obtener un archivo o _recurso_ del servidor. Básicamente, es el método que nos devuelve los datos de una página o del pedido que hayamos hecho.

El siguiente es `POST`, que sirve para enviarle información al servidor, la cual se almacenará como actualización de cierto elemento o recurso existente. Lo más común es usarlo en el envío de formularios que se encuentran en la página web.

Así como podemos obtener y actualizar algo existente, también deberíamos poder crear o eliminar. Para eso existen los métodos `PUT` y `DELETE`. `PUT` creará en el servidor un nuevo recurso, o reemplazará a otro en caso de que ya exista, mientras que `DELETE` obviamente le pide al servidor que borre cierto recurso específico. Esto se podría usar, por ejemplo, cuando creas un nuevo usuario en alguna página, o cuando te das de baja. 