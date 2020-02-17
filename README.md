| Description | Instruction/Command |
| --- | --- |
| Install Docker and Related library (Ubuntu) | https://docs.docker.com/install/linux/docker-ce/ubuntu/ |  
| Create a docker file | Dockerfile |
| Write Base Code at Dockerfile | See Dockerfile |
| Create requirements.txt file | See requirements.txt |
| Create app folder | app folder at root |
| Run command from root directory | sudo docker build . |
| | |
| Install Docker Compose | https://docs.docker.com/compose/install/ |
| Create Docker compose file | docker-compose.yml |
| Write all Service in docker-compose.yml file | See docker-compose.yml |
| Run Command for build  | sudo docker-compose build | 
||
| Run Command for creating django project | sudo docker-compose run app sh -c "django-admin.py startproject app ." |
| Run the application | docker-compose up |