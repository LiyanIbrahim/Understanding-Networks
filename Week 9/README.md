Understanding what MQTT brokers are. </br> 
The first part of this weeks assignment was spent trying to figure out and understand what exactly MQTT brokers are. To my understanding from the research I’ve done on this, is that put in the simplest terms, MQTT are message control protocols and plattform that are lightweight and reliable (and hence, designed for unreliable networks) and commonly used for IoT applications.  </br> 
How it works is that devices use MQTT to publish messages a “topic” to a “broker” and other devices subscribe to these topics to then receive these messages. 
A broker is kind of like a dedicated message manager for the IoT  </br> 
Questions in my mind:  </br> 
What position does a client hold? Are clients just the “devices” that are part of the IoT network that I set up?  </br> 
 </br>  </br> 
Getting MQTT Explorer  </br> 
After downloading the app, i went in to subscribe to the topic but as predicted, it kept crashing on test.mosquitto.org </br> 
<img width="1020" alt="Screenshot 2024-11-05 at 3 35 13 PM" src="https://github.com/user-attachments/assets/02bb0073-259b-499e-a827-42c9190f6aae">

I then tried to connect to  tigoe.net  </br> 
<img width="1027" alt="Screenshot 2024-11-05 at 3 38 01 PM" src="https://github.com/user-attachments/assets/f1cc6781-7cb9-4692-a8c3-15d812710e67">
<img width="596" alt="Screenshot 2024-11-07 at 2 16 28 PM" src="https://github.com/user-attachments/assets/d9387688-22e0-4305-8d05-c6d0efaf27f0">

I'm still unsure about the messages and topics. who sets those? Can we just subscribe or do can we add topics? 

