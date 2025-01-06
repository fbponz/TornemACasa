# 🌐 Tornem A Casa

Este proyecto es un sitio web desarrollado con **Hugo** y **Bootstrap**, diseñado específicamente para el cierre de la página oficial:  
[🔗 https://tornemacasa.es/](https://tornemacasa.es/)

---

## 📁 Repositorio Oficial

El código fuente de este proyecto está disponible en el siguiente repositorio de GitHub:  
[🔗 https://github.com/fbponz/TornemACasa.git](https://github.com/fbponz/TornemACasa.git)

---

## 📂 Estructura del Proyecto

La estructura principal del proyecto es la siguiente:

```plaintext
TornemACasa/
├── archetypes/         # 📝 Plantillas base para nuevos contenidos
├── assets/             # 🎨 Recursos personalizados como CSS y JavaScript
├── content/            # ✍️ Contenido del sitio web
├── data/               # 📊 Archivos de datos para personalización
├── i18n/               # 🌍 Archivos de internacionalización
├── layouts/            # 🖼️ Plantillas personalizadas de páginas
├── public/             # 🌐 Archivos generados para producción
├── resources/          # ⚙️ Recursos procesados por Hugo
├── static/             # 🖼️ Archivos estáticos como imágenes
├── themes/             # 🎨 Temas para el proyecto
├── .gitmodules         # ⚙️ Configuración de submódulos git
├── .hugo_build.lock    # 🔒 Archivo de bloqueo generado por Hugo
├── hugo.exe            # ⚙️ Binario de Hugo
├── hugo.toml           # ⚙️ Archivo de configuración de Hugo
├── package-lock.json   # 🔒 Archivo de bloqueo de dependencias npm
├── package.json        # 🗂️ Configuración de scripts y dependencias npm
└── README.md           # 📖 Este archivo

```

## ⚙️ Dependencias y Scripts

### 🔗 Dependencias principales:

- @fortawesome/fontawesome-svg-core: ^6.7.2
- @fortawesome/free-brands-svg-icons: ^6.7.2
- @fortawesome/free-regular-svg-icons: ^6.7.2
- @fortawesome/free-solid-svg-icons: ^6.7.2
- bootstrap: ^5.3.3
- viewerjs: ^1.11.7

### 🛠️ Dependencias de desarrollo:

- autoprefixer: ^10.4.20
- postcss: ^8.4.49
- postcss-cli: ^11.0.0

### 🚀 Scripts disponibles:

- start: **hugo server -D**
  Inicia un servidor local para desarrollo, incluyendo contenido en borrador.

- build: **hugo --minify**
  Genera el sitio optimizado para producción.

- dev: **hugo server -D --noHTTPCache**
  Inicia un servidor local con la caché deshabilitada.

## 🛠️ Instalación y Configuración

Sigue los pasos a continuación para configurar el proyecto en tu máquina local:

1️⃣ Clonar el repositorio  
git clone https://github.com/fbponz/TornemACasa.git  
cd TornemACasa

2️⃣ Instalar las dependencias  
npm install

3️⃣ Iniciar el servidor de desarrollo  
npm run start

## 🌟 Publicación

Para generar y publicar el sitio web en producción, ejecuta: `npm run build`  
Los archivos generados estarán disponibles en el directorio `public/`, listos para ser subidos al servidor.

## ℹ️ Información Adicional

Este proyecto tiene como objetivo cerrar la página oficial:  
🔗 https://tornemacasa.es/

Si tienes dudas o necesitas asistencia, no dudes en contactarnos.
