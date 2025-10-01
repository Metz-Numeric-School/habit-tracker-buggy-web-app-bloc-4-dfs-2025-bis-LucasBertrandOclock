# Procédure de Déploiement

Décrivez ci-dessous votre procédure de déploiement en détaillant chacune des étapes. De la préparation du VPS à la méthodologie de déploiement continu.

## Préparation du VPS

- Connexion au VPS en ssh (ssh root@172.17.4.24)
- Instalation de git sur le VPS : ```sudo apt-get install git```
- Installation de aaPanel : ```URL=https://www.aapanel.com/script/install_7.0_en.sh && if [ -f /usr/bin/curl ];then curl -ksSO "$URL" ;else wget --no-check-certificate -O install_7.0_en.sh "$URL";fi;bash install_7.0_en.sh aapanel```
- Déplacement dans le dossier wwwroot : cd /www/wwwroot/

## Méthode de déploiement

Todo...
