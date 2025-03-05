# Para conectarse a la consola de psql


## Paso 1 

### Encontrar el docker-compose que contiene la BBDD ejecutamos docker-compose ps -a y buscamos el que tenga postgres


## Paso 2 

### Entrar al contenedor usando docker-compose exec -it nombre_dc_bbdd bash para poder interactuar con la BBDD


## Paso 3 

### Entrar a la BBDD mediante el comando psql -U postgres -d torneigdb y accederá si pidese pw sería postgres
