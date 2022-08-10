## ❯ Prerequisitos:

1. Instar Docker Compose:

```

sudo curl -L "https://github.com/docker/compose/releases/download/1.26.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

```

2. Establecemos los permisos correctos para que el comando "docker-compose" sea ejecutable:

```

sudo chmod +x /usr/local/bin/docker-compose

```

3. Verificamos que la instalación se realizó correctamente:

```
docker-compose --version

```

## ❯ Instalamos

```
docker-compose up -d
```

## ❯ Verificamos que los contenedores se hayan creado

```
docker-compose ps
```
<img width="913" alt="img" src="https://user-images.githubusercontent.com/1218979/172497026-27923303-90dc-41f3-a8b4-e63c9018395e.png">


## ❯ Navegamos a los aplicativos

<img width="1100" alt="Screen Shot 2022-06-07 at 6 07 00 PM" src="https://user-images.githubusercontent.com/1218979/172497823-45857b42-db0f-4280-b5e9-a6bdd788632c.png">


<img width="990" alt="Screen Shot 2022-06-07 at 6 06 51 PM" src="https://user-images.githubusercontent.com/1218979/172497882-d22c046b-f9f4-46cb-8417-0581b85dffb7.png">
