


> Escrito con [ StackEdit ](https://stackedit.io/) .# Despliegue de la aplicación PokeDex en Vercel

Este documento te guiará paso a paso en el proceso para desplegar tu aplicación **PokeDex** desde un repositorio de GitHub en Vercel.

## Pasos para desplegar la aplicación PokeDex en Vercel:

### 1. **Asegúrate de que tu repositorio en GitHub esté listo**
   - Verifica que tu aplicación **PokeDex** esté en un repositorio de GitHub accesible.  
   - Asegúrate de que el repositorio contenga un archivo `package.json` en la raíz del proyecto (esto es necesario para aplicaciones Node.js) y que esté configurado correctamente para que Vercel pueda construir y desplegar tu proyecto.

### 2. **Inicia sesión en Vercel**
   - Accede a tu cuenta de Vercel en [https://vercel.com/dashboard](https://vercel.com/dashboard). Si no tienes una cuenta, puedes seguir el archivo [`README.md`](README.md) para crear una.

### 3. **Importa tu proyecto desde GitHub**
   - En el panel de control de Vercel, haz clic en el botón "New Project" o "Nuevo Proyecto".
   - Selecciona **GitHub** como la plataforma de control de versiones.
   - Vercel te pedirá que otorgues permisos para acceder a tus repositorios de GitHub si es la primera vez que lo usas. Autoriza Vercel para que pueda importar tu proyecto.
   - Luego de otorgar permisos, busca y selecciona el repositorio que contiene tu aplicación **PokeDex**.

### 4. **Configura las opciones de despliegue**
   - Después de seleccionar tu repositorio, Vercel te llevará a una página de configuración donde deberás definir algunos parámetros:
     - **Nombre del proyecto:** Puedes aceptar el nombre predeterminado (el nombre de tu repositorio) o cambiarlo si lo deseas.
     - **Branch (Rama):** Elige la rama que deseas desplegar (generalmente `main` o `master`).
     - **Configuración de framework:** Si tu aplicación está construida con un framework común (como Next.js, React, etc.), Vercel lo detectará automáticamente y configurará las opciones adecuadas. Si no, puedes especificar manualmente el framework si es necesario.
     - **Variables de entorno (opcional):** Si tu aplicación utiliza variables de entorno, agrégalas en este paso. Haz clic en "Environment Variables" y define las claves y valores necesarios.

### 5. **Inicia el despliegue**
   - Una vez configurados los detalles del proyecto, haz clic en el botón **"Deploy"**.
   - Vercel iniciará el proceso de construcción y despliegue de tu aplicación. Este proceso puede tomar unos minutos, dependiendo del tamaño y la complejidad del proyecto.
   - Durante este proceso, puedes ver el registro en tiempo real de la construcción para monitorear si todo está funcionando correctamente.

### 6. **Verifica el despliegue**
   - Cuando el despliegue haya finalizado, Vercel te proporcionará una URL única para acceder a tu aplicación PokeDex en producción. La URL tendrá el formato `https://nombre-proyecto.vercel.app`.
   - Haz clic en el enlace para verificar que tu aplicación se haya desplegado correctamente.

### 7. **Configuración adicional (opcional)**
   - Si deseas vincular un dominio personalizado a tu aplicación, puedes hacerlo desde el panel de control de Vercel.
   - También puedes configurar automáticamente nuevas versiones del despliegue cada vez que hagas un `push` a la rama seleccionada en GitHub.

## Enlaces útiles:

- [Dashboard de Vercel](https://vercel.com/dashboard)  
  Accede directamente al panel de control de Vercel para gestionar tus despliegues.
- [Documentación de Vercel sobre despliegue](https://vercel.com/docs/deployments)  
  Información adicional sobre las configuraciones de despliegue y buenas prácticas.

