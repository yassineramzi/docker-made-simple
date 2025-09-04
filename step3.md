# Step 3 - Inspect Images & Layers 🧩

Docker images are made of **layers**. Let’s explore.

Run:

docker images


You should see the `hello-world` and `nginx` images.

Now inspect Nginx layers:

docker history nginx


👉 You’ll see each layer corresponds to an instruction in the image build.

**Mini-Challenge:**  
1. Run:

docker run -it python:3.12 python

2. Exit with `Ctrl+D`.  
3. Then run:

docker images

Notice how the new `python:3.12` image was pulled, composed of multiple layers — only the missing layers were downloaded.

🎉 Congrats! You’ve completed your first Docker challenge.
