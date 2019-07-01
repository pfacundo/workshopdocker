FROM ubuntu
RUN apt-get update
RUN apt-get install -y vim iputils-ping nginx
RUN echo "prueba de Dockerfile" >> /root/prueba.txt
ENTRYPOINT ["ping","-c","10"]
