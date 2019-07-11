# Hello World

## A simple hello world example making use of Nginx, Docker, Docker-Compose, and Spring Boot

Download:
```
git clone https://github.com/hbuck95/spring-boot-nginx-hello-world-docker-compose/
```
Install Docker (if not installed)
```
sudo apt update
sudo apt install -y docker.io
sudo usermod -aG docker $(whoami)
sudo systemctl enable docker
sudo systemctl start docker
exit
```

Install docker-compose:
```
# download the docker-compose binary
sudo curl -L "https://github.com/docker/compose/releases/download/1.23.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

# make the binary executable
sudo chmod +x /usr/local/bin/docker-compose
```

Run:
```
docker-compose up -d
```

View:
```
http://localhost/
```
