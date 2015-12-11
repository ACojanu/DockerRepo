FROM java:openjdk-8u45-jdk
RUN echo "Hello docker edited!"

WORKDIR /
COPY hello.sh /
RUN chmod 777 hello.sh
CMD ["./hello.sh"]

