### Criando a imagem da aplicação e passando um nome
```bash
$ docker build . -t leodev0/node-server
```

### Criando o contêiner a partir da imagem que foi criada e fazendo port forwarding na porta 8080 para acessar o projeto na máquina. 
```bash
docker run -p 8080:8080 --name ambiente-node node-server
```

### Acessando o sistema de arquivos do contêiner
```bash
docker exec -it teste sh
```
