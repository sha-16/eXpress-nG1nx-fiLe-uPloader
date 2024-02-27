# eXpress-nG1nx-fiLe-uPloader
Servidor express con nginx para transferencia de archivos a través del protocolo HTTP.

**Importante:** Antes de clonar este proyecto, me es importante hacerte saber que no se han contemplado mecanismos de seguridad como la autenticación, ni tampoco el uso de demonios que se consideren medianamente restringidos y seguros. Si vas a utilizar este proyecto en un entorno expuesto a Internet, por favor modifica el archvio de configuración de tal manera que no te expongas a sufrir ataques.

### Arranque del Servidor

```
# Test file
nginx -c /full-path/nginx.conf -t 

# Start Server
nginx -c /full-path/nginx.conf

# Stop Server
nginx -c /full-path/nginx.conf -s stop
```

### Probando funcionalidad de subida de archivos

Transfiriendo archvios al servidor del atacante.

![Subida del archivo](https://github.com/sha-16/eXpress-nG1nx-fiLe-uPloader/assets/89037170/65ac35e2-946a-4614-a4e3-e7a21cc091b3)

Archivo recibido correctamente en el servidor del atacante.

![Archivo recibido](https://github.com/sha-16/eXpress-nG1nx-fiLe-uPloader/assets/89037170/78a3e81b-5fc8-4b31-8772-c5badee773b2)

Happy Hacking!
