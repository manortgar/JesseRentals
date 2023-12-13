# 🏗️ Alquiler de Maquinaria de Construcción (Proyecto AMJR) 🏗️

## Código del Proyecto
AMJR

## Director del Proyecto
- Ana Lucía Durán Lengo
- Carlos Varela Soult
- Álvaro Rodríguez García
- Manuel Ortega García
- Alonso Codesal Martínez

## Descripción del Proyecto
Este proyecto se centra en el desarrollo de un sistema para el alquiler de maquinaria de construcción durante un tiempo determinado. La plataforma está construida utilizando el framework Django.

## Ejecutando el Proyecto

**Para poner en marcha este proyecto, asegúrate de tener Python instalado en tu computadora. Se recomienda crear un entorno virtual para almacenar las dependencias del proyecto de manera independiente. Puedes instalar `virtualenv` con:**

pip install virtualenv

**Clona o descarga este repositorio y ábrelo en tu editor de preferencia. En un terminal (mac/linux) o terminal de Windows, ejecuta el siguiente comando en el directorio base de este proyecto:**

virtualenv env

**Esto creará una nueva carpeta llamada `env` en el directorio de tu proyecto. Luego, actívalo con el siguiente comando en mac/linux:**

source env/bin/activate

**Después, instala las dependencias del proyecto con:**

pip install -r requirements.txt

**Ahora puedes ejecutar el proyecto con este comando:**

python manage.py runserver

**Nota: Si deseas que los pagos funcionen, deberás ingresar tus propias claves de API de Stripe en el archivo `.env` en los archivos de configuración.**
