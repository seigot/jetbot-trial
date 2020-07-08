FROM ubuntu:18.04

#RUN apt update ;\
#    apt -y upgrade ;\	
#    apt install -y sudo
#
#RUN sudo apt install -y tzdata ;\
#    sudo apt install -y wget cmake git p7zip-full


# コンテナ起動時に実行する
ADD  start.sh  /
RUN  chmod +x /start.sh
CMD  ["/start.sh"]

