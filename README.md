<!-- @format -->

# Todo APP

## Descripción

Esta es una aplicación de tareas sencillas que le permite agregar, editar, eliminar y marcar como realizadas sus tareas.

## Instalación del Backend

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

## Instalación del Frontend

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