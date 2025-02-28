📌Requisitos

Antes de comenzar, tener instalado:

Python 3.x

Docker

Docker Compose

Git

👅 Clonar el repositorio

#comando para clonar el repositorio.

git clone https://github.com/Haroldmedina2003/flask-postgres-docker.git
cd flask-postgres-docker

🔧 Configurar el entorno

Crea y activa un entorno virtual

python3 -m venv venv
source venv/bin/activate  # En Linux/macOS
venv\Scripts\activate     # En Windows

Instala las dependencias:

pip install -r requirements.txt

🛠 Configurar la base de datos

Asegúrate de que Docker esté corriendo.

Ejecuta el siguiente comando para levantar los contenedores:

docker-compose up -d

🚀 Ejecutar la aplicación

Para iniciar el servidor Flask manualmente, usa:

python app.py

La aplicación se ejecutará en http://127.0.0.1:5000/.

🔄 Detener y eliminar contenedores

Cuando termines, puedes detener y eliminar los contenedores con:

docker-compose down
