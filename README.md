# Ping

Aplicação Java com container para exemplo

## Pré-requisitos

- Java 17+
- Docker 
- Acesso a internet
- Acesso ao Docker Hub

## Instalação

#### Clone

```
git clone https://github.com/jungabriel56/ping.git
```

## Execução


#### Docker

* Criação de imagem

```
docker build -t ping .
```

* Executar container

spring.profiles.active=dev


```
docker run -d -p 8080:8080 -e PROFILE=prd ping
```

```
docker run  -p 8080:8080 minhaimagem.tag
```

### Menu iniciar
> Menu Iniciar: Selecionar e clicar em aplicação X

#### Navegação

- Base

http://localhost:8080

- Endpoint que retorna string "Pong"

http://localhost:8080/ping 


## Features (Funcionalidades)

- Múltiplos profiles

## Contatos

- Desenvolvedor 1 - desenvolvedor1@email.com
- Desenvolvedor 2 - desenvolvedor2@email.com

## Referencias

 - [UOL](https://www.uol.com.br/)
 - [Gov br](https://www.gov.br/)