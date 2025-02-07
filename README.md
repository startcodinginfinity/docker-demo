1 -> Run the Application using the command [mvn clean install]. It will create .jar file in target folder
2 -> Go to the spring Application folder open cmd and type this command [docker build -t(target) <docker-image-name> .(you should use dot after image name because it resembles the root folder)]
3 -> After image has created run the image by using this command [docker run -p <container-port>:8080 --name <container-name> <image-name>]
