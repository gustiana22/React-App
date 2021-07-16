# React-App
with Docker and Nginx

## Configuration Nginx

### Install Nginx
a. sudo apt update <br />
b. sudo apt install nginx <br />

### Customize firewall
a. sudo ufw app list <br />
b. sudo ufw allow 'Nginx HTTP' </br>
c. sudo ufw status <br />

### Checking the Web Server
a. systemctl status nginx

### to test whether Nginx has been successfully configured is to type 'localhost' in your browser

## Configuration Docker

### Install Docker 
a. sudo apt-get install docker-engine -y <br />

### Start Docker
a. sudo service docker start <br />

### Verify Docker
a. sudo docker run hello-world <br />
b  sudo service docker start




