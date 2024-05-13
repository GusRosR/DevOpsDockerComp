# DevOpsDockerComp
En este repositorio se encuentra el proceso para realizar la clonación del Moodle y los comandos para realizar el Docker Compose

# Procedimiento para clonar el Learning Management System (LMS) Moodle

1. Es necesario crear una carpeta en donde se almacenarán los datos del repositorio a clonar así como su base de datos

    mkdir docker

En este caso, se le puede poner el nombre que se desee.

2. Cambiarse al directorio o carpeta que se acaba de crear

    cd docker


3. Se clona el siguiente repositorio con el siguiente comando:

    git clone https://github.com/jmlcas/moodle


4. Cambiarse al directorio que se añade luego de clonar el repositorio

   cd moodle


5. Realizar el Docker compose con el siguiente comando:

   docker compose up -d

Es importante realizar el docker compose con el parámetro -d ya que sin él se corre el riesgo de echar a perder toda la configuración previa de docker que se ha realizado. La información que controla el usuario y la contraseña con la cual se accede al panel administrativo se encuentra en el archivo docker-compose.yml que se encuentra en el repositorio, en dicho archivo se realizan diferentes configuraciones y parámetros necesarios para que funcione el servicio sin ningún problema.

# Configurar Moodle

En este caso, primero se debe acceder al Moodle en el navegador, para ello se debe escribir en el buscador lo siguiente:

    localhost:8200 o bien laip:8200
    
A continuación, accedemos al Moodle utilizando el usuario y contraseña por defecto. Estos son:

Usuario: User
Password: p4ssw0rd





