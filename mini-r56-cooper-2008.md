# Petrol motors 
This page considers a Cooper 120 hp 120 ch 1.6L model year 2008: N12 (N12B16) équivaut à PSA EP6.

From [3] 2A-1:
- 1.4L 1397cc N12B14
- 1.6L 1598cc
	- Non-turbo (up to 2010) N12B16
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

<cite> Un truc simple : ton autoradio (lecteur CD) est gris, c'est une pré-facelift. ton autoradio est noir, c'est une facelift. </cite>

# Battery
- Varta A7 form-factor.
- Cale B13
- AGM or EFB should be prefered (due to start & stop).
- Note that start and stop is capricious, don't expect much.
- I've seen a Bosch none EFB/AGM battery running for 7 years.

# Brake
Prefer dedicated grease such as Bosch Superfit TO 100 instead of copper grease as we used to. 
## Pads
## Discs
- Rear wear min thickness: 8.4 mm.
- Delphi bg3662 or bg3662c (newer, do not require to be cleaned).

# Sièges
- Les dossiers des sièges avant ont du jeu.
- Il y a un couinement de petit oiseau dans un siège arrière qui est absent banquettes rabattues.
# Tempétature moteur
N'est pas affichée, certainement pour ne pas effrayer l'utilisateur car elle monte haut et varie beaucoup sur ces moteurs [2].

# Infotainment
## Réglages
Heure
## Consultations des défauts
## Remise à zéro entretien

# Vidange huile moteur
- Filtre Purflux (ce sont les meilleurs), L358A (OE 11427622446).
- Huile
	- BMW LL-04 Long-life 04. ([3] 0-16)
	- Pour appoint, SAE 0W-30; SAE 5W-30 ou ACEA A3 possible. ([3] 0-16)
	- Total Classic 9 LL 5W-30
	- Total Classic 9 C3 5W-30
	- Evolution FULLTECH LLX 5W-30
	- Quartz Ineo Long Life 5W-30
	- Quartz Ineo RCP 5W-30

0W30 consomme plus mais c'est mieux pour la visco à froid de ce moteur, surtout pour les petits trajets donc.
Il semble que plus une huile répond à de normes, plus elle est performante car cela demande d'ajouter plus de coûteux additifs.
Dans le doute, on préfèrera une huile qui répond à beaucoup de normes.

- Joint cuivre diamétre int 16mm et ext 22mm (Restagraf 227372 x4), OE 11 13 7 546 275 / 11137546275 / 12617546239.
- Bouchon (et joint) : OE 11137546274, 11137585928.
- https://static.nhtsa.gov/odi/tsbs/2016/MC-10147575-9999.pdf

# Jauge moteur
Illisible. Trouvable à moins de 10 euro. Attention cependant les autres modèles peuvent être plus larges entre min et max!
- **MINI 11 43 7 585 970 / 11437585970**
- PEUGEOT / CITROËN / DS 1174.A4
- PEUGEOT / CITROËN / OPEL / DS 98 307 794 80
- MINI 11 43 7 549 422 / 11437549422
- MINI 11 43 7 561 567 / 11437561567
- MINI 11 43 7 566 021 / 11437566021
- MINI 11 43 7 568 567 / 11437568567

# Thermostat et boîtier de thermostat
- Le boîtier a tendance à se fendre (corps en plastique) et donc fuire.
- Le thermostat ne se démonte pas de ce boîtier. On ne le changera donc pas seul.
- Il a une prise de sonde de température d'eau, connecteur vert en plastique vert sur le faisceu qui devient cassant (sûrement à cause du colorant du plastique).
	- Elle est difficile à trouver mais on tentera de bricoler un faisceau.
- There is another plug to heat-control the internal wax.

## Code P0597 Thermostat Heater Control Circuit/Open
- "Control Circuit open": circuit refers to an electrical device and "control" corroborates it is not the coolant system that is open.
- Il semble qu'un tel thermostat contrôlé électriquement devrait présenter une résitance de 10 Ohm à 30 Ohm et est ouvert quand la pièce est défectueuse.
- Il faudrait mesurer la résistance pour diagnostiquer un problème.
- On pourrait peut-être aussi tester le faisceau avant de remplacer la pièce, mais comment?
- On présume que par défaut le circuit de liquide est ouvert (le moins dangereux) et qu'au démarrage à froid, le calculateur alimente à 12V pour chauffer la cire, 
fermer le circuit et ainsi accélérer la chauffe.
- Il semble que ce soit un fonctionnement on/off (12V ou 0V).

# Courroie alternateur
- 11287566789 (6K X 905)

# Distribution
- Serait conseillée tous les 150000km [2].
- J'avais pensé arbitrairement 160000km.
- Il semble que des morceaux de guide finissent par se promener
	- On vérifiera bien l'intégrité des guides au démontage.
	- S'il manque des morceaux, ils peuvent être dans la crépine de la pompe à huile immergée ou au fond du carter.
	- Dans les 2 cas, il faut démonter le carter et refaire son joint à la pâte.
- [Tuto changement](https://forum-auto.caradisiac.com/topic/480032-probl%C3%A8me-de-chaine-de-distribution-r%C3%A9solue-moteur-thp-mini-jcw/)
	## Tensionner
	- À minima, il faudrait changer le tendeur car la pièce originale posait problème (trop courte).
	- C'est une des causes du claquement à froid (death rattle), plutôt sur les Cooper S. La chaîne pas assez tendue claque sur le guide.
	- tensionneur chaine 11317607551 remplace 11314609482.
	- Joint (11317631972) à renouveler à chaque manipulation. 
	- On voit souvent que la pièce mise à jour à un petit trou central côté écrou (extérieur). 
Pourtant, une pièce commandée chez BMW en 2026 est bel et bien plus longue et plus dure mais sans ce trou.
	- Normalement, pour le changer, il faudrait tout de même caler la distribution:
		- Haynes "Before the tensioner is removed, make sure camshafts and crankshaft are locked in position." ([3] 2A-6 / 6.11)
		- Le risque serait de sauter une dent je présume.
	- La monte d'origine est souvent pas suffisamment serrée et est une cause de fuite.
	- https://www.youtube.com/watch?v=xbtgm9kZe30 : le gars s'emmerde pas avec le calage! 

- Autre source de fuite : joint villebrequin Shaft seal 61X75X8 Qty:1 ; OE: 11117568264. 
- À remplacer au moment de la distri si possible?

# Reniflard
- Il convoie les vapeurs d'huiles du haut du moteur vers l'admission (pour les brûler avec les explosions).
- Semble être une maladie. C'est un plastique dur qui devient cassant, je ne sais pas si c'est à cause des contraintes mécaniques ou si c'est la matière.
- S'il est cassé ou fendu, cela cause un suintement. La courroie d'accessoires (sensible à l'huile) n'est pas loin.
- Il existe une version climat extrêmes (avec une sonde en plus dessus). 
	- J'ai pris celui-là l'extrémité côté papillon/admission est métallique, 
	- je me suis dit que ce serait plus solide et moins sujet à fuites à cet endroit (même si la sonde n'est pas branchée).
- Renforcé environ 35 euro : Gates EMH229 ou 7471-00229; OE 11157569967, **11157612996**, 11157592995
- Standard Environ 25 euro : Gates EMG442 ou 7471-00442; OE 11157568081, **11157555261**.
- Penser à changer joint du boîtier papillon lors de l'opération (cf. section).
- Soit enlever sortir le collecteur d'admission : 
	- https://www.youtube.com/watch?v=dewmOqi0oZU
- Soit simplement dévisser ce collecteur pour l'écarter (attention, il y a des écrous dessus mais aussi une ou deux vis derrière en dessous).
	- Dans ce cas, il faudra travailler un peu sous la voiture, démonter quelques trucs autour du démarreur pour pouvoir bien brancher le reniflard sur l'admission.
- On peut en profiter pour changer les joints du collecteur aussi.
- Note : il y a un ordre de serrage des écrous du collecteur d'admission.

# Papillon
Joint Elring 895.580, OE 11617528174 (environ 5 euro).

# PCV Valve
![PCV Valve](./meat-doria_91669.jpg "Meat&Doria PCV Valve")
- Fait normalement partie du couvre culasse mais on peut le trouver au détail (environ 25 euro) :
	- VAICO V20-3344 PCV valve
	- Meat & Doria 91669
- Certains présentes cela comme la solution miracle aux surconsommations d'huile. 
- C'est peut-être vrai si le joint est abîmé.
- https://www.youtube.com/watch?v=lKcHQOotoJQ
- Attention, il y a peut-être un couple de serrage pour les vis du cache, à vérifier.

# Barre stab arrières
- Silent blocs: il y a 2 diamètres, il faut mesurer avant de commander.
	- Version 16mm : 33556754823. Rappel, utiliser un liquide de montage spécial (OE 83192405829) ou de la graisse silicone qui n'abîme pas le caoutchouc.
	- Version 18mm : 33556772788.
- On pourrait changer les 2x2 vis des supports de silentblocs M8X12-8.8-ZNS3 07119904134.
- Bielettes : 33506772789.
	- Hexagon nut with collar M10-10 ZNS3 (x4) 33326768884, normalement fournies avec les biellettes.

# Support fixation cric
- OE 51717039760
- Testé et approuvé AIC Jürgen Liebisch GmbH réf : 55712 (env. 11,50 euro).

# Filtre habitable
- Se change par l'intérieur, sous la boîte à gants. 
- Préférer Purflux au charbon actif, il existe des versions anti-bactérien, à creuser.
- Note : il n'est pas monté à plat et visible de l'extérieur derrière la batterie.
- OE: 64317944407 / 64319127516

# Light
H4

# Ecrou antivol
Il faut compter le nombre de dents, on peut ansuite le trouver sur Internet. 

# Carrosserie
## Peinture
- On trouve le code couleur sur la plaque signalétique port côté droit il me semble.
- Pinceau de retouche. 
- Comment l'embellir ?
## Carters plastiques devant le pare-brise
- Pour les modèles où la batterie est à côté droit dans le sens de la marche: 
	- Carter gauche 51132751209
	- Carter droit  51132751210
	- Joint entre pare-brise et carters : 51312756196, impossible à mettre, sûrement parce que le pare-brise a été changé...
	- Joint latéral 51132756405, est clipsé verticalement sous le carter droit, normalement protégé donc inutile de la changer.

# Clé télécommande
- Contient une pile lithium qui se recharge une fois insérée.
- Après un passage à la machine à laver et un changement de la pile, elle semble envoyer erratiquement une commande d'ouverture du coffre.

# Nettoyage
Comment soigner les cuirs et les tissus ?

# Quincaillerie
- Ecrous plastique 10mm : 51161943122 (Restagraf 12665) ou 07147336362 (ou 07147221224 mais peu répandus)
- Rivets plastiques (notamment passages de roue) : 
	- Référence constructeur : 94530623, 91503-SP0-003, 07 13 0 702 966
	- Pour numéro OE : 91503SP0003, 07130702966, 94530623
	- Restagraf réf. 11755 (x8) / réf. 228171 (x4) / réf. 42661 (x100)
	- Il faudrait en trouver des dimensions équivalentes (à pousser par ex.) car à dévisser comme ceux-là, ça ne fonctionne pas bien.
- Agraphes métal 07146981767, Restagraf 11964.
	## Pour passages de roue :
		### Front
		- Hex bolt with washer 	M6X20 	X4 			07147151867
		- vis torx et rondelle x4 : 51712754669
		- C-clip nut 		X2 			07146981767

		### Rear
		- Agraphes clips x2 : 51451949950  / 07146988451.
		- fillister head screw x2 : 07147115231  / 07147146367

# Tapis
Il faut le percer ?

# Petrol filter
- Cannot be renewed, in case of probem, the whole assembly needs to be replaced
- https://forum-auto.caradisiac.com/topic/87804-remplacer-le-filtre-%C3%A0-essence-cooper-120cv-de-2009/
- We come over OE: 11252754870 sometimes but not sure it can fit somewhere.

# Couples serrage
- roues : 140 Nm (semble beaucoup) ([3] 1A-2)
- filtre huile : 25 Nm ([3] 1A-2)
- bouchon huile : 30 Nm ([3] 1A-2)
- bougies : 23 Nm ([3] 1A-2)
- tendeur chaîne : 65Nm ([3] 2A-2).
- carter moteur (bobines) ?
- carter huile ?
- écrous collecteur admission ?
- support silent-blocs barre stab ar ?

# Liquides
Huile BMW LL-04, long-life 04, qté 4.2L

# Essuies-glaces
## Arrière
Balai d'essuie-glace VALEO 574247 VR30.

# Resources
- realoem.com
- [2] Manu Classic Car
- [3] Haynes
- http://distributionthp.free.fr/ressources/argus_enquete_moteurs_psa_vti_thp.pdf [local copy](./argus_enquete_moteurs_psa_vti_thp.pdf)
