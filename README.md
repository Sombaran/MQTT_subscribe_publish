# MQTT_subscribe_publish
Created by Sombaran Gupta. For any further query email me @ guptasombaran@yahoo.com Dependency JSON-C Library. This Synchronous client application used for subscribing to a topic and then publishing to another topic simultaneously using C++ managed build. This application used thread to subscribe continuously on a topic and then publish on another topic.
Broker used Mosquitto, client Eclipse paho using C
Compile g++ sub-pub.cpp -lpthread -lpaho-mqtt3c -ljson-c -fpermissive -std=c++11. 
