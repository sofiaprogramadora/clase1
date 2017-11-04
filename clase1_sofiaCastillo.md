1. Entrar a la raíz y ver los archivos y directorios

cd /
ls -la

Respuesta:

total 34236
drwxr-xr-x  25 root root     4096 oct 31 07:13 .
drwxr-xr-x  25 root root     4096 oct 31 07:13 ..
drwxr-xr-x   2 root root     4096 sep 26 14:37 bin
drwxr-xr-x   4 root root     4096 nov  1 23:03 boot
drwxrwxr-x   2 root root     4096 jun 12 12:31 cdrom
-rw-------   1 root root 35135488 ago 25 00:40 core
drwxr-xr-x  20 root root     4160 nov  3 22:31 dev
drwxr-xr-x 158 root root    12288 nov  1 23:01 etc
drwxr-xr-x   4 root root     4096 jul 15 23:04 home
lrwxrwxrwx   1 root root       33 oct 31 07:13 initrd.img -> boot/initrd.img-4.10.0-38-generic
lrwxrwxrwx   1 root root       33 ago 31 10:16 initrd.img.old -> boot/initrd.img-4.10.0-33-generic
drwxr-xr-x  24 root root     4096 sep  4 16:36 lib
drwxr-xr-x   2 root root     4096 sep 28 16:49 lib32
drwxr-xr-x   2 root root     4096 jun 28 12:41 lib64
drwx------   2 root root    16384 jun 12 12:27 lost+found
drwxr-xr-x   3 root root     4096 jun 12 08:37 media
drwxr-xr-x   2 root root     4096 feb 15  2017 mnt
drwxr-xr-x   7 root root     4096 oct 13 22:29 opt
dr-xr-xr-x 234 root root        0 nov  3 22:31 proc
drwx------   9 root root     4096 sep 14 18:37 root
drwxr-xr-x  27 root root      840 nov  3 22:36 run
drwxr-xr-x   2 root root    12288 oct 31 07:11 sbin
drwxr-xr-x   4 root root     4096 oct  5 14:29 snap
drwxr-xr-x   2 root root     4096 feb 15  2017 srv
dr-xr-xr-x  13 root root        0 nov  3 22:31 sys
drwxrwxrwt  13 root root     4096 nov  3 22:41 tmp
drwxr-xr-x  12 root root     4096 sep 28 16:49 usr
drwxr-xr-x  15 root root     4096 ago 28 13:48 var
lrwxrwxrwx   1 root root       30 oct 31 07:13 vmlinuz -> boot/vmlinuz-4.10.0-38-generic
lrwxrwxrwx   1 root root       30 ago 31 10:16 vmlinuz.old -> boot/vmlinuz-4.10.0-33-generic

2. Entrar a la carpeta usuario y ver los archivos y
directorios

cd /home/
ls -la

Respuesta:

total 24
drwxr-xr-x   4 root     root      4096 jul 15 23:04 .
drwxr-xr-x  25 root     root      4096 oct 31 07:13 ..
drwxr-xr-x  15 invitado invitado  4096 oct  1 20:28 invitado
drwxr-xr-x 140 sofia    sofia    12288 nov  3 22:31 sofia

3. Ir una carpeta más atrás de la carpeta usuario

cd ..
ls -la

Respuesta:

total 34236
drwxr-xr-x  25 root root     4096 oct 31 07:13 .
drwxr-xr-x  25 root root     4096 oct 31 07:13 ..
drwxr-xr-x   2 root root     4096 sep 26 14:37 bin
drwxr-xr-x   4 root root     4096 nov  1 23:03 boot
drwxrwxr-x   2 root root     4096 jun 12 12:31 cdrom
-rw-------   1 root root 35135488 ago 25 00:40 core
drwxr-xr-x  20 root root     4160 nov  3 22:31 dev
drwxr-xr-x 158 root root    12288 nov  1 23:01 etc
drwxr-xr-x   4 root root     4096 jul 15 23:04 home
lrwxrwxrwx   1 root root       33 oct 31 07:13 initrd.img -> boot/initrd.img-4.10.0-38-generic
lrwxrwxrwx   1 root root       33 ago 31 10:16 initrd.img.old -> boot/initrd.img-4.10.0-33-generic
drwxr-xr-x  24 root root     4096 sep  4 16:36 lib
drwxr-xr-x   2 root root     4096 sep 28 16:49 lib32
drwxr-xr-x   2 root root     4096 jun 28 12:41 lib64
drwx------   2 root root    16384 jun 12 12:27 lost+found
drwxr-xr-x   3 root root     4096 jun 12 08:37 media
drwxr-xr-x   2 root root     4096 feb 15  2017 mnt
drwxr-xr-x   7 root root     4096 oct 13 22:29 opt
dr-xr-xr-x 234 root root        0 nov  3 22:31 proc
drwx------   9 root root     4096 sep 14 18:37 root
drwxr-xr-x  27 root root      840 nov  3 22:36 run
drwxr-xr-x   2 root root    12288 oct 31 07:11 sbin
drwxr-xr-x   4 root root     4096 oct  5 14:29 snap
drwxr-xr-x   2 root root     4096 feb 15  2017 srv
dr-xr-xr-x  13 root root        0 nov  3 22:44 sys
drwxrwxrwt  13 root root     4096 nov  3 22:45 tmp
drwxr-xr-x  12 root root     4096 sep 28 16:49 usr
drwxr-xr-x  15 root root     4096 ago 28 13:48 var
lrwxrwxrwx   1 root root       30 oct 31 07:13 vmlinuz -> boot/vmlinuz-4.10.0-38-generic
lrwxrwxrwx   1 root root       30 ago 31 10:16 vmlinuz.old -> boot/vmlinuz-4.10.0-33-generic

4. Entrar a la carpeta de escritorio

cd ~/Escritorio
ls -la

Respuesta:

total 968
drwxr-xr-x   6 sofia sofia   4096 nov  2 16:59 .
drwxr-xr-x 140 sofia sofia  12288 nov  3 22:31 ..
-rw-rw-r--   1 sofia sofia  45812 oct 29 14:11 autosave.h2song
-rw-rw-r--   1 sofia sofia 161557 oct 24 11:30 dorasofi.jpg
drwxrwxr-x  37 sofia sofia   4096 oct 18 23:48 Escritorio
drwxrwxr-x   2 sofia sofia   4096 oct 30 16:21 Makeup
-rw-rw-r--   1 sofia sofia 421020 oct 30 12:21 martingirlixen.xcf
dr-xr-xr-x   7 sofia sofia   4096 jul 22  2016 MDB Free
-rw-rw-r--   1 sofia sofia    331 nov  2 16:59 newhtmlfile.html
-rw-rw-r--   1 sofia sofia    250 oct 28 11:12 Notas
-rw-rw-r--   1 sofia sofia    130 oct 24 10:38 notas.txtxtextxtx
-rw-rw-r--   1 sofia sofia  35382 oct 27 21:16 piplup (copy).jpg
-rw-rw-r--   1 sofia sofia  35382 oct 27 21:16 piplup.jpg
-rw-rw-r--   1 sofia sofia    452 oct 28 11:11 Songs
drwxrwxr-x   4 sofia sofia   4096 sep 23  2016 sublime_text_3
-rw-rw-r--   1 sofia sofia     40 oct 30 13:05 Suricata
-rw-rw-r--   1 sofia sofia 211836 oct 28 09:40 whylinux.jpg

5. Crear una carpeta clase1 dentro del escritorio

mkdir clase1
ls -la | grep 'clase1'

Respuesta:

drwxrwxr-x   2 sofia sofia   4096 nov  3 22:55 clase1

6. Entrar a la carpeta

cd clase1
pwd

Respuesta:

/home/sofia/Escritorio/clase1

7. Volver atrás

cd ..
pwd

Respuesta:

/home/sofia/Escritorio

8. Crear una carpeta clase2

mkdir clase2
ls -la | grep 'clase2'

Respuesta:

drwxrwxr-x   2 sofia sofia   4096 nov  3 23:10 clase2

9. Mover la carpeta de la clase 2 dentro de la clase1

mv clase2 clase1/clase2
ls clase1

Respuesta:

clase2

10. Renombrar la carpeta de la clase 2 a estamos_terminando

cd clase1
mv clase2 estamos_terminando
ls -la

Respuesta:

total 12
drwxrwxr-x 3 sofia sofia 4096 nov  3 23:27 .
drwxr-xr-x 8 sofia sofia 4096 nov  3 23:16 ..
drwxrwxr-x 2 sofia sofia 4096 nov  3 23:10 estamos_terminando

11. Borrar la carpeta de la estamos_terminando

rm -rf estamos_terminando
ls -la

Respuesta:

drwxrwxr-x 2 sofia sofia 4096 nov  3 23:28 .
drwxr-xr-x 8 sofia sofia 4096 nov  3 23:16 ..

12. Crear una carpeta llamada recursivo

mkdir recursivo
ls -la

Resultado:

total 12
drwxrwxr-x 3 sofia sofia 4096 nov  3 23:36 .
drwxr-xr-x 8 sofia sofia 4096 nov  3 23:16 ..
drwxrwxr-x 2 sofia sofia 4096 nov  3 23:36 recursivo

13. Crear dentro de la carpeta el archivo mi_documento

cd recursivo
touch mi_documento
ls -la

Respuesta:

total 8
drwxrwxr-x 2 sofia sofia 4096 nov  3 23:38 .
drwxrwxr-x 3 sofia sofia 4096 nov  3 23:36 ..
-rw-rw-r-- 1 sofia sofia    0 nov  3 23:38 mi_documento

14. Borrar la carpeta recursivo

cd ..
rm recursivo

15. ¿Qué error se obtiene?

rm: cannot remove 'recursivo/': Is a directory

16. ¿Cómo se puede borrar la carpeta sin tener que borrar primero el
archivo que hay dentro?

rm -rf recursivo

17. Crear el directorio clase1

mkdir clase1
ls -la

Respuesta:

total 12
drwxrwxr-x 3 sofia sofia 4096 nov  3 23:43 .
drwxr-xr-x 8 sofia sofia 4096 nov  3 23:16 ..
drwxrwxr-x 2 sofia sofia 4096 nov  3 23:43 clase1

18. Entrar a la clase1

cd clase1
pwd

Respuesta:

/home/sofia/Escritorio/clase1/clase1

19. Crear el archivo hola

touch hola
ls -la

Respuesta:

total 8
drwxrwxr-x 2 sofia sofia 4096 nov  3 23:44 .
drwxrwxr-x 3 sofia sofia 4096 nov  3 23:43 ..
-rw-rw-r-- 1 sofia sofia    0 nov  3 23:44 hola

20. Crear el archivo chao

touch chao
ls -la

Respuesta:

total 8
drwxrwxr-x 2 sofia sofia 4096 nov  3 23:45 .
drwxrwxr-x 3 sofia sofia 4096 nov  3 23:43 ..
-rw-rw-r-- 1 sofia sofia    0 nov  3 23:45 chao
-rw-rw-r-- 1 sofia sofia    0 nov  3 23:44 hola

21. Borrar el archivo chao

rm chao
ls -la

Respuesta:

total 8
drwxrwxr-x 2 sofia sofia 4096 nov  3 23:46 .
drwxrwxr-x 3 sofia sofia 4096 nov  3 23:43 ..
-rw-rw-r-- 1 sofia sofia    0 nov  3 23:44 hola

22. Abrir con un editor el archivo hola y agregar “lorem ipsum”

nano hola
lorem ipsum

23. Leer el archivo desde la línea de comandos utilizando cat

cat hola

Respuesta:

lorem ipsum

24. Leer el archivo utilizando el comando less

less hola

Respuesta:

lorem ipsum
