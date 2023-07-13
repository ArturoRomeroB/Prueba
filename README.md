# Pwnagotchi
Una versión moderna del Tamagatchi de los años 90.
El Pwnagotchi es un proyecto de software libre que utiliza un dispositivo Raspberry Pi para crear un "asistente" autónomo que aprende de las redes Wi-Fi a su alrededor y mejora continuamente sus habilidades para descifrar claves y capturar datos. Configurar el Pwnagotchi implica varios pasos, y aquí te proporcionaré una guía básica para comenzar:
•	Hardware necesario:
Raspberry Pi Zero W (u otro modelo compatible)
Tarjeta microSD
Batería externa o adaptador de corriente
Pantalla OLED (opcional)
Carcasa para Raspberry Pi (opcional)
•	Instalación del sistema operativo:
Descarga la imagen del sistema operativo Pwnagotchi desde el repositorio oficial.
Graba la imagen en la tarjeta microSD utilizando un programa como Etcher.
Inserta la tarjeta microSD en la Raspberry Pi.
•	Configuración básica:
Conecta la Raspberry Pi a una fuente de energía.
Espera unos minutos para que se inicie el sistema operativo Pwnagotchi.
Conecta un cable USB al puerto micro USB de la Raspberry Pi y a tu computadora.
Abre una terminal en tu computadora y conéctate a la Raspberry Pi a través de SSH usando la dirección IP de la Pi (por ejemplo, ssh pi@192.168.1.100).
El usuario predeterminado es "pi" y la contraseña es "pwnagotchi".
Sigue las instrucciones en pantalla para configurar la contraseña y otros ajustes básicos.
•	Personalización:
Puedes personalizar la configuración del Pwnagotchi editando el archivo de configuración ubicado en /etc/pwnagotchi/config.toml.
Aquí puedes ajustar diversos parámetros como el nombre del Pwnagotchi, el modo de entrenamiento, los límites de potencia de Wi-Fi, entre otros.
•	Opcionales avanzados:
Si deseas agregar una pantalla OLED, puedes seguir las instrucciones de conexión y configuración proporcionadas en la documentación oficial del Pwnagotchi.
También puedes explorar características adicionales como el almacenamiento en la nube de los datos capturados, la visualización web de los datos y la integración con otras herramientas de seguridad.
Recuerda que el uso de un Pwnagotchi debe ser ético y respetar la privacidad de los demás. Siempre es importante obtener el permiso adecuado antes de realizar pruebas en redes Wi-Fi o capturar datos.
