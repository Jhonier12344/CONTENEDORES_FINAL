# Proyecto final

Esta es la practica final de telemática donde se trabajará con contenedores

Para comenzar esta practica debes primero clonar el repositorio con el siguiente comando: 
git clone https://github.com/Jhonier12344/CONTENEDORES_FINAL.git 

1. Para iniciar el contenedor se ejecuta el siguiente comando:
  sudo docker build -t proyectofinal:01 .

2. Para ejecturar el servicio se usa el siguiente comando:
  sudo docker run -it -p 80:80 proyectofinal:01 python3 app.py 

Nota: El parametro -it es para ver de forma interactiva el proceso e interactuar con la                                                                           maquina por comandos, aunque se puede cambiar por el parametro -d para que corra por                                                                       medio de memoria ram o sea por background                                                                 
  


