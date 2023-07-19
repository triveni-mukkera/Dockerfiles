FROM almalinux:8
RUN yum update -y
RUN yum install nginx -y
#cmd instruction is useful to run the container.it should run foreground and it should run infinite times.
CMD ["nginx", "-g", "daemon off;"]

#RUN vs CMD
#RUN command will execute at the time of image creation.
#CMD command will execute at the time of running container.
