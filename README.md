# Detector de Noticias Falsas

Este repositorio contiene la implementación de la etapa 2 del proyecto. Originalmente, esta etapa fue desarrollada en un repositorio separado: [proyecto1-etapa2-bi](https://github.com/Yesopi/proyecto1-etapa2-bi.git). Sin embargo, debido a que las instrucciones indicaban que debía guardarse en el mismo repositorio de la etapa 1, se agregó manualmente a este repositorio. Si deseas ver los commits originales de la etapa 2, puedes acceder al repositorio mencionado en el enlace anterior.

## Instrucciones de ejecución

```sh
# 0. Entrar a la carpeta etapa 2
cd './etapa 2/'

# 1. Crear entorno virtual
python -m venv env

# 2. Activar entorno virtual
# En Windows:
./env/Scripts/activate
# En macOS/Linux:
# source env/bin/activate

# 3. Instalar dependencias
cd ./text_classifier_app/
pip install -r requirements.txt

# 4. Ejecutar la aplicación
python run.py
