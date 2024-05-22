# Docker
## Install docker engine using this manual:
[Docker Installing](https://docs.docker.com/engine/install/ubuntu/)

# Broadsea
Broadsea runs the core OHDSI technology stack using cross-platform Docker container technology.
### Git clone github repo 
````
git clone https://github.com/OHDSI/Broadsea.git
````
### Start the broadsea containers
````
cd Broadsea
docker compose pull && docker-compose --profile default up -d
````

In the web browser, open the URL 
[ATLAS](https://127.0.0.1)

#OHDSI containers; ATLAS, HADES & ARES should open
Reference link;
[Broadsea Containers](https://github.com/OHDSI/Broadsea)
