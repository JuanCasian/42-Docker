FROM alpine
# This is creating the docker image based on the alpine image

MAINTAINER jcasian	<jcasian@student.42.us.org>
#It is good practice to put who is in charge of the file

RUN apk update && apk upgrade && apk add vim
#Run commands are the ones run when the image is being built

ENTRYPOINT vim
#Entrypoint command defines which is the command run in the container when it is being run, but you can still add more to that command

#Ex: if you run docker run <name> hello.txt it is going to excecute vim hello.txt


