# Emot3D

Trabajo de Fin de Grado de Álvaro Domínguez Aguilar, estudiante de Ingeniería Informática en la Universidad de Granada. El proyecto consiste en el desarrollo de un videojuego adaptativo a las emociones del jugador.

Este repositorio contiene el código del videojuego, importado desde Unity, así como la memoria realizada durante el propio desarrollo y la presentación utilizada para la defensa final del proyecto.



## Uso del Software
### Prerrequisitos
1. [Descargar e instalar](https://www.emotiv.com/emotiv-launcher/) la aplicación de Emotiv, disponible para Windows y macOS.

2. Instalar Unity (versión 2020.3.33f1 para un correcto funcionamiento).

### Configuración
1. En primer lugar es necesario crear una cuenta de Emotiv.

2. Una vez registrado un usuario y descomprimido e importado el código a Unity, modificar las parámetros del archivo `AppConfig.cs`: ClientId, ClientSecret, AppVersion y TmpAppDataDir en un editor de texto. Los datos relativos a los dos primeros parámetros se pueden obtener a partir de la información de la cuenta registrada.

3. Si los parámetros introducidos son correctos, el juego puede ejecutarse, comenzado por realizar la conexión a la aplicación de Emotiv.


Para más información consultar la [memoria](TFG_DominguezAguilarAlvaro.pdf) y el [plugin de Emotiv](https://github.com/Emotiv/unity-plugin).

