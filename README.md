# Grav Docker

Como rodar o [Grav](https://getgrav.org/) localmente utilizando o `docker` e `docker-compose`. Este projeto é baseado no original [docker-grav](https://github.com/getgrav/docker-grav).

## Testado no ambiente

* MacOS `10.13.6`
* Docker version `18.06.0-ce, build 0ffa825`
* docker-compose version `1.22.0, build f46880f`
* Grav+Admin `1.7.5`

## Instalação

Clone este repositório no diretório desejado.

```
$ docker-compose up --build
```

## Rodando o projeto através do `docker-compose`

```
$ docker-compose up -d
```

## Verificar se a máquina `docker` está funcionando

```
$ docker ps
```

## Parando o projeto

```
$ docker-compose down
```

