# Instrucciones para usar este repositorio

Este repositorio contiene un proyecto Dockerizado que puedes clonar, construir y ejecutar fácilmente.

## Paso 1: Clonar el repositorio

Puedes clonar este repositorio ejecutando el siguiente comando en tu terminal:

```sh
git clone https://github.com/nvaneg/repositorio.git
```

##Paso 2: Construir la imagen

```sh
cd repositorio
```

```sh
docker build -t nagios-test .
```

##Paso 3: ejecutar el contenedor

```sh
docker run -it -d -p 0.0.0.0:80:80 nagios-test
```

##Paso 4: conexion

Credenciales:
Usuario: admin
Clave: duoc.2024

Recuerda usar tu ip 
Reemplaza "tu.ip" por la ip publica de tu maquina
```sh
http://tu.ip/nagios/
```
