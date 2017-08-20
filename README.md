## About

Simple shell script that automatically installs the latest version of PhpMyAdmin
on a Laravel Homestead box.

## Usage

1. SSH into your Homestead box `homestead ssh` or `vagrant ssh`

2. `cd` to your code/projects directory (by default `~/Code`)

3. `$ curl -sS https://raw.githubusercontent.com/grrnikos/pma/master/pma.sh | sh`

4. Open the `/etc/hosts` file on your main machine and add `127.0.0.1  phpmyadmin.app`

5. Go to [http://phpmyadmin.app:8000](http://phpmyadmin.app:8000). Default credentials are username `homestead` and password `secret`

In Homestead 3.0:

use systemctl restart nginx.service and reconfigure https liste phpmyadmin.app config

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
