# Instalación y Ejecución del Proyecto con Yarn

Para comenzar con el proyecto, necesitarás tener [Yarn](https://yarnpkg.com/) instalado en tu máquina.

## Instalación de Yarn Globalmente con npm

Sigue estos pasos para instalar Yarn globalmente en tu sistema:

1. **Instalación de npm:**

   Si aún no tienes npm instalado, puedes descargarlo e instalarlo desde [Node.js](https://nodejs.org/).

2. **Instalación de Yarn Globalmente:**

   Utiliza el siguiente comando npm para instalar Yarn globalmente:

   ```bash
   npm install -g yarn
   ```

   Este comando instalará Yarn de manera global en tu sistema, lo que te permitirá utilizarlo en cualquier proyecto sin necesidad de descargar binarios específicos.

## Clonar el Proyecto

Clona el repositorio del proyecto desde la terminal usando el siguiente comando:

```bash
git clone https://github.com/SAGESPRA/SAGESPRA_FrontEnd.git
cd SAGESPRA_FrontEnd/source
```

## Instalación de Dependencias

Una vez que estás en la carpeta del proyecto, ejecuta el siguiente comando para instalar todas las dependencias:

```bash
yarn install
```

Este comando leerá el archivo `package.json` del proyecto y descargará todas las dependencias necesarias.

## Iniciar el Proyecto

Después de la instalación de las dependencias, puedes iniciar el proyecto con el siguiente comando:

```bash
yarn start
```

Este comando ejecutará el script de inicio especificado en el archivo `package.json` y lanzará tu aplicación. Abre tu navegador y visita [http://localhost:3000](http://localhost:3000) para ver la aplicación en acción.

## Documentación Adicional

Si tienes alguna duda o pregunta sobre la instalación o el proyecto en sí, consulta la [documentación oficial](https://themesbrand.com/steex/docs/react/installation.html) proporcionada por el equipo de desarrollo. Allí encontrarás información detallada sobre la configuración y el funcionamiento del proyecto.