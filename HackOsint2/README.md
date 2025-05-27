# Write-up – HACK'OSINT 2

_Type : CTF OSINT  
Date : Mai 2025  
Classement 🥇 : **Top 3/378** (qualifiés pour la finale)_

_Réalisé en équipe de 4 avec Yukss/Emerald/Nyxou sous le nom d'équipe **OsintSpecialSquad117**_

_Tous les flags ne sont pas dans le meilleur ordre possible, mais c'est l'ordre dans lequel on les a trouvé._

## 📌 Sommaire

- [Declare ton equipe](#1-declare-ton-equipe)
- [Remember](#2-remember)
- [Interview](#3-interview)
- [Qui es-tu](#4-qui-es-tu)
- [Pseudonyme](#5-pseudonyme)
- [Premiere approche](#6-premiere-approche)
- [Vacances entre amis](#7-vacances-entre-amis)
- [Identite](#8-identite)
- [Un chanceux](#9-un-chanceux)
- [Double identite](#10-double-identite)
- [Ou es-tu](#11-ou-es-tu)
- [Revele ton secret](#12-revele-ton-secret)
- [Combien d'Hivers ?](#13-combiendhiver)
- [Les amoureuses](#14-les-amoureuses)
- [Joyeux anniversaire](#15-joyeux-anniversaire)
- [HOTEL CALIFORNIA](#16-hotel-california)
- [CCTV](#17-cctv)
- [L'element cle](#18-lelementcle)
- [Communication](#19-communication)
- [Le cote obscur](#20-le-cote-obscur)
- [Pardon vous etes](#21-pardon-vous-etes)
- [Pseudonyme 2](#22-pseudonyme-2)
- [Home Sweet Home](#23-home-sweet-home)
- [Envole-toi](#24-envole-toi)
- [Objectif EAGLE](#25-objectif-eagle)
- [Nouvelle cible 2](#26-nouvelle-cible-2)
- [Petit bateau](#27-petit-bateau)
- [Site vitrine 1](#28-site-vitrine-1)
- [L'allie](#29-lallie)
- [Jour J](#30-jour-j)
- [Mine d'or](#31-mine-dor)
- [L'oublié(e)](#32-l-oubliee)
- [Une drole d'entreprise](#33-unedroledentreprise)
- [Site vitrine 2](#34-site-vitrine-2)
- [Discretion assuree](#35-discretion-assuree)
- [TocTocToc](#36-toctoctoc)
- [Challenge Indefini](#37-challenge-indefini)
  
### 1. Declare ton equipe

![image](https://github.com/user-attachments/assets/bbf6fe98-0739-46b6-934c-19eaf292a7e7)

**🎯 Flag :** `Notre token`

---

### 2. Remember

![image](https://github.com/user-attachments/assets/cf1cc544-f142-417b-a930-ee207400c6ae)

**🎯 Flag :** `Mettons un point final à la menace 509`

---

### 3. Interview

![image](https://github.com/user-attachments/assets/998e52e6-9b84-425a-ad71-aa1101f332b6)

> En regardant le PDF donné on trouve le [compte X](https://x.com/CN_CumSpe) et le [medium](https://medium.com/@charlotte.nectoux/about) de Charlotte Nectoux.
> On voit aussi qu'elle a fait [une interview](https://medium.com/@marcsteinerdailynews/cybers%C3%A9curit%C3%A9-le-pi%C3%A8ge-du-phishing-et-la-chute-du-groupe-509-60db7eab364e) avec Marc Steiner et sur son compte X, la date.

**🎯 Flag :** `02/02/2025`

---

### 4. Qui es-tu 

![image](https://github.com/user-attachments/assets/da10133e-c1fb-44a3-8501-215fa4016296)

> On lit juste l'interview et on voit la réponse.

**🎯 Flag :** `Nicolas de Richelieu`

---

### 5. Pseudonyme

![image](https://github.com/user-attachments/assets/bb6b7a3b-f749-41ea-a4fa-140cdc2b1a3b)

> En cherchant dans les réseaux de Nicolas, on finit par trouver son [Facebook](https://www.facebook.com/profile.php?id=61576075067801&sk=friends).
> Une photo de sa chambre y est présente dans ses stories, et dedans, un tshirt avec écrit "Xnicolasht".

![image](https://github.com/user-attachments/assets/2e4ed592-63b8-4b47-a93d-1a66dc579e56)

**🎯 Flag :** `Xnicolasht`

---

### 6. Premiere approche

![image](https://github.com/user-attachments/assets/671ad762-1539-4bae-aebe-b3a59378d6db)

> En cherchant le [Bluesky](https://web-cdn.bsky.app/profile/xnicolasht.bsky.social/) de Nicolas, on voit qu'il a posté un photo.
> Dessus une url où on ne voit pas le domaine, mais on reconnait le site de [cryptpad](https://cryptpad.fr/drive/#/2/drive/view/f3YGBpPsdLVDxwpvH+PfWsHBS2nNHpOgLwGr-VP9cHI/) .

![image](https://github.com/user-attachments/assets/d9de77f4-b130-4809-9174-bc24f372c8de)

> En regardant dans les messages dans /509/F-memory-2023-2024, on voit qu'il a commencé à parler a Foxtrot, de son vrai nom Hugo Lecomte, le 7 septembre 2023.

![image](https://github.com/user-attachments/assets/e3770440-cfdd-43c0-bb1d-f40dae65e7e2)

**🎯 Flag :** `07/09/2023`

---

### 7. Vacances entre amis

![image](https://github.com/user-attachments/assets/50949d66-944f-4898-b3d0-18c0f209c5e6)

> Toujours dans les photos du cryptpad, Foxtrot explique être parti avec #H en vacances.
> Il montre une photo d'un restaurant, qu'on peut retrouver avec un peu de GEOINT, le Dar Chef, à Marrakech

![image](https://github.com/user-attachments/assets/308557e5-27b0-4c0e-9713-722a0b73ab4c)

> En regardant sur le site https://www.flightera.net/, on trouve le bon vol

![image](https://github.com/user-attachments/assets/4e4eba61-ffdf-4410-915f-9343c9894303)

**🎯 Flag :** `Marrakech U24663`

---

### 8. Identite

![image](https://github.com/user-attachments/assets/df97c9cb-373f-472f-9759-882c758c2efa)

> En regardant les avis récents sur [TripAdvisor](https://www.tripadvisor.fr/Profile/78478HBethune) à Marrackech, on voit un certain Henry B, et dans son username HBethune.

**🎯 Flag :** `Henry Bethune`

---

### 9. Un chanceux

![image](https://github.com/user-attachments/assets/7db65d84-3823-4fc4-be67-5f9c6f4bb469)

> En regardant les dates d'arrestation on a vu qu'elles se situaient le 23 juin.
> Challenge qui nous a couté la moitié de nos fails (2), en se basant sur ces commentaires Tripadvisor qui concordaient au niveau des dates en emmenant vers le marché d'APT.
> En regardant par la suite son [carnet de voyage](https://www.myatlas.com/HenryBethune?t=user&q=Henrybethune) on a vu qu'il se trouvait au Japon, et avec les photo on voit que c'est au "Chanko & Wanko Restaurant" (avec le décalage horaire).

**🎯 Flag :** ![image](https://github.com/user-attachments/assets/2821d8ab-073e-4e17-8142-dd73cc99a5bd)

---

### 10. Double identite

![image](https://github.com/user-attachments/assets/5a129d38-75fc-4412-956c-a051f4d358b0)

> Toujours sur son carnet de voyage on peut voir qu'il a publié une photo au Japon, sur un carnet intitulé "Retour au pays natal", ce qui concorde avec un message vu dans le cryptpad où on voit un drapeau japonais.
> En traduisant le nom de la photo on tombe sur Ren Sato.

**🎯 Flag :** `Ren Sato`

---

### 11. Ou es tu

![image](https://github.com/user-attachments/assets/44c5b1f5-9611-473a-8b73-95fae7a8a75d)

> Toujours sur le [MyAtlas](https://www.myatlas.com/HenryBethune?t=user&q=Henrybethune) on voit qu'Hotel possède un compte Snapchat :

![image](https://github.com/user-attachments/assets/4500fcd6-c5ed-475f-b930-8a2249138dcb)

> En regardant ses stories on aperçoit une photo à Disneyland Paris.

**🎯 Flag :** `Disneyland Paris`

---

### 12. Revele ton secret

![image](https://github.com/user-attachments/assets/0c15427f-8e98-418f-90cb-5ca1090411dd)

> Dans une autre story Snapchat on le voit parler avec "lg-account".
> En regardant les photos publiées par cette personne on voit un numéro de téléphone sur le collier d'un chien qu'on rattache à un WhatsApp.

![image](https://github.com/user-attachments/assets/d7ca61c3-0c10-409e-b2c4-1f2577af865d)

> En bas sur la photo de profil WhatsApp on peut voir écrit "by [eliasphotography.blog](https://eliasphotography.blog/)"
> On s'inscrit à sa newsletter qui nous dit comment rentrer en contact avec lui, et en lui parlant et à l'aide des exfis des photos il finit par nous donner son nom.

![image](https://github.com/user-attachments/assets/15d775c5-2dce-4416-b867-a360267f3323)

**🎯 Flag :** `Léa Gaudreau`

---

### 13. Combien d'Hivers ?

![image](https://github.com/user-attachments/assets/ff63f579-c9f8-477f-a6a7-80e8b2e2181b)

> En ayant son nom avec une recherche rapide on trouve son compte [Instagram](https://www.instagram.com/lgaudreau_/)
> Dans sa bio, on peut voir son age

![image](https://github.com/user-attachments/assets/93fb4b4b-f69b-4ac7-b990-c8d34196ffba)

**🎯 Flag :** `27`

---

### 14. Les amoureuses

![image](https://github.com/user-attachments/assets/91ec435b-9858-4cdc-85e5-d745ac8b3b2f)

> Sur sa bio [Instagram](https://www.instagram.com/lgaudreau_/) on voit écrit "#L <3" et pareil dans une de ses stories.
> Sa photo a été prise par "Lise".
> On trouve aussi le [Google Calendar](https://calendar.google.com/calendar/u/0/embed?src=lea.gaudreau.pro@gmail.com) de Léa avec Epieos qui nous confirme des soupçons en fouillant dans les dates.
> En regardant son compte [Theads](https://www.threads.com/@lgaudreau_?xmt=AQF0UhQeU8aIylmLc6bSg25HAnaWmpZFWoG7qlX2lr_Drhw) on voit qu'elle se plaint que notre mystérieuse personne joue trop aux echecs avec une "JLMaigot" 
> Avec une recherche sur [Instant Username](https://instantusername.com/?q=JLMaigot) on trouve qu'elle à un compte [Chess.com](https://www.chess.com/member/JLMaigot) et qu'elle joue beaucoup avec une certaine "ChessM8_Saunier" (les refs KC/JL/M8.. du CTF sont marrantes).

![image](https://github.com/user-attachments/assets/69cf834a-e808-4d65-b8f3-0840470b6e1a)

> En regardant le compte de [ChessM8_Saunier](https://www.chess.com/member/chessm8_saunier) on trouve un [linktree](https://linktr.ee/m8_lsaunier).
> On a donc maintenant son nom et son prénom

**🎯 Flag :** `Lise Saunier`

---

### 15. Joyeux anniversaire

![image](https://github.com/user-attachments/assets/147883bb-87ca-44ca-a10a-6057f6046713)

> Avec le [linktree](https://linktr.ee/m8_lsaunier) on tombe sur son site [https://mymemoriegram.xyz/](https://mymemoriegram.xyz/).
> Une photo d'elle est postée où elle deux QRCode et un code barre de tatoué.
> En déchiffrant le tout (et en esquivant les QRCodes qui emmenent vers RickRoll...) on tombe sur sa carte vitale (validé par le [Google Calendar](https://calendar.google.com/calendar/u/0/embed?src=lea.gaudreau.pro@gmail.com) qui correspond au niveau de la date de naissance)
> Toutes les infos sont dans la carte il suffit de savoir la lire.

![image](https://github.com/user-attachments/assets/eba8e7a6-a17b-4db2-8d6d-945a16c2050b)

**🎯 Flag :** `14/08/1993 Vaucluse`

---

### 16. HOTEL CALIFORNIA

![image](https://github.com/user-attachments/assets/f92fea68-fa4f-4e0e-a06b-da895091d05d)

> Sur le [Theads](https://www.threads.com/@lgaudreau_?xmt=AQF0UhQeU8aIylmLc6bSg25HAnaWmpZFWoG7qlX2lr_Drhw) de November on peut voir qu'elle a séjourné dans un Airbnb avec "vue sur la dame de fer" (donc à Paris).
> Dans un autre poste on voit qu'elle vend des vêtements et avec quelques recherches on arrive à son compte [Vinted](https://www.vinted.fr/member/266597511).
> Dedans une photo d'une image d'elle avec vue sur la Tour Eiffel, on croise les infos avec "Nicolas", Airbnb, Tour Eiffel et la photo qu'on a et on tombe sur le bon [Airbnb](https://www.airbnb.fr/rooms/53885435).
> Avec StreetView on trouve les coordonnées exactes.

**🎯 Flag :** ![image](https://github.com/user-attachments/assets/287f4edd-caa0-473e-bf17-3afc0d243ae0)

---

### 17. CCTV

![image](https://github.com/user-attachments/assets/e0a0d15d-b3fa-4b52-a7b0-cb749ac614f8)

> Toujours avec le [Instagram](https://www.instagram.com/lgaudreau_/) de Léa, dans ses stories, on peut voir une photo de la boite d'un Iphone qu'elle a eu il y a un an.

![image](https://github.com/user-attachments/assets/57cc17d8-8561-437a-b429-bb63f06620c6)

> La seule donnée non floutée est le numéro de série qu'on peut trouver avec [https://checkcoverage.apple.com/?locale=fr_FR](https://checkcoverage.apple.com/?locale=fr_FR).

![image](https://github.com/user-attachments/assets/abd8f101-79ea-4a2c-8165-e3a00c2aa4d6)

> Avec le [Google Calendar](https://calendar.google.com/calendar/u/0/embed?src=lea.gaudreau.pro@gmail.com) trouvé précédemment on cherche à cette date et on voit que le weekend du 18 au 20 avril 2024 elle était à Lyon.
> On sait que c'est une fan d'apple, elle va donc acheter directement en magasin et pas à la revente, et on sait aussi qu'elle était l'après-midi dans le 3ème arrondissement.

![image](https://github.com/user-attachments/assets/1ed7667a-8360-4064-8a5d-511128afb5c9)

> Il n'y a qu'un seul AppleStore proche de cette zone.

**🎯 Flag :** `Centre commercial La Part-Dieu 17 Rue du Docteur Bouchut 69003 Lyon`

---

### 18. L'élément clé

![image](https://github.com/user-attachments/assets/9d1f4bf8-fa12-4213-9bff-bb73dce1d6e8)

> En regardant le robots.txt (guessing) du site [https://mymemoriegram.xyz/](https://mymemoriegram.xyz/) on trouve le user-agent pour aller dans /private/

![image](https://github.com/user-attachments/assets/9c5d4a2a-45dd-4ab5-80f8-669a40040fa0)

> Avec User-Agent Switcher on se connecte donc au /private/ avec le bon user et on a maintenant accès aux images.

![image](https://github.com/user-attachments/assets/2c55ae1f-e698-4928-9dff-bf6a201cc8d4)

> Dans les screen on voit que ça parle d'une application de pêche de Mike.

![image](https://github.com/user-attachments/assets/de206a6d-a8af-47e5-a430-09892c4666e1)

> En cherchant sur le PlayStore on finit par la trouver et dans l'url de appli on peut voir la réponse.

**🎯 Flag :** `com.hackosint.myapplicationn`

---

### 19. Communication

![image](https://github.com/user-attachments/assets/c79e3b15-1736-4966-aca6-a81cac1c606f)

> Dans la FishingApp, en cliquant 3x sur Info (comme écrit dans les screen trouvés dans le /private/ au-dessus) on arrive sur un chat privé.
> Depuis le début du CTF les différents membres parlent d'un moyen de communication "T" plus secure, on tente donc l'adresse Telegram [https://t.me/APT509TMP](https://t.me/APT509TMP).
> En regardant l'historique du Telegram on voit que ça a commencé le 25/04/2025.

**🎯 Flag :** `25/04/2025`

---

### 20. Le cote obscur

![image](https://github.com/user-attachments/assets/c10a9beb-4ada-4070-8142-a4a2d4ef3af9)

> En allait dans les infos de la FishingApp, il faut penser à la mettre en mode sombre, ce qui dévoilait l'adresse contact de Mike.

**🎯 Flag :** `str3etf1sher@mail.com`

---

### 21. Pardon vous etes

![image](https://github.com/user-attachments/assets/9ec27873-48c5-4dfa-a109-590581c37a3d)

> On a maintenant un pseudo, str3etf1sher, un petit coup de [tool chez Zulu](https://usercheck.oscarzulu.org/) (merci les rhinos) et on trouve son [Mastodon](https://usercheck.oscarzulu.org/).
> On sait qu'il pêche avec November, et qu'il s'appelle Fabien Daucourt (F.Daucourt sur Mastodon, et elle disait Fabien dans sa story Snapchat).

**🎯 Flag :** `Fabien Daucourt`

---

### 22. Pseudonyme 2

![image](https://github.com/user-attachments/assets/d36aad44-d37d-46c6-bde7-c14d80a7d8d4)

> Sur le [Telegram](https://t.me/APT509TMP) dans les médias il y a une image, et dessus on peut voir qu'il s'appelle G0lf7 sur Discord, et en le retrouvant on a aussi son pseudo :

![image](https://github.com/user-attachments/assets/7236a45d-bc5f-41a5-93af-f7b17df0387d)


**🎯 Flag :** `g0lf_et_apt`

---

### 23. Home Sweet Home

![image](https://github.com/user-attachments/assets/d6497df4-6b1e-4071-b2ac-9cee0d8b4e58)

> En cherchant F Daucourt en dorkant on tombe sur un [site de pêche](https://absolu-peche.fr/profil/10018-f-daucourt).
> En regardant les lieux de pêches qui correspondent à sa description (le temps, l'emplacement, la boulangerie...) on tombe sur Dun-les-Places.

![image](https://github.com/user-attachments/assets/e1cae938-ff3c-4900-87dc-c3b2bcef1526)

**🎯 Flag :** `Dun-les-Places`

---

### 24. Envole-toi

![image](https://github.com/user-attachments/assets/a6f58d73-afb7-4ff9-aa8f-d431dd26a9bb)

> Sur le [Telegram](https://t.me/APT509TMP), il y avait aussi un lien [Cryptpad](https://cryptpad.fr/drive/#/2/drive/edit/l2MS2EEV9OuI0mEnOo2rW7Xw/p/) avec un mot de passe, qu'on pouvait retrouver dans la conversation entre November et Bravo.

![image](https://github.com/user-attachments/assets/fe05ce4c-1d67-4dd6-89e3-e85742eff9cd)

> Dans le Drive, en allant dans CYBERBUNKER, on trouve une lien [Vimeo](https://vimeo.com/1079165051/4addc0ed2c?share=copy).

> En faisant un reverse image du batiment sur la droite :

![image](https://github.com/user-attachments/assets/9e602003-a250-4cbb-bd36-704bcc25e0de)

> On tombe sur [plusieurs site](https://www.naturimages.com/en/photo-essays/environment/saint-honore-1500---ski-resort-in-isere-abandoned-by-developers-enx1addedac7110000000001208.htm) parlant de Saint Honoré 1500.
> Sur Maps je m'assure que ça soit le bon endroit à l'aide du mur tagué qu'on voit au début de la vidéo.

![image](https://github.com/user-attachments/assets/ade60016-8c41-44d2-aa3e-c0aefda05ad8)

> En regardant où est le mur par rapport au drône on peut voir sur Maps que ça correspond à peu près au parking de Saint-Honoré.
> Au début de la vidéo on entend le bruit d'une voiture qui se gare, c'est donc le bon endroit.

**🎯 Flag :** ![image](https://github.com/user-attachments/assets/89faf6ff-ab6f-4079-800c-843ee0c9e557)

---

### 25. Objectif EAGLE

![image](https://github.com/user-attachments/assets/7907353f-20ec-4636-84de-aad82e34477d)

> Au bruit du drône qui décolle on sait que c'est un DJI, reste à trouver lequel.
> En sachant que le drône avait un Zoom x28, et au son au moment de l'envole, avec deux trois recherches Youtube on trouve le bon drône.

**🎯 Flag :** `DJI Mavic 3`

---

### 26. Nouvelle cible 2

![image](https://github.com/user-attachments/assets/a6e9de8e-83e2-4ed8-8c74-bdadb6130db1)

> Toujours dans le [Cryptpad](https://cryptpad.fr/drive/#/2/drive/edit/l2MS2EEV9OuI0mEnOo2rW7Xw/p/) on voit dans Target un PDF qui contient l'emplacement de leur cible.
> On enleve le filigrane pour une lecture plus simple.

![image](https://github.com/user-attachments/assets/413a785b-ecc1-46bd-adf1-1133c5439182)

> On peut voir une gare, des ronds points, et surtout à coté de la gare un grand parvis/jardin avec une structure particulière.
> En cherchant on finit par trouver la gare de Reims.

Sur Maps, on peut reconnaitre facilement deux endroits collés au point rouge : 

![image](https://github.com/user-attachments/assets/82a5a9ea-e077-4ea5-bb3a-f5109016aee8)

> On trouve donc que c'est le CIC.

![image](https://github.com/user-attachments/assets/efb991d1-70ad-49a5-a5a4-addf9dd5165e)

**🎯 Flag :** `Crédit Industriel et Commercial`

---

### 27. Petit bateau

![image](https://github.com/user-attachments/assets/b501dd21-1d5e-4e2c-8ba3-99b16b23f3e3)

> Sur la page [absolute peche](https://absolu-peche.fr/profil/10018-f-daucourt) de Fabien, on voit un nom : "Seashell Injection".
> En le cherchant sur [Marine traffic](https://www.marinetraffic.com/en/ais/details/ships/shipid:9565794/mmsi:912010044/imo:0/vessel:SEASHELL_INJECTION#overview), on voit que son call sign est APT509, ce qui confirme que c'est le bateau qu'on cherche.
> Juste à coté, son MMSI.

**🎯 Flag :** `912010044`

---

### 28. Site vitrine 1

![image](https://github.com/user-attachments/assets/61731272-179b-4a2b-9dea-3db2750f2952)

> Dans les vessel characteristics du site [Marine traffic](https://www.marinetraffic.com/en/ais/details/ships/shipid:9565794/mmsi:912010044/imo:0/vessel:SEASHELL_INJECTION#overview), on trouve une url : https://loueuneencre.online

**🎯 Flag :** `loueuneencre.online`

---

### 29. L'allié

![image](https://github.com/user-attachments/assets/72d3878a-e17b-48a4-b2de-dd87b6527227)

> En guessing, on a trouvé que [https://loueuneencre.online/dashboard.html](https://loueuneencre.online/dashboard.html) fonctionnait.
> En fouillant dans les commande disponible, on tente alerte :

![image](https://github.com/user-attachments/assets/608c8665-81a1-432e-8f12-066bb23eeb61)

> Le "view logs" ne semble pas cliquable dans un premier temps mais avec un clic molette (nouvelle onglet), on arrive à atteindre les archives (source croisée avec celle du code source).

![image](https://github.com/user-attachments/assets/34c26720-289d-4707-98c2-68b05d3d131e)

![image](https://github.com/user-attachments/assets/cc3e0d34-af10-43e4-a03d-62ed9d6a9d56)

**🎯 Flag :** `3ND0FW47CH509`

---

### 30. Jour J

![image](https://github.com/user-attachments/assets/5314dc31-d5d0-4489-8d63-afd414b507e6)

> Dans le dossier Target, il y avait aussi un fichier "daterevendication-secure.glb"
> En l'ouvrant on voit un renard avec plein de mots en Japonais dessus.
> Sous ses pattes, une date.

**🎯 Flag :** `17/07/2025`

---

### 31. Mine d'or

![image](https://github.com/user-attachments/assets/3a1e5716-3edd-4666-a27c-6730c42ea799)

> On sait maintenant le pseudo qu'on cherche, en voyant le format du flag ".carotte" on a su qu'il faudrait un .onion (pour Tor par exemple).
> Un site qui est souvent associé un .onion est Pastebin, et en cherchant à l'url https://pastebin.com/u/3ND0FW47CH509 puis [https://pastebin.com/u/3ND0FW47CH](https://pastebin.com/u/3ND0FW47CH) on tombe sur le sien.
> A l'intérieur une note :

![image](https://github.com/user-attachments/assets/678154b6-6e3e-4fcd-8eb1-1c06c554e254)

> On dechiffre avec [CyberChef](https://gchq.github.io/CyberChef/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true,false)&input=YnpJMGNITjNkMkp3YW5wNU5taGpNelp0Wm1KNGNIazJlSEZoZVhrM1kzUmhOSGMxZUdadmIzSjBkM1psYUdJeU56SmxaV1ZtZVdRPQ&oeol=FF), et on recupère l'adresse onion.

**🎯 Flag :** `o24pswwbpjzy6hc36mfbxpy6xqayy7cta4w5xfoortwvehb272eeefyd`

---

### 32. L'oublié(e)

![image](https://github.com/user-attachments/assets/0ed1e4ac-726d-46a9-8cf9-0c53d2786c64)

> En arrivant sur le .onion on tombe sur un site ou on n'a acces à rien.

![image](https://github.com/user-attachments/assets/267004ac-508b-49e8-a191-932f0fa44e88)

> En regardant dans le code source on voit une balise "access-blocker", et en la retirant dans "Inspecter", on arrive à tout voir.

![image](https://github.com/user-attachments/assets/0f947c3b-1cb4-4dbe-9e98-30f0ad032352)

> Il fallait ensuite penser à aller sur [archive.js](https://archive.ph/mRpDW) pour regarder un snapshot du site où on voit toutes les informations qu'il nous manquait.

![image](https://github.com/user-attachments/assets/27c7ede9-39de-43a2-81e9-7644b0408054)

**🎯 Flag :** `Kilo chargée d’intelligence sociale`

---

### 33. Une drôle d'entreprise

![image](https://github.com/user-attachments/assets/ed597868-097a-49ad-b5b1-d7db2eee28d8)

> Dans le [Cryptpad](https://cryptpad.fr/drive/#/2/drive/edit/l2MS2EEV9OuI0mEnOo2rW7Xw/p/) toujours, il y a un devis (format .docx)
> En analysant les metadadonnées du document on trouve "destinataire : betaoespatulaparker"

**🎯 Flag :** `Betao Espatula Parker`

---

### 34. Site vitrine 2

![image](https://github.com/user-attachments/assets/0c2061fd-af18-43db-acd5-cbaf8ba1111b)

> Avec le nom qu'on a maintenant on va voir sur [Whoxy](https://www.whoxy.com/keyword/betaoespatulaparker)
> On trouve deux domaines qu'on cherche sur [Censys](https://search.censys.io/search?resource=hosts&sort=RELEVANCE&per_page=25&virtual_hosts=EXCLUDE&q=betaoespatulaparker.eu)

![image](https://github.com/user-attachments/assets/7a5252b0-eae8-484a-91ef-e38bef2662df)

![image](https://github.com/user-attachments/assets/4c7011bc-9a9c-4726-8316-370ed4576783)

> On a donc l'adresse [vmi](http://vmi2561640.contaboserver.net/) qui nous envoie vers le site, ce qui valide ce qu'on avait au-dessus.


**🎯 Flag :** `betaoespatulaparker.eu`

---

### 35. Discretion assuree

![image](https://github.com/user-attachments/assets/468d5b4b-3e47-44a3-969e-a9ab1cd27691)

> En repartant du site qu'on vient de trouver, on regarde le /robots.txt

![image](https://github.com/user-attachments/assets/6b4a61e7-ba07-4af3-8acb-5a99eb1509a7)

> On trouve un /index.php accessible et en cherchant dedans on trouve des comptes rendus de réunion (en esquivant encore un rickroll).

![image](https://github.com/user-attachments/assets/bc73c2c2-fc59-4bef-8ad0-a7d8059d6b58)

> Après avoir abandonné le code du lieu ne sachant pas quoi en faire, on a décidé de s'y replonger dessus.
> On finit par trouver que c'est du geocode et on tombe sur [mapcode](https://www.mapcode.com/)
> Après s'être rendu dans le North Dakota on a finit par se dire que le XXX dans le .txt à coté du code pourrait signifier FRA.
> On tape le code, et on tombe sur une petite cabane isolée en France.

**🎯 Flag :** ![image](https://github.com/user-attachments/assets/09e16ccb-6ec1-4bba-9af5-c9eee0447754)

---

### 36. TocTocToc

![image](https://github.com/user-attachments/assets/9f7fd6e8-7c8b-44a1-8e35-afcf5fc68e5d)

> On arrive au pire challenge, qu'on a eu très rapidement au début du CTF, et qui a donné mal au crâne à 99% des participants (j'entends encore le bruit dans ma tête).
> On reprend tout ce qu'on savait sur Nicolas, son [Facebook](https://www.facebook.com/profile.php?id=61576075067801&sk=friends), son [Bluesky](https://web-cdn.bsky.app/profile/xnicolasht.bsky.social/) et les informations du [cryptpad](https://cryptpad.fr/drive/#/2/drive/view/f3YGBpPsdLVDxwpvH+PfWsHBS2nNHpOgLwGr-VP9cHI/).
> La résolution va paraitre simple mais avant de savoir vraiment quoi chercher ça partait dans tout les sens.
> En cherchant Lycée privé Saint-Joseph, on en trouve 4 dans l'Ain : à Bourg-en-Bresse, Oyonnax, Saint-Didier-sur-Chalaronne et Miribel.
> C'est parti pour rechercher sur [WayBack](https://web.archive.org/) dans les actualités des 4 sites des 4 villes...
> On finit par trouver un snapshot pour Miribel qui parle de la rue Pellera.
> Dans [StreetView](![image](https://github.com/user-attachments/assets/e424258b-416d-4d77-9277-3dcb8698d7aa) on retrouve une maison en construction en 2023 qui correspond à tout ce qu'on avait comme information.

**🎯 Flag :** ![image](https://github.com/user-attachments/assets/a815f9fa-462b-407f-8724-fe2bf3f1aab0)

---

### 37. Challenge Indefini

![image](https://github.com/user-attachments/assets/ec750380-5d97-40c9-ba20-374896bb2377)

> Fin du CTF !

**🎯 Flag :** `EndOfWatch`

---
<!-- Hashtags pour référencement -->
#OSINT #Cybersecurity #CTF #ThreatIntelligence #Investigation #Renseignement
