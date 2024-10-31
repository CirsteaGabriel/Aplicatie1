# Introduction 
Acesta este un exemplu de test pentru echipele DEV cu utilizarea platformei Azure DevOps Server.
# Ce este Azure DevOps Server?
Azure DevOps Server oferă numeroase beneficii pentru echipele de dezvoltare software, facilitând colaborarea și gestionarea eficientă a proiectelor. Este replica On-premise a serviciului Azure DevOps Service din Cloud-ul Microsoft.

# Utilizare
Se pot utiliza urm[toarele:
1. Controlul versiunilor:
        Oferă suport pentru două tipuri de control al versiunilor: Team Foundation Version Control (TFVC) și Git, permițând gestionarea eficientă a codului sursă.
2.	Managementul proiectelor:
        Managementul proiectelor: Include instrumente pentru gestionarea cerințelor, planificarea și urmărirea progresului proiectelor, fiind adaptabil atât pentru metodologiile agile, cât și pentru cele tradiționale basic, Scrum etc...
3.	Automatizarea proceselor:
        Azure DevOps Server permite configurarea de build-uri automate, teste și managementul lansărilor, facilitând livrarea continuă a software-ului.
4.	Integrarea cu alte instrumente:
        Se poate integra cu diverse medii de dezvoltare (IDE-uri) și servicii externe prin API-uri deschise, precum REST API   etc.
5.  Planificare și testare:
        Oferă Azure Boards pentru planificarea muncii și Azure Test Plans pentru testarea aplicațiilor, asigurându-se că produsele livrate sunt de calitate.
6.  Raportare și analiză:
        Permite generarea de rapoarte complexe și analize prin integrarea cu SQL Server Reporting Services și alte instrumente de raportare.


# Beneficii

1.  Control total asupra datelor:
        Putem obtine control uniformizat si complet asupra infrastructurii și datelor, ceea ce este esențial pentru reglementări stricte privind securitatea codurilor.
2.  Flexibilitate în personalizare: 
        Azure DevOps Server permite personalizarea proceselor de lucru prin modele de proces bazate pe XML sau prin interfața grafică, adaptându-se nevoilor specifice ale echipelor.
3.  Scalabilitate:
        Server-ul central poate fi scalat pentru a sustine multiple proiecte in paralele. 
4.  Securitate:
        Server-ul are realizate implementarile de securitate specifice sysadmin si se bazeaza pe masurile avansate de la Microsoft.
5.  Flexibilitate:
        Existenta unui hub central de proiecte si utilizatori + gestionare uniformizata si centralizata faciliteaza adaptarea rapida la modificarea echipelor si acordarea de sprijin intre echipe la diferite proiecte.

        
# Build and Test
    Codul cuprinde un build clasic de aplicatie si 2 pipeline-uri pentrru testare automata.
    Acestea sunt declansate de modificarea in `main-ul` repo-ului.

