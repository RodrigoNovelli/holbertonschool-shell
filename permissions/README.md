0-iam_Betty su (su + username) changes username
1--who_im id -un (identificar username)
2- id -nG for user groups
3- CHANGE FILE owner, chown (user) (file)
4-empty touch hello
5-execute chmod u+x hello
6- 754 (rwxr-xr--)
7- +x (agraga permisos de ejecutar a todos) 
8- 007 (solo permisos comoletos a other)
9- 753 (rwxr-x-wx)
10- MIRROR PERMISSIONS chmode --reference=fileref file
11- chmod -R (para q sea todas) +x (agregar ex) */ (todos los sub d la carp actual)
12- mkdir -m (gives the permissions with this parameter) 777 dirname
13- chgrp (cambiar de grupo) new group and file
14- chown-R new.user:newgroup
15- chown -h (-h para q sepa q es un symb link) user:group file
