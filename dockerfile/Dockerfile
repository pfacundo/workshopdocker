FROM facundop/nginx-ping:latest
RUN apt install -y vim
EXPOSE 80
#CMD ping -c 10 www.google.com
#CMD ["10", "www.google.com"]
ENTRYPOINT ["ping","-c","5"] 
