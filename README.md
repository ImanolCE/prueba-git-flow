# Landing Page con CI/CD en GitHub

Este proyecto que relizado es una landing page que se desarrollo en con ReactJS y que es desplegado automáticamente en GitHub Pages utilizando un flujo de trabajo automatizado con GitHub Actions (CI/CD).

##  Tecnologías utilizadas

- ReactJS
- Git y GitHub
- GitHub Actions (CI/CD)
- GitHub Pages

## Requisitos

Antes de clonar este repositorio asegúrate de tener instalado:

- Node.js v18+
- npm
- Git

## Instalación y ejecución local

1. Primero clona el repositorio y despues entrar a la carpeta qeu se creo:

git clone https://github.com/ImanolCE/prueba-git-flow.git

cd prueba-git-flow

## Para instalar dependencias 

npm install

## Despliegue del (CI/CD)

El proyecto relizado utiliza un workflow de GitHub Actions que se activa automáticamente cuando se hace push a la rama main. El archivo de configuración se encuentra en: .github/workflows/main.yml

El workflow realiza las siguientes acciones:

- Instala dependencias
- Ejecuta pruebas
- Construye la app
- Publica el contenido del directorio build/ en la rama gh-pages usando la acción peaceiris/actions-gh-pages.

## Enlaces importantes

- Repositorio en GitHub: https://github.com/ImanolCE/prueba-git-flow

- Página desplegada: https://imanolce.github.io/prueba-git-flow/
