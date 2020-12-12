# La datation absolue.

Au XVIIIe et au XIXe, les géologues posent les fondements de la chronologie relative. Cependant, ils ne possèdent aucun moyen de quantifier le temps écoulé entre un phénomène géologique et la période actuelle, c’est à dire de déterminer l’âge absolu du phénomène. Au cours du XXe siècle, la radio-chronologie permet d'estimer l'âge en années (datation absolue) avec plus ou moins de précision des objets et des évènements géologiques et biologiques. La radio-chronologie est basée sur les propriétés de désintégration de certains éléments radioactifs.

### Propriétés des atomes radioactifs.

La Terre possède naturellement des atomes radioactifs (élément père: P) qui ont la propriété de se désintégrer en émettant une particule énergétique (électron, photon... à l’origine d’un rayonnement) et en donnant naissance à un autre atome stable (élément fils: F). La réaction est la suivante: **P → F + particule**

La vitesse de cette réaction de désintégration à l’instant t est proportionnelle au nombre P d’éléments pères radioactifs: plus la quantité P est élevée, plus la quantité d’éléments F produits est importante, et inversement. Mathématiquement, cette loi fondamentale de la radioactivité s’écrit: **dP/dt = - λ P**

*dP/dt: la variation de P sur l’intervalle de temps dt (vitesse de désintégration) de signe négatif*

*λ : le facteur proportionnel ou constante radioactive ( λ = ln2 / T)*

La fermeture du système correspond au moment (t0) à partir duquel il n’y a plus d’échange entre les éléments chimiques des minéraux d’une roche et le milieu environnant de cette roche. Une fois le système dit « fermé », la quantité d’isotopes radioactifs susceptibles de se désintégrer diminue. Pour les roches magmatiques et métamorphiques, la fermeture du système correspond au moment de la cristallisation de la roche (température en dessous d’un certain seuil). Généralement les roches sédimentaires ne forment pas un système fermé (contamination avec le milieu extérieur à l’échantillon toujours possible).

### L'équation de décroissance radioactive.

Mathématiquement, la loi fondamentale de la radioactivité est une dérivée (pente d’une courbe exprimée en fonction de la variable en abscisse, ici, une vitesse de réaction: variation d’une quantité en fonction du temps) dont la résolution (équation différentielle) exprime les variations de P en fonction du temps sous la forme P = f(t).


Ainsi, si **dP / dt = - λ P** 

Alors **P = P0 e<sup>-λt</sup>** 

Soit **t = [ ln (Po / P) ] / λ** 

<div align=center><a href="https://ipfs.io/ipfs/QmfCdjc87w9VfbqY562VKnLqbCsHRNR4szYXFEA5yepmGM"><img src="https://ipfs.io/ipfs/QmfCdjc87w9VfbqY562VKnLqbCsHRNR4szYXFEA5yepmGM" width=60%></a></div>

D’autre part **F = Fo + (P0 – P)** 

Alors **F=F0 +P(e<sup>λt</sup>–1)** est une équation de type **y = b + a.x** avec **a = e<sup>λt</sup> – 1** donc **t = [ln (a + 1) ]/ λ**


### Développement physique vs développement mathématique.

Mathématiquement, la loi de décroissance radioactive est une suite géométrique de raison q < 1. Les notations diffèrent cependant entre les 2 approches , l’utilisation du symbole λ peut prêter à confusion:

<div align=center width=100%><table width=100%>
<tr><th>Développement physique</br>(Loi de décroissance radioactive)</th><th>Développement mathématique</br>(<a href="https://gist.github.com/YannBouyeron/243714f934852fc9b28887f4b36bf924">Suite géométrique</a>)</th></tr>
<tr><td align=center>dP / dt = - λ P</td><td align=center>dN / dt = r N</td></tr>
<tr><td align=center>λ : constante radioactive (λ = ln(2) / T)</td><td align=center>r : taux de (dé)croissance intrinsèque (r = ln(2) / T)</td></tr>
<tr><td align=center>P = P0 e<sup>-λt</sup></br>On rajoute le signe - car λ est noté en valeur absolue</td><td align=center>Nt =N0 e<sup>rt</td></tr>
<tr><td align=center></td><td align=center>λ : taux de (dé)croissance discret = raison q de la suite</br>λ = e<sup>r</sup></br>r = ln(λ)</td></tr>
<tr><td align=center>T est la période ou demie vie. C'est le temps nécessaire pour que la moitié des noyaux de l'isotope initialement présents se désintègrent naturellement</br>T = ln(2) / λ</td><td align=center>T est considérée comme une demie vie dans le cas d'une décroissance (q < 1), et comme un temps de doublement dans le cas d'une croissance (q > 1)</br>T = ln(2) / r</td></tr> 
</table></div>

### Les couples d’isotopes utilisés en SVT

<div align=center>
<table>
<tr><th>Couples d’isotopes</th><th>Demie vie: T (an)</th><th>Constante radioactive: λ (an<sup>-1</sup>)</th><th>Objet à dater</th><th>Fermeture du système</th><th>Domaine d’utilisation</br>T/100 < âge présumé < 10T</th></tr>

<tr><td align=center><sup>14</sup>C / <sup>14</sup>N</td><td align=center>5,73 . 10<sup>3</sup></td><td align=center>1,21 . 10<sup>-4</sup></td><td align=center>Matière organique</td><td align=center>Mort de l’organisme</td><td align=center>57,3 ans < âge présumé de l'objet < 57300 ans</td></tr>

<tr><td align=center><sup>87</sup>Rb / <sup>87</sup>Sr</td><td align=center>48,8 . 10<sup>9</sup></td><td align=center>1,42 . 10<sup>-11</sup></td><td align=center>Biotite</br>Muscovite</td><td align=center>t° < 300°C</br>t° < 500°C</td><td align=center>100 Ma < âge présumé de l'objet</td></tr>

<tr><td align=center><sup>40</sup>K / <sup>40</sup>Ar</br><sup>40</sup>K / <sup>40</sup>Ca</td><td align=center>1,248 . 10<sup>9</sup></td><td align=center>5,543 . 10<sup>-10</sup></td><td align=center>Biotite</br>Muscovite</br>Hornblende</td><td align=center>t° < 280°C</br>t° < 350°C</br>t° < 530°C</td><td align=center>1 Ma < âge présumé de l'objet < 300 Ma</td></tr>

<tr><td align=center><sup>238</sup>U / <sup>206</sup>Pb</br><sup>235</sup>U / <sup>207</sup>Pb</td><td align=center>4,47 . 10<sup>9</sup></br>703,8 . 10<sup>6</sup></td><td align=center>1,55 . 10<sup>-10</sup></br>9,8485.10<sup>-10</sup></td><td align=center>Zircon</br>Monazite</br>Apatite</td><td align=center>t° < 1000°C</br>t° < 450°C</br>t° < 1000°C</td><td align=center>25 Ma < âge présumé de l’objet</td></tr>




</table></div>

### Le principe de la méthode <sup>14</sup>C (Programme ES classe de première)

Il existe 3 isotopes du carbone: le <sup>12</sup>C et le <sup>13</sup>C qui sont stables; et le <sup>14</sup>C qui est instable: **<sup>14</sup>C → <sup>14</sup>N + énergie**

Le carbone 14 est principalement utilisé pour dater des restes d'êtres vivants (animaux ou végétaux). Tant qu'un individu est vivant, il échange du carbone avec son milieu (alimentation, photosynthèse, respiration); son rapport <sup>14</sup>C/<sup>12</sup>C reste constant durant toute sa vie. 

A sa mort, les échanges de carbone cessent, on considère le système comme étant fermé, la quantité de <sup>14</sup>C diminue du fait de son non renouvellement et de sa désintégration en <sup>14</sup>N.

On considère que le rapport <sup>14</sup>C/<sup>12</sup>C est resté constant au cours des temps géologiques, la concentration initiale de <sup>14</sup>C (<sup>14</sup>Co) est donc égale à la concentration mesurée actuellement dans l'atmosphère; soit <sup>14</sup>Co = 13,56 dpm.

La quantité de <sup>14</sup>C présente dans l'objet à dater peut être mesurée par spectrométrie de masse. Connaissant <sup>14</sup>Co et <sup>14</sup>C on peut appliquer directement la loi de désintégration radioactive pour calculer l'âge de l'objet: **t = [ ln ( <sup>14</sup>Co/ <sup>14</sup>C) ] / λ**


### Le principe de la méthode <sup>87</sup>Rb / <sup>87</sup>Sr

Au cours de leur formation, certains minéraux des roches magmatiques et métamorphiques intègrent quelques atomes du rubidium. Son isotope 87 (<sup>87</sup>Rb) qui est radioactif se désintègre en strontium 87 (<sup>87</sup>Sr): **<sup>87</sup>Rb → <sup>87</sup>Sr + énergie**

Le <sup>87</sup>Sr ayant les mêmes propriétés chimiques que le Ca, il peut se substituer au Ca dans les minéraux qui en incorporent. Le <sup>87</sup>Rb ayant quant à lui les mêmes propriétés chimiques que le K (potassium) , il peut se substituer au K dans les minérux qui en incorporent.

La détermination de l'âge d'une roche par cette méthode est complexe car:

- On ne connait pas la quantité initiale P0 d'élément père (<sup>87</sup>Rb0)

- On ne connait pas non plus la quantité d'élément fils (<sup>87</sup>Sr) provenant uniquement de la désintégration du <sup>87</sup>Rb car les minéraux au moment de leur formation incorporent également une certaine quantité de <sup>87</sup>Sr non radiogénique (non issu de la désintégration d’un élément père radiactif). La quantité de <sup>87</sup>Sr mesurée à l'instant t correspond donc à la quantité initiale de <sup>87</sup>Sr non radiogénique plus la quantité de <sup>87</sup>Sr issue de la désintégration du <sup>87</sup>Rb.

Pour surmonter cette difficulté, il faut des mesures provenant d'au moins deux minéraux d'une même roche (minéraux ayant cristallisé en même temps à partir du même magma = minéraux cogénétiques) et prendre en compte un isotope de référence indispensable pour comparer les mesures des différents échantillons. C'est l'isotope <sup>86</sup>Sr qui est stable (comme <sup>87</sup>Sr) et qui n'est pas radiogénique (contrairement à <sup>87</sup>Sr) qui sert de référence dans ce cas.


<div align=center>
<table>


<tr><td>

<p>À t0, lors de la fermeture du système le rapport <sup>87</sup>Sr/<sup>86</sup>Sr est identique dans tous les minéraux de l'échantillon. Cela s'explique par le fait que les minéraux ont la même affinité pour les deux isotopes du strontium. Ainsi, des minéraux cristallisant à partir d'un même magma intégreront du strontium avec un rapport isotopique <sup>87</sup>Sr / <sup>86</sup>Sr identique à celui du magma d'origine. On dit que ces minéraux sont cogénétiques. Et même si certains minéraux intégreront plus de strontium que d'autres, tous auront le même rapport initial <sup>87</sup>Sr0 / <sup>86</sup>Sr0</p>

<p>À t0, les minéraux possèdent des rapports <sup>87</sup>Rb/<sup>86</sup>Sr différents les uns des autres car ils possèdent chacun une affinité différente pour Rb et Sr.</p></td>

<td><a href="https://ipfs.io/ipfs/QmbmH5khG67P8xQuS5BQZ7tLdcZJnwkUzE4jonCTrHtiXz"><img src="https://ipfs.io/ipfs/QmbmH5khG67P8xQuS5BQZ7tLdcZJnwkUzE4jonCTrHtiXz" alt="" width=4500></a></td></tr>



<tr><td>Au cours du temps, <sup>87</sup>Rb étant radioactif, il se désintègre en <sup>87</sup>Sr; donc la quantité de <sup>87</sup>Rb diminue tandis que la quantité de <sup>87</sup>Sr augmente. Le <sup>86</sup>Sr n'étant ni radioactif ni radiogénique, sa quantité reste constante: <sup>86</sup>Sr0 = <sup>86</sup>Sr actuel. Ainsi le rapport <sup>87</sup>Rb/<sup>86</sup>Sr diminue tandis que le rapport <sup>87</sup>Sr/<sup>86</sup>Sr augmente.</td>

<td><a href="https://ipfs.io/ipfs/Qmb2ksUinB8nZsdJeMZ9yRvXAjUyfRW9MfdCEYi6gTyzXf"><img src="https://ipfs.io/ipfs/Qmb2ksUinB8nZsdJeMZ9yRvXAjUyfRW9MfdCEYi6gTyzXf" alt="" width=4500></a></td></tr>


<tr><td>Au temps actuel, on peut mesurer les rapports <sup>87</sup>Sr/<sup>86</sup>Sr et <sup>87</sup>Rb/<sup>86</sup>Sr par spectrométrie de masse dans différents minéraux cogénétiques, et tracer le graphique **<sup>87</sup>Sr/<sup>86</sup>Sr = f (<sup>87</sup>Rb/<sup>86</sup>Sr)**.

On obtient alors une droite dite « isochrone » dont l’équation est de type y = a.x + b :

<p align=center><strong><sup>87</sup>Sr/<sup>86</sup>Sr = (e<sup>λt</sup> – 1) . <sup>87</sup>Rb/<sup>86</sup>Sr + <sup>87</sup>Sr0/<sup>86</sup>Sr</strong></p>

On observe que plus le temps écoulé depuis la fermeture du système est grand, plus la pente de la droite isochrone est élevée. On en déduit que la pente a = (e<sup>λt</sup> – 1) est fonction du temps écoulé depuis la fermeture du système. Donc, si <strong>a = e<sup>λt</sup> – 1</strong> Alors, <strong>t = [ln (a + 1) ]/ λ** </td></strong>

<td><a href="https://ipfs.io/ipfs/QmdMFfYnLUWDEJ529wzjcVV4Ac6QU8wo1F2SkqsdJ4Spgz"><img src="https://ipfs.io/ipfs/QmdMFfYnLUWDEJ529wzjcVV4Ac6QU8wo1F2SkqsdJ4Spgz" alt="" width=4500></a></td></tr>

</table></div>





### Le principe de la méthode <sup>40</sup>K / <sup>40</sup>Ar

Le potassium 40 est un isotope instable qui se désintègre:

- En argon 40: **<sup>40</sup>K → <sup>40</sup>Ar + énergie (γ)** , avec λ<sub>Ar</sub> = 5,81 . 10<sup>−11</sup> an<sup>−1</sup>

- En calcium 40: **<sup>40</sup>K → <sup>40</sup>Ca + énergie (β<sup>-</sup>)** , avec λ<sub>Ca</sub> = 4,962 . 10<sup>−10</sup> an<sup>−1</sup>

λ = λ<sub>Ar</sub> + λ<sub>Ca</sub> = 5,543 . 10<sup>-10</sup>
 

Le couple potassium-argon est utilisé pour des roches magmatiques contenant des minéraux riches en K (silicates). De nombreux minéraux contiennent du potassium; ils incorporent donc au moment de leur formation une faible quantité de l'isotope radioactif <sup>40</sup>K; cependant on ne connait pas la quantité initiale de <sup>40</sup>K incorporée: <sup>40</sup>Ko = inconnue. On ne peut donc pas utiliser directement la loi de décroissance radioactive !

L’argon est un gaz qui s’échappe du magma avant sa cristallisation. Ainsi les quantités initiales d’éléments fils sont considérées comme nulles: 40 Aro = 0 Lorsque le magma a terminé sa cristallisation, tout l'argon formé par désintégration du potassium 40 reste emprisonné dans les minéraux, il n y' a plus d'échanges avec le milieu extérieur, le système est fermé.

A l'instant t, les quantités de <sup>40</sup>K et <sup>40</sup>Ar peuvent être mesurées dans la roche; le rapport <sup>40</sup>Ar / <sup>40</sup>K est donc connu. A to, le rapport <sup>40</sup>Aro / <sup>40</sup>Ko = 0

Au cours du temps, à partir de la fermeture du système, le <sup>40</sup>K se désintègre en <sup>40</sup>Ar qui reste piégé dans la roche, la quantité de <sup>40</sup>K diminue tandis que la quantité de <sup>40</sup>Ar augmente. Le rapport <sup>40</sup>Ar / <sup>40</sup>K augmente donc au cours du temps.

L'âge de la roche est donné par la formule suivante: **t = [ ln (1 + ( λ . <sup>40</sup>Ar / λ<sub>Ar</sub> . <sup>40</sup>K ) ) ] / λ**



### Le principe de la méthode U / Pb

La datation par la méthode U / Pb est une datation par concordia-discordia. Cette technique graphique permet de dater la fermeture du système (cristallisation roche magmatique) et de dater aussi la réouverture du système (métamorphisme).

L’Uranium 238 se désintègre en Plomb 206 avec une constante de désintégration λ<sub>238</sub> : **<sup>238</sup>U -> <sup>206</sup>Pb + énergie**


L’Uranium 235 se désintègre en Plomb 207 : avec une constante de désintégration λ<sub>235</sub>: **<sup>235</sup>U -> <sup>207</sup>Pb + énergie**

Selon le même principe que la méthode Rb/Sr, on utilise un isotope stable (non radioactif) et non radiogénique: le <sup>204</sup>Pb pour obtenir les équations des droites isochrones suivantes:

- **(<sup>206</sup>Pb / <sup>204</sup>Pb)<sub>t</sub> = (<sup>206</sup>Pb / <sup>204</sup>Pb)<sub>0</sub> + (<sup>238</sup>U / <sup>204</sup>Pb)<sub>t</sub> . (e<sup>λ<sub>238</sub>t</sup> – 1)**

- **(<sup>207</sup>Pb / <sup>204</sup>Pb)<sub>t</sub> = (<sup>207</sup>Pb / <sup>204</sup>Pb)<sub>0</sub> + (<sup>235</sup>U / <sup>204</sup>Pb)<sub>t</sub> . (e<sup>λ<sub>235</sub>t</sup> – 1)**


Comme il n’y a pas de Plomb au départ dans le système: <sup>206</sup>Pb0 = 0 et <sup>207</sup>Pb0 = 0 , donc:

- **(<sup>206</sup>Pb / <sup>204</sup>Pb)<sub>t</sub> = (<sup>238</sup>U / <sup>204</sup>Pb)<sub>t</sub> . (e<sup>λ<sub>238</sub>t</sup> – 1)**

- **(<sup>207</sup>Pb / <sup>204</sup>Pb)<sub>t</sub> = (<sup>235</sup>U / <sup>204</sup>Pb)<sub>t</sub> . (e<sup>λ<sub>235</sub>t</sup> – 1)**

Donc:

- **(<sup>206</sup>Pb / <sup>238</sup>U)<sub>t</sub> = (e<sup>λ<sub>238</sub>t</sup> – 1)**

- **(<sup>207</sup>Pb / <sup>235</sup>U)<sub>t</sub> = (e<sup>λ<sub>235</sub>t</sup> – 1)**

Pour chaque âge (par intervalle de 100 Ma), et pour chaque couple d’isotopes, on calcule avec les formules précédentes la valeur du rapport Pb/U. On reporte les valeurs dans un graphique <sup>206</sup>Pb/<sup>238</sup>U = f (<sup>207</sup>Pb / <sup>235</sup>U) . On obtient une courbe appelée concordia : les âges donnés par les deux couples sont concordants.

Ainsi, plus une roche (ses minéraux) vieillit (vieillissent), plus elle se déplace sur la concordia ; c’est ce qu’on voit sur le graphique ci dessous où la roche se déplace jusqu’à avoir 500Ma.

<div align=center><a href="https://ipfs.io/ipfs/QmNNDNaKf5KzjxhnNYqdyBnKSQgNcWSHNHibQYVWj9tUxF"><img src="https://ipfs.io/ipfs/QmNNDNaKf5KzjxhnNYqdyBnKSQgNcWSHNHibQYVWj9tUxF" alt="" width=60%></a></div>


*<p align=center><a href="http://tristan.ferroir.fr/index.php/2020/07/25/la-datation-par-concordia-discordia/">Graphique: Tristan Ferroir</a></p>*

Si un événement géologique (métamorphisme) réouvre le système, on a alors deux cas extrêmes :

- Tout le plomb est perdu et l’un des minéraux de la roche retourne à (0;0) puisqu’il a tout perdu

- Aucun plomb n’est perdu et à ce moment là, le minéral reste sur la concordia

Ainsi, les mesures des rapports <sup>206</sup>Pb / <sup>238</sup>U et <sup>207</sup>Pb / <sup>235</sup>U effectuées sur les minéraux de la roche ne sont pas situées sur la concordia, mais s’alignent sur une droite: la discordia.

En effet, selon les minéraux, plus ou moins de plomb sont perdus donc les minéraux vont se retrouver sur une droite comprise entre (0;0) et l’endroit ou la roche était arrivée sur la concordia. La discordia est donc une droite matérialisée par l’ensemble des minéraux qui ont perdu du plomb. Cette droite s’appelle la discordia car si on datait le minéral avec chacun des couples isotopiques, on trouverait des âges différents donc discordants.


<div align=center><a href="https://ipfs.io/ipfs/QmSHKiZqeQ18oW1XbD8HEdtip1UaqCHHeVCfjJZjJLuL1U"><img src="https://ipfs.io/ipfs/QmSHKiZqeQ18oW1XbD8HEdtip1UaqCHHeVCfjJZjJLuL1U" alt="" width=60%></a></div>


*<p align=center><a href="http://tristan.ferroir.fr/index.php/2020/07/25/la-datation-par-concordia-discordia/">Graphique: Tristan Ferroir</a></p>*

Une fois cet événement passé, la désintégration de l’uranium en plomb se poursuit et les minéraux évoluent alors hors de la concordia mais restent alignés sur une discordia. La discordia va donc avoir deux intercepts avec la concordia :

- L’intercept supérieur qui correspondrait à un minéral n’ayant perdu aucun isotope, cet intercept donne l’âge de la roche

- L’intercept inférieur qui correspondrait à un minéral qui aurait perdu tout son plomb, il se serait alors retrouvé au début de la concordia et aurait alors évolué dessus à nouveau, cet intercept correspond donc à l’âge de réouverture du système donc du métamorphisme

<div align=center><a href="https://ipfs.io/ipfs/QmQCSKwErexCCj9QbQftfJmDDDbJ3KV55SytWKoaskTH4A"><img src="https://ipfs.io/ipfs/QmQCSKwErexCCj9QbQftfJmDDDbJ3KV55SytWKoaskTH4A" alt="http://tristan.ferroir.fr/index.php/2020/07/25/la-datation-par-concordia-discordia/" width=60%></a></div>

*<p align=center><a href="http://tristan.ferroir.fr/index.php/2020/07/25/la-datation-par-concordia-discordia/">Graphique: Tristan Ferroir</a></p>*




[^1]: Radiogénique : Se dit d'un élément issu de la désintégration d'un élément radioactif.
