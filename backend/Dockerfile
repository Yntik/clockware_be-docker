 FROM yntik123/be_test

# The Dockerfile's author
LABEL Ivashenko O.V.


# Set this as the default, working directory.
# We'll land here when we SSH into the container.
WORKDIR /BE

# Our Nginx container will forward HTTP traffic to containers of 
# this image via port 3000.
EXPOSE 3000

RUN apt-get update -y
RUN npm install
RUN npm install pm2 -y -g 
#CMD ["/bin/sh", "start.sh"]