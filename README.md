# wifimosys
Ataque EVIL TWIN

WIFIMOSYS (WIFI MOron's SYStem es un clon de LINSET (del gran vk496) con algunas mejoras

ATENCIÓN: todavía NO funciona con páginas HTTPS y la opción de actualizar por ahora está desactivada.

    Escanea la red.
    Selecciona la red.
    Busca handshake (NO se puede usar sin handshake)
    Se comprueba la validez del handshake mediante pyrit
    Se monta un FakeAP imitando al original
    Se crea un servidor DHCP sobre el FakeAP
    Se crea un servidor DNS para redirigir todas las peticiones al Host
    Se lanza el servidor web con la interface seleccionada
    Se lanza el mecanismo para comprobar la validez de las contraseñas que se van a introducir
    Se desautentifica a todos los usarios de la red, esperando que se conecten al FakeAP e introduzcan la contraseña
    Se detiene el ataque tras la comprobación correcta de la contraseña
