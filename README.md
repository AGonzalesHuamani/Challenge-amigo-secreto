Challenge Amigo Secreto

Descripción

Este proyecto es una aplicación web interactiva para gestionar una lista de amigos y realizar un sorteo aleatorio entre ellos. Permite a los usuarios agregar nombres a una lista y luego seleccionar de forma aleatoria a un amigo secreto.

Funcionalidades

1. Capturar el valor del campo de entrada

Utiliza document.getElementById o document.querySelector para obtener el texto ingresado por el usuario.

Valida que el campo no esté vacío.

Si está vacío, muestra un mensaje de error: "Por favor, inserte un nombre."

Si el valor es válido, lo agrega a un array amigos con .push().

Limpia el campo de entrada después de agregar el nombre.

2. Mostrar la lista de amigos

Obtiene el elemento de la lista con document.getElementById() o document.querySelector().

Limpia la lista antes de actualizar (lista.innerHTML = "").

Itera sobre el array amigos y agrega cada nombre como un elemento de lista (<li>).

3. Sorteo de amigo secreto

Verifica que haya amigos en la lista antes de hacer el sorteo.

Usa Math.random() y Math.floor() para generar un índice aleatorio.

Obtiene el nombre sorteado del array amigos.

Muestra el nombre seleccionado en la interfaz.

Tecnologías Utilizadas

HTML: Estructura de la página web.

CSS: Estilos para mejorar la apariencia de la aplicación.

JavaScript: Lógica de la aplicación para manejar eventos y manipular el DOM.

Instalación y Uso

Clona el repositorio:

git clone https://github.com/tu-usuario/amigo-secreto.git

Abre el archivo index.html en un navegador.

Ingresa nombres en el campo de entrada y agrégalos a la lista.

Presiona el botón de sorteo para seleccionar un amigo secreto.

Contribución

Si deseas contribuir, realiza un fork del repositorio, crea una rama y envía un pull request con tus mejoras.

Licencia

Este proyecto está bajo la licencia MIT.
