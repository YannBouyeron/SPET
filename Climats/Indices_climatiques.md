# Les indices climatiques.

La prévision des climats futurs nécessite l’identification des principaux paramètres responsables des variations climatiques. Cette identification des facteurs responsables des fluctuations climatiques est à rechercher dans l’analyse des climats passés ou paléoclimats.
Il faut pour cela trouver des indices climatiques permettant de reconstituer les paléoclimats.

[Lien vers les fichiers excel paléoclimatologie](https://github.com/YannBouyeron/SVT-TS/tree/master/SPE-Climat/Excel%20Paleoclimatologie)

## Le delta isotopique des glaces polaires.

Les calottes glaciaires qui recouvrent les pôles sont constituées d'une accumulation de neige déposée années après années et compressée sous son propre poids. Les [carottes](https://ipfs.io/ipfs/QmTn4z8to4KTHiudDpuX6ZBV2q3vWB3PCSxtJipsmu1334) de glace extraites de certains forages donnent accès à des échantillons de glace issus de précipitations neigeuses dont l'âge dépend de la profondeur de l'échantillon. En certains forages, les glaces les plus profondes ont jusqu'à 800 000 ans.

Il existe plusieurs isotopes stables de l'oxygène dont <sup>16</sup>O et <sup>18</sup>O qui sont les plus abondants (respectivement 99,8 % et 0,2 %). On les retrouve dans tous les composés oxygénés naturels, notamment l'eau et les carbonates. L'eau (océan, vapeur, pluie, glace, etc.) est constituée essentiellement à partir de l'isotope 16 de l'oxygène qui est le plus répandu.

### La notion de delta isotopique.

Le δ<sup>18</sup>O indique la différence entre le rapport <sup>18</sup>O / <sup>16</sup>O mesuré dans échantillon d'eau et le rapport <sup>18</sup>O / <sup>16</sup>O moyen des océans actuels  (nommé SMOW). Il est exprimé en pour mille et il se calcule selon la formule suivante :

<p align="center">δ<sup>18</sup>O = 1000 . [(<sup>18</sup>O/<sup>16</sup>O)<sub>mesuré</sub> / (<sup>18</sup>O/<sup>16</sup>O)<sub>SMOW</sub> - 1]</p>

SMOW désigne la composition moyenne de l’océan (Standard Mean Ocean Water), qui vaut :  (<sup>18</sup>O/<sup>16</sup>O)<sub>SMOW</sub> = 2005,2.10-6

Lorsque la concentration en <sup>18</sup>O de l'eau diminue le δ<sup>18</sup>O diminue.

### Les variations du δ<sup>18</sup>O.

<p align="center">Moyennes mensuelles du δ<sup>18</sup>O des eaux de précipitation:</p>

 
<table>

<tr>
<td><img src="http://acces.ens-lyon.fr/acces/thematiques/paleo/variations/paleoclimats/images/glob2-O18.gif" alt=""></td>
    
<td><img src="http://acces.ens-lyon.fr/acces/thematiques/paleo/variations/paleoclimats/images/glob3-O18.gif" alt=""></td> 
    
</tr>
</table>


Le δ<sup>18</sup>O varie en fonction de la latitude: plus la latitude est élevée plus le δ<sup>18</sup>O est faible. Le δ<sup>18</sup>O varie aussi en fonction du temps (saisons); il est plus faible en janvier qu'en juillet. La variation temporelle s'observe surtout aux hautes latitudes.

Ces variations spatiales et temporelles suggèrent une influence de la température sur le δ<sup>18</sup>O. Pour tester cette hypothèse il faut mesurer la corrélation entre le δ<sup>18</sup>O et la température:

### Étude de la corrélation δ<sup>18</sup>O / température.

Le dossier temp_<sup>18</sup>O contient des fichiers xlsx mettant en relation la date, le δ<sup>18</sup>O mesuré dans l’eau de pluie et la température mesurée , en différents lieux. On peut donc tracer les graphiques suivants : δ<sup>18</sup>O = f(température) et afficher leurs droites de régression, ainsi que leurs équations et coefficients de corrélation R, pour différents lieux.



<table>

<tr>
<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/halley.png" alt=""></td>
    
<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/murmansk.png" alt=""></td> 

</tr>

<tr>

<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/barrow.png" alt=""></td> 

<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/kinshasa.png" alt=""></td> 

</tr>
</table>



En fonction du lieu choisi, il n'existe pas toujours une corrélation entre les valeurs du δ<sup>18</sup>O des eaux de précipitations et la moyenne mensuelle (ou annuelle) des températures de l'air. La corrélation est forte (les points s'alignent) aux hautes latitudes (Pôles), mais très faibles (mauvais alignement, points dispersés) aux faibles latitudes (Équateur).

La corrélation observée entre t° et δ<sup>18</sup>O aux hautes latitudes est une corrélation positive: une augmentation de la température de l'air est corrélée à une augmentation du δ<sup>18</sup>O des précipitations. Les informations relatives à la notion de δ isotopique et au principe de fractionnement isotopique de l'oxygène, permettent de préciser le sens de la corrélation: c'est l'augmentation de la température de l'air qui induit l'augmentation du δ<sup>18</sup>O des eaux de précipitations. Une augmentation du δ<sup>18</sup>O traduit donc une augmentation de la température. Et inversement. 

### Application.

Aux hautes latitudes, si on connaît (mesure) le δ<sup>18</sup>O, on peut alors déterminer la température de l'air au moment de la précipitation grâce à l'équation de la droite de régression. Le δ<sup>18</sup>O constitue ainsi un thermomètre isotopique.

Les équations des droites de régression varient en fonction de la localisation. L’utilisation du δ<sup>18</sup>O pour reconstituer les variations paléoclimatiques en un lieu donné nécessite donc d’utiliser l’équation spécifique à ce lieu.

<p align="center"> <img src="http://acces.ens-lyon.fr/acces/thematiques/paleo/variations/paleoclimats/images/cor_temp.gif" alt=""></p>


<i>Jouzel J., C. Lorius, S. Johnsen and P. Grootes, 1994 :  
Climate instabilities : Greenland and Antarctic records. 
Compte Rendu de l'Académie des Sciences de Paris. vol. t. 319, série II, 65-77</i>

Les équations des droites de régression du graphique de Jouzel sont du type : y = a.x + b c'est à dire δ = a.(Température) + b            
Donc: Température = (δ - b) / a 

On peut donc mesurer graphiquement cette relation à partir du graphique de Jouzel:

- À vostok (Antarctique): t° = (δD + 31,5) / 6,5
- À GRIP (Arctique): t° = (δ<sup>18</sup>O + 14) / 0,66

Les carottes de glaces, issues des forages réalisés en Antarctique (pôle Sud) et au Groenland (pôle Nord), donnent accès à des échantillons de glaces anciennes que l'on peut dater (plus la profondeur de la carotte est élevée, plus la glace est âgée) et sur lesquelles on peut mesurer le delta isotopique. 

Le dossier ice_<sup>18</sup>O contient des fichiers xlsx qui mettent en relation, pour différents forages, l’âge de la glace, et le δ<sup>18</sup>O mesuré:

<table>

<tr>
<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/delta_vostok.png" alt=""></td>
    
<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/delta_grip.png" alt=""></td> 

</tr>
</table>




Connaissant la relation entre la température et le delta isotopique de l'eau (équations des droites de Jouzel à Vostok et à GRIP),  on peut alors déterminer la température qui régnait au moment des précipitations à l'origine des échantillons de glace en antarctique et en arctique:

<table>

<tr>
<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/temp_vostok.png" alt=""></td>
    
<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/temp_grip.png" alt=""></td> 

</tr>
</table>


L'application de l'équation de la droite de Jouzel montre que la température actuelle en Antarctique est de - 62°, alors qu'il y a 21000 ans lors du dernier minima du δD la température était de -70°. Il y' a 21000 ans la température au dessus de l'antarctique était inférieure de 8°C à la température actuelle. On trouve un écart de 10° C pour le Groenland.

L'analyse du δ<sup>18</sup>O (ou du δD) des carottes glaciaires met ainsi en évidence sur 400 000 ans une alternance de périodes froides (δ faible) et de périodes chaudes (δ élevé) avec un écart de température d'une dizaine de degrés Celsius. Ces périodes sont approximativement synchrones en Antarctique et au Groenland. Il s'agit donc de changements globaux d'un ou plusieurs paramètres du climat. Ces périodes "froides" (périodes glaciaires) ont une périodicité de 100 000 ans et sont entrecoupées de périodes chaudes (périodes inter-glaciaires) d'environ 10 000 ans.

## Le delta isotopique des foraminifères benthiques.

Les foraminifères sont des organismes unicellulaires hétérotrophes (protozoaires) aquatiques. Ils vivent dans un test calcaire («coquille» constituée de carbonate de calcium: CaCO3 contenant du <sup>18</sup>O et du <sup>16</sup>O) qui s'accumule à leur mort dans certaines conditions sur les fonds marins. Le groupe est très diversifié tant d'un point de vue morphologique que biologique. Ainsi certaines espèces sont planctoniques alors que d'autres vivent sur les fonds océaniques (on les dit alors benthiques) où la température est considérée constante au cours du temps.




### Les facteurs influençant le δ<sup>18</sup>O des foraminifères 


Le δ<sup>18</sup>O des foraminifères dépend de la température et du δ<sup>18</sup>O de l'eau de mer: 

- Corrélation positive entre le δ<sup>18</sup>O des foraminifères et le δ<sup>18</sup>O de l'eau de mer:      

<h6 align="center">δ<sup>18</sup>O foraminifères = f (δ<sup>18</sup>O eau de mer)</h6>

- Corrélation négative entre le δ<sup>18</sup>O des foraminifères et la température de l'eau de mer:     

<h6 align="center">δ<sup>18</sup>O foraminifères = - f (T° eau)</h6>



Les foraminifères benthiques (FB) vivent au fond des océans où la température est constante; le δ<sup>18</sup>O des foraminifères benthiques dépend donc uniquement du δ<sup>18</sup>O de l'eau: il existe une corrélation positive entre le δ<sup>18</sup>O des foraminifères benthiques et le δ<sup>18</sup>O de l'eau de mer: 

<h6 align="center">δ<sup>18</sup>O FB = f (δ<sup>18</sup>O eau de mer)</h6>

### Les facteurs influençant le δ<sup>18</sup>O de l’eau des océans

En période plus froide qu'actuellement, l'eau s'évapore sous les tropiques, précipite sous forme de neige et s'accumule sous forme de glace dans les glaciers et les calottes polaires; donc le volume des océans diminue tandis que le volume des calottes polaires augmente. 
L'eau qui s'évapore des océans et qui s'accumule sous forme de glace est appauvrie en <sup>18</sup>O ( δ<sup>18</sup>O de la glace polaire = -40 à – 50 pour mille); l'eau qui reste dans les océans se retrouve donc relativement enrichie en <sup>18</sup>O; le δ<sup>18</sup>O de l'eau de mer est alors supérieur à l'actuel c'est à dire supérieur à 0.

<p></p>

En période plus chaude qu'actuellement, la glace des calottes polaires fond et le volume des océans augmente. 
L'eau provenant de la fonte des calottes polaires qui retourne aux océans est appauvrie en <sup>18</sup>O; le δ<sup>18</sup>O de l'eau de mer diminue et devient alors inférieur à l'actuel c'est à dire inférieur à 0

<p></p>

On en déduit que le δ<sup>18</sup>O de l'eau de mer dépend du volume relatif entre les océans et les calottes glaciaires: il existe une corrélation positive entre le δ<sup>18</sup>O de l'eau de mer et le volume des calottes glaciaires: 

<h6 align="center">δ<sup>18</sup>O eau de mer = f (volume calottes glaciaires)</h6>


Le volume des calottes glaciaires dépend du climat global:

<h6 align="center"> V calottes = -f (T° globale)</h6>

Le δ<sup>18</sup>O de l'eau de mer dépend donc aussi du climat global: il existe une corrélation négative entre le δ<sup>18</sup>O de l'eau de mer et la température globale: 

<h6 align= "center">δ<sup>18</sup>O eau de mer = - f (T° globale)</h6>




Il existe donc une corrélation négative entre le δ<sup>18</sup>O des FB et le climat global:   

<h6 align="center"> δ<sup>18</sup>O FB = - f (T° globale) </h6>


Les forages des fonds océaniques donnent accès à des sédiments océaniques contenant des restes de tests calcaires de foraminifères que l'on peut dater (plus les sédiments sont profonds plus ils sont anciens). Ces données sont disponibles dans le dossier ocean_o18. En mesurant le δ<sup>18</sup>O de ces tests calcaires, et connaissant la relation ci dessus, il est alors possible de reconstituer les variations paléo-climatiques:

- Une augmentation du δ<sup>18</sup>O des FB témoigne d'une augmentation du volume des calottes glaciaires, c'est à dire d'un refroidissement climatique. 

- Une diminution du δ<sup>18</sup>O des FB témoigne d'une diminution du volume des calottes glaciaires, c'est à dire  d'un réchauffement climatique.   

<table>

<tr>
<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/75D13DDD-D4A1-452F-BE36-0FF4B9A2070C.png" alt=""></td>
    
<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/BF36B891-1BD7-46B0-B487-C4BD165AC9BA.png" alt=""></td> 


<td><img src="https://github.com/YannBouyeron/SVT-TS/blob/master/SPE-Climat/doc/F0D26D5F-1C26-4AFE-827C-4E6734A5E6D9.png" alt=""></td> 

</tr>
</table>



Le δ<sup>18</sup>O des foraminifères benthiques dépend du volume relatif océans / calottes glaciaires et donc du climat. Les mesures du δ<sup>18</sup>O des tests calcaires des foraminifères benthiques des sédiments océaniques, mettent ainsi en évidence une alternance de périodes à δ<sup>18</sup>O des formainifères benthiques élevé c'est à dire des périodes plus froides qu'actuellement (périodes glaciaires d'environ 80 000 ans) , entrecoupées de périodes à δ<sup>18</sup>O des foraminifères benthiques faible c'est à dire des périodes plus chaudes qu'actuellement (périodes interglaciaires d'environ 15 000 ans). Ces résultats sont concordants (mêmes variations paléo-climatiques) sur les trois forages océaniques étudiés, et concordants avec les résultats issus du delta isotopique des glaces polaires; ils traduisent des changements climatiques globaux à l'échelle planétaire.


## La palynologie

Les archives climatiques enregistrées dans les glaces ou les Foraminifères montrent des alternances périodiques entre des climats glaciaires et interglaciaires. On dispose d’autres archives pour étudier les climats anciens : les pollens.


### La relation entre le climat et les peuplements végétaux

Chaque espèce végétale présente des exigences ou des préférences climatiques particulières principalement en relation avec la pluviométrie et les températures saisonnières. Le développement d'une espèce végétale en un lieu donné dépend donc de ces conditions climatiques. (Rabat livre - Pollens). La répartition géographique des végétaux dépend de leurs exigences écologiques et est donc fonction du climat. La même relation peut s'établir à une échelle plus grande en considérant des peuplements végétaux constitués par l'association de différentes espèces végétales partageant une même zone géographique et ayant les mêmes exigences climatiques (Document 2 page 82): la nature d'un peuplement végétal est  un indicateur du climat.

La vallée de Wormsa est peuplée par une forêt tempérée mixte (feuillus et conifères). Ces deux peuplements végétaux peuvent coexister la où leurs exigences climatiques permettent leur développement; c'est a dire entre 2 et 15 °C de température moyenne annuelle, et entre 125 et 175 cm de précipitations annuelles (zone commune verte claire et verte foncée). Ces exigences sont en accord avec les conditions climatiques constatées dans la vallée (9°C de température moyenne annuelle, et 170 cm de précipitations moyennes annuelles).


### La détermination des peuplements végétaux passés

La composition d'un peuplement végétal est donc un indicateur des conditions climatiques qui règnent dans la zone géographique du peuplement à l'instant donné. Pour reconstituer des variations paléo-climatiques, il faut donc déterminer la nature des peuplements végétaux passés; cela est possible grâce à l'étude des pollens anciens issus des lacs et tourbières. 

En effet, les pollens présentent des caractéristiques favorables à ce type d'études:

- Les grains de pollens présentent des formes particulières qui permettent de les distinguer au microscope. 

- Chaque espèce végétale produit un seul type de grain de pollen qui lui est caractéristique. 

- Les grains de pollen possèdent une enveloppe très résistante qui permet leur conservation et leur accumulation dans les sédiments (leur conservation est favorisée par l'acidité des tourbières).

- Les pollens possèdent une forme et une structure qui permet leur dispersion sur une échelle géographique suffisante pour pouvoir s'accumuler dans les tourbières, et telle que la reconstitution réalisée est caractéristique d'un peuplement végétal régional, donc d'un climat local. 


Ainsi, le recensement des pollens présents à une même profondeur d'une carotte de sédiments ou de tourbe (spectre pollinique) permet d’estimer les proportions d’espèces végétales à un âge donné et donc de déterminer le climats régnant sur le site au moment de la sédimentation. (Postulat de base: les espèces dont on utilise le pollen ou les spores existaient déjà au début du Quaternaire et n'ont pas évolué depuis (ni au niveau de leur pollen, ni au niveau de leur écologie... Principe d'actualisme))


### La reconstitution des variations paléo-climatiques à partir de l'analyse des diagrammes polliniques 

Un spectre pollinique permet de réaliser un « instantané » sur le climat régional à l’époque de la sédimentation. Différents spectres polliniques superposés forment un diagramme pollinique qui permet de reconstituer les fluctuations climatiques au cours du temps. On distingue ainsi 4 périodes sur le diagramme pollinique de la vallée de Wormsa (pages [82](https://ipfs.io/ipfs/Qmb3QVGXo3gJSLhsKwBWYfWzmBZesNeEcYVmaVWynBFeDy)-[83](https://ipfs.io/ipfs/QmQiSRTfMP5a96RMVh2zt5JRzp9oTuQqF3WTijrq1dvpd1)):

- De -17000 à -13500 ans: peuplement de type steppe caractéristique d'un climat sec.

- De -13500 à -10000 ans: peuplement de type forêt boréale caractéristique d'un climat plus humide et plus froid.

- De -10000 à -7000 ans: peuplement de type forêt tempérée de feuillus caractéristique d'un climat humide et plus "chaud" (tempéré).

- De -7000 à l'actuel: le peuplement ce modifie un peu (diminution de l'abondance relative du noisetier, augmentation de celles du sapin et du hêtre) mais reste caractéristique d'un climat humide tempéré.

Ce diagramme pollinique met ainsi en évidence un réchauffement climatique régional sur la période considérée.


L'étude de nombreux diagrammes polliniques permet de reconstituer et comparer les peuplements végétaux actuels et ceux d'il y'a 18000 ans à l'échelle de l'Europe. On montre ainsi (page 83) que:

Les glaciers ont régressé au profit de la forêt boréale dans le nord de l'Europe.
La toundra et les déserts péri-glaciaires ont laissé place aux forêts tempérées mixtes et de feuillus au centre de l'Europe.
La steppe arborée et la végétation méditerranéenne se sont développées dans le sud de l'Europe.

Ces modifications des peuplements végétaux témoignent d'un réchauffement climatique à l'échelle de l'Europe.


### Conclusion:

L'étude des pollens issus des différents niveaux des carottes de tourbes permet de caractériser les peuplements végétaux passés à l'échelle régionale. Connaissant les exigences climatiques actuelles des végétaux, et appliquant le principe d'actualisme, il est possible de reconstituer des variations climatique récentes,  locales, en milieu continental. 
