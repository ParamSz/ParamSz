# Proyecto de Servidor Minecraft Bedrock

¡Bienvenido al proyecto de Servidor Minecraft Bedrock! Este proyecto está diseñado para trabajar con PocketMine y Nukkit, proporcionando una plataforma robusta y flexible para administrar y personalizar tu servidor de Minecraft Bedrock Edition.

<style>
  .header {
    background-color: #282c34;
    color: white;
    padding: 10px;
    border-radius: 5px;
  }
  .description {
    background-color: #f9f9f9;
    padding: 10px;
    border-left: 5px solid #007acc;
    border-radius: 5px;
  }
  .description h2 {
    color: #007acc;
  }
  .content {
    margin: 10px 0;
  }
</style>

<div class="header">
  <h1>Sobre Mí</h1>
</div>

<div class="description">
  <h2>¡Hola!</h2>
  <p>Me llamo [Tu Nombre] y soy un apasionado desarrollador con una gran experiencia en la gestión y personalización de servidores de Minecraft Bedrock Edition utilizando <strong>PocketMine-MP</strong> (PMMP) y <strong>Nukkit</strong>. Mi objetivo es proporcionar herramientas y guías que faciliten la creación y administración de servidores robustos y personalizados.</p>
</div>

## Índice

1. [Descripción](#descripción)
2. [Características](#características)
3. [Requisitos](#requisitos)
4. [Instalación](#instalación)
5. [Configuración](#configuración)
6. [Uso](#uso)
7. [Contribuir](#contribuir)
8. [Licencia](#licencia)
9. [Créditos](#créditos)

## Descripción

Este proyecto integra y extiende las funcionalidades de PocketMine y Nukkit, permitiendo a los usuarios crear y gestionar servidores de Minecraft Bedrock Edition con facilidad. Ofrecemos scripts de automatización, plugins personalizados y una guía detallada para maximizar tu experiencia de administración de servidores.

## Características

- **Compatibilidad**: Soporte tanto para PocketMine como para Nukkit.
- **Automatización**: Scripts para instalar y actualizar el servidor automáticamente.
- **Personalización**: Amplia gama de plugins y configuraciones personalizadas.
- **Documentación**: Guías completas y documentación detallada para cada paso.

## Requisitos

- **Sistema Operativo**: Windows, Linux, o macOS
- **Java**: JDK 8 o superior (solo para Nukkit)
- **PHP**: PHP 7.2 o superior (solo para PocketMine)
- **Memoria RAM**: Al menos 2 GB de RAM libre
- **Almacenamiento**: Al menos 1 GB de espacio libre en disco

## Instalación

### PocketMine

1. Descarga el instalador de PocketMine:
    ```sh
    curl -sL https://get.pmmp.io | bash -s -
    ```

2. Ejecuta el script de instalación:
    ```sh
    ./start.sh
    ```

3. Sigue las instrucciones en pantalla para completar la instalación.

### Nukkit

1. Descarga el último build de Nukkit desde [aquí](https://ci.nukkitx.com/job/NukkitX/job/Nukkit/job/master/).
2. Ejecuta el servidor con:
    ```sh
    java -jar nukkit-1.0-SNAPSHOT.jar
    ```

3. Sigue las instrucciones en pantalla para completar la configuración inicial.

## Configuración

### PocketMine

La configuración de PocketMine se encuentra en el archivo `server.properties`. Aquí puedes ajustar varios parámetros como el nombre del servidor, la motd, y más.

### Nukkit

La configuración de Nukkit también se maneja a través de un archivo `server.properties`, además de otros archivos de configuración en la carpeta `nukkit`.

## Uso

### Iniciar el Servidor

Para iniciar el servidor, simplemente ejecuta el script correspondiente:
- **PocketMine**: `./start.sh`
- **Nukkit**: `java -jar nukkit-1.0-SNAPSHOT.jar`

### Detener el Servidor

Para detener el servidor de manera segura, utiliza el comando `stop` dentro de la consola del servidor.

### Plugins

Puedes agregar plugins personalizados descargándolos y colocándolos en la carpeta `plugins` del servidor correspondiente.

## Contribuir

¡Las contribuciones son bienvenidas! Si deseas contribuir, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una rama para tu función (`git checkout -b feature/tu-funcion`).
3. Realiza tus cambios y haz commit (`git commit -am 'Añadir nueva función'`).
4. Sube tus cambios (`git push origin feature/tu-funcion`).
5. Abre un Pull Request.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para obtener más detalles.

## Créditos

Gracias a todos los contribuidores y a la comunidad de PocketMine y Nukkit por su apoyo y desarrollo continuo.
