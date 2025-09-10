# DriveUploader Test

## 🧭 Descripción de la aplicación

**DriveUploader Test** es una aplicación de escritorio desarrollada en Python que permite a los usuarios subir archivos locales a su cuenta de Google Drive. Está diseñada para automatizar flujos de trabajo en proyectos de scraping, análisis de datos y procesamiento de archivos estructurados como `.parquet`, `.csv` y otros formatos compatibles.

## 🔐 Política de Privacidad

- La aplicación no recopila, almacena ni comparte datos personales del usuario.
- El acceso a Google Drive se realiza mediante el protocolo OAuth 2.0 directamente con los servidores de Google.
- Los archivos subidos permanecen en la cuenta de Google Drive del usuario y no son accesibles por el desarrollador ni por terceros.
- No se realiza ningún tipo de análisis, procesamiento o almacenamiento de los archivos subidos fuera del entorno del usuario.

## ⚙️ Justificación del uso de permisos

La aplicación solicita el permiso `https://www.googleapis.com/auth/drive.file` para poder crear y subir archivos a la cuenta de Google Drive del usuario. Este permiso está limitado a archivos generados por la propia aplicación y no permite acceder ni modificar otros archivos existentes en el Drive del usuario.

## 📘 Documentación técnica

- **Lenguaje:** Python  
- **Bibliotecas utilizadas:**  
  - `google-auth-oauthlib`  
  - `google-api-python-client`  
- **Tipo de aplicación:** Escritorio local  
- **Flujo de autenticación:** OAuth 2.0 con `InstalledAppFlow`  
- **Redirección:** `http://localhost`  
- **Alcance solicitado:** `https://www.googleapis.com/auth/drive.file`  
- **Funcionalidad principal:** Subida de archivos locales a una carpeta específica en Google Drive

## 👥 Audiencia prevista

Usuarios técnicos, desarrolladores, analistas de datos y científicos que trabajan con archivos locales y necesitan una forma segura y rápida de almacenarlos en la nube.

## 📇 Contacto del desarrollador

- **Correo de soporte:** aliskairraul@gmail.com  
- **GitHub:** [https://github.com/aliskairraul/uploaderDriveTest](https://github.com/aliskairraul/uploaderDriveTest)

