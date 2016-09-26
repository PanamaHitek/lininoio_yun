# lininoio_yun
Ejemplos, scripts y códigos para el Arduino Yun corriendo LininoIO

Para configurar el uhttpd de tal forma que podamos acceder a los ficheros alojados en la memoria microSD del Arduino Yun
desde el servidor web, es necesario ejecutar las siguientes instrucciones:

wget --no-check-certificate https://raw.githubusercontent.com/PanamaHitek/lininoio_yun/master/uhttpd-conf


sh uhttpd-conf


rm uhttpd-conf

Esto creará un hipervínculo en la ruta /osjs/dist llamada sd, desde donde tendremos acceso a la memoria microSD
