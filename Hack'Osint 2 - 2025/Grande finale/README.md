# Write-up – HACK'OSINT 2 - Grande Finale

_Type : CTF OSINT  
Date : Mai 2025  
Classement 🥈 : **Top 2/4**_

_Réalisé en équipe de 4 avec Yukss/Emerald/Nyxou sous le nom d'équipe **OsintSpecialSquad117**_

_Tous les flags ne sont pas dans le meilleur ordre possible, mais c'est l'ordre dans lequel on les a trouvé._

## 📌 Sommaire

- [CN Solve](#1-cn-solve)
- [Site vitrine](#2-site-vitrine)
- [TocTocToc](#3-toctoctoc)
- [Mon amie](#4-mon-amie)
- [H Solve](#5-h-solve)
- [En public](#6-en-public)
- [G Solve](#7-g-solve)
- [Il etait une fois](#8-il-etait-une-fois)
- [Politique d'envoi](#9-politique-d-envoi)
- [Une passion](#10-une-passion)
- [Tout est lie](#11-tout-est-lie)
- [F Solve](#12-f-solve)
- [Bienvenue](#13-bienvenue)
- [Drôle d'individu 3](#14-drole-d-individu-3)
- [Une adresse ? Où ca ?!](#15)
- [Entree gratuite](#16-entree-gratuite)
- [Drôle d'individu 2](#17)
- [Au soleil](#18-au-soleil)
- [Drôle d'individu 1](#19)
- [Monsieur X](#20-monsieur-x)
- [Drôle d'individu 4](#21)
- [El creator](#22-el-creator)
  
### 1. CN Solve

![image](../ImagesCTF/1a.png)

> Dans la salle de Charlotte Nectoux de nombreux élément étaient reliés entre eux par des fils (éléments qui nous serviront par la suite)
> En parlant avec le directeur de Charlotte (RP) présent dans la salle on finit par savoir que la société s'appelle Mysterio et qu'elle a été crée en 2025.
> En le distrayant on arrive à récupérer le badge initialement dans sa poche et à sortir de la salle.
> Avec un lecteur RFID, son badge nous indique "ID RS AGENCE : 7481703571864978455"

![image](../ImagesCTF/11a.png)

**🎯 Flag :** `2025_7481703571864978455`

---

### 2. Site vitrine

![image](../ImagesCTF/2a.png)

> Avec la phrase récupérer grace au badge on en déduit qu'un des réseaux sociaux (ID RS) va nous aider à avancer.
> En rentrant ces numéros sur tiktok (/@7481703571864978455) on tombe sur [leur entreprise](https://www.tiktok.com/@mystoriagency).

![image](../ImagesCTF/21a.png)

> En connaissant maintenant le nom de l'entreprise complet on tombe rapidement sur leur [site](https://mystoriagency.pro/).

**🎯 Flag :** `mystoriagency.pro`

---

### 3. TocTocToc

![image](../ImagesCTF/3a.png)

> Le nom du challenge a réveillé des traumatismes encore récent, mais il fallait continuer...


**🎯 Flag :** `ENTRER VILLE`

---

### 4. Mon amie

![image](../ImagesCTF/4a.png)

> Sur le site on voit qu'on peut cliquer sur différents profils et que le nom est dans l'url.

![image](../ImagesCTF/41a.png)

> Sur cette base là on écrit charlottenectoux, on tombe bien sur son profil et sur ses relations, dont une seule lui écrit des commentaires, Anne Franck.

![image](../ImagesCTF/42a.png)

> En cliquant sur "Contacter" on récupère son adresse mail : annefranck74000@mystoria.fr et en cherchant son pseudo sur les différents réseaux on finit par tomber sur son Pinterest.

![image](../ImagesCTF/43a.png)

**🎯 Flag :** `Annelies Marie Aude Franck`

---

### 5. H Solve

![image](../ImagesCTF/5a.png)

> Nouvelle salle en physique, on récupère les informations dans la pièce et au tableau dans un premier temps, ainsi qu'une paire de jumelles.
> En regardant à travers la fenêtre on observe dehors un homme de dos en train de téléphoner, avec sur son t-shirt un site internet : Adopte un phishing.

**🎯 Flag :** `adopteunphishing`

---

### 6. En public

![image](../ImagesCTF/8a.png)

> En ayant le nom du site on cherche dans les .x les plus connus, et .eu nous donne la réponse.

![image](../ImagesCTF/81a.png)

**🎯 Flag :** `adopteunphishing.eu`

---

### 7. G Solve

![image](../ImagesCTF/6a.png)

> Encore une salle en physique, et cette fois des plus musclés !
> En cherchant et en notant là-encore tout ce qu'on voit, je finis par trouver un bout de papier caché derrière la télé.
> Avant même d'avoir eu le temps de lire la note, je me fais attraper par deux personnes capuché dans une autre salle et me retrouve à passer un interrogatoire.
> Sans le savoir les autres faisaient la même chose de l'autre coté, et nous étions jugés sur la cohérence de nos histoires.

**🎯 Flag :** `LotusBlood`

---

### 8. Il etait une fois

![image](../ImagesCTF/7a.png)

**🎯 Flag :** `Notre token`

---

### 9. Politique d'envoi

![image](../ImagesCTF/9a.png)

**🎯 Flag :** `Notre token`

---

### 10. Une passion

![image](../ImagesCTF/100a.png)

**🎯 Flag :** `Notre token`

---

### 11. Tout est lié

![image](../ImagesCTF/110a.png)

**🎯 Flag :** `Notre token`

---

### 12. F Solve

![image](../ImagesCTF/120a.png)

**🎯 Flag :** `Notre token`

---

### 13. Bienvenue

![image](../ImagesCTF/130a.png)

**🎯 Flag :** `Notre token`

---

### 14. Drôle d'individu 3

![image](../ImagesCTF/140a.png)

**🎯 Flag :** `Notre token`

---

### 15. Une adresse ? Où ca ?!

![image](../ImagesCTF/150a.png)

**🎯 Flag :** `Notre token`

---

### 16. Entree gratuite

![image](../ImagesCTF/160a.png)

**🎯 Flag :** `Notre token`

---

### 17. Drôle d'individu 2

![image](../ImagesCTF/170a.png)

**🎯 Flag :** `Notre token`

---

### 18. Au soleil

![image](../ImagesCTF/180a.png)

**🎯 Flag :** `Notre token`

---

### 19. Drôle d'individu 1

![image](../ImagesCTF/190a.png)

**🎯 Flag :** `Notre token`

---

### 20. Monsieur X

![image](../ImagesCTF/200a.png)

**🎯 Flag :** `Notre token`

---

### 21. Drôle d'individu 4

![image](../ImagesCTF/210a.png)

**🎯 Flag :** `Notre token`

---

### 22. El creator

![image](../ImagesCTF/220a.png)

**🎯 Flag :** `Notre token`

---
<!-- Hashtags pour référencement -->
#OSINT #Cybersecurity #CTF #ThreatIntelligence #Investigation #Renseignement
