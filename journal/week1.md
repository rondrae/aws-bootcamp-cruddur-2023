# Week 1 — App Containerization

# FrontEnd and BackEnd working together

I am doing everything locally. So I had to install docker desktop. When I was trying to build out the container and I reach the instructions that npm i, it said it can't find npm. I had no idea what that was. I googled it found it what it was so I installed it. Then when I got to docker compose, the webpage would load but it wouldn't read data from the backend. I now hate CORS as you said in class. I decided to use a browser plugin to temporarily disable it. So I have both front and backend container working together. Now to the other parts.



# Push an image to docker hub
https://hub.docker.com/r/rondrae/aws-bootcamp-cruddur-2023-backend-flask

# Notifications

Adding the frontend notification page by copying and editing the code from the main page and also added the notification backend. I used my name as the poster and set my like count to 99 because I am cool like that. Each time I made a change I and relaunch the container, I assume this because I am running it locally and not using Gitpod.
![image](https://user-images.githubusercontent.com/18177131/222917960-56afc1bb-dd44-4273-a1ed-e426b81b20ce.png)


# DB

To get postgres working locally with git bash, I had to first download and install then edit the windows environment path to get it to work. Just typing psql it tried to connect with using my windows user account which does not exist in postgres. So I had to use psql -u postgres. I now have 4 containers running in my docker compose file and I am ready for week 2. I also installed and configured AWS CLI.

![image](https://user-images.githubusercontent.com/18177131/222918072-377bce0a-c908-4858-8fb1-b73cab8ab6fe.png)
