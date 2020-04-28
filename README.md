IIEC DOCKER PROJECT 

--I have learnt the docker under the guidence of MR.Vimal Daga sir in campaign IIEC-RISE 1.0 which is his intiative on youtube.
--This project of docker is to set-up enviroment of wordpress on loacal machine.
--you  know that  wordpress run on data base so it is necessary to create database here i am using mysql
--it is been assumed that docker is pre configured in your os here i am using redhat8



For setting up the enviroment you should have installed docker in you os

--So to seting up the enviroment 
--you should install docker compose in you os

--all the instruction can be shown here:-
https://docs.docker.com/compose/install/

--after that to verify the installation of docker use 
docker-compose version
--if you see version then you are good to go
then follow below steps

--mkdir /mycompose
--cd /mycompose
--extract docker-compose.yml file and paste that file in that location
--after that use docker-compose up
now go to your local host 
localhost:8081
to see if its working or not 