FROM openjdk:8

# Install additional tools / libraries needed
RUN apt-get install gradle

# Compile source
COPY . /usr/src/app
WORKDIR /usr/src/app
#RUN javac Main.java
RUN gradle build


# Run app
#CMD ["java", "Main"]
#CMD ["java", "/user/src/app/build/libs/my.jar"]
CMD ["bash"]