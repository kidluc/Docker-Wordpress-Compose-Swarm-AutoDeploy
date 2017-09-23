# Docker-Wordpress-Compose-Swarm-AutoDeploy
Auto deploy wordpress by using docker swarm and docker compose

1. Install docker compose and docker swarm
2. Join Swarm to manager
3. Create overlay network
`** docker network create -d overlay --attachable <network name> **`
4. Deploy wordpress
``` docker stack deploy -c docker-compose.yml <Service name> ```
  
