# wifimosys 0.21
Ataque EVIL TWIN

WIFIMOSYS (WIFI MOron's SYStem es un clon de LINSET (del gran vk496) con algunas modificaciones.

    Escanea las redes.
    Selecciona la red a atacar.
    Busca handshake (NO se puede usar sin handshake)
    Comprueba la validez del handshake mediante pyrit
    Monta un FakeAP imitando al original
    Crea un servidor DHCP sobre el FakeAP
    Crea un servidor DNS para redirigir todas las peticiones al Host
    Lanza el servidor web con la interface seleccionada
    Lanza el mecanismo para comprobar la validez de las contraseñas que se van a introducir
    Desautentifica a todos los usarios de la red, esperando que se conecten al FakeAP e introduzcan la contraseña
    Detiene el ataque tras la comprobación correcta de la contraseña
