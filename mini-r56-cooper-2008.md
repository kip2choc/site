# Mini R56 Cooper 2008 maintenance guide
This page considers a Cooper 120 hp 1.6L model year 2008: N12 (N12B16) équivaut à PSA EP6.

## Table of Contents
1. [Petrol Engines](#petrol-engines)
2. [Battery](#battery)
3. [Infotainment](#infotainment)
4. [Brakes](#brakes)
5. [Petrol Filter](#petrol-filter)
6. [Lubrication](#lubrification)
7. [Cooling](#cooling)
8. [Alternator Belt](#courroie-alternateur)
9. [Distribution / Timing Chain](#distribution)
10. [Reniflard (CCV/PCV)](#reniflard)
11. [Throttle Body (Papillon)](#papillon)
12. [PCV Valve](#pcv-valve)
13. [Rear Stabilizer Bar](#barre-stab-arrières)
14. [Cabin Filter](#filtre-habitacle)
15. [Lights](#light)
16. [Remote Key](#clé-télécommande)
17. [Exterior](#extérieur)
18. [Interior](#intérieur)
19. [Hardware/Fasteners](#quincaillerie)
20. [Torque Specs](#couples-serrage)
21. [Wiper Blades](#essuies-glaces)
22. [Resources](#resources)

## Petrol engines
From 2A-1[^Haynes]:
- 1.4L 1397cc N12B14 (1.4 VTi 95 ch, code technique PSA: EP3)
- 1.6L 1598cc
	- Non-turbo (up to 2010) N12B16 (1.6 VTi 120 ch, code technique PSA: EP6)
	- Non-turbo (2010-on) N16B16
	- Turbo (2006 - 2010) N14B16
	- Turbo (2010-on 181 bhp) N18B16

Another listing:
- Cooper (non-turbocharged) 2007 - 2010: N12
- Cooper (non-turbocharged) 2011 - 2013: N16
- Cooper S (turbocharged) 2007 - 2010: N14
- Cooper S (turbocharged) 2011 - 2013: N18
- Cooper JCW (turbocharged) 2007 - 3/2013: N14 (turbo, compression ratio, and other components differ from the S model)
- Cooper JCW (turbocharged) 3/2013 and up: N18 (turbo, compression ratio, and other components differ from the S model)

LCI (facelift) à partir de mars ou août 2010. 
> Un truc simple : ton autoradio (lecteur CD) est gris, c'est une pré-facelift. ton autoradio est noir, c'est une facelift.

## Electricité
### Battery
- Varta A7 form-factor.
- Cale B13
- AGM or EFB should be prefered (due to start & stop).
- Note that start and stop is capricious, don't expect much.
- I've seen a Bosch none EFB/AGM battery running for 7 years in that car.
- Il y a notamment une tresse de masse sur la gauche du compartiment moteur et un fil sous le couvre culasse à vérifier
	- [Masse - vidéo](https://youtu.be/Rcj1SJjjm4A?t=983)
- Vérifier la continuité de la masse avec le bloc moteur
### Fusibles et relais
- Il y a un relais noir en bas de la colonne du milieu de la boîte à fusible aux pieds intérieur avant droit, relais R2
	- c'est une relais "30G" donc toujours actif une fois la clé insérée du moins
	- en fonction de ce qu'il alimente, c'est normal qu'il chauffe, vérifier que ce n'est cependant pas le cas voiture éteinte et fermée
	- un relais peut avoir une température de 40-50°c, mais à 70°c il faut le remplacer
	- je l'ai enlevé pour voir, les essuies-glaces se sont mis en route
## Infotainment
### Réglages
	Heure
### Consultations des défauts
### Remise à zéro entretien

## Brakes
### Rear
#### Pads
- OE: 34216778327
- Avoid Bosch reference since they either come with no screws or at best only two screws instead of 4 needed
- Also try to get a reference with anti-rattle clips. 
#### Discs
- Diameter : 259mm (I advise to check before), 4 holes, entre-axe (ET) 100
- OE: 34216774987
- Rear wear min thickness: 8.4 mm.
- Delphi bg3662 or bg3662c (newer reference, do not require to be cleaned).

## Petrol filter
- Cannot be renewed, in case of probems, the whole assembly needs to be replaced
- https://forum-auto.caradisiac.com/topic/87804-remplacer-le-filtre-%C3%A0-essence-cooper-120cv-de-2009/
- We come over OE: 11252754870 sometimes but not sure it can fit somewhere.

## Lubrification
### Jauge moteur
- Illisible. Trouvable à moins de 10 euro. Attention cependant les autres modèles peuvent être plus larges entre min et max!
- **MINI 11 43 7 585 970 / 11437585970**
- PEUGEOT / CITROËN / DS 1174.A4
- PEUGEOT / CITROËN / OPEL / DS 98 307 794 80
- MINI 11 43 7 549 422 / 11437549422
- MINI 11 43 7 561 567 / 11437561567
- MINI 11 43 7 566 021 / 11437566021
- MINI 11 43 7 568 567 / 11437568567
### Bouchon
OE: 11127542116
### Vidange huile moteur
- Filtre Purflux (ce sont les meilleurs), L358A (OE 11427622446).
- Huile (4.25L says 1A-2[^Haynes])
	- BMW Longlife-01 (LL-01) [^Manuel]
	- BMW Longlife-01 FR (LL-01 FR) [^Manuel]
	- **BMW LL-04 Long-life 04. (0-16[^Haynes] et [^Manuel])**
	- Pour appoint, SAE 0W-30; SAE 5W-30 ou ACEA A3 possible. (0-16[^Haynes])
	- À la rigueur, BMW Longlife 98 ou ACEA A3/B4 [^Manuel]
	- Total Classic 9 LL 5W-30
	- Total Classic 9 C3 5W-30
	- Evolution FULLTECH LLX 5W-30
	- Quartz Ineo Long Life 5W-30
	- Quartz Ineo RCP 5W-30
	
0W30 consomme plus mais c'est mieux pour la visco à froid de ce moteur, surtout pour les petits trajets donc.
Il semble que plus une huile répond à de normes, plus elle est performante car cela demande d'ajouter plus de coûteux additifs.
Dans le doute, on préfèrera une huile qui répond à beaucoup de normes en plus de celle requise.

- Joint cuivre diamétre int 16mm et ext 22mm (Restagraf 227372 x4), OE 11 13 7 546 275 / 11137546275 / 12617546239.
- Bouchon (et joint) : OE 11137546274, 11137585928.
- https://static.nhtsa.gov/odi/tsbs/2016/MC-10147575-9999.pdf
### Causes de fuites
- [tendeur](#tensioner) original mal serré
- joint couvre culasse
- joint support du filtre à huile
- [reniflard](#reniflard)
- [crankshaft seal](#distribution)

## Cooling
### Thermostat housing
- Le boîtier a tendance à se fendre (corps en plastique) et donc fuire.
- Le thermostat ne se démonte pas de ce boîtier. Il faut changer tout le boîtier.
- La sonde est cependant démontable.
- Il y a une prise de sonde de température d'eau
	- sur le faisceau, un connecteur en plastique vert qui devient cassant (sûrement à cause du colorant du plastique).
	- Elle est difficile à trouver mais on tentera de bricoler un faisceau.
- There is another plug to heat-control the internal wax.
- Those 2 plugs are very similar but seem to have different keyed connections. 
- An issue may stems from the silicone gasket within the thermoplastic housing.
	- While it performs well under high heat, oil exposure causes it to swell over time
	- FIx and clean oil leaks around the thermostat housing.
- https://www.tomorrowstechnician.com/diagnosing-electronically-controlled-thermostats/

### Code P0597 Thermostat Heater Control Circuit/Open
- "Control Circuit open": circuit refers to an electrical device and "control" corroborates it is not the coolant system that is open.
- Il faudrait mesurer la résistance des 2 prises (sonde et contrôle) pour diagnostiquer un problème sur la pièce.
	- Aux bornes du contrôle électrique, ordre de grandeur attendu de 10 Ohm à 30 Ohm et ouvert quand la pièce est défectueuse.
		- une des bornes devrait être à la masse (ou parfois au 12V)
	- Aux bornes du capteur de température on a mesuré 4,12 kOhm à froid, cela semble correct
		- la résitance baisse quand la température monte (capteur type NTC/CTN - coefficient de température négatif)
		- ordre de grandeur de ce type de capteurs auto; à froid plusieurs kOhm et à chaud, qq dizaines d'Ohm, ci-après:
| Température | Résistance (Ω) |
|-------------|---------------|
| 0 °C        | 8 200 - 11 000 |
| 20 °C       | 2 500 - 5 000  |
| 40 °C       | 1 500 - 3 000  |
| 60 °C       | 600 - 2 600    |
| 80 °C       | 200 - 1 300    |
| 100 °C      | 50 - 500       |
- On pourrait peut-être aussi tester le faisceau avant de remplacer la pièce, mais comment?
- On présume que par défaut le circuit de liquide est ouvert (le moins dangereux) et qu'au démarrage à froid, le calculateur alimente à 12V pour chauffer la cire, 
fermer le circuit et ainsi accélérer la chauffe.
	- Si cette théorie est vraie, la conduite qui mène au radiateur doit chauffer rapidement (au toucher ou avec un thermomètre infra-rouge)
	- on devrait pouvoir vérifier qu'il y a 12V au bornes au démarrage à froid
- Il semble que ce soit un fonctionnement on/off (12V ou 0V).
- In my case, the error occured after having filed with a slightly different coolant and also noticing the expansion tank screw plug could be indefinitely screwed (maybe coincidence)
- Thermostat housing replacement videos
	- https://youtu.be/K4q0tBGFe1w
	- https://www.youtube.com/watch?v=LZZnzX3yHVE
	- https://www.youtube.com/watch?v=JTjCEk2pUog

### Coolant
- 82 14 0 031 133 / 82-14-0-031-133 / 82-14-0-031-133-M26 / 82.14.0.031.133 / **82140031133**
	- Can be bought from Mini
		- This phosphate and nitrite-free, non-diluted coolant should be used with a 50/50 distilled water mix. 
- Hard to know what is the aftermarket equivalent
	- [Pentosin NF](./docs/Pentosin-Product-Data-Sheet-Antifreeze-Pentofrost-NF.pdf) fits
- Le bouchon semble pouvoir tourner sans fin
	- essayer de le changer et sinon, il faudra changer le vase
		- bouchon OE : **17135A1BD89**, 17117639024, 17132754264, 7639024, 2754264
		- vase OE : **17137539267** / 17137823626
### Tempétature moteur
- N'est pas affichée, certainement pour ne pas effrayer l'utilisateur car elle monte haut et varie beaucoup sur ces moteurs [^manu-classic-car].
- [Car hidden menu - youtube video](https://www.youtube.com/watch?v=pZI1_S9ffX0)

## Courroie alternateur
- les différents suintements du moteur peuvent la contaminer, les caoutchouc y sont très sensibles
- 11287566789 (6PK905)

## Distribution
- Serait conseillée tous les 150000km [manu-classic-car].
- J'avais pensé arbitrairement 160000km.
- [kit outil clas, environ 89 euro](https://www.clas.com/fr/calage-psa-mini-1-4-1-6-vti-thp-16v-om-3748.html)
- on trouve des kits similaires un peu moins chers qui doivent sortir de la même usine asiatique, certains parlent d'un des outils qui serait à réusiner cependant...
- Pour savoir si elle est détendue
	- visser le faux tendeur du kit outil
	- visser la tige qui est en son centre à la main 2A-6.4[^Haynes] (**non pas à 8Nm comme dit [là](https://youtu.be/Rcj1SJjjm4A?t=968)**)
	- vérrouiller la tige centrale à l'aide du contre écrou
	- dévisser le faux tendeur
	- la longueur (hors écrou de serrage) doit être inférieur à **68mm** (2A-6.4[^Haynes])
- Il semble que des morceaux de guide finissent par se promener
	- On vérifiera bien l'intégrité des guides au démontage.
	- S'il manque des morceaux, ils peuvent être dans la crépine de la pompe à huile immergée ou au fond du carter.
	- Dans les 2 cas, il faut démonter le carter et refaire son joint à la pâte.
- [Tuto changement](https://forum-auto.caradisiac.com/topic/480032-probl%C3%A8me-de-chaine-de-distribution-r%C3%A9solue-moteur-thp-mini-jcw/)
- https://www.planete-citroen.com/topic/129344-calage-distribution-moteur-thp-ep6/
- https://www.nomaallim.com [EN](https://www.nomaallim.com/ep6-timing-chain-refitting-and-setting.html) / [FR](https://www.nomaallim.com/calage-chaine-distribution-moteur-ep6.html)
- Vidéos changement de kit de chaîne de distribution
	- https://www.youtube.com/watch?v=hp8RKApbcxc
	- https://www.youtube.com/watch?v=VoPz9sEvYN4
	- https://www.youtube.com/watch?v=hdM0t7FYGOA
	- https://www.youtube.com/watch?v=8Wpdm_36_6o
- Autre source de fuite : joint villebrequin Shaft seal 61X75X8 Qty:1 ; OE: 11117568264. 
	- À remplacer au moment de la distri si possible?
	- MINI Cooper Front Crankshaft Seal Installer (suits N12, N14, N16, N18 engines)
		- Schwaben 003413SCH01A
			- just tighten the three inner bolts over the front crankshaft to attach the inner piece of the tool
			- insert the seal into the outer portion of the tool
			- then place the outer portion over the now-attached stud
			- use the included pushing nut to press it securely onto the front crankshaft. 
			- The included pushing nut ensures uniform pressure, preventing leaks and ensuring optimal engine performance.
		- [119600](./docs/crankshaft-seal-tool-engine-n12-ep6.jpg) / 1 19 600
		- 11117568264
		- 83300495926
		- 11311439853
		- TCS 46127
		- 83300495940
### Tensioner
- À minima, il faudrait changer le tendeur car la pièce originale posait problème (trop courte).
- Il semble qu'il y ait eu 3 versions de cette pièce.
- On voit souvent que la pièce mise à jour à un petit trou central côté écrou (extérieur). 
- Pourtant, une pièce commandée chez BMW en 2026 est bel et bien plus longue et plus dure mais sans ce trou.
- C'est une des causes du claquement à froid ("rattle of death" like marbles in a tin can), plutôt sur les Cooper S.
	- La chaîne pas assez tendue claque sur le guide ou sur la paroi du moteur.
	- On l'entend moins à chaud car le tendeur est hydraulique et se charge d'huile à chaud
- tensionneur chaîne **11317607551** remplace 11314609482.
- Joint (11317631972) à renouveler à chaque manipulation. 
- Normalement, pour le changer, il faudrait tout de même caler la distribution:
	- Haynes "Before the tensioner is removed, make sure camshafts and crankshaft are locked in position." (2A-6 / 6.11 [^Haynes])
	- Le risque serait de sauter une dent je présume.
- La monte d'origine d'ailleurs est souvent pas suffisamment serrée et une cause de fuite.
- https://www.youtube.com/watch?v=xbtgm9kZe30 : le gars s'emmerde pas avec le calage!
### Vanos solenoids
- peuvent être encrassés, notamment si problème de ralenti
- https://www.pelicanparts.com/techarticles/MINI_R56/14-FUEL-VANOS_Solenoid_Replacing/14-FUEL-VANOS_Solenoid_Replacing.htm

## Reniflard
- Il convoie les vapeurs d'huiles du haut du moteur vers l'admission (pour les brûler avec les explosions).
- Semble être une maladie. C'est un plastique dur qui devient cassant, je ne sais pas si c'est à cause des contraintes mécaniques ou si c'est la matière.
- S'il est cassé ou fendu, cela cause un suintement. La courroie d'accessoires (sensible à l'huile) n'est pas loin.
- Il existe une version climat extrêmes (avec une sonde en plus dessus). 
	- J'ai pris celui-là l'extrémité côté papillon/admission est métallique, 
	- je me suis dit que ce serait plus solide et moins sujet à fuites à cet endroit (même si la sonde n'est pas branchée).
- Renforcé environ 35 euro : Gates EMH229 ou 7471-00229; OE 11157569967, **11157612996**, 11157592995
- Standard Environ 25 euro : Gates EMG442 ou 7471-00442; OE 11157568081, **11157555261**.
- Penser à changer joint du boîtier [papillon](#papillon) lors de l'opération.
- Soit enlever et sortir le collecteur d'admission : 
	- https://www.youtube.com/watch?v=dewmOqi0oZU
- Soit simplement dévisser ce collecteur pour l'écarter (attention, il y a des écrous dessus mais aussi une ou deux vis derrière en dessous).
	- Dans ce cas, il faudra travailler un peu sous la voiture, démonter quelques trucs autour du démarreur pour pouvoir bien brancher le reniflard sur l'admission.
- On peut en profiter pour changer les joints du collecteur aussi.
- Note : il y a un ordre et couple de serrage des écrous du collecteur d'admission.

## Admission
### Collecteur d'admission
- [Ordre de serrage et couple - vidéo](https://youtu.be/Rcj1SJjjm4A?t=71)
	- 5 vis, d'abord milieu puis droite puis extrême droite puis gauche puis extrême gauche
	- couple 20 Nm
### Papillon
- Joint Elring 895.580, OE 11617528174 (environ 5 euro).
- Vissage: https://youtu.be/Rcj1SJjjm4A?t=1045

## PCV Valve
![PCV Valve](./docs/meat-doria_91669.jpg "Meat&Doria PCV Valve")
- Fait normalement partie du couvre culasse mais on peut le trouver au détail (environ 25 euro) :
	- VAICO V20-3344 PCV valve
	- Meat & Doria 91669
- Certains présentent cela comme la solution miracle aux surconsommations d'huile. 
- C'est peut-être vrai si le joint est abîmé.
- https://www.youtube.com/watch?v=lKcHQOotoJQ
- Attention, il y a peut-être un couple de serrage pour les vis du cache, à vérifier.

## Barre stab arrières
- Silent blocs: il y a 2 diamètres, il faut mesurer avant de commander.
	- Version 16mm : 33556754823. Rappel, utiliser un liquide de montage spécial (OE 83192405829) ou de la graisse silicone qui n'abîme pas le caoutchouc.
	- Version 18mm : 33556772788.
- On pourrait aussi changer les 2x2 vis des supports de silentblocs M8X12-8.8-ZNS3 07119904134.
- Bielettes : 33506772789.
	- Hexagon nut with collar M10-10 ZNS3 (x4) 33326768884, normalement fournies avec les biellettes.

## Filtre habitacle
- Se change par l'intérieur, sous la boîte à gants. 
- Préférer Purflux au charbon actif, il existe des versions anti-bactérien, à creuser.
- Note : il n'est pas monté à plat et visible de l'extérieur derrière la batterie.
- OE: 64317944407 / 64319127516

## Light
- H4
- plate : c5w / 5W (5 watts) / 12V 

## Clé télécommande
- Contient une pile lithium qui se recharge une fois insérée.
- Après un passage à la machine à laver et un changement de la pile, elle semble envoyer erratiquement une commande d'ouverture du coffre.

## Extérieur
### Ecrou antivol
Il faut compter le nombre de dents, on peut ansuite le trouver sur Internet. 
### Support fixation cric
- OE 51717039760
- Testé et approuvé AIC Jürgen Liebisch GmbH réf : 55712 (env. 11,50 euro).
### Peinture
- On trouve le code couleur sur la plaque signalétique port côté droit il me semble.
- Pinceau de retouche. 
- Comment l'embellir ?
### Carters plastiques devant le pare-brise
- Pour les modèles où la batterie est à côté droit dans le sens de la marche: 
	- Carter gauche 51132751209
	- Carter droit  51132751210
	- Joint entre pare-brise et carters : 51312756196, impossible à mettre, sûrement parce que le pare-brise a été changé...
	- Joint latéral 51132756405, est clipsé verticalement sous le carter droit, normalement protégé donc inutile de la changer.

## Intérieur
### Nettoyage
Comment soigner les cuirs et les tissus ?
### Sièges
- Les dossiers des sièges avant ont du jeu.
- Il y a un couinement de petit oiseau dans un siège arrière qui est absent banquettes rabattues.
### Tapis
Il faut le percer ?

## Quincaillerie
- Ecrous plastique 10mm : 51161943122 (Restagraf 12665) ou 07147336362 (ou 07147221224 mais peu répandus)
- Rivets plastiques (notamment passages de roue) : 
	- Référence constructeur : 94530623, 91503-SP0-003, 07 13 0 702 966
	- Pour numéro OE : 91503SP0003, 07130702966, 94530623
	- Restagraf réf. 11755 (x8) / réf. 228171 (x4) / réf. 42661 (x100)
	- Il faudrait en trouver des dimensions équivalentes (à pousser par ex.) car à dévisser comme ceux-là, ça ne fonctionne pas bien.
- Agraphes métal 07146981767, Restagraf 11964.

### Pour passages de roue :
#### Front
- Hex bolt with washer 	M6X20 	X4 			07147151867
- vis torx et rondelle x4 : 51712754669
- C-clip nut 		X2 			07146981767

#### Rear
- Agraphes clips x2 : 51451949950  / 07146988451.
- fillister head screw x2 : 07147115231  / 07147146367

## Couples serrage
- roues : 140 Nm (semble beaucoup) (1A-2[^Haynes])
- filtre huile : 25 Nm (1A-2[^Haynes])
- bouchon huile : 30 Nm (1A-2[^Haynes])
- bougies : 23 Nm (1A-2[^Haynes])
- tendeur chaîne : 65Nm (2A-2[^Haynes]).
- carter moteur (bobines) ?
- couvre culasse 10 Nm (https://youtu.be/Rcj1SJjjm4A?t=983)
- carter huile ?
- écrous collecteur admission ?
- support silent-blocs barre stab ar ?
- papillon 3 vis torx : 10 Nm (4A-2[^Haynes], [^manu-classic-car], note: me semble un peu trop

## Essuies-glaces
### Arrière
Balai d'essuie-glace VALEO 574247 VR30.

## Resources
- realoem.com
- http://distributionthp.free.fr/ressources/argus_enquete_moteurs_psa_vti_thp.pdf [local copy](./docs/argus_enquete_moteurs_psa_vti_thp.pdf)
[^manu-classic-car]: Manu Classic Car
[^Haynes]: Haynes
[^Manuel]: Manuel de la voiture
