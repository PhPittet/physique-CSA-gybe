# Ondes sonores {#sect:Son}

Une onde sonore est une onde mécanique progressive périodique longitudinale pouvant se propager dans un milieu matériel (gaz, liquide ou solide). Cette onde est due à des successions de compressions et de
dilatations de couches du milieu matériel
(Fig. [1](#Fig:OndeSon){reference-type="ref" reference="Fig:OndeSon"}).

![*Propagation d'une onde sonore. La vibration des molécules d'air se
transmet de proche en proche. [@Kartable]*](OndeSon.jpg){#Fig:OndeSon
height="2cm"}

Par commodité, on représentera cette perturbation longitudinale par une
onde transversale:

::: center
![image](RepresOndeSon.jpg){height="4cm"}
:::

-   L'oreille humaine est sensible aux ondes sonores dont la fréquence
    est approximativement comprise entre $20\,[Hz]$ et $20\,[kHz]$.

-   Les sons graves sont les sons de basses fréquences et les sons aigus
    sont les sons de hautes fréquences.

Les ondes sonores dont la fréquence est inférieure à $20\,[Hz]$ sont
appelées des *infrasons* et celles dont la fréquence est supérieure à
$20\,[kHz]$ sont appelées **ultrasons**.\
Les éléphants peuvent communiquer sur des distances atteignant les
$10\,[km]$ grâce à des infrasons, les chauves-souris emploient des
ultrasons de fréquence comprise entre $50\,[kHz]$ et $200\,[kHz]$ pour
percevoir l'environnement.

## Vitesse du son

La vitesse de propagation (ou célérité) d'une onde sonore est
indépendante de sa fréquence, mais dépend du milieu de propagation. Dans
l'air, la vitesse du son est de $340\,[m/s]$, dans les milieux plus
denses, elle est plus importante.\

::::: center
:::: small
::: {#tab:Vmilieu}
  **Milieu**    **Célérité du son** $\boldsymbol{[m/s]}$
  ------------ ------------------------------------------
  Air                            $340$
  Hélium                         $965$
  Hydrogène                      $1280$
  Eau douce                      $1440$
  Eau de mer                     $1560$
  Acier                          $5940$
  Granite                        $6000$

  : Vitesse approximative du son dans différents milieux.
:::
::::
:::::

## Analyse spectrale d'un son

Les sons produits par une source peuvent être de deux types:

-   Le son est dit **pur** si l'onde sonore est une fonction
    sinusoïdale.

-   Le son est dit **complexe** si l'onde sonore est périodique mais non
    sinusoïdale.

![*Son pur (en haut) et son complexe (en
bas). [@Kartable]*](SonPur.jpg){#Fig:SonPur height="4cm"}

Pour définir la composition d'un son complexe, on réalise l'analyse
spectrale du son. L'analyse spectrale, aussi appelée spectre en
fréquence, est la représentation graphique de l'amplitude relative d'un
signal quelconque en fonction de la fréquence.

![*Spectre d'un signal*](AnalyseSpectre.jpg){#Fig:AnalyseSpectre
height="7cm"}

## Hauteur et timbre d'un son

### Hauteur d'un son

La hauteur d'un son est **la fréquence du signal correspondant** à
l'onde sonore, appelée **fréquence fondamentale** ou simplement
**fondamentale**.\
La figure [4](#Fig:HauteurSon){reference-type="ref"
reference="Fig:HauteurSon"} montre le signal et le spectre d'un son
correspondant à la note $La=440\,[Hz]$ émis par un diapason:

![*Son pur correspondant à la note $La$ et dont la hauteur est de
$440\,[Hz]$. [@Kartable]*](HauteurSon.jpg){#Fig:HauteurSon height="7cm"}

### Timbre d'un son

Le timbre d'un son est défini par la présence et l'amplitude relative
des différents pics du spectre en fréquence de ce son appelés
harmoniques. Voici le signal et le spectre d'un son correspondant au La
émis par un instrument

![*Note $La$ jouée par un
instrument. [@Kartable]*](TimbreSon.jpg){#Fig:TimbreSon height="7cm"}

La hauteur de ce son est toujours de $440\,[Hz]$ (puisque la fréquence
fondamentale vaut $440\,[Hz]$) mais le spectre en fréquence contient de
nombreuses harmoniques définissant le timbre du son complexe émis par
l'instrument.\
Les fréquences des harmoniques sont toutes multiples de la fréquence
fondamental $f_{1}$. Ainsi, la fréquence $f_{n}$ d'une harmonique de
rang $n$ est: $$f_{n}=n\cdot f_{1}$$

Puisque la fréquence fondamentale d'un son correspondant à la note $La$
est $f_{1}=440\,[Hz]$, les fréquences de ces harmoniques sont:

-   $f_{2}=2\cdot f_{1}=2\cdot 440=880\,[Hz]$

-   $f_{3}=3\cdot f_{1}=3\cdot 440=1320\,[Hz]$

-   $f_{4}=4\cdot f_{1}=4\cdot 440=1760\,[Hz]$

-   etc...

C'est la différence de timbre, et donc de répartition des harmoniques,
qui fait que les sons émis par deux instruments différents jouant la
même note sont quand même discernables.

## Intensité et niveau sonores

L'**intensité** sonore, notée $\boldsymbol{I}$, d'une onde sonore
correspond à l'énergie transportée par cette onde par unité de surface
et par unité de temps. Elle s'exprime en watts par mètre carré
($[W\cdot [m^{-2}]$). Il s'agit donc d'une puissance par mètre carré.\
L'oreille humaine étant sensible à une gamme d'intensité sonore très
grande, on a introduit une grandeur, le **niveau sonore**, permettant de
comparer l'intensité sonore d'une source à une valeur de référence
$I_{0}$.\

:::: {style="background-color: DefColor"}
::: flushright
[**Niveau sonore**]{style="color: TextColorDef"}
:::
::::

Le niveau sonore d'une source est défini par la relation suivante:
$$\setlength{\fboxrule}{2pt}
 \fcolorbox{BoxColor}{MathColor}{
 \begin{LARGE}
 $\boldsymbol{\textcolor{StudentCol}{L=10\cdot \log (\dfrac{I}{I_{0}})}}$
 \end{LARGE}}$$ avec:

-   $L$ le niveau sonore (exprimé en décibel $[dB]$).

-   $I$ l'intensité sonore de la source (en $[W\cdot [m^{-2}]$).

-   $I_{0}$ une intensité de référence:\
    $I_{0}=1,0\cdot 10^{-12}\,[W\cdot [m^{-2}]$.

\
L'intensité de référence $I_{0}$ correspond à l'intensité sonore la plus
faible que peut détecter l'oreille humaine, appelée **seuil
d'audibilité**. Le niveau sonore se mesure à l'aide d'un sonomètre.\
La perception du niveau sonore d'un son est liée à son amplitude, mais
varie également avec sa fréquence.

![*Intensités et niveaux sonores pour l'oreille
humaine. [@Kartable]*](NiveauSon.jpg){#Fig:NiveauSon}

## Effet Doppler

\[8pt\] Le son émis par le sifflet d'un train n'est pas toujours perçu
de la même façon pour un observateur situé au bord des voies: il paraît
plus aigu que le son réellement émis par le sifflet lorsque le train se
rapproche et plus grave lorsque le train s'éloigne. Cette modification
de la fréquence perçue est connue sous le nom d'effet Doppler; il peut
être causé par le mouvement de la source sonore, par le mouvement de
l'observateur ou encore par les deux mouvements simultanés.

### Effet du mouvement de la source

On considère une source sonore émettant un son de fréquence constante
$f$, donc de période $T=1/f$.\
Si la source est immobile, les fronts d'onde successifs forment des
sphères concentriques (représentées par des cercles sur le schéma)
centrées sur la source et séparées par une longueur d'onde $\lambda$ de
l'onde émise (Fig. [7](#Fig:Doppler1){reference-type="ref"
reference="Fig:Doppler1"}).

![*Source $S$ immobile: les fronts d'onde sont des sphères
concentriques. [@AKPP]*](Doppler1.jpg){#Fig:Doppler1 height="2.5cm"}

Le problème se complique si la source se déplace à la vitesse
(constante) $v_{source}$. Pour décrire cette situation, la figure
Fig. [8](#Fig:Doppler2){reference-type="ref" reference="Fig:Doppler2"}
représentent des photographies prises à intervalles de temps réguliers
$T$, où $T$ représente exactement la période de l'onde émise.\

![*Source $S_{1}$ en mouvement à différent
instant. [@AKPP]*](Doppler2.jpg){#Fig:Doppler2 height="5.5cm"}

Durant ce laps de temps,

-   la source avance d'une distance $d=v_{source}\cdot T$;

-   l'onde émise progresse d'une longueur d'onde
    $\lambda =v_{son}\cdot T$, où $v_{son}$ est la vitesse du son dans
    l'air.

Sur la première photographie, la source se trouve en $S_{1}$ et émet un
son.\
Sur la deuxième photographie, la source a avancé de la distance $d$ et
se trouve en $S_{2}$. Le front d'onde émis en $S_{1}$ se trouve
maintenant sur une sphère (cercle) centrée en $S_{1}$ et de rayon
$\lambda$.\
Sur la troisième photographie, la source a avancé de la distance $d$ et
se trouve en $S_{3}$. Le front d'onde émis en $S_{1}$ se trouve
maintenant sur une sphère (cercle) centrée en $S_{1}$ et de rayon
$2\cdot \lambda$ alors que le front d'onde émis en $S_{2}$ se trouve sur
une sphère (cercle) centrée en $S_{2}$ et de rayon $\lambda$.\
Sur la quatrième photographie, la source se trouve en $S_{4}$. Le front
d'onde émis en $S_{1}$ se trouve maintenant sur une sphère (cercle) de
rayon $3\cdot \lambda$, le front d'onde émis en $S_{2}$ se trouve sur
une sphère (cercle) de rayon $2\cdot \lambda$ et le front d'onde émis en
$S_{3}$ se trouve sur une sphère (cercle) de rayon $\lambda$.\
Le mouvement de la source a pour effet de décaler les fronts d'onde en
les tassant dans le sens du mouvement. Ces fronts d'onde ne sont plus
concentriques et la longueur d'onde $\lambda '$ reçue par un observateur
$O'$ situé en avant de la source est plus petite que la longueur d'onde
$\lambda ''$ reçue par un observateur $O''$ situé en arrière de la
source. Il est possible de déterminer ces longueurs d'onde et d'en
déduire les fréquences $f'$ et $f''$ (et par conséquent les hauteurs des
sons) perçues par chacun des observateurs.\
On peut déjà remarquer, puisque $\lambda '<\lambda ''$, que la période
$T'$ entre la réception de deux crêtes par $O'$ sera plus petite que la
période $T''$; à l'inverse, la fréquence $f'$ sera plus grande que la
fréquence $f''$.

Sur le schéma, on constate que: $$\begin{aligned}
2\cdot \lambda &= d+\lambda +\lambda '\\
\lambda ' &= \lambda-d
\end{aligned}$$ Or $$\begin{aligned}
\lambda &= v_{son}\cdot T=\dfrac{v_{son}}{f}\\
\lambda ' &= v_{son}\cdot T'=\dfrac{v_{son}}{f'}\\
d &= v_{source}\cdot T=\dfrac{v_{source}}{f}
\end{aligned}$$ Par substitution, on trouve:
$$\dfrac{v_{son}}{f'}=\dfrac{v_{son}-v_{source}}{f}$$ et finalement
l'équation simplifiée de l'effet Doppler pour une source s'approchant
d'un observateur: $$f'=\dfrac{v_{son}}{v_{son}-v_{source}}\cdot f$$\
En faisant le même type de raisonnement pour une source s'éloignant de
l'observateur fixe, puis pour un observateur lui-même en mouvement, on
arrive à l'équation de l'effet Doppler pour un cas général:\

:::: {style="background-color: DefColor"}
::: flushright
[**Effet Doppler**]{style="color: TextColorDef"}
:::
::::

Une source sonore en mouvement à la vitesse $v_{source}$ émet un son à
la fréquence $f$. La fréquence $f'$ perçue par un observateur en
mouvement à la vitesse $v_{obs}$ est définie par l'équation générale de
l'effet Doppler: $$\label{eq:EffetDoppler}
\setlength{\fboxrule}{2pt}
\fcolorbox{BoxColor}{MathColor}{
\begin{LARGE}
$\boldsymbol{\textcolor{StudentCol}{f'=\dfrac{v_{son}+ v_{obs}}{v_{son}- v_{source}}\cdot f}}$
\end{LARGE}}$$ avec:\
[.]{style="color: white"} $\quad f’$ la fréquence reçue par
l'observateur en $[Hz]$.\
[.]{style="color: white"} $\quad f$ la fréquence émise par la source en
$[Hz]$.\
[.]{style="color: white"} $\quad v_{son}$ la vitesse du son dans le
milieu en $[m/s]$.\
[.]{style="color: white"} $\quad v_{source}$ la vitesse de la source en
$[m/s]$.\
[.]{style="color: white"} $\quad v_{obs}$ la vitesse de l'observateur en
$[m/s]$.\
[***Avec la convention suivante:***]{.underline}

-   $\boldsymbol{v_{source}>0}$ lorsque la source **s'approche** de
    l'observateur.

-   $\boldsymbol{v_{obs}>0}$ lorsque l'observateur **s'approche** de la
    source

Dans les cas où la source (respectivement l'observateur) **s'éloigne**,
on devra prendre la **vitesse négative** dans
l'équation [\[eq:EffetDoppler\]](#eq:EffetDoppler){reference-type="ref"
reference="eq:EffetDoppler"}.  

### Onde de choc

Les canards ou les bateaux laissent derrière eux un sillage formant un
angle plus ou moins ouvert. Dans ce cas, la vitesse de la source (le
canard ou le bateau) est plus grande que la vitesse de propagation des
ondes à la surface de l'eau.

![*Sillage d'un canard.*](SillageCanard.jpg){#Fig:SillageCanard
height="4cm"}

\
En construisant un schéma analogue aux précédents, en prenant garde à ce
que la distance $d$ parcourue par la source entre deux photographies
soit plus grande que la longueur d'onde $\lambda$, on constate que les
fronts d'onde successifs ne sont plus les uns dans les autres.

![*Cône de Mach. [@AKPP]*](OndeChoc.jpg){#Fig:OndeChoc height="5.5cm"}

Leur enveloppe commune forme les côtés d'un angle sur lesquels l'énergie
transportée par l'onde s'accumule. Cet angle correspond au sillage du
bateau et on peut facilement déterminer sa valeur $\alpha$ par:
$$\sin\alpha=\dfrac{\lambda}{d}=\dfrac{v_{onde}\cdot T}{v_{source}\cdot T}=\dfrac{v_{onde}}{v_{source}}$$

On désigne souvent cette situation par l'expression onde de choc . Ce
phénomène se produit aussi lors du bang des avions supersoniques volant
à une vitesse supérieure à celle du son.

![*Ondes de choc produites par les ailes d'un avion $FA-18$. Elles sont
rendues visibles par la diminution subite de la pression de l'air, qui
cause la condensation des molécules d'eau, produisant un épais
brouillard.*](BangAvion.jpg){#Fig:BangAvion height="4cm"}

## Exercices

::: exercice
[]{#Exo:Son.1 label="Exo:Son.1"} Vous assistez à un concert en plein air
et vous vous trouvez à $300\,[m]$ des haut-parleurs. Le concert est
également diffusé en direct par satellite (à la vitesse de la lumière,
soit à $3,00\cdot 10^{8}\,[m/s]$). Un auditeur capte l'émission du
concert à $5'000\,[km]$ de distance. Oui est le premier à entendre la
musique, vous ou l'auditeur éloigné? Quel est le délai entre les deux
écoutes?
:::

::: exercice
[]{#Exo:Son.2 label="Exo:Son.2"} Une colonne de soldats qui marchent à
un rythme de 120 pas à la minute garde la cadence en suivant le
battement d'un tambour à l'avant de la colonne. On observe que les
soldats à l'arrière de la colonne posent le pied gauche lorsque le
batteur pose le pied droit. Quelle est la longueur approximative de la
colonne?
:::

::: exercice
[]{#Exo:Doppler.1 label="Exo:Doppler.1"} La sirène d'une ambulance émet
un son à $1500\,[Hz]$.

-   Cette sirène s'approche d'un observateur immobile à la vitesse de
    $80\,[km/h]$. Calculer la fréquence perçue par l'observateur avant
    puis après le passage de la sirène.

-   L'ambulance est maintenant immobile. Calculer la fréquence perçue
    par un observateur qui s'approche puis s'éloigne de l'ambulance à la
    vitesse de $80\,[km/h]$.

-   Refaire les calculs des questions a) et b) avec la vitesse d'un
    train à très grande vitesse de $300\,[km/h]$

-   Les situations a) et b) sont-elles parfaitement symétriques?
:::

::: exercice
[]{#Exo:Doppler.2 label="Exo:Doppler.2"} La sirène d'une ambulance émet
une onde sonore à $450\,[Hz]$. Un observateur perçoit cette onde à
$415\,[Hz]$.\
Comment se déplace l'ambulance par rapport à l'observateur et quelle est
la vitesse de l'ambulance par rapport à l'observateur?
:::

:::: exercice
[]{#Exo:Doppler.3 label="Exo:Doppler.3"} Un sous-marin français et un
sous-marin américain se dirigent l'un vers l'autre lors de manœuvres
dans l'océan Atlantique, où l'eau est immobile. Le module de la vitesse
du sous-marin français est de $50,0\,[km/h]$ et celui du sous-marin
américain est de $70,0\,[km/h]$. Le sous-marin français envoie un signal
sonar (onde sonore sous-marine) à $1'000\,[Hz]$. Les ondes se propagent
dans l'eau à une vitesse ayant un module de $5'470\,[km/h]$.

-   Quelle est la fréquence du signal détecte par le sous-marin
    américain?

-   Quelle fréquence est détectée par le sous-marin français dans le
    signal réfléchi par le sous-marin américain?

::: center
![image](ExoSousMarin.jpg)
:::
::::

::: exercice
[]{#Exo:Doppler.4 label="Exo:Doppler.4"} Un système d'alarme sonore se
compose d'une source qui émet des ondes à $28,0\,[kHz]$. Quelle est la
fréquence de battements entre les ondes émises et les ondes réfléchies
par un cambrioleur qui marche à une vitesse moyenne de $0,95\,[m/s]$ en
s'éloignant de l'alarme?
:::

::: exercice
[]{#Exo:Doppler.5 label="Exo:Doppler.5"} Un projectile est tiré à une
vitesse ayant un module de $68,5\,[m/s]$. Trouvez l'angle formé par
l'onde de choc et la trajectoire du projectile.
:::

::: exercice
[]{#Exo:Doppler.6 label="Exo:Doppler.6"} Un avion à réaction passe
au-dessus de vous à une altitude de $5000\,[m]$ à une vitesse de Mach de
$1,5$.

-   Trouvez l'angle du cône de Mach,

-   Combien de temps après que l'avion soit passé au-dessus de votre
    tête l'onde de choc vous atteint-elle?

Le module de la vitesse du son est de $331\,[m/s]$.
:::
