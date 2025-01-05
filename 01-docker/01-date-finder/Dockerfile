FROM alpine
RUN apk add openjdk17
ENV PATH $PATH:/usr/lib/jvm/java-17-openjdk/bin/javac
WORKDIR /Users/home/Docker
ADD Test.java Test.java
ENTRYPOINT javac Test.java && java Test $NUMBER