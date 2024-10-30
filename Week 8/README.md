Blog before office hours (I wrote this earlier in the week but I then met Tom for office hours to debug so this may or may not be relevant but posting it for documentation purposes):  
</br></br>
I spent this week mostly troubleshooting. Particularly because I think after last class, I have a greater understanding of where and what everything is and does. I did, in that moment, think that I got what I did wrong last week and I’m able to fix it now. </br>
The first thing I did to troubleshoot everything was make my node file exactly the same as the one in the tutorial and on the github to make sure that it wasn’t all the additional stuff that I have done with the API’s that impacted anything. I then wanted to make sure that I directed my file to the server correctly (re the garden / apps example) so I used sudo nano /etc/nginx/sites-available/default to do that, initially without realizing that this altering the default page and not the liyanib.com page which I then went back and did so that /apps would load what is on port 8080.
</br></br>
<b>BUT IT STILL WOULD NOT WORK. </b>
</br></br>
My hypothesis is that when I created this nodejs project, I put it in a folder called try but when I ls, I get project-dir then all my node related files are there. So I tried doing  https://liyanib.com/project-dir/apps to locate my project but that still wouldn’t work. 
</br>
