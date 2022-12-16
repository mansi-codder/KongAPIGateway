# KongAPIGateway

##Open command Prompt 
go to the location where you cloned the repo
run command **_docker-compose up -d_**


##To remove all the container 
**docker-compose down**


### For windows 

change image name in migration :
kong-migration:
    container_name: kong-migration
    image: kong:2.1.4-alpine


change image name in kong container :
kong:
    container_name: kong
    image: kong:2.1.4-alpine



