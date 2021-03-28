# CR

28/03/2021 08:42

# Roles
- Zak est le résponsable de cette journée et on ne fait RIEN sans son accord
- Isma est son backup et s'occupe de côté DATA
- Juju du contrôle et dispatch vers les PP
- Je suis en contact avec AIV pour me synchroniser avec eux et tester à la fin

** EN CAS DE PROBLEME, JM PREND LES DECISIONS (avec Zak et Isma)
Moi je ne serais pas à la maison toute la journée mais tjs up sur Team et je prends mon laptop avec moi.

# Steps
- [X] 8H30 : Isma coupe les cron
- [X] 8h30 : JMS contact AIV pour couper le flux
- [X] 9h00 : Juju check les PP
- [X] 10h00 : Zak commence es mise à jour
- ......
- 

# COTE FD
-----------------------
## A FAIRE AVANT MAJ ##
- [X] désactivation crontab api 
- [X] désactiver crontab DOCDROP 
- [X] désactiver crontab printgen 
- [X] désactiver crontab affligem
- [X] kill consumers avant MAJ
- [ ] commencer MAJ par RABBITMQ afin de le relancer au plus vite et ne pas perdre de messages

## A FAIRE APRES ##
- [ ] remettre crontab API
- [ ] remettre crontab DOCDROP
- [ ] remettre crontab pritngen
- [ ] remettre crontab affligem
- [ ] relancer consumers

