# apache_ssh2
Comandos utilizados:
•	#git clone  https://github.com/elcaza/curso_docker.git
•	#cat dockerfile 
•	#docker build -t jesusextevez/extevex:1.0 .
•	#docker stop $(docker ps -a -q)
•	
Se corre de la siguiente manera 
•	#docker images
o	fc25db1f6f66
•	#docker run -p 8080:80 -p 2222:22 fc25db1f6f66
•	#sudo docker run -p 8080:80 -v /home/kali/curso_docker/ejemplos/creacion_imagenes/apache_ssh:/var/www/html/ fc25db1f6f66
Login
•	#docker login 
o	user: jesusextevex
o	Password: **********
Subir imagen 
•	#docker push jesusextevex/extevex:1.0
