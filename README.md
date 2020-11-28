# DockerProject
Proyecto Docker con Mysql, Dash y Cuaderno de Jupyter
 Integrantes:
 Julían Falquez
 Jesús Romero
 Sebastián Santander

Para iniciar:
-Abrir el terminal
-Ubicarse en la carpeta DockerProject
-Escribir docker-compose up -d
-Esperar que se descarguen todas las imagenes
-Asegurarse de tener el puerto 3306 sin usar(Este puerto sera usado por Mysql)
-Al abrir el cuaderno de jupyter se requerira un Token, para acceder a el primero debemos
 1. En el container donde esta ubicado el cuaderno de jupyter abrir el CLI
 2. Escribir el comando jupyter notebook list
 3. Copiar el token que aparece como resultado   ejemplo: http://localhost:8888/?token=5c13abbd9f50068b4bb37a1f5cddbeba82d79f0c423a8595 :: /home/jupyter
 4. En este ejemplo el token seria:"5c13abbd9f50068b4bb37a1f5cddbeba82d79f0c423a8595"
