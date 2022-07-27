# traccar-server
 Instalacion de Tracker GPS "Traccar", para seguimiento satelital de Vehiculos, Personas, Animales ....

 Instrucciones para la instalacion:
   
   Debemos tener instalado Docker y Docker-Compose
   
   Creamos una carpeta donde clonaremos el repositorio, por ejemplo:
    
        sudo mkdir /docker
    
   Despues clonamos el repositorio

        git clone https://github.com/davidpebe78/traccar-server.git

   Tenemos que modificar el archivo .env, con los datos que necesitemos (HAY QUE CAMBIAR TODAS LAS MAYUSCULAS ENTRE [], "se quitan los []")

        sudo nano .env
   
   Y tambien el archivo ./traccar/config/traccar.xml con los datos que pusimos en el archivo .env

   Y para terminar ejecutamos el docker-compose.yaml

        docker compose up -d
   
