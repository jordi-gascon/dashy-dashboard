# Dashy Dashboard
![dashy Dashboard](/img-repo/01.png)

El siguiente repo es una modificación de la imagen de docker de Dashy creada por [@Lissy93](https://github.com/Lissy93) con el cual podrás levantar una instancia de Dashy con tan solo un comando.

El repositorio está preparado con las carpetas necesarias y los iconos añadidos para que tan solo lances la instancia con docker compose y esté listo para funcional

Dashy es una aplicación de panel de control de código abierto, altamente personalizable, fácil de usar y que respeta la privacidad. Está repleto de características útiles para ayudarlo a crear su panel de control perfecto. Incluye comprobaciones de estado, atajos de teclado, widgets dinámicos, íconos de favicon de búsqueda automática y compatibilidad con fuentes impresionantes, autenticación integrada, toneladas de temas, un editor de configuración interactivo, muchos diseños de visualización y mucho más.



## Requisitos previos

Se requiere disponer instalado previamente:
- Docker
- Docker-compose


## Autor

- [@jordi-gascon](https://www.github.com/jordi-gascon)


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Instalación
A continuación te muestro como descargarlo y ejecutarlo.

Descargamos el repositorio en el directorio que queramos

```bash
# git clone https://github.com/jordi-gascon/dashy-dashboard.git
```
A continuación accedemos al a la carpeta dashy-dasboard
```bash
# cd dashy-dashboard/
```
El puerto que está seteado por defecto es el 8080. Puedes cambiarlo a otro si ese lo tienes ocupado o simplemente quieres usar otro.

Para ello, tenemos que modificar el archivo docker-compose.yml y salvarlo con los cambios realizados
```bash
# nano docker-compose.yml 
```
Por último, lanzamos el comando de docker-compose para levantar la instancia
```bash
# docker-compose up -d 
```
Una vez completada la tarea, podemos comprobar si el servicio se ha levantado correctamente con el siguiente comando.
```bash
# docker ps 
```
Si todo se ha ejecutado correctamente abrimos el navegador web e introducimos la dirección IP de nuestro servidor, seguido del puerto que hayamos configurado.
```bash
http://youripaddress:8080 
```

