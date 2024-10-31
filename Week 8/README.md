Blog before office hours (I wrote this earlier in the week but I then met Tom for office hours to debug so this may or may not be relevant but posting it for documentation purposes):  
</br>
I spent this week mostly troubleshooting. Particularly because I think after last class, I have a greater understanding of where and what everything is and does. I did, in that moment, think that I got what I did wrong last week and I’m able to fix it now. </br>
The first thing I did to troubleshoot everything was make my node file exactly the same as the one in the tutorial and on the github to make sure that it wasn’t all the additional stuff that I have done with the API’s that impacted anything. I then wanted to make sure that I directed my file to the server correctly (re the garden / apps example) so I used sudo nano /etc/nginx/sites-available/default to do that, initially without realizing that this altering the default page and not the liyanib.com page which I then went back and did so that /apps would load what is on port 8080.
</br></br>
<b>BUT IT STILL WOULD NOT WORK. </b>
</br></br><img width="879" alt="Screenshot 2024-10-29 at 4 12 05 PM" src="https://github.com/user-attachments/assets/eba39c69-3912-4d4d-82da-34d899396ff0">

My hypothesis is that when I created this nodejs project, I put it in a folder called try but when I ls, I get project-dir then all my node related files are there. So I tried doing  https://liyanib.com/project-dir/apps to locate my project but that still wouldn’t work. 
</br>

After Office Hours Debugging: 
![Screenshot 2024-10-31 at 11 32 05 AM](https://github.com/user-attachments/assets/cdb95774-abf6-4264-bc1c-cee237225d9a)
</br> 

Because of the time I spent debugging and figuring out what and how I was wrong, I worked on just experimenting with adding some simple additional features to my server file such as a color changing feature based on user input, one that gets a random quote (all halloween based facts, one that gets server info on json along with the date and data get requests that were already implemented (all under the proxylocation I set which was apps) 

But I'm also unclear about how to get user input while just using nodejs and running that without an html file. 
