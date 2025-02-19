# 🚀 ASP.NET MVC con Entity Framework y Patrón Repository

Este es un proyecto de práctica desarrollado en **ASP.NET MVC** utilizando **Entity Framework** y el **patrón Repository**. Su propósito es mejorar la comprensión de estos conceptos y su aplicación en un entorno real con **SQL Server** como base de datos.

## 🛠️ Tecnologías utilizadas

- 💻 **ASP.NET MVC** - Para la estructura del proyecto y la lógica de la aplicación.
- 🗃️ **Entity Framework (EF Core)** - Como ORM para la gestión de la base de datos.
- 📂 **Patrón Repository** - Para una mejor organización del acceso a datos.
- 🏦 **SQL Server** - Como sistema de base de datos.
- 🔄 **Liquibase** - Para la gestión de migraciones y versionado de la base de datos.

## ✨ Características principales

- 📝 Implementación del **CRUD** para entidades.
- 🔌 Uso de **inyección de dependencias** para una mejor escalabilidad.
- ⚡ Manejo asincrónico con **async/await**.

## ⚙️ Instalación y configuración

1. **Clonar el repositorio:**
   ```sh
   git clone <URL_DEL_REPO>
   cd <NOMBRE_DEL_PROYECTO>

/NOMBRE_DEL_PROYECTO
│-- 📂 Controllers/        # Controladores MVC
│-- 📂 Models/            # Modelos de datos
│-- 📂 Views/             # Vistas de la aplicación
│-- 📂 Repositories/      # Implementación del Patrón Repository
│-- 📂 Data/             # Contexto de EF y configuraciones
│-- 📂 Migrations/       # Migraciones de base de datos
│-- 📂 wwwroot/          # Archivos estáticos (CSS, JS, etc.)
│-- 🛠️ appsettings.json  # Configuración del proyecto
│-- 🚀 Program.cs        # Configuración y entrada del programa

dotnet build
dotnet run
