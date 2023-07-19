FROM almalinux:8
RUN useradd user1
# user instruction is  very useful to restrict the root privileges inside the images and containers
USER user1
RUN echo "hello" > /tmp/hello.txt