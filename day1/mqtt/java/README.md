Auf meinem Windows PC l�uft das JAVA Programm *MqttSubscribeSample.java*. Dieses empf�ngt MQTT Messages , analysiert einige und formt daraus
 einfache Messages via Topic "/actor/linoino" an den Arduino Yun.

Dazu habe ich das Apache Paho Beispielprogramm *MqttSubscribeSample.java* f�r meine Bed�rfnisse angepasst und das entsprechende Paho Artefakt in meine
Maven Dependencies gepackt.
```xml
     <dependency>
        <groupId>org.eclipse.paho</groupId>
        <artifactId>org.eclipse.paho.client.mqttv3</artifactId>
        <version>1.0.2</version>
    </dependency>
```
