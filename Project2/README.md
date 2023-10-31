This project demonstrates how to create a VPC that we can use for servers in a production environment. To improve resiliency, we deploy the servers in two Availability Zones, by using an Auto Scaling group and an Application Load Balancer. For additional security, we deploy the servers in private subnets. The servers receive requests through the load balancer. The servers can connect to the internet by using a NAT gateway. To improve resiliency, we deploy the NAT gateway in both Availability Zones.

PROJECT ARCHITECTURE:

![image](https://github.com/sidd-2399/cloud/assets/149344610/da5952a6-5e2e-48d8-bfad-077c21e3d5d5)
