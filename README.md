# Experiment 5 build pipeline job

Source Code Management > git > https://github.com/chinmay770/hello-world


------------------------------------------------------------------


# Experiment 7 selenium

Application > https://classic.cmpro.com/index.html
Browser > Chrome Firefox IE
XML Suite > testing.xml

Source Code Management > git > https://github.com/chinmay770/Framework

Build > Framework/pom.xml > clean install -Dbrowser=$browser -DurlToBeTested=$Application -DxmlFiles=$XMLSuite


------------------------------------------------------------------


# Experiment 8  Install and execute docker cmmds

sudo apt-get update
sudo apt-get install docker.io
sudo docker pull ubuntu
sudo docker run -it -d ubuntu
sudo docker ps
sudo docker exec -it [id] bash


------------------------------------------------------------------


# Experiment 9  Build an image for sample web app using docker

git clone https://github.com/chinmay770/docker-nginx 
cd docker-nginx/
sudo docker build -t rait-web-app .
sudo docker images
sudo docker run -it -p 70:80 rait-web-app bash 
#cd /var/www/html/
Service nginx start
