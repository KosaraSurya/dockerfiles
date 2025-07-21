FROM almalinux:9
RUN mkdir /tmp/workdir-demo
#RUN cd /tmp/workdir-demo
WORKDIR /tmp/workdir-demo
RUN pwd
RUN echo "Hello I am in work dir" > hello.txt
CMD ["sleep","1000"]

# Here cd wont work so dicrectly we can give our workdir path os it will go to that particular path.