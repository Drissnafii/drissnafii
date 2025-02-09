<div align="center">

![](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=18&duration=2000&pause=1000&color=00FF00&center=true&vCenter=true&multiline=true&repeat=false&width=600&height=100&lines=Initializing+Developer+Profile...;System+Status%3A+Online;Loading+...+...)
 </div>
<div align="center">
    
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:drissnafi3@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/driss-nafii-333379248/)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/drissnafii)


usecaseDiagram

actor Visiteur
actor UtilisateurInscrit
actor Administrateur

Visiteur --> [VoirVilles]
Visiteur --> [VoirStades]
Visiteur --> [VoirMatches]
Visiteur --> [VoirInfosBasiques]
Visiteur --> [Inscription]
Visiteur --> [Connexion]

UtilisateurInscrit --> [EnregistrerFavoris]
UtilisateurInscrit --> [VoirInfosDetaillees]
UtilisateurInscrit --> [AccederInfosTransport]
UtilisateurInscrit --> [VoirHebergements]
UtilisateurInscrit --> [VoirInfosCulturelles]
UtilisateurInscrit --> [LireArticles]
UtilisateurInscrit --> [GererProfil]

Administrateur --> [GererVilles]
Administrateur --> [GererStades]
Administrateur --> [GererMatches]
Administrateur --> [GererArticles]
Administrateur --> [GererHebergements]
Administrateur --> [GererUtilisateurs]
Administrateur --> [VoirAnalytiques]
