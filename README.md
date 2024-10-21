# README

## Proyecto: Alojamiento de un Sitio Web Estático con AWS Amplify

Este tutorial se encuentra en [AWS Getting Started](https://aws.amazon.com/getting-started/hands-on/host-static-website/?ref=gsrchandson).


AWS Amplify permite tener un sitio web estático, además ofrece un flujo de trabajo CI/CD basado en Git para la construcción y el alojamiento de sitios. Los sitios web estáticos son de bajo costo, altamente fiables y requieren mínima administración de TI, además de escalar para manejar tráfico empresarial sin esfuerzo adicional. Se logrará alojar un sitio utilizando la consola de AWS y configurar el despliegue continuo, permitiendo actualizaciones automáticas con cada confirmación de código. Este tutorial proporciona una guía práctica para aprovechar AWS Amplify en la gestión y despliegue eficiente de sitios web.


# README

## Pasos para Activar el Proyecto en Local

1. **Clonar el repositorio**: Ejecutar el siguiente comando en la terminal:
   ```bash
   git clone https://github.com/EliuMR/Staticwebsite.git
   ```

2. **Instalar dependencias**: Navegar a la carpeta del proyecto y ejecutar:
   ```bash
   npm install
   ```

3. **Iniciar el servidor local**: Ejecutar el siguiente comando para iniciar la aplicación en modo de desarrollo:
   ```bash
   npm start
   ```

## Pasos para Activar el Proyecto en AWS Amplify

1. **Iniciar sesión en la consola de AWS**: Acceder a la consola de AWS y buscar "AWS Amplify".

2. **Crear un nuevo proyecto**: Hacer clic en "Get Started" y conectar el repositorio de Git donde está alojado el proyecto.

3. **Configurar el flujo de trabajo**: Seguir las instrucciones para configurar el flujo de trabajo CI/CD, eligiendo las ramas a desplegar.

4. **Desplegar el proyecto**: Hacer clic en "Deploy" y esperar a que AWS Amplify construya y despliegue la aplicación.

5. **Acceder al sitio**: Una vez desplegada, se proporcionará una URL donde se puede acceder al sitio web.

