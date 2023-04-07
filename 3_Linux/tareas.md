```
crontab -e 
```
Abre el editor de texto predeterminado para editar el archivo crontab del usuario actual.
```
crontab -l 
```
Muestra la lista de tareas programadas en el archivo crontab del usuario actual.
```
crontab -r 
```
Elimina el archivo crontab completo del usuario actual.
```
crontab -i 
```
Pide confirmación antes de eliminar el archivo crontab del usuario actual.
```
crontab -u 
```
Permite editar o ver el archivo crontab de otro usuario.
```
cron 
```
Es el demonio del sistema que ejecuta tareas programadas en función de las instrucciones en el archivo crontab.
```
systemctl enable cron 
```
Habilita el demonio cron para que se inicie automáticamente en el arranque del sistema.
```
systemctl start cron 
```
Inicia el demonio cron de inmediato.
```
systemctl stop cron 
```
Detiene el demonio cron.
```
systemctl status cron 
```
Muestra el estado actual del demonio cron y si está en ejecución.
