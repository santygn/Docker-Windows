# Docker-Windows

## Pasos para la instalación de Docker en Windows

## Ander Santiago Guillen Nazareno
***
- Acceder a la web oficial de [Docker](https://www.docker.com/products/docker-desktop/) y le damos a Windows para descargarlo en nuestro dispositivo con SO Windows.
- Abrir el instalador de Docker que hemos descargado previamente para que se instale correctamente.
- Una vez instalado tendremos que reiniciar el dispositivo.
- Tras esto, recibiremos una advertencia de que necesitamos tener instalado Linux kernel.
- Antes de instalar el Kernel, nos iremos nuestro powerShell para ver que version de WSL tenemos en nuestro Windows. Introduciremos el codigo `wsl --set-default-version 2`
- Instalamos la version mas reciente de Kernel WSL 2 desde este [link](https://docs.microsoft.com/es-es/windows/wsl/install-manual#step-4---download-the-linux-kernel-update-package)
- Instalamos el paquete que acabamos de descargar y podemos reinicar el dispositivo para  poder ejecutar Docker.

