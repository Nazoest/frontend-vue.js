This is my POs built wit VueJS 3 Framework-CDN that is running on Docker.

Docker Commands

Create a DockerFile - This holds the configuration/specifications of your computer
Run the command docker build -t vue-pos . - This is building the computer(image) specified in the Dockerfile. -t means tagname.

Run the command docker run -p 5050:80  -d -t vue-pos.5050 means the external port(host) 80 exposes the NGINX in the container -t is the image created above.-d makes the container run in background even if you close the terminal.