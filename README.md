# mba-docker-compose


## Código
https://github.com/matheustf/mba-emailserver

https://github.com/matheustf/mba-avaliacao

https://github.com/matheustf/mba-eurekaserver

## Imagens docker hub
https://hub.docker.com/r/matheustf/mba-avaliacao/tags

https://hub.docker.com/r/matheustf/mba-emailserver/tags

https://hub.docker.com/r/matheustf/mba-eurekaserver/tags

## Para executar:

1. Docker instalado
2. Baixar o arquivo docker-compose.yaml
3. Executar: 
  docker-compose up
  
## Comandos extras:
 
### Derrubar todos os serviços:
docker kill $(docker ps -q)

### Excluir todos os serviços:
docker rm $(docker ps -a -q)

### Deletar todas as imagens:
docker rmi $(docker images -q)

## Arquitetura

![Arquitetura Mba Docker-compose (1)](https://user-images.githubusercontent.com/16195588/155224200-bdfd669b-b98c-4f8e-8ee7-ba1406fe7fb7.jpg)
