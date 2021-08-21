# Object-Storage-Symfony-Flysystem-Minio
Création d'un service d'object storage de type AWS-S3 dockérisé pour Symfony 5

### Environnement de développement
* PHP 7
* MySQL
* Composer
* Symfony CLI
* Docker
* Docker-compose

### Bundles & librairies
* Minio (https://min.io/)
* Flysystem-bundle
* flysystem-aws-s3-v3
* VichUploader
* EasyAdmin

### URL's
Projet : http://127.0.0.1:8000
Minio : http://127.0.0.1:9000

### Lancer l'environnement de développement
```bash
composer install
docker-compose up -d
symfony serve -d
```
