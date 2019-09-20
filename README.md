## Acerca

Un script para instalar PhpMyAdmin en Laravel Homestead

## Uso

1. Ingresar via SSH a Homestead `homestead ssh` or `vagrant ssh`

2. `cd` al directorio de los proyecto (by default `~/code`)

3. `$ curl -sS https://raw.githubusercontent.com/grrnikos/pma/master/pma.sh | sh`

4. Abrir `/etc/hosts` en la máquina host y agregar `192.168.10.10  phpmyadmin.test`

5. Mapear /home/vagrant/code/phpmyadmin to phpmyadmn.test en el archivo yaml de homestead

6. Ejecutar vagrant provision. Para recargar el nginx de vagrant

5. Ir a [http://phpmyadmin.test](http://phpmyadmin.test). El usuario es `homestead` y el password `secret`

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

## Nota
9/2019 : Probado en Homestead beta
