# DockerProject
Proyecto Docker con Mysql, Dash y Cuaderno de Jupyter
 Integrantes:
 Julían Falquez
 Jesús Romero
 Sebastián Santander

Para iniciar:
 1.Abrir el terminal
 2.Ubicarse en la carpeta DockerProject
 3.Escribir docker-compose up -d
 4.Esperar que se descarguen todas las imagenes
 5.Asegurarse de tener el puerto 3306 sin usar(Este puerto sera usado por Mysql)
 6.Al abrir el cuaderno de jupyter se requerira un Token, para acceder a el primero debemos
 7. En el container donde esta ubicado el cuaderno de jupyter abrir el CLI
 8. Escribir el comando jupyter notebook list
 9. Copiar el token que aparece como resultado   ejemplo: http://localhost:8888/?token=5c13abbd9f50068b4bb37a1f5cddbeba82d79f0c423a8595 :: /home/jupyter
 10. En este ejemplo el token seria:"5c13abbd9f50068b4bb37a1f5cddbeba82d79f0c423a8595"
