# CoAP, MQTT JMeter Script

JMeter CoAP Plugin

- https://github.com/xmeter-net/coap-jmeter

The coap plugin is to ready to use, you need to build coap to generate the plugin file(.jar)

- Install Maven
  - https://maven.apache.org/download.cgi
- After download the plugin code base and install maven

  ```javascript
      cd coap-jmeter & mvn install
  ```

- After build successfully the coap plugin using maven. Install coap plugin manually: \* copy coap-xmeter-jar-with-dependencies.jar to $JMETER/lib/ext
  coap-xmeter.jar is in target folder

JMeter MQTT Plugin

- https://github.com/xmeter-net/mqtt-jmeter

- Install MQTT plugin
  - The MQTT plugin is to ready to use.
    You just need to follow the plugin instruction and add .jar manually OR by Jmeter GUI plugin

Script/Demo reference:

- https://youtu.be/OYRh_gciB-o
