#Funcionamiento

Te despliega un contenedor nginx con ssl de letsencrypt creadas automaticamente y las renueva.
En la carpeta www van los ficheros de la pagina.
En caso de desplegar mas de 1 web, añadir en el docker-compose un www2 y crear otra carpeta ww2



Solo hay que clonar y actualizar estas variables.


environment:

      - VIRTUAL_HOST=joanciber.tk
      - LETSENCRYPT_HOST=joanciber.tk
      - LETSENCRYPT_EMAIL=joan.garciai.ieti@gmail.com
