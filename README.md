# CoAP, MQTT JMeter Script

JMeter CoAP Plugin

- https://github.com/xmeter-net/coap-jmeter

The coap plugin is not to ready to use.
First you need to generate the plugin file(.jar)

- Install Maven
  - https://maven.apache.org/download.cgi
- After download the coap plugin codebase and install maven
  ```javascript
      cd coap-jmeter & mvn install
  ```
- After build successfully the coap plugin using maven. Install coap plugin manually:
  - copy the coap-xmeter-jar-with-dependencies.jar(it's in target folder) to $JMETER/lib/ext

[You can build a new one or use the plugin(.jar) in coap/pluginReadyToImport]

JMeter MQTT Plugin

- https://github.com/xmeter-net/mqtt-jmeter

- Install MQTT plugin
  - The MQTT plugin is ready to use.
    You just need to follow the plugin instruction, adding .jar manually OR by Jmeter GUI plugin

[You can download or use the plugin(.jar) in mqtt/pluginReadyToImport]

Script/Demo reference:

- https://youtu.be/OYRh_gciB-o
