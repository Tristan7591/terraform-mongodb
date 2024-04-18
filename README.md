# terraform-mongodb
simple terraform mongodb deployment
Prérequis:
-un compte mongodb 
-un utilisateur mongodb avec les permissions
-Clé API a créer sur mongodb (C'est lors de la création de l'API que les accès seront donnée: private_key, public_key, org_id)
!! Il et probable que la version free de mongodb limite certainnes possibilités de deploiement. 
Template minimaliste
!! Bien configurer le fichier .tfvars au risque de devoir a chaque terrafrom plan et terraform apply devoir rentrer manuellement les clées et org_id!!
Ceci est réaliser dans le cadre d'un entrainement et n'est pas optimiser pour de la production.
