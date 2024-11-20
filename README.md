# MyMvcApp-Contact-Database-Application

## Descripción
MyMvcApp-Contact-Database-Application es una aplicación web MVC diseñada para gestionar una base de datos de contactos. Permite a los usuarios agregar, editar, eliminar y visualizar contactos de manera eficiente.

## Características
- Agregar nuevos contactos
- Editar contactos existentes
- Eliminar contactos
- Visualizar una lista de contactos
- Búsqueda y filtrado de contactos

## Requisitos del Sistema
- .NET Core 3.1 o superior
- SQL Server
- Visual Studio 2019 o superior

## Instalación
1. Clona el repositorio:
    ```bash
    git clone https://github.com/tu-usuario/MyMvcApp-Contact-Database-Application.git
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd MyMvcApp-Contact-Database-Application
    ```
3. Restaura los paquetes NuGet:
    ```bash
    dotnet restore
    ```
4. Configura la cadena de conexión a la base de datos en `appsettings.json`.
5. Aplica las migraciones a la base de datos:
    ```bash
    dotnet ef database update
    ```
6. Ejecuta la aplicación:
    ```bash
    dotnet run
    ```

## Uso
1. Abre tu navegador web y navega a `https://localhost:5001`.
2. Utiliza la interfaz para gestionar tus contactos.

## Contribuciones
Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request para discutir cualquier cambio que desees realizar.

## Licencia
Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## Contacto
Para cualquier consulta, por favor contacta a [tu-email@dominio.com](mailto:tu-email@dominio.com).

