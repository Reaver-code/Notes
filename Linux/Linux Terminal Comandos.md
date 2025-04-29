## Navegación y Gestión de Archivos

1. **`ls`** - Lista el contenido de un directorio.
    
    - `-l` : Lista en formato largo.
    - `-a` : Muestra archivos ocultos.
    - `-h` : Tamaños legibles por humanos.
    - `-R` : Lista recursivamente los subdirectorios.
2. **`cd`** - Cambia el directorio actual.
    
    - `cd ..` : Sube un nivel en la jerarquía de directorios.
    - `cd /path/to/directory` : Va al directorio especificado.
3. **`pwd`** - Muestra el directorio actual (ruta completa).
    
4. **`mkdir`** - Crea un nuevo directorio.
    
    - `-p` : Crea directorios padres si no existen.
5. **`rmdir`** - Elimina un directorio vacío.
    
6. **`cp`** - Copia archivos o directorios.
    
    - `-r` : Copia directorios de forma recursiva.
    - `-i` : Pide confirmación antes de sobrescribir.
7. **`mv`** - Mueve o renombra archivos o directorios.
    
    - `-i` : Pide confirmación antes de sobrescribir.
8. **`rm`** - Elimina archivos o directorios.
    
    - `-r` : Elimina directorios de forma recursiva.
    - `-f` : Fuerza la eliminación sin preguntar.

### Información del Sistema y Procesos

1. **`top`** - Muestra los procesos en tiempo real.
    
2. **`ps`** - Muestra los procesos actuales.
    
    - `-e` : Muestra todos los procesos.
    - `-f` : Muestra una lista completa con más información.
3. **`kill`** - Termina un proceso.
    
    - `-9` : Fuerza la terminación del proceso.
4. **`df`** - Muestra el uso del espacio en disco.
    
    - `-h` : Tamaños legibles por humanos.
5. **`du`** - Muestra el uso del espacio en directorios.
    
    - `-h` : Tamaños legibles por humanos.
    - `-s` : Muestra un resumen total.
6. **`free`** - Muestra el uso de la memoria.
    
    - `-h` : Tamaños legibles por humanos.

### Gestión de Usuarios y Permisos

1. **`chmod`** - Cambia los permisos de un archivo o directorio.
    - `+x` : Añade permiso de ejecución.
    - `u, g, o` : Usuario, grupo, otros.
2. **`chown`** - Cambia el propietario de un archivo o directorio.
    - `usuario:grupo` : Especifica el nuevo propietario y grupo.
3. **`usermod`** - Modifica cuentas de usuario.
    - `-aG` : Añade un usuario a un grupo (usado con `-G`).
4. **`passwd`** - Cambia la contraseña de un usuario.

### Red y Conexión

1. **`ping`** - Comprueba la conectividad con un host.
    
    - `-c` : Especifica el número de paquetes a enviar.
2. **`ifconfig`** - Muestra o configura interfaces de red.
    
    - `-a` : Muestra todas las interfaces.
3. **`netstat`** - Muestra estadísticas de la red.
    
    - `-tuln` : Muestra puertos en escucha.
4. **`ssh`** - Conecta a un host remoto mediante SSH.
    
    - `user@host` : Especifica el usuario y host.

### Compresión y Archivos

1. **`tar`** - Trabaja con archivos tar (empaquetado y compresión).
    
    - `-cvf` : Crea un archivo tar.
    - `-xvf` : Extrae un archivo tar.
    - `-z` : Comprime/Descomprime con gzip.
2. **`gzip`** - Comprime archivos con gzip.
    
    - `-d` : Descomprime archivos.
3. **`zip`** - Comprime archivos con zip.
    
    - `-r` : Comprime directorios recursivamente.
4. **`unzip`** - Descomprime archivos zip.
    

### Búsqueda y Filtrado

1. **`grep`** - Busca texto en archivos.
    
    - `-i` : Ignora mayúsculas/minúsculas.
    - `-r` : Busca recursivamente en directorios.
2. **`find`** - Busca archivos y directorios.
    
    - `-name` : Busca por nombre.
    - `-type` : Busca por tipo (f para archivos, d para directorios).
3. **`locate`** - Encuentra archivos rápidamente usando una base de datos.
    

### Utilidades Varias

1. **`echo`** - Imprime texto en la terminal.
    
    - `-n` : No añade una nueva línea al final.
2. **`cat`** - Muestra el contenido de un archivo.
    
    - `-n` : Muestra los números de línea.
3. **`less`** - Muestra el contenido de un archivo página por página.
    
4. **`head`** - Muestra las primeras líneas de un archivo.
    
    - `-n` : Especifica el número de líneas.
5. **`tail`** - Muestra las últimas líneas de un archivo.
    
    - `-n` : Especifica el número de líneas.
    - `-f` : Sigue mostrando nuevas líneas añadidas al archivo.

### Administración del Sistema

1. **`sudo`** - Ejecuta un comando con privilegios de superusuario.
    
2. **`apt-get`** (Debian/Ubuntu) - Gestiona paquetes de software.
    
    - `update` : Actualiza la lista de paquetes.
    - `upgrade` : Actualiza los paquetes instalados.
    - `install` : Instala un nuevo paquete.
3. **`yum`** (RHEL/CentOS) - Gestiona paquetes de software.
    
    - `install` : Instala un nuevo paquete.
    - `update` : Actualiza los paquetes instalados.
4. **`systemctl`** - Gestiona servicios del sistema.
    
    - `start` : Inicia un servicio.
    - `stop` : Detiene un servicio.
    - `status` : Muestra el estado de un servicio.
    - `enable` : Habilita un servicio para que inicie en el arranque.
    - `disable` : Deshabilita un servicio para que no inicie en el arranque.