## IIEC DOCKER PROJECT 
 I have learnt the docker under the guidence of **MR.Vimal Daga sir** in campaign **IIEC-RISE 1.0** which is his intiative on youtube.
 If you all want you can go to this link https://www.youtube.com/channel/UCtY-JhEZ3iPLtozWGgd2efQ for more getting more Knowledge regarding the project. 
* This project of docker is to set-up enviroment of wordpress on docker  .
* Here we have used docker conatainer technique as we all are aware from it if load increase on website it might require to launch multiple os and launching new os in VB or seeting other is time consumming but in docker it only take 5 sec to launch os so if client side increase we can launch simaltaniously new os quickly.
* You  know that  wordpress run on data base so it is necessary to create database and to creat the database in docker we have to launch one different container with different image and different conatiner for wordpress so if you want to set in one computer its okay but suppose you want to set up in different 100 computer of your comapny so its a big problem so to overcome this we use docker compose basically it run multiple conatiner in one comand.Docker Compose is used to run multiple containers as a single service.
* Here we have use volumes so if suppose container is crashed by chance so we have mounted to local volume to docker continer so that if container is crashed our data will be safe and we can  launch container again.
* VOLUME NAME:-
* for wordpress i have used html_new_db
* for database i have used database_new
* i have use port 8086 you can use any
* It is been assumed that docker is pre configured in your os here i am using redhat8.




* For setting up the enviroment you should have installed docker in your os.

 ## So to seting up the enviroment : ##
 * You should install docker compose in you os.

* All the instruction can be shown here:-

* https://docs.docker.com/compose/install/

* After that to verify the installation of docker use 
docker-compose -v
* If you see version then you are good to go
## then follow below steps ##

* mkdir /mycompose
* cd /mycompose
* extract docker-compose.yml file and paste that file in that location
* after that 
* use docker-compose up
* now go to your local host 
* localhost:port number
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
* to visit site goto ip:portnumber
* example- 192.168.1.32:8086
* If you want to run this on windows remember to disable firewall
* Simply use systemctl stop firewalld
