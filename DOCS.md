# Apuntes de este proyecto

## Instalación

Para empezar, no se ha usado create-react-app. Se ha hecho uso de: <https://vitejs.dev/guide/>. Es una herramienta que permite el desarrollo front, de manera mucho más limpia, y sobre todo, rápida.

Seguidamente se ha instalado tailwindcss. <https://tailwindcss.com/docs/guides/create-react-app>, y se han ejecutado los comandos:
    npm install -D tailwindcss postcss autoprefixer
    npx tailwindcss init -p

Este proceso nos genera los archivos de configuración tailwind.config.cjs, y el vite.config.js, y se deben de configurar.
    vite.config.js, nos especifica el tipo de proyecto que estamos trabajando, podemos trabajar con react.ts por ejemplo.

    Para el archivo de tailwind, copié los estilos del señor de este video. https://www.youtube.com/watch?v=_oO4Qi5aVZs&t=1s de su git: https://github.com/adrianhajdin/project_hoobank/blob/main/tailwind.config.cjs
        Este, simplemente declara unas variables, que se van a usar a lo largo del proyecto.

En el index.css, es donde queremos hacer uso de tailwind, y para ello, el css, se sustituye, por lo que esta en el proyecto si releo esto. (<https://github.com/adrianhajdin/project_hoobank/blob/main/src/index.css>)

Después se descarga la carpeta de assets, que nos proporciona el señor, y se mete en el proyecto.
    <https://minhaskamal.github.io/DownGit/#/home?url=https:%2F%2Fgithub.com%2Fadrianhajdin%2Fproject_hoobank%2Ftree%2Fmain%2Fsrc%2Fassets>

## Estructura de archivos

## *En negrita, lo nuevo*

src>*constants*>*index.js* Archivo para definir variables constantes dentro de la pagina.
src>*style.js* Estilos para todo el proyecto

## Código

Hecho esto, se ha seguido el código que pica el señor en el video. (Min: 16)
