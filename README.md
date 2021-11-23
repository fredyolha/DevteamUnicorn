# DevteamUnicorn

1. Instalacia GIT-u
https://git-scm.com/download/win

2. Generacia SSH kluca 
a. Otvorit Git bash (to je to co sa instalovalo predtym)
b. V git bashi: ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
c. Na vsetky otazky nechat defaultne hodnoty (len stlacte enter enter enter)
d. V zlozke C:/Users/<tvojUser>/.ssh sa vytvoria 2 subory (id_rsa a id_rsa.pub)

3. Pridanie SSH kluca do GitHubu
a. Otvorit https://github.com/settings/keys
b. Klik na "New SSH key"
c. Vlozit tam kompletny obsah id_rsa.pub suboru z 2d
d. Tot vse 

4. Stiahnutie repozitara
V git bash pouzit prikaz "git clone" -> git clone git@github.com:fredyolha/DevteamUnicorn.git

5. Zmena suborov a ich upload
Zmente ktorykolvek textovy subor alebo pridajte novy 
Prikaz "git add --all" urci ze vsetky zmeny sa pridaju do commitu
Prikaz "git commit -m "Nejaky commit message"" vytvori commit ktory budete schopny "uploadnut"
Prikaz "git push" odosle zmeny na server

6. Aktualizacia lokalneho priecinka pokial niekto urobi zmeny
Prikaz "Git pull"

