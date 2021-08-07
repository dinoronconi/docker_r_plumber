# docker_r_plumber
# Ver el Docker file: parte de la imagen rocker/r-ver y le agrega todo lo necesario para correr una API con Plumber
# Está armada tomando el Dockerfile de la imagen rstudio/plumber, haciendo un par de modificaciones para ejecutar mi API de pruebas

Armar la imagen con:
docker build -t dinoronconi/mi_r_plumber_demo .

Ejecutarla para probar con:
docker run  -d -p 8000:8000 dinoronconi/mi_r_plumber_demo

Subirla a DockerHub con:
docker push dinoronconi/mi_r_plumber_demo

