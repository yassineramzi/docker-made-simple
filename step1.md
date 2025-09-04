# Step 1 - Run Your First Container 🚀

Let’s start simple with Docker’s classic test image.

👉 Run this command in the terminal (on the right):

docker run hello-world

✅ What happened?
- Docker pulled the `hello-world` image.
- It created a container from that image.
- The container printed a message and then exited.

> **Challenge:** Run it again. Notice how this time Docker didn’t download the image again (it reused the cached layers).
