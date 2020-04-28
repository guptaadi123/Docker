## IIEC DOCKER PROJECT 
 I have learnt the docker under the guidence of **MR.Vimal Daga sir** in campaign **IIEC-RISE 1.0** which is his intiative on youtube.
 If you all want you can go to this link https://www.youtube.com/channel/UCtY-JhEZ3iPLtozWGgd2efQ for more getting more Knowledge regarding the project. 
* This project of docker is to set-up enviroment of wordpress on loacal machine.
* You  know that  wordpress run on data base so it is necessary to create database here i am using mysql
* It is been assumed that docker is pre configured in your os here i am using redhat8



* For setting up the enviroment you should have installed docker in your os

 ## So to seting up the enviroment : ##
 * You should install docker compose in you os.

* All the instruction can be shown here:-

* https://docs.docker.com/compose/install/

* After that to verify the installation of docker use 
docker-compose version
* If you see version then you are good to go
## then follow below steps ##

* mkdir /mycompose
* cd /mycompose
* extract docker-compose.yml file and paste that file in that location
* after that 
* use docker-compose up
* now go to your local host 
* localhost:8080
* to see if its working or not 
* you can use this cmnd to run file detach mode
* docker-compose up -d
* to stop the sevices you can use
* docker-compose stop
* So once you stop everything you can start everything from following comand
* docker-compose start
* You can stop or delete all the container  made by docker-compose up
* docker-compose down
* To delete all the volumes created by docker compose up you can use
* docker-compose down --volumes
