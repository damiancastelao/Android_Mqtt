# Android_Mqtt

Utilización de la [librería paho](https://www.eclipse.org/paho/index.php?page=clients/python/index.php) como cliente MQTT

[Tutorial](https://www.emqx.com/en/blog/android-connects-mqtt-using-kotlin) de ayuda

## Gradle

Enlace a la libreria en el `build.gradle(:app)`

`implementation 'org.eclipse.paho:org.eclipse.paho.client.mqttv3:1.2.4'`

## Broker

Uso de la imagen de docker de [mosquitto](https://hub.docker.com/_/eclipse-mosquitto)

`$docker run -it -p 1883:1883 eclipse-mosquitto:1.6`

mejor usar version 1.6, la v2 necesita configuración extra
