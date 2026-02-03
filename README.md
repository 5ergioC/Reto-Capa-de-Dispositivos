## Configuración previa a la ejecución

Por razones de seguridad se quito nuestras información personal y de internet, por lo que antes de compilar y cargar el programa en la placa NodeMCU, es necesario modificar las siguientes constantes definidas al inicio del código fuente:

- Reemplace los valores de las constantes `ssid` y `password` por el nombre y la contraseña de la red Wi-Fi que será utilizada por el dispositivo.
- Reemplace los valores de las constantes `HOSTNAME` y `MQTT_USER` por su usuario Uniandes (sin el dominio `@uniandes.edu.co`).
- Reemplace el valor de la constante `MQTT_PASS` por la contraseña de MQTT, la cual corresponde a su código de estudiante Uniandes.

Una vez realizados estos cambios, el sistema estará listo para establecer conexión con la red Wi-Fi y el bróker MQTT.
