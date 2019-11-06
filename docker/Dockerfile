FROM openjdk:8
COPY . /app
ENV URL="localhost:5432/tp_devops"
ENV USERNAME="tp_devops"
ENV PASSWORD="tp_devops"
ENTRYPOINT java -jar -Ddatabase.url=$URL -Ddatabase.username=$USERNAME -Ddatabase.password=$PASSWORD app/tp-docker-1.0.0.jar
