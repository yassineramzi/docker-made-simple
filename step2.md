# Step 2 - Expose a Web Server 🌍

Now let’s run a real service: **Nginx**.

Run this command:

docker run -d -p 8080:80 nginx

- `-d` = detached (runs in background)  
- `-p 8080:80` = map local port 8080 to container’s port 80  

👉 Click the **port 8080 badge** that appears above the terminal to open Nginx in your browser.

> **Challenge:** Stop and remove the container:
