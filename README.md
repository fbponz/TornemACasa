# 🌐 Tornem A Casa

Este proyecto es un sitio web desarrollado con **Hugo** \*, diseñado específicamente para el cierre de la página oficial:  
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
├── content/            # ✍️ Contenido del sitio web, organizado por secciones
├── data/               # 📊 Archivos de datos dinámicos (JSON)
├── i18n/               # 🌍 Archivos de internacionalización
├── layouts/            # 🖼️ Plantillas personalizadas de páginas
├── public/             # 🌐 Archivos generados para producción (NO MODIFICAR)
├── resources/          # ⚙️ Recursos procesados por Hugo
├── static/             # 🖼️ Archivos estáticos como imágenes
├── themes/             # 🎨 Temas para el proyecto
├── .gitmodules         # ⚙️ Configuración de submódulos git
├── hugo.toml           # ⚙️ Archivo de configuración de Hugo
├── package-lock.json   # 🔒 Archivo de bloqueo de dependencias npm
├── package.json        # 🗂️ Configuración de scripts y dependencias npm
└── README.md           # 📖 Este archivo

```

## ⚙️ Scripts

Desde **PowerShell**, los comandos se ajustan al entorno, se detallan los scripts disponibles:

- start: **.\hugo server -D**
  Inicia un servidor local para desarrollo, incluyendo contenido en borrador.

- build: **.\hugo --minify**
  Genera el sitio optimizado para producción.

- dev: **.\hugo server -D --noHTTPCache**
  Inicia un servidor local con la caché deshabilitada.

## 🛠️ Instalación y Configuración

Sigue los pasos a continuación para configurar el proyecto en tu máquina local:

1️⃣ Clonar el repositorio  
git clone https://github.com/fbponz/TornemACasa.git  
cd TornemACasa

2️⃣ Iniciar el servidor de desarrollo  
Desde PowerShell, ejecuta: .\hugo server -D

Esto iniciará un servidor local en http://localhost:1313 para previsualizar el sitio, incluyendo contenido en borrador.

## 📊 Uso de Datos Dinámicos

El proyecto utiliza la carpeta data/ para almacenar información dinámica que puede ser utilizada en las plantillas de Hugo. Esto permite centralizar datos y personalizar contenido de forma eficiente.

## 🗂️ Estructura de la Carpeta data/

La carpeta data/ contiene archivos en formato JSON que se pueden usar directamente en las plantillas.

```plaintext
data/
├── campaigns.json       # Detalles de las campañas activas
├── collaborators.json   # Lista de colaboradores
├── statistics.json      # Estadísticas generales

```

## 📖 Cómo Usarlos en las Plantillas

1️⃣ Accediendo a los datos
Para acceder a un archivo en la carpeta data/, utiliza la variable .Site.Data en tus plantillas.

2️⃣ Integración con Single Pages
Si estás trabajando con single.html, puedes combinar los datos dinámicos con los contenidos específicos de una página.

3️⃣ Actualizar los Datos
Simplemente edita los archivos .json en la carpeta data/. Los cambios se reflejarán automáticamente cuando reinicies el servidor con .\hugo server -D.

## 🌟 Publicación

Para generar y publicar el sitio web en producción, ejecuta: .\hugo --minify
Los archivos optimizados estarán disponibles en el directorio public/, listos para ser subidos al servidor.

## ℹ️ Información Adicional

Este proyecto tiene como objetivo cerrar la página oficial:  
🔗 https://tornemacasa.es/

Si tienes dudas o necesitas asistencia, no dudes en contactarnos.
