# MyMCP Application

## Descripción

MyMCP es una aplicación .NET que utiliza el protocolo Model Context Protocol (MCP) para proporcionar herramientas que pueden ser invocadas desde un cliente. Actualmente, incluye herramientas como `Echo` y `ReverseEcho` para procesar mensajes.

## Características

- **Echo**: Devuelve el mensaje enviado por el cliente.
- **ReverseEcho**: Devuelve el mensaje enviado por el cliente en orden inverso.

## Requisitos

- .NET 9.0 o superior
- Una base de datos (opcional, si se desea extender la funcionalidad para consultas en lenguaje natural)

## Configuración

1. Clona este repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   ```
2. Navega al directorio del proyecto:
   ```bash
   cd DotNet/MyMCP
   ```
3. Restaura las dependencias:
   ```bash
   dotnet restore
   ```

## Ejecución

Para ejecutar el servidor MCP:

```bash
   dotnet run --project MyMCP.csproj
```

## Uso

1. Inicia el servidor MCP como se indica en la sección de ejecución.
2. Usa un cliente MCP para interactuar con las herramientas disponibles (`Echo` y `ReverseEcho`).

## Extensiones

Este proyecto puede extenderse para incluir:

- Conexión a una base de datos para consultas en lenguaje natural.
- Nuevas herramientas MCP personalizadas.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o un pull request para sugerir mejoras o reportar problemas.

## Licencia

Este proyecto está bajo la licencia MIT.
