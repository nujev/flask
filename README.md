#Intalación de ambiente

Instalación de ambiente en Fedora
```sh

sudo dnf install python3 python3-pip python3-virtualenv

```

Instalación de ambiente en Ubuntu
```sh

sudo apt install python3 python3-pip python3-virtualenv

```

#Configuración de ambiente
Configurar el ambiente python para el proyecto
```sh

cd ~/path/to/code
virtualenv venv
source venv/bin/activate
pip3 install flask
pip3 install flask-bootstrap

```

#Usar el código
Para iniciar la aplicación ejecutar
```sh

python3 main.py

```

Acceder a la aplicación desde 

```sh

http://localhost:5000/

```
#Salir del ambiente
Terminar ambiente de python del proyecto
```sh

deactivate

```
