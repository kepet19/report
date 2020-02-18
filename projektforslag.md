# Foreløbig titel og dato
**Foreløbig titel:** creditoro
**Afleveringsdato:** 29-05-2020 kl. 12.00

# Uddannelse
Softwareteknologi

# Projegruppe og vejleder
**Gruppenummer:** 06
**Kontaktoplysninger:** Findes i [gruppekontrakten](gruppekontrakt.md)

# Problemstilling
![system drawing](https://cdn.discordapp.com/attachments/673822129946361859/674706669921632256/TV2-Credits-Management.png)
Vores system afspejler det system TV2 har lagt op til i projekt-casen. Der er tale om et system hvor man kan se - og redigere krediteringstekster for programmer.
Systemet indeholder forskellige bruger roller:
- Administrator
  * Kan redigere, oprette - samt slette krediteringstekster.
- Bruger
  * Kan redigere samt oprette krediteringstekster.
- Gæst (ikke authentikeret)
  * Kan se krediterikstekster for programmer.

Systemet består af forskellige programmer:
- EPG Poller (should have)
  * Henter data fra Electronic Program Guide (EPG) og indsætter nye programmer i vores database via REST API'et, der gør at brugerer ikke skal oprette programmet, men blot tilføje krediteringstekster.
- Desktop Client (must have)
  * Brugergrænseflade, der gør det let at se, søge, redigere samt slette krediteringstekster for programmer.
- Rest API (must have)
  * Api'et binder alle de andre programmer sammen, ved at udbyde nogle endpoints der gør det muligt at foretage alle aktionerne beskrevet i de andre programmer.
- Website (nice to have)
  * Brugergrænseflade som beskrevet i *Desktop Client* men som website i stedet for, da det vil afspejle den løsning TV2 nok vil bruge i sidste ende.
  
Dette er implementeret via et REST API, som er den applikation der styrer vores business logic. For at gøre systemet brugervenligt, laves en dekstop client (GUI). 



# Faglig og personlig motivation
Motivation er at Vi vil ikke bare lave minimus kravet, da der er en støre personlig interesse for at lave et større system, der afspejler det system som projekt casen har lagt op til
og kunne være en interesse for TV2.
hvad kan vi få ud af det
fx. farveligt



# Nuværende viden
TV2 efterspørg en løsning der gør de kan cutte de ruller testker der kommer efter en film eller linged og derved få ekstra 30 sekunder visning af reklamer.
Administrator 	(se/redigere/oprette og slette bruger)
TV2 brugere 	(se/redigere)
Bruger der kan 	(se)


# Rammetidsplan
[Rammetidsplan](https://docs.google.com/document/d/1GcyBqYznrnS67T8T1zZoPxFWeUDLLc6jlVvnFreY6GU/edit)

# Gruppeværktøjer
**Gruppeværktøjer:** Se [Gruppekontrakt](gruppekontrakt.md) under afsnittet Værktøjer

# Gruppekontrakt
[Gruppekontrakt](gruppekontrakt.md)

# Vejlederkontrakt
[Vejlederkontrakt](Vejlederkontrakt.md)
