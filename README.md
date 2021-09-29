# Configuration d'un proxy nginx pour linshare	

ce dépot a pour vocation de remplacer la configuration contenant 3 nom de domaine pour la version 4.2.2 de Linshare
par un proxy Nginx avec une seul adresse IP ou URL


	linshare-user.local devient http://IP/ 
	linshare-admin.local devient http://IP/admin
	linshare-upload-request.local devient http://IP/upload

le fichier hosts du serveur est malgrés tout à surcharger avec le script maj_host.sh pour faire les correspondances locales

Le site devra par la suite être paramettré au niveau de la configuration pour modifier l'url dans les mails envoyés à l'utilisateur

dans l'admin - fonctionnalités - url anonymes - URL de notification courriel
et dans fonctionnalités -domaines - URL de bases pour les notifications.





