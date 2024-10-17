For setting up my nginx as a web server and adding HTTP/HTTPS certificates, it was relatively straightforward following the tutorials on the website. I purchased the domain liyanib.com on namecheap.com and set-up the custom DNDs on namecheap to link to Digitalocean. I also setup 2 DNS records of type A routing to my public IP. At one point when I was debugging, I deleted the NS DNS records on digitalocean to set something up and that kind of caused an issue when I was setting up the custom DNDs since they were linking to ns1.digitalocean.com, ns2.digitalocean.com, ns3.digitalocean.com which the NS records were pointing to. So I just had to manually re-add them but I don’t fully understand what happened. </br>
<img width="1167" alt="Screenshot 2024-10-16 at 9 51 24 PM" src="https://github.com/user-attachments/assets/df24f2c1-e391-447f-ad88-c127d9d48e7a">
<img width="1066" alt="Screenshot 2024-10-16 at 3 57 42 PM" src="https://github.com/user-attachments/assets/241dc9c3-4e5e-4b2d-a02d-95782af8ce85">
</br>
For the actual webpage, I wanted to embed a video of the dead internet theory. So I added a title that disappears on hover and embedded a youtube video. I used these commands and edited the files in my terminal. I don’t know why youtube can't connect to my mainpage, I tried multiple other videos too and it still wouldn’t work. </br>
<<img width="716" alt="Screenshot 2024-10-16 at 10 02 41 PM" src="https://github.com/user-attachments/assets/7f44435f-14ab-4c9b-9c69-5e8c4d748aa1">
</br>
Also, when I normally do any sort of web edits, I have a local folder that has all the html, css, js files and any pictures, videos that are embedded in and I use a text editor which is a lot easier for me to navigate and I wonder how I can do that/ locate my domain locally, especially if I wanted to add an image like a favicon for my website. 
</br>
</br>
