# Write-up – Medileak 2

_Type : CTF OSINT  
Date : Mai 2025  
Classement 🥇 : **Top 17/134** en étant premier des personnes seules (équipe de 4 sinon)
Réalisé en solo sous le nom d'équipe **OneForAll** (même si je dis nous/je/on)_

_Tous les drapeaux ne sont pas dans le meilleur ordre possible, mais c'est l'ordre dans lequel je les ai trouvé._

## 📌 Sommaire

- [#Intro](#1-intro)
- [#legacy](#2-legacy)
- [#reboot](#3-reboot)
- [#notcyprus](#4-notcyprus)
- [fanclub](#5-fanclub)
- [NewJob](#6-newjob)
- [IciCaRecrute](#7-icicarecrute)
- [#NewPartner](#8-newpartner)
- [#Historique](#9-historique)
- [#MauvaiseNouvelle](#10-mauvaisenouvelle)
- [#TropTard](#11-troptard)
- [#Source](#12-source)
- [#Modem](#13-modem)
- [#medileak](#14-medileak)
- [#TeamFLS-1](#15-teamfls-1)
- [#TeamFLS-2](#16-teamfls-2)
- [#Hack](#17-hack)
- [#MasterMind](#18-mastermind)
- [#backtobusiness](#19-backtobusiness)
- [#MaisonMère](#20-maisonmère)
- [#MaiSonPère](#21-maisonpère)
- [#MaisonChère](#22-maisonchère)
- [#TeamFLS-3](#23-teamfls-3)
- [#RadioGaga](#24-radiogaga)
- [#MeetMe](#25-meetme)
- [#Halftime](#26-halftime)
- [#PasSympa](#27-passympa)
- [#Soldes](#28-soldes)
- [#AvisNégatif](#29-avisnegatif)
- [#Fl4G(Bonus)](#30-flag)
- [#OldLove](#31-oldlove)
- [#Clochint (Bonus)](#32-clochint)
- [#Insécurité](#33-insecurite)
- [#LesBonsComptes](#34-lesbonscomptes)
- [#Mission](#35-mission)
- [#IA](#36-ia)
- [#Malins](#37-ia)
- [#SoyonsDésinvoltes](#38-soyonsdesinvoltes)
- [#HomeSick](#39-homesick)
- [#END](#40-end)
- [Tous les challenges](#tous-les-challenges)
- [Toutes les techniques utilisées](#toutes-les-techniques-utilisees)
  
### 1. #Intro
 
>  Réponse dans la phrase, il suffit de la réécrire

![image](https://github.com/user-attachments/assets/2fd6bb70-b5d5-40ec-8544-668dfa8b9851)

**🎯 Flag :** `Surtout pas de cloches`

---

### 2. #legacy

![image](https://github.com/user-attachments/assets/b790f348-da02-41f6-aa98-e87b4a374f98)  

> Dans ce cas, il suffit de revenir à l'ancienne description du premier [Medileak](https://oscarzulu.org/wu-medileak/) et de trouver le nom à l'intérieur.

![image](https://github.com/user-attachments/assets/15b9980e-5516-4975-9549-be781f518a5b)

**🎯 Flag :** `Dr. Revel’s Marvel Oils`

---

### 3. #reboot

![image](https://github.com/user-attachments/assets/0d95b52b-48a4-4161-b8b7-6d96c8267e74)  

> J'ai d'abord essayé sur Youtube et je n'ai rien trouvé, alors je suis allé sur Tiktok et j'ai tapé Dr Revel et je suis tombé sur son [compte](https://www.tiktok.com/@drrevelmarveloil) .

![image](https://github.com/user-attachments/assets/5296fec7-dcf6-48c9-bffe-0a049f78d5e4)

**🎯 Flag :** `drrevelmarveloil`

---

### 4. #notcyprus

![image](https://github.com/user-attachments/assets/ecb98b21-ce14-4aa3-ac60-525f79e7f8f4)

> En cherchant sur son [tiktok](https://www.tiktok.com/@drrevelmarveloil/video/7489168481376652566), on voit que son appartement est en face d'une tour, avec un revere image on trouve qu'il s'agit de la Tour Al Manara (Dubaï), on cherche le bâtiment blanc en forme de U en face, et on met le point sur la carte là où il devrait être (Damac Zada Tower).

**🎯 Flag :** ![image](https://github.com/user-attachments/assets/7c45bcb6-a9e2-4013-a4d0-65e827277f06)

---

### 5. #fanclub

![image](https://github.com/user-attachments/assets/33dfcfcf-876c-4854-b36c-85d12bc9e033) 

>  Dans les commentaires, un pseudonyme revient souvent : celestin_aitoubib.
> Une visite sur le site d'[AI Toubib](https://aitoubib.fr/) révèle non seulement que c'est là que travaille Raoul (Dr Revel), mais aussi que son PDG est Celestin Marchevend.
> La plupart des profils trouvées jusqu'à maintenant ont l'air d'avoir des Bluesky, il y a donc surement des pivots autours de ça.

![image](https://github.com/user-attachments/assets/073045b7-feed-4c6b-b9ae-2cba89fd3da6)

**🎯 Flag :** `Celestin Marchevend`

---

### 6. #NewJob

![image](https://github.com/user-attachments/assets/5984c7bb-beef-4674-8377-898b80e9276d)  

>  Comme indiqué ci-dessus, le nom commercial de l'entreprise est [AI TOUBIB](https://aitoubib.fr/).

![image](https://github.com/user-attachments/assets/9c608479-dc2c-4978-9cbc-bd021f155e6c)

**🎯 Flag :** `AITOUBIB`

---

### 7. #IciCaRecrute

![image](https://github.com/user-attachments/assets/6b9b8465-3f61-4f73-8eee-c14688ac27d9)  

> En allant dans la section « Actualités », on voit qu'ils recherchent un nouveau directeur technique, et en allant sur [l'offre d'emploi](https://aitoubib.fr/page/offre-demploi-cto/), on voit le site sur lequel postuler.

![image](https://github.com/user-attachments/assets/96b0c392-e25a-4708-ac34-ad99e27b1292)

**🎯 Flag :** `https://ctf.iraoul.fr` (et pas de / à la fin)

---

### 8. #NewPartner

![image](https://github.com/user-attachments/assets/ef68c5b9-4297-406c-a4da-1b8fd1d10656)  

> Ce flag est un croisement entre deux sites : https://mediprecog.eu/histoire.html et https://finint.ninja.
> Le premier site peut être trouvé en regardant les nouvelles sur [AI Toubib](https://aitoubib.fr/page/actualites/), un lien qui parle d'un partenariat avec Mediprecog nous amène à [cet article](https://mednews.tech/2025/04/mediprecog-envisage-un-investissement-dans-ai-toubib-une-phase-de-test-strategique-en-cours/).
> On tombe sur leur site https://mediprecog.eu/ où un seul onglet est cliquable : [Notre histoire](https://mediprecog.eu/histoire.html).
> On trouve trois noms différents pour la société au cours des années : Précision Médicale, Boutevieux Médical et Mediprecog.
> Une visite sur finint.ninja révèle que le nom correct est [Boutevieux Médical](https://finint.ninja/companies/boutevieux-medical-none/).

![image](https://github.com/user-attachments/assets/0cc689c7-c3ae-402a-8179-fc5c3539143e)

**🎯 Flag :** `Boutevieux Medical`

---

### 9. #Historique

![image](https://github.com/user-attachments/assets/1f506874-3c13-44ee-b817-fa5a5aabcb8f)  

>  En découvrant sur [finint.ninja](https://finint.ninja/companies/boutevieux-medical-none/) que l'entreprise est Boutevieux Médical depuis 1953, on retourne sur l'historique de l'entreprise sur [Notre Histoire](https://mediprecog.eu/histoire.html) et on se rend compte que le produit est un sphygmomanomètre.

![image](https://github.com/user-attachments/assets/62f26445-c381-4e21-a310-affc670e8f77)

**🎯 Flag :** `sphygmomanomètres`

---

### 10. #MauvaiseNouvelle

![image](https://github.com/user-attachments/assets/a805dbe5-627c-491c-8cdb-1e16d27b08d8)

>  En cherchant sur Mednews avec Boutevieux on tombe sur un [article](https://mednews.tech/2025/05/mediprecog-denonce-une-tentative-de-destabilisation-orchestree-a-travers-des-diagnostics-medicaux-falsifies/) qui explique qu'ils sont au coeur d'une affaire avec la maladie de Huntington.

![image](https://github.com/user-attachments/assets/3fe76015-befe-4da1-9a38-bf4282ca6929)

**🎯 Flag :** `Maladie de Huntington`

---

### 11. #TropTard

![image](https://github.com/user-attachments/assets/68fb6655-a949-429f-b61c-e16bbd1e187e)  

> À partir de ce moment, je ne vois pas d'autre solution que de faire le CTF à l'adresse https://ctf.iraoul.fr. On n'oublie pas qu'il s'agit essentiellement d'un CTF OSINT et que Stegano, Crypto et autres divertissements ne sont pas nécessairement à la portée de tout le monde... Il existe donc une alternative ailleurs.

> En se promenant, on tombe sur https://gitlab.com/marshack, qui a toutes les réponses en se baladant entre les différentes années de write-ups

![image](https://github.com/user-attachments/assets/2fafec69-3bda-4f7e-9fc9-e4600ab0c843)

> Et on débloque le dernier défi où il est dit :

![image](https://github.com/user-attachments/assets/39739455-656c-499a-8730-c1c7c2c876bf)

> Comme on connaît le nouveau CTO sur la page AI Toubib (Lucas Tranolond), on sait maintenant que son pseudonyme est « Fastictac », membre du groupe « Fun Loving Squirrels ».

**🎯 Flag :** `Fun Loving Squirrels`

---
   
### 12. #Source

![image](https://github.com/user-attachments/assets/fe0335e8-b133-4a57-9199-865dfb5250bf)

> En connaissant le nom de ce groupe et en cherchant un peu, nous tombons sur [leur site](https://funlovingsquirrels.wordpress.com/) et sur les contacts, nous trouvons une adresse IP.

![image](https://github.com/user-attachments/assets/dfe63f8b-c687-483e-84bf-1966d2537c25)  

> Une connexion Telnet révèle des discussions internes.

![image](https://github.com/user-attachments/assets/f4c100aa-0593-41b4-95e2-16d3c70a4155)

> Lucas est donc finalement un agent double qui travaille pour les concurrents Tchèques, Advanced Medical Systems... A l'aide de plusieurs personnes.

**🎯 Flag :** `Fastictac`

---

### 13. #Modem

![image](https://github.com/user-attachments/assets/7f466c5a-96ca-4106-bdac-c538da87bafd)  

> Sur l'écran d'accueil, on voit mentionné **BBS**.

**🎯 Flag :** `bbs`

---

### 14. #medileak

![image](https://github.com/user-attachments/assets/7ba91422-b2c4-4c9a-9547-eeb20feaf15f)  

> En continuant à chercher sur le bbs, on tombe sur une conversation ou une partie avec des fichiers `xsf` existerait. On tape donc « xsf » au lieu des numéros qu'ils proposent et bingo.

![image](https://github.com/user-attachments/assets/c89f3e95-15de-4ef8-b4dd-c078c4ba0151)  

![image](https://github.com/user-attachments/assets/016a8306-19cb-4c6d-92c5-6d7836bb54f8)  

> On voit que ce hash est stocké sur IPFS, on va donc regarder le [hash d'AI TOUBIB](https://bafybeicstsx4twfjzqfb3fzlmnwlllkfbcabxqp2yvt7cjgo5pgipcuygm.ipfs.dweb.link/).

![image](https://github.com/user-attachments/assets/ae23c5eb-d392-4ceb-8325-a41580c2bf35)

> En combinant sa date de naissance sur finint.ninja (26/05/1959), et les fichiers csv de diagnostic et de patient, on trouve que la date de diagnostic est 20220308.

**🎯 Flag :** `08/03/2022`

---

### 15. #TeamFLS-1

![image](https://github.com/user-attachments/assets/75cb3e9f-891d-4c33-85e2-5720f6b9cd25)

>  Nous savons depuis un certain temps qu'il s'agit de Lucas Tranolond.

**🎯 Flag :** `Lucas Tranolond`

---

### 16. #TeamFLS-2

![image](https://github.com/user-attachments/assets/953d58e2-c277-453e-8f57-69a81ca3a297)  

> Grâce à [usercheck.oscarzulu.org](https://usercheck.oscarzulu.org/), on remonte jusqu'à un profil Steam.

![image](https://github.com/user-attachments/assets/19f4a76c-92a6-4fde-a324-9330a1f1b713)

> Lucas est donc avec le fils de Zoran, jumeau de Vesna qui travaille elle aussi pour AI Toubib (trouvable [ici](https://finint.ninja/companies/sci-beau-soleil-none/) ).

**🎯 Flag :** `Josip Dvořáková`

---

### 17. #Hack

![image](https://github.com/user-attachments/assets/31703d8b-3fc6-46c9-9482-503369ee7ae5)  

> On explore les fichiers `.xsf` trouvés, [un seul](https://ipfs.io/ipfs/bafybeib7dw7gjpeu6wnw5et32hatx6wwbjtd5ooeixnt2uy4dh6g53lcta) est parlant et correspond à la demande.

![image](https://github.com/user-attachments/assets/ea21328c-a118-413e-ba18-452811800297)

**🎯 Flag :** `ACORN Financial`

---

### 18. #MasterMind

![image](https://github.com/user-attachments/assets/4a90c57a-a7d3-45a2-af6d-c3d8ea530c85)  

> Vu la façon dont MasterVeverka parle sur le bbs, on est sûr qu'il est à la tête de la société concurrente Advanced Medical Systems (trouvée sur [MedNews](https://mednews.tech/2025/04/advanced-medical-system-le-geant-tcheque-qui-convoite-mediprecog/)). On recherche donc cette société sur [finint.ninja](https://finint.ninja) et on trouve un document contenant les statuts de la société. Sur la dernière ligne, sa signature.

![image](https://github.com/user-attachments/assets/13aac4e0-449e-4936-8aeb-8d761e122604)

**🎯 Flag :** `Zoran Dvořáková`

---

### 19. #backtobusiness

![image](https://github.com/user-attachments/assets/4ec5957e-0b78-4287-a205-63d6aad3718b)  

> Sur le tiktok de Raoul, le 10/04/2025, il explique qu'il retourne à Limoges.
> En regardant les avions ce jour-là, il y en a 3 (les métadonnées donnaient la date du 06/04 à 10h15, mais je ne sais pas s'il faut l'utiliser).
> Après quelques tentatives infructueuses (je n'ai pas réussi à trouver comment tomber dessus la première fois), nous avons trouvé le drapeau.

**🎯 Flag :** `EK73`

---

### 20. #MaisonMère

![image](https://github.com/user-attachments/assets/95f107dc-d150-41a4-bdc1-06d8c1953135)  

> [finint.ninja](https://finint.ninja/companies/advanced-medical-system-none/) montre qu'Advanced Medical Systems est détenu à 100 % par Pokročilý Medicínský Systém.

![image](https://github.com/user-attachments/assets/0fbfea74-a019-4042-80c7-23b2964885c7)

> Mednews nous dit que cette société est tchèque. Nous écrivons donc le nom dans l'url (guessing) sans accents et ajoutons .cz, et nous trouvons un site qui existe [bel et bien](https://pokrocilymedicinskysystem.cz/).


**🎯 Flag :** `pokrocilymedicinskysystem.cz`

---

### 21. #MaiSonPère

![image](https://github.com/user-attachments/assets/f165d2de-03ad-48cd-be9a-605539167331)

> On l'a déjà depuis longtemps.

**🎯 Flag :** `Zoran Dvořáková`

---

### 22. #MaisonChère

![image](https://github.com/user-attachments/assets/6a6f085a-7aef-48dd-a63e-6b5024d4c0a7)  

> Sur [finint.ninja](https://finint.ninja/companies/advanced-medical-system-none/), les coordonnées d'AMS mènent à un château sur Google Maps.

![image](https://github.com/user-attachments/assets/10a6e1ce-b2a5-43e1-9577-de24970a0a83)  

> On tombe sur un château (ce qui correspond parfaitement au jeu de mots du nom du défi). 

**🎯 Flag :** ![image](https://github.com/user-attachments/assets/b63d39ed-713f-424c-a5ee-7b76333e5e0b)

---

### 23. #TeamFLS-3

![image](https://github.com/user-attachments/assets/08f61d1e-c007-4abc-a20e-771b078a4a0e)

> En faisant des WebCheck si tous les sites, j'ai fini par tomber sur une information importante sur [pokrocilymedicinskysystem.cz](https://web-check.xyz/check/https%3A%2F%2Fpokrocilymedicinskysystem.cz%2F).

![image](https://github.com/user-attachments/assets/f79f3ba5-d5df-4ee1-88a4-a39998b50be1)

> Comme tous les personnages depuis le début on un Bluesky, on va voir pour lui aussi et en tapant son nom on trouve.

![image](https://github.com/user-attachments/assets/0780ccad-12cb-4044-91d4-933e021c02cc)

**🎯 Flag :** `Ivan Kanalchukiev`

---

### 24. #RadioGaga

![image](https://github.com/user-attachments/assets/5a54cb0f-873c-4d8c-b57a-251e954223b2)

> Une chose que je n'avais pas encore tenté du CTF est d'utiliser OIW pour les [lieux](https://medileak2.oiw.fr/dashboard/locations), en ayant trouvé Chez le Rat j'essaye ce code et ça marche
> On se met à parler avec Pierre le jardinier qui nous donne des informations importantes sur la vie de Zoran et sa famille. Il confirme qu'il a bien des jumeaux, mais aussi une femme... Andrea.

![image](https://github.com/user-attachments/assets/e515d7a4-3731-4dff-b13e-db1d83b1a54e)

> Il nous dit que Zoran essaierait de lancer une radio "La voix de l'Europe".
> En cherchant je trouve que voiceofeurope.com existe, et avec du guessing je finis par trouver que https://lavoixdeleurope.eu/ existe aussi.

![image](https://github.com/user-attachments/assets/d8a24f88-55d2-471d-bd19-8280232a5f32)

**🎯 Flag :** `lavoixdeleurope.eu`

---

### 25. #MeetMe

![image](https://github.com/user-attachments/assets/a42874f4-980f-4071-ba0e-e3485efae092)

> En continuant les recherches cotés Zoran, je trouve que sur la société [Advanced Medical Systems](https://finint.ninja/companies/advanced-medical-system-none/) il y a deux personnes que je n'ai pas encore recherché : M. Alec BOUCHARDIN et M. André FEUILLATON
> Ils ont eux aussi un Bluesky et en regardant du coté de André on trouve un événement

![image](https://github.com/user-attachments/assets/e8653423-9b4d-4e83-9ccc-b40006751e01)

![image](https://github.com/user-attachments/assets/8881867f-4d61-4ea4-8038-1bf89e4bd4d0)

**🎯 Flag :** `pragomedica`

---

### 26. #Halftime

![image](https://github.com/user-attachments/assets/598bb24b-2abf-46ce-9e3f-ef090cde806d)

> Cette fois ci du coté d'Alec on voit qu'il parle de Hockey.

![image](https://github.com/user-attachments/assets/b0f4112c-e91d-42ff-bc21-4cc211004295)

> L'homme sur l'image a l'air d'être de l'équipe des Icemen de Jacksonville et parle d'un certain Christophe Lalancette et d'une rencontre avec Zoran lors du troisième tour des séries éliminatoires.
> En recherchant ce joueur on voit qu'il appartient à l'équipe des HC ŠKODA PLZEŇ et en cherchant leur résultat lors de leur [troisième matchs](https://www.sofascore.com/fr/tournoi/hockey-sur-glace/czech-republic/extraliga/237#id:61241) on voit que c'est eux qui l'ont remporté.

![image](https://github.com/user-attachments/assets/7fe3d5a8-e2aa-4c48-96a5-0d6c09b412e2)

> Les deux podcaster sont donc avec Advanced Medical Systems et vont surement precher leur paroisse...

**🎯 Flag :** `HC ŠKODA PLZEŇ`

---

### 27. #PasSympa 

![image](https://github.com/user-attachments/assets/385bea59-82f6-4798-9783-f562fb0b0103)

> De retour sur Raoul, mon cerveau fait tic, si j'ai pu regardé Chez le rat, pourquoi pas à l'ancienne adresse de Raoul ?
> Je la rentre sur OIW et je tombe sur les [bonnes informations](https://drive.proton.me/urls/TTCDH92BGW#u80H1wvANV4c).

![image](https://github.com/user-attachments/assets/ca36339e-cfb7-44ca-b342-01854e3f8fb3)

**🎯 Flag :** `Z090425`

---

### 28. #Soldes

![image](https://github.com/user-attachments/assets/6c99940d-5008-4061-b43d-7ed4603a5cbe)

> Apres avoir découvert https://lavoixdeleurope.eu/ j'ai écouté la radio pendant 30 min pour avoir toutes les informations.
> On sait donc que Raoul à un [site internet](https://drrevel.onlineweb.shop) et que les podcaster Alec et André expriment leur avis en faveur des tchèques contre Mediprecog.
> En regardant sur le site de Raoul on peut voir la même montre que sur le Bluesky de Alec, sur [pokrocilymedicinskysystem.cz](https://pokrocilymedicinskysystem.cz/) et qui a les caractéristiques dont ils parlent dans le podcast.

![image](https://github.com/user-attachments/assets/9d79e575-8e20-45ea-95db-16c0856396b3)

> On rentre dans OIW le code SHOP ainsi que l'image de la montre et il sort un token.

> Raoul est donc lui aussi avec Advanced Medical Systems ??

**🎯 Flag :** `7ef4f88c-fc53-4e70-8e21-49f248c45feb`

---

### 29. #AvisNégatif

![image](https://github.com/user-attachments/assets/d2233769-5733-46a6-ae2d-3070b75e3983)

> En regardant dans le code source du site [AI Toubib](https://aitoubib.fr/) on peut voir qu'il a été fait par LVC1-F3R.
> Comme tout bonne développeuse qui se respecte cette personne à un Github (trouvable avec https://usercheck.oscarzulu.org/) et on apprend que c'est Lucie Monlucin, qu'on avait déjà vu dans des articles, ancienne CTO de Ai Toubib.

![image](https://github.com/user-attachments/assets/d12dc5ee-ac06-42e6-899c-d64b82e2f9be)

> En cherchant dans les commits on finit par trouver un OIW pour discuter avec elle

![image](https://github.com/user-attachments/assets/bfcb6d04-9ae4-4e12-8c43-639dc3d1872e)

> Après quelques échanges avec elle, elle donne un lien [proton](https://drive.proton.me/urls/PRQPD201BC#VcvKWueJyu5F) qui contient les informations qu'on cherche (avec une conversion CZK -> Euros à faire)

> Dans son profil on peut voir qu'elle a été à l'IUT avec Lucas à la même période, encore une personne qui joue double-jeu ?

**🎯 Flag :** `8€ / 43.8 %`

---

### 30. #Fl4G (Bonus)

![image](https://github.com/user-attachments/assets/165d1e93-e4c7-4a7a-bb51-a193d8a679b2)

> Une fois qu'on sait qu'elle a vécu un temps avec Lucas j'ai été sur son OIW pour la questionné, elle m'a bien parlé de moment avec lui par rapport à du code mais rien qui ne donne la réponse.
> En cherchant son pseudo sur [un site](https://instantusername.com/?q=LVC1-F3R) j'ai trouvé qu'elle était sur d'autre plateforme, dont [Replit](https://replit.com/@LVC1-F3R/Eliza2?v=1#logs/conversation_20250429_134709_bllls.txt) où en cherchant dans le code, et plus précisement dans l'historique des messages j'ai fini par trouvé le bon flag.

![image](https://github.com/user-attachments/assets/b2a04d50-1cbf-4785-9cac-2b3282c19641)

> On découvre une nouvelle personne, Rania Bouhamed, à voir s'il servira.

**🎯 Flag :** `FLAG{M4G1C_W0RD_F0UND_CTF_2018}`

---


### 31. #OldLove

![image](https://github.com/user-attachments/assets/7b37a56d-2733-49f2-a941-754221e5effe)

> Le passé de Raoul refait surface -> ça fait penser qu'il faut aller vérifier là où on a plein d'anciennes infos sur lui, le [write-up](https://oscarzulu.org/wu-medileak/) du Medileak 1.
> En cherchant, on trouve qu'il a encontré Gizem dans une pharmacie en stage, qu'il lui a rédigé un poème romantique, et qu'il lui vouait une loyauté dans ses mails.

**🎯 Flag :** `Gizem Ihanet`

---

### 32. #Clochint (Bonus)

![image](https://github.com/user-attachments/assets/5d176265-e8ed-4a53-a46a-510b17e7f559)

> Ici pas de stratégie particulière, j'ai écouté le [top 10 des sons de cloches](https://www.youtube.com/watch?v=asqExKVkyAw) et j'ai trouvé à l'oreille celle qui correspondait.
> Attention cependant à bien mettre le nom complet trouvable sur [Wikipedia](https://fr.wikipedia.org/wiki/La_Savoyarde) et pas son surnom utilisé.

**🎯 Flag :** `Françoise Marguerite du Sacré-Cœur de Jésus`

---

### 33. #Insécurité

![image](https://github.com/user-attachments/assets/4fd765aa-bad3-4229-a3fd-569e1a88eda8)

> Mauvaise compréhension de ma part j'ai cru qu'il fallait continuer de chercher dans son passé pour les menaces et donc mauvais flag car on repartait sur une attaque récente.
> On continue les recherches sur le [write-up](https://oscarzulu.org/wu-medileak/) et on voit qu'elle a un [profil Strava](https://www.strava.com/athletes/135688719?num_entries=10).
> En se connectant on voit qu'elle a été attaqué et qu'ils ont détruit son téléphone sur un chemin qu'elle avait déjà pris auparavant.

![image](https://github.com/user-attachments/assets/ccfcd822-a74a-46db-a249-241f6d4a4a39)

**🎯 Flag :** ![image](https://github.com/user-attachments/assets/5fa0890e-7955-4373-ba12-eac0f6f00c17)

---

### 34. #LesBonsComptes

![image](https://github.com/user-attachments/assets/a2567e91-e6c4-4be9-8196-6b87c436f186)

> En retournant sur [finint.ninja](https://finint.ninja/) j'ai été interpellé par le fait de voir 3 documents, j'avais déjà ouvert les 3 mais jamais encore pensé à y regarder les metadatas.
> Je teste sur les 3 et celui de Advanced Medical Systems me donne "Alisha dy compta" ainsi que son site https://alishady.eu/

![image](https://github.com/user-attachments/assets/cef1e571-b5cf-43f2-8c1e-3e97469fd883)

**🎯 Flag :** `Alisha Dy`

---

### 35. #Mission

![image](https://github.com/user-attachments/assets/a100d7c0-bdf3-488e-a95e-5fb65162a106)

> Sur https://lavoixdeleurope.eu/ on entend à un moment un signal sonore strident d'une quarantaine de seconde qui se finit par "Pour R".
> A force d'avoir enquêter sur le Medileak et en regardant aussi le write-up du premier du nom, on sait que R a de grandes chances de signifier Raoul.
> A force de recherche sur Youtube on finit par trouver que c'est un audio qu'on peut transformer avec robot36.
> On le fait écouter à l'application et il nous donne cette image :

![image](https://github.com/user-attachments/assets/e45a2484-cf74-4f1a-93da-cec30a3f429b)

> On reconnait le format de https://what3words.com qui permet de donner une localisation avec 3 mots.

**🎯 Flag :** A Limoges ![image](https://github.com/user-attachments/assets/868f9b51-4bfb-4f29-81c0-d0f10dbb79f0)

---

### 36. #IA

> (Changement de PC donc pas les mêmes couleurs)

![image](https://github.com/user-attachments/assets/68cbd733-2bd4-44a7-8873-671b5320914b)

> Sur le [site de Raoul](https://drrevel.onlineweb.shop/product/reveltracker) on peut voir en bas "healthcloud.iraoul.fr" qui mène vers une page de connexion.
> Dans un premier temps on peut trouver les logs facilement en testant les plus connus et admin:admin123 fonctionne, ce qui nous permet de visiter le site.
> En guessing on voit aussi que le /.git/ est ouvert, et en fouillant dedans, sur le app.py on voit écrit "Code généré par assistant DeepSeek v3 le 20/04/2025"

**🎯 Flag :** `DeepSeek-V3`

---

### 37. #Malin

![image](https://github.com/user-attachments/assets/9c2216f1-5682-4f73-a8e8-ab43ca6b8722)

> Toujours sur le pdf d'Advanced Medical Systems, on peut aussi voir la signature JSON Web Token qui mentionne "alishady.eu:1337".
> En pivotant sur ce site https://alishady.eu:1337 on tombe sur son site web "obscur".
> On trouve un OIW pour lui parler mais qui ne m'a rien donné, et un PDF à l'adresse "https://alishady.eu:1337/assets/plaquette.pdf".
> En retournant à /assets on trouve tous les clients de Alisha, on cherche jusqu'à trouver le fichier qui parle du rachat par Advanced Medical Systems.

![image](https://github.com/user-attachments/assets/e8530b01-330b-4006-b581-755118989a9e)

**🎯 Flag :** `50%`

---

### 38. #SoyonsDésinvoltes

![image](https://github.com/user-attachments/assets/07b0099b-129c-4caf-bfd0-c1f8fc9e327f)

> On sait que Zoran a plusieurs sites, 3 d'entre eux étant https://medinews.tech/ , https://pokrocilymedicinskysystem.cz/ et https://lavoixdeleurope.eu/
> En cherchant dans les codes sources avec un ctrl+F sur "id", on peut voir que les 3 sites ont la même ID, et ici le même Google Tag Manager.

**🎯 Flag :** `GTM-5J4M3JV8`

---

### 39. #HomeSick

![image](https://github.com/user-attachments/assets/4bf18246-d5ab-4796-bd2c-7681a7a996c8)

> Ici j'ai pris un indice qui m'a dit d'aller chercher du coté des avis que Vesna aurait pu laisser.
> En reprenant son pseudo [Bluesky](https://bsky.app/profile/vesnadvorak.bsky.social), avec [IDCrawler](https://www.idcrawl.com/u/vesnadvorak) on trouve qu'elle a un [TripAdvisor](https://www.tripadvisor.com/Profile/VesnaDvorak?tab=reviews&fid=e4a26390-7353-4143-b5f6-02eba1f22b83) !
> On traduit ce qu'elle a dit et on voit qu'elle a parlé avec son père à la Chapelle Saint Aurélien de Limoges.

**🎯 Flag :** ![image](https://github.com/user-attachments/assets/fe4c4d88-bd57-4b2b-a8d2-7c37690edf2c)

---

### 40. #END

![image](https://github.com/user-attachments/assets/14b3b47e-addd-46f1-8066-50352c64c17c)

**🎯 Flag :** `#Limoges`

---

## Tous les challenges

![image](https://github.com/user-attachments/assets/14fe2541-3919-40aa-bea2-065e5f092f90)

---

## Toutes les techniques utilisées

Voici un récapitulatif exhaustif des techniques, outils, sites et pivots utilisés tout au long du CTF :

### 🌐 OSINT web & recherche en profondeur

- Recherche de pseudonymes et identités sur :
  - [usercheck.oscarzulu.org](https://usercheck.oscarzulu.org)
  - [idcrawl.com](https://idcrawl.com/)
  - [instantusername.com](https://instantusername.com)
- Recherche sur les réseaux sociaux : TikTok, Bluesky, Steam, Strava, TripAdvisor
- Exploration de sites de news OSINT : [mednews.tech](https://mednews.tech)
- Exploration de write-ups précédents (ex : [Medileak 1](https://oscarzulu.org/wu-medileak/))
- Lecture attentive de sites d’entreprise pour découvrir des liens ou changements :
  - Pages "Actualités"
  - Mentions légales
  - Filtres `robots.txt`, `/.git/`, `/assets/`, `/logs/`

---

### 🕸️ Analyse technique & investigation réseau

- Exploration de répertoires `.git/` ouverts et analyse de `app.py`
- Telnet vers une IP trouvée pour lire une messagerie texte
- Analyse de JWT signés dans des PDF
- Décodage SSTV via l’application [Robot36](https://play.google.com/store/apps/details?id=xdsopl.robot36)
- Extraction de métadonnées dans des documents PDF/JSON
- Guessing de mots-clés sur interface (`xsf`, `bbs`, etc.)
- Recherche dans les commits GitHub pour identifier OIW, auteurs ou artefacts

---

### 🔎 Analyse de code source / dev

- Analyse de signatures Google Tag Manager (GTM)
- Détection d’ID ou variables partagées entre sites
- Lecture directe du code HTML/JS (ex : DeepSeek mentionné dans `app.py`)
- Pivot sur signatures de développeurs (`LVC1-F3R`, `DeepSeek-V3`)

---

### 🌍 Géolocalisation & investigation physique

- Recherche inversée d’images (Google, Yandex)
  - Ex : Tour Al Manara, Damac Zada Tower
- Croisement TikTok + date + métadonnées vidéo pour reconstituer un trajet
- Recherche de vols (ex : EK73)
- Détection d’objets récurrents (ex : montre connectée sur plusieurs supports)
- Utilisation de [What3words](https://what3words.com/)
- [Google Maps](https://maps.google.com) + Street View

---

### 🔗 Pivots entre entités / personnes

- Cross-pivoting entreprise/personne via [finint.ninja](https://finint.ninja)
- Identification d’actionnaires, employés, liens historiques
- Croisements de relations (anciens collègues, camarades, réseaux sociaux)
- Détection de doubles affiliations (Raoul, Lucas, Lucie, etc.)
- Analyse de signatures ou mentions légales

---

### 🧩 Utilisation de plateformes spécialisées

- [WebCheck](https://web-check.xyz) pour révéler des connexions entre sites
- **OIW** (Open Intelligence Wall) : tokens, dialogues avec PNJ, codes lieux
- IPFS : exploration de fichiers hébergés via `bafy...`
- [GitLab](https://gitlab.com), [Replit](https://replit.com) pour explorer logs, historiques de projets
- Plateformes sociales secondaires : Steam, TripAdvisor, Strava, Bluesky

---

### 🎧 Médias & sons

- Analyse de podcasts (ex : discours pro-AMS)
- Repérage d’infos dans les dialogues audio
- Décodage de signal SSTV avec [Robot36](https://robot36.com)

---

### 📁 Dossiers & documents

- Exploration de répertoires `/assets/`, `/logs/`, `/replays/`, `/history/`
- Fichiers détectés :
  - Plaquettes commerciales
  - Rapports clients
  - Achats, devis, contrats
- Métadonnées dans PDF, CSV
- Fichiers hébergés sur Proton Drive, Replit, IPFS

---

### 🧠 Stratégies spécifiques

- Guessing intelligent d’URL (ex : `pokrocilymedicinskysystem.cz`)
- Conversion CZK → EUR pour comprendre un flag
- Recherche sur `.bsky.social` à partir de noms
- Écoute attentive + comparaison manuelle (ex : sons de cloche sur YouTube)

---

### 🧪 Techniques OSINT mobilisées

- **OSINT Humain** : relations, identités, doubles jeux
- **OSINT Réseau** : fichiers `.git`, JWT, Telnet, IPs
- **OSINT Entreprise** : analyse financière & historique (finint.ninja)
- **OSINT Média** : TikTok, podcast, vidéo, SSTV
- **OSINT Documents** : PDF, métadonnées, commits, logs
- **OSINT Lieu** : Strava, TripAdvisor, What3words, TikTok, Google Maps
- **Social Engineering passif** : interprétation de dialogues OIW & comportements

---
