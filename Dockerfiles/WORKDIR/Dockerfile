FROM almalinux
WORKDIR /tmp
RUN touch hello{1..6}.txt 
RUN yum install nginx -y
CMD ["nginx","-g","daemom off;"]
ENTRYPOINT ["ping","-c5","google.com"]
