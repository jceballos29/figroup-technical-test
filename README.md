<!-- @format -->

# Todo APP

## Descripción

Esta es una aplicación de tareas sencillas que le permite agregar, editar, eliminar y marcar como realizadas sus tareas.

## Instalación 

Para esté proyecto se utiliza una base de datos SQL Server
- server= localhost
- database= todoApp

_Si desea hacer cambios de servidor o del nombre de la base de datos diríjase al archivo appsettings.json en todo-api-figroup/TodoApi_

### General

1. Clonar el repositorio
```
  git clone https://github.com/jceballos29/figroup-technical-test.git
```

2. Ir a la carpeta de proyecto
```
  cd figroup-technical-test
```
### Backend
1. Ir a la carpeta raíz del API

```
  cd todo-api-figroup/TodoApi
```

2. Instalar NET CLI - si ya se encuentra instaladoi omitir este paso

```
  dotnet tool install --global dotnet-ef
```

3. Configurar la base de datos para este proyecto

```
  dotnet ef database drop
  dotnet ef migrations add InitialMigrate
  dotnet ef database update
```

4. Ejecutar el proyecto

```
  dotnet run
```

### Frontend

1. Ir a la carpeta raíz del Frontend

```
  cd todo-app-figroup
```

2. Instalar las dependencias

```
  npm install
```

3. Ejecutar el proyecto

```
  npm start
```
