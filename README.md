# Flask_Python_Example

# Docker:

docker build . -t flaskprueba

docker run --rm -p 5000:5000 -v C:\Users\ruperez\Documents\Flask_Python_Example:/app -e FLASK_DEBUG=1 --name flaskprueba flaskprueba

# Docker-compose:

docker-compose up
