# Containerizing a Slack Clone App Built with the MERN Stack

## Getting Started

## Cloning the repository


```
 git clone https://github.com/dockersamples/slack-clone-docker
```

## Building the Service containers

```
 docker compose up -d —build
```

```
 docker compose ps
               Name                             Command               State            Ports        -----------------------------------------------------------------------------
slack-clone-docker_db_1              docker-entrypoint.sh mongod      Up      0.0.0.0:27017->27017/tcp
slack-clone-docker_nodebackend_1     docker-entrypoint.sh node  ...   Up      0.0.0.0:9000->9000/tcp 
slack-clone-docker_slackfrontend_1   docker-entrypoint.sh yarn  ...   Up 
```

## Viewing the containers via Docker Dashboard


## Viewing the Messages




