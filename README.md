# API Maquinas

API RESTful desarrollada en C# con .NET 6 y SQL Server para gestionar un catálogo de máquinas. Permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar), búsqueda por filtros y validación de datos. Ideal para integrarse con aplicaciones web o móviles que requieran manejo de inventarios o catálogos de productos industriales.

---

## Características

- Crear, obtener, actualizar y eliminar máquinas
- Búsqueda por marca con filtro
- Validaciones básicas en los datos de entrada
- Documentación automática con Swagger

---

## Requisitos

- [.NET 6 SDK](https://dotnet.microsoft.com/download/dotnet/6.0)
- SQL Server (local o remoto)
- Visual Studio / VS Code u otro IDE compatible

---

## ENDPOINTS Principales


| Método | Ruta                         | Descripción               |
| ------ | ---------------------------- | ------------------------- |
| GET    | `/api/maquina`               | Listar todas las máquinas |
| GET    | `/api/maquina/{id}`          | Obtener máquina por ID    |
| GET    | `/api/maquina/marca/{marca}` | Buscar máquinas por marca |
| POST   | `/api/maquina`               | Crear nueva máquina       |
| PUT    | `/api/maquina/{id}`          | Actualizar máquina        |
| DELETE | `/api/maquina/{id}`          | Eliminar máquina          |
