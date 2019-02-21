# aws-certification


vpc pairing
layer 7 netowrking

eventual read =2
storng read =1


---------------------------
MUM-AISEZ-YOS-B-2F-W0266

REQIN0011760309
---------------------------



		MYSQL INSTALLATION
==============================================

wget https://dev.mysql.com/get/mysql57-community-release-el6-11.noarch.rpm
yum localinstall mysql57-community-release-el6-11.noarch.rpm
yum remove mysql55 mysql55-common mysql55-libs mysql55-server
yum install mysql-community-server
service mysqld restart
mysql_upgrade -p


Red shift 
==================================================
is a master client architecture
we create nodes(slaves)

what is the difference between spot instance and redshift?
we never run spot or ondemand .
there should be master running always
so use reserved instance.
what is maintenece track in redshift


redshift allows automatic snapshots which will take the sanpshots and transfer across regions

work load management 


=======================================
Elastic load balancer and auto scaling
-------------------------------------


autoscaling 
autos scaling is achieved 



elb
types of elb
1.classic clb
2.appliaction alb
3.network nlb


region wide load balancing
can be userd internallu or externally
layer 4 and layer 7
ssl terminiation and processing 
cookie based sticky session




supported ports 25 80 443 1024-65535
does not support eip 
supports domain zone apex
support IPV4
integrates cloud trail for log security analyssi
wild card certificates


------------------------------------------------------
alb characters
layer 7
content based routuing
support for microservices and containers
integrates with ecs
better performance for real time streaming
reduce hourly cost
deletion protection
better health checks and cloud watch metrics


path based routing and host based routing alb supports
connection draining


the differebnce vetweeb application load balancer nad nw load balancer
what is proxy proto and xff
alb can be on premisis




