# dolitiers
Hello, I'm not in informatics, this is part of a Dolibarr fork for you to have 1 Dolibarr for you and 1 Dolibarr for third part. I'll put the images and the installation suggestion. But not Dolibarr. The only files you will find here are my images.

Download your Dolibarr from official GIT.
sudo mv dolibarr dolitiers
sudo mv dolitiers /var/www/html
sudo chmod -R 777 /var/www/html/dolitiers/doc/images/
sudo chmod -R 777 /var/www/html/dolitiers/htdocs/theme/
sudo mv -f /home/USER/whatever/images/ /var/www/html/dolitiers/doc/images/
sudo mv -f /home/USER/whatever/theme/ /var/www/html/dolitiers/htdocs/theme/
*Your chmod and mv folder may be different then mine, please check.
sudo chmod -R 755 /var/www/html/dolitiers/doc/images/
sudo chmod -R 755 /var/www/html/dolitiers/htdocs/theme/
sudo chown -R root:root /var/www/html/dolitiers/doc/images
sudo chown -R root:root /var/www/html/dolitiers/htdocs/theme/
Installation advices:
New database > dolitiers + utf8_general_ci
PhpMyAdmin > User Accounts > Add user account new user
database: dolitiers > Privilèges : Edit Privilèges > database > Database Specific Privileges for new user
Install as usual
Make sure default database is dolitiers
Make sure default user folder is different from your first dolibarr
Like that you can take care if ever you need of other business sales and keep both Dolibarr and Dolitiers without confusion.





