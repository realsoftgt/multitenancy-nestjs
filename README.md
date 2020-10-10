# Cloud Based Nest.js Multitenancy Application

Aprenda a crear una pequeña aplicación Nest.js para diferentes clientes con diferentes bases de datos que comparten la misma base de código.

Más conocida como Multi-Tenancy

## Technology Stack

- Nest.js
- Docker (Opcional)
- MySQL
- Microsoft Azure (Opcinal)
  - Puede ejecutarse en local.

## Documentation

Instalación de todas las dependencias necesarias con el siguiente comando:
```shell
npm i
```

Levantamos la instancia Doker con el siguiente comando:
Solo se usa para tener la base de datos MySQL, por eso puede ser opcional.
```shell
#Opcional
docker-compose up -d
```

Levantamos la aplicación en modo escucha por los cambios que deseemos realizar.
```shell
nest start --watch
```

## Authors

- [Henry Díaz Gutiérrez](https://twitter.com/intelguasoft)
