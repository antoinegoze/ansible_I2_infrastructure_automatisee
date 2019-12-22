------------------------------------------------------------------------------------------------

# PROJET ANSIBLE | EQUIPE 3 | OPTION CC 

================================================================================================

Ce projet ansible permet d'exécuter le déploiement de notre infrastructure.


Pour déployer le projet, tapez la commande :
$ ansible-playbook -i /etc/ansible/hosts infra.yml

Pour déployer une sous-partie de l'infrastructure, se référer aux groupes dans le fichier d'inventaire, et tapez la commande :
$ ansible-playbook -i /etc/ansible/hosts infra.yml --limit 


------------------------------------------------------------------------------------------------

## RESUME

------------------------------------------------------------------------------------------------

Pour rappel, notre projet vise à déployer 2 principaux services pour les utilisateurs, à savoir :
1) un service Apache hébergeant tout type d'applications web
2) un service Tomcat hébergeant des applications java pour les développeurs


Notre solution met en évidence 3 différents types d'utilisateurs :
1) Les utilisateurs : droit d'accès aux services minimaux
2) Les admins service : droits d'accès aux services minimaux, et droit d'édition de certains fichiers
3) Les admins system : droits d'accès, d'édition et de création de nouveaux services


Cette solution doit répondre aux différents aspects de management de tout SI, à savoir :
1) La disponibilité des services
2) La sécurité de l'infrastructure
3) La maintenance et l'évolutivité de l'infrastructure
4) La supervision de l'infrastructure
5) La sauvegarde des éléments importants




----------------------------------------------------------------------------------------------------
## ANSIBLE DOC
----------------------------------------------------------------------------------------------------

Un lien vers la doc ansible si besoin : https://docs.ansible.com/ansible/latest/
Vous retrouverez toute la documentation liée à notre projet dans OpenProject


----------------------------------------------------------------------------------------------------
## REFERENCES
----------------------------------------------------------------------------------------------------

Nous avons fait de notre mieux pour respecter les bonnes pratiques ansible pour vous permettre de le réutiliser, en se rérérent à des conventions comme :
https://docs.ansible.com/ansible/latest/user_guide/playbooks_best_practices.html
https://github.com/ansible/ansible-examples
