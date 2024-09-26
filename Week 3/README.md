For this assignment, I decided to start simple then later expand since I do want to try to enclose the controller. For my PCOMP final project last year, I made a type of controller that communicates with p5js and then sends prompts to Dalle and then Dalle sends the images back and so I really wanted to create an enclosed controller. I also wanted to have part of the controller be non-gamer user friendly so I wanted to print out the directions and stick them to the buttons. I didn’t stick them on yet because I do want to enclose it first but I laser printer and engraved the buttons I want to use. </br>
I had some questions about the code and networks part of it that were answered during office hours but I’m adding those in here for documentation purposes and for my future reference.  
</br>
<b>Confusion 1. IP address distinction  </b> </br>

Two types of IP addresses used in this assignment: </br>
</br>1. Server IP address --  ifconfig -- 10.18.241.74 is this right? Does it depend on where I ran ifconfig from ?? </br>
<img width="768" alt="Screenshot 2024-09-25 at 9 59 34 AM" src="https://github.com/user-attachments/assets/ba367367-5e9a-480d-b9f0-e49eead08063">

2. Local mac IP address: used to run processing  192.168.1.52 </br>
-- how do I find this? Does it always have to start with 192 -- is this how i look for it </br>

<b> Confusion 2:  Code logic </b> </br>
-- Instead of using analogue inputs and mapping them to values on the screen, I decided to use digital inputs because I wanted to laser cut the instructions on and stick them to buttons -- I didn't do any mapping 

<img width="617" alt="Screenshot 2024-09-26 at 10 37 49 AM" src="https://github.com/user-attachments/assets/8dee02c1-b299-4cda-a72a-a5dd79a5584a">
<img width="615" alt="Screenshot 2024-09-26 at 10 37 57 AM" src="https://github.com/user-attachments/assets/658241b6-d4a3-460a-af6d-0ee6a815c34e">

New code used: </br>
In the previous iteration of the code, I didn’t track every button's change in state so it kept sending in the commands for the time the button was pressed. Therefore, even though the game connected and the networks part of it worked, it wasn’t running properly. For the new code, for every directional button used, I had to implement a button change state so it would only send once. Here is the code used!  </br>

Circuit used: </br>
I had 5 buttons in my circuit and one LED to indicate connectivity and so the circuit is pretty simple but I do want to enclose it into a controller type game for non-games for future iterations </br>
<img width="927" alt="Screenshot 2024-09-26 at 1 41 06 PM" src="https://github.com/user-attachments/assets/1c5de87a-263a-41c9-bdb5-2266e99129d1">
![IMG_6252](https://github.com/user-attachments/assets/92a8e442-4c8f-4970-96f0-31bfcdaa64ee)



