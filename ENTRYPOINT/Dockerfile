FROM almalinux:8
#ENTRYPOINT ["ping", "-c5", "google.com"]
CMD ["google.com"]
ENTRYPOINT ["ping", "-c5"]

#CMD VS ENTRYPOINT
#cmd can be overridden ,
# entrypoint can not be ovverriden,instead it will go append.
# if you use both,cmd will provide args to entrypoint.but you can always ovveridden cmd through commadline. 
# docker build -t entrypoint:v1 .
# docker run entrypoint:v1
# docker run entrypoint:v1 ping -c5 facebook.com
# docker ps -a
# docker build -t entrypoint:v1 .
# docker run entrypoint:v1
# docker run entrypoint:v1 ping -c5 facebook.com
# docker ps -a --no-trunc
# docker build -t entrypoint:v1 .
# docker run entrypoint:v1
# docker run entrypoint:v1 facebook.com
# docker ps -a
