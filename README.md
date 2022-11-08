# WIK-DPS-TP03
    DevOps TP 3: Créer un docker-compose avec le tp précédent

##  SOMMAIRE
- [WIK-DPS-TP03](#wik-dps-tp03)
  - [SOMMAIRE](#sommaire)
  - [I. Sujet (checkList)](#i-sujet-checklist)
  

## I. Sujet (checkList)

- [ ] Créer un docker-compose avec pour seul service un container basé sur le Dockerfile créé dans le TP [WIK-DPS-TP02](https://github.com/Hyuga974/WIK-DPS-TP02.git)
- [ ] Augmenter le nombre de réplicas à 4 pour ce service
- [ ] Ajouter un reverse-proxy (nginx), 
  - [ ] seule le reverse-proxy doit être exposé sur votre hôte sur le port 8080
- [ ] Configurer nginx (nginx.conf) pour loadbalancer les requêtes vers le service basé sur votre image
- [ ] Modifier le code de votre API pour 
  - [ ] Afficher le hostname dans les logs à chaque requête sur /ping, 
  - [ ] Lancer votre docker-compose.yaml 
  - [ ] Observer l'effet du l'équilibrage de charge