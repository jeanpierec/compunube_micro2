# Usamos una imagen base de Python
FROM python:3.9

# Establecemos el directorio de trabajo en /app
WORKDIR /app

# Copiamos el código de la aplicación a la imagen
COPY app.py .

# Instalamos las dependencias necesarias
RUN pip install flask

# Exponemos el puerto en el que se ejecutará la aplicación
EXPOSE 5000

# Comando para iniciar la aplicación cuando se inicie el contenedor
CMD ["python", "app.py"]
