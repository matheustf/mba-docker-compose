# mba-docker-compose

https://github.com/matheustf/mba-emailserver

https://github.com/matheustf/mba-avaliacao

https://github.com/matheustf/mba-eurekaserver


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

![Arquitetura Mba Docker-compose](https://user-images.githubusercontent.com/16195588/155223395-0f70924b-29fe-4d8a-ad1a-01b52952aefd.jpg)
