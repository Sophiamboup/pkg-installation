#!/bin/bash
    
        #AUTHOR: Sophia Mboup
        #DATE: October 2022

        ##-------- Packages installation ------

echo "Please be patient as the packages are being installed. It might take a few minutes....."

yum install wget -y 
yum install net-tools -y 
yum install sysstat -y 
yum install finger -y 
yum install gcc -y 
yum install make -y 
yum install python3 -y 
yum install epel-release -y 
yum install git -y 
yum install vim -y 

echo "Packages are now installed . Thank you for being patient!"