# dolitiers
Hello, I'm not in informatics, this is part of a Dolibarr fork for you to have 1 Dolibarr for you and 1 Dolibarr for third party. I'll put the images and the installation suggestion. But not Dolibarr. The only files you will find here are my images. I can't help with the install as I'm not a professional. Please don't copy paste Dolibarr in here as I don't have the rights. But you can copy the Dolitiers images to your fork, no problem. And create your Dolitiers. You can also propose your art images as mine aren't art, it's just the T letter over the D of Dolibarr for the eye not to get confusion with two Dolibarrs.

## Image customization of Dolitiers
- Download your Dolibarr from official GIT.
- sudo mv dolibarr dolitiers
- sudo mv dolitiers /var/www/html
- sudo chmod -R 777 /var/www/html/dolitiers/doc/images/
- sudo chmod -R 777 /var/www/html/dolitiers/htdocs/theme/
- sudo mv -f /home/USER/whatever/images/ /var/www/html/dolitiers/doc/images/
- sudo mv -f /home/USER/whatever/theme/ /var/www/html/dolitiers/htdocs/theme/
- *Your chmod and mv folder may be different then mine, please check.
- sudo chmod -R 755 /var/www/html/dolitiers/doc/images/
- sudo chmod -R 755 /var/www/html/dolitiers/htdocs/theme/
- sudo chown -R root:root /var/www/html/dolitiers/doc/images
- sudo chown -R root:root /var/www/html/dolitiers/htdocs/theme/
## Installation advice for Dolitiers
- It's important to create dolitiers database, to separate its data from your dolibarr database.
- New database > dolitiers + utf8_general_ci
- PhpMyAdmin > User Accounts > Add user account new user
- database: dolitiers > Privilèges : Edit Privilèges > database > Database Specific Privileges for new user
- Install as usual and add new user (same as created) at the end of installation.
- Make sure default database is dolitiers ! Important.
- Make sure default user folder is different from your first dolibarr ! Important.
- Like that you can take care if ever you need of other business sales and keep both Dolibarr and Dolitiers without confusion.

## Legal advice to copy-paste

Whether the applicant, employer or client is an individual, a third party individual entrepreneur or a company, if COMPANY NAME or individual entrepreneur CONTRACTOR NAME F/M accepts or enters into a contract with a third party. And it turns out that there is an unproven suspicion that the service provision:
- induces the company manager to commit actions that may be liable to be illegal in the countries concerned
- damages its reputation
- involves taking a physiological, physical, psychological, social or moral risk
-> Then the individual entrepreneur CONTRACTOR NAME F/M or his company NAME OF THE COMPANY will immediately cease the provision of service. And the individual or the third party individual entrepreneur or the company will owe him the full amount of the service requested or accepted, but the service will no longer be performed and will be without results and without achievement. The only justification will be endangering the service provider.

Que le demandeur, l’employeur ou le client soit un particulier, un entrepreneur individuel tiers ou une entreprise, si NOM DE L'ENTREPRISE ou l’entrepreneur individuel NOM DE L'ENTREPRENEUR F/H accepte ou pose un contrat avec un tiers. Et qu’il s’avère qu’il y ait une suspicion sans preuves que la prestation de service :
- induit la/le chef d’entreprise à commetre des actions pouvant être suceptibles d’être illégales dans les pays concernés
- nuit à sa réputation
- implique une prise de risque physiologique, physique, psychologique, social ou moral
-> Alors l’entrepreneur individuel NOM DE L'ENTREPRENEUR F/H ou son entreprise NOM DE L'ENTREPRISE cesseront sur le champ la prestation de service. Et le particulier ou l’entrepreneur individuel tiers ou l’entreprise lui devront la totalité de la somme de la prestation de service demandée ou acceptée, mais la prestation de service ne sera plus exécutée et sera sans résultats et sans réalisation. La seule justification sera mise en danger du prestataire de services.




