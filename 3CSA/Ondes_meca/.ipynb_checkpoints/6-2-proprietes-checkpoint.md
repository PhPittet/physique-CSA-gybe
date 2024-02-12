(sect:propriete)=
# Propriétés de l'onde : vitesse, amplitude, fréquence et période

## Caractéristiques d'onde

Dans ce chapitre, nous allons définir les caractéristiques suivantes pour décrire une onde :

Amplitude :
: L'amplitude $A$ d'une onde est la distance entre la position de repos et le déplacement maximal de l'onde.

  Elle se mesure en mètre ($\text{m}$)

Fréquence :
: La fréquence $f$ est le nombre d'ondes passant par un point spécifique par seconde.

  Elle se mesure en inverse de seconde  ($\text{s}^{-1}$) ou en Hertz  ($\text{Hz}$)

Période :
: La période $T$ d'une d'une onde est le temps nécessaire à la réalisation d'un cycle d'onde.

  Elle se mesure en seconde ($\text{s}$)

Longueur d'onde :
: La longueur d'onde $\lambda$ est la distance entre les parties identiques adjacentes d'une onde, parallèle à la direction de propagation.

  Elle se mesure en ($\text{m}$)

Vitesse d'onde :
: La vitesse de l'onde $v_{w}$ est la vitesse à laquelle la perturbation se déplace.

  Elle se mesure en ($\text{m/s}$)

:::{admonition} Conseils pour réussir
:class: astuce
La vitesse des vagues est parfois aussi appelée *vitesse de propagation* (ou *célérité*) car la perturbation se propage d'un endroit à un autre.
:::

Considérons la vague d'eau périodique dans {numref}`wavelenght`. Sa longueur d'onde $\lambda$ est la distance d'une crête à l'autre ou d'un creux à l'autre. La longueur d'onde peut également être considérée comme la distance parcourue par une onde après un cycle complet - ou une période $T$. Le temps d'un mouvement complet de haut en bas est également la période $T$ de la vague. Sur la figure, l'onde elle-même se déplace vers la droite avec une vitesse d'onde $v_{w}$. Son amplitude $A$ est la distance entre la position de repos et le déplacement maximal - *soit la crête ou le creux* - de la vague. Il est important de noter que ce mouvement de la vague est en fait la `perturbation` qui se déplace vers la droite, et non l'eau elle-même ; sinon, la mouette se déplacerait aussi vers la droite. Au lieu de cela, la mouette se déplace uniquement de haut en bas sur place au fur et à mesure que les vagues passent en dessous, parcourant une distance totale de $2A$ en un cycle. Cependant, comme mentionné dans le texte sur le surf, les vagues réelles de l'océan sont plus complexes que cet exemple simplifié.

:::{figure} figures/wavelenght.jpg
:name: wavelenght
:align: center
:width: 50%
*L'onde a une longueur d'onde $\lambda$, qui est la distance entre les parties identiques adjacentes de l'onde. La perturbation de haut en bas de la surface se propage parallèlement à la surface à une vitesse $v_w$.*
:::

:::{admonition} YouTube
:class: dropdown admonition-youtube
Cette vidéo est la suite de la vidéo *Introduction aux vagues* de la section [Types d'ondes](sect:TypesOndes). Il traite des propriétés d'une onde périodique : amplitude, période, fréquence, longueur d'onde et vitesse d'onde.
%%HTML [--isolated]
<div align="center">
 <iframe width="600" height="400" src="https://www.youtube.com/embed/ipRVXarbK3k" allowfullscreen></iframe>
</div>

:::

:::{admonition} Remarque
:class: astuce
La crête d'une vague est parfois aussi appelée le *pic*.
:::

::::{admonition} Question
:class: question
Si vous êtes sur un bateau dans le creux d'une vague sur l'océan, et que l'amplitude de la vague est de $1\,\text{m}$, quelle est la hauteur de la vague à partir de votre position ?

1. $1\,\text{m}$
2. $2\,\text{m}$
3. $4\,\text{m}$
4. $8\,\text{m}$
:::{admonition} *réponse*
:class: dropdown questionsol
Réponse 2. : $2\,\text{m}$

L'amplitude est la distance entre la position de repos et le déplacement maximal de la vague. Comme vous vous trouvez dans le creux de la vague, vous êtes à une position de $-1\,\text{m}$ par rapport à la position de repos (*négatif, car vous êtes sous la position de repos*). Le sommet de la vague, qui est $1\,\text{m}$ au-dessus de la position de repos de la vague, se trouve donc à une distance de $1\,\text{m}+1\,\text{m}=2\,\text{m}$ de vous.
:::
::::


## Relation entre la fréquence d'onde, la période, la longueur d'onde et la vitesse

Étant donné que la fréquence d'onde est le nombre d'ondes par seconde, et que la période est essentiellement le nombre de secondes par onde, la relation entre la fréquence et la période est
:::{math}
f = \frac{1}{T}
:::
ou
:::{math}
T = \frac{1}{f}
:::

Nous pouvons voir à partir de cette relation qu'une fréquence plus élevée signifie une période plus courte. Rappelez-vous que l'unité de fréquence est le hertz ($\text{Hz}$) et que $1\text{Hz}$ correspond à un cycle - *ou une onde* - par seconde.

La vitesse de propagation $v_{w}$ est la distance parcourue par l'onde dans un temps donné ($v=\frac{d}{t}$). Dans le cas d'une onde périodique, on sait qu'elle parcourt une distance égale à sa longueur d'onde $\lambda$ dans un temps équivalent à une période $T$. Sous forme d'équation, on obtient :

::::{admonition} Relation fondamentale
:class: formule
La relation fondamentale d'une onde, relie sa vitesse de propagation $v_w$ avec sa longueur d'onde $\lambda$, sa fréquence $f$ et sa période $T$ :
:::{math}
v_{w} = \dfrac{\lambda}{T}
:::
ou
:::{math}
v_{w} = \lambda\cdot f
:::
::::

À partir de cette relation, nous voyons que dans un milieu où$v_{w}$ est constant, plus la fréquence est élevée, plus la longueur d'onde est petite - voir la {numref}`speaker`.

:::{figure} figures/speaker.jpg
:name: speaker
:align: center
:width: 30%
*Parce qu'ils se déplacent à la même vitesse dans un milieu donné, les sons à basse fréquence doivent avoir une longueur d'onde plus grande que les sons à haute fréquence. Ici, les sons de basse fréquence sont émis par le grand haut-parleur, appelé woofer, tandis que les sons de haute fréquence sont émis par le petit haut-parleur, appelé tweeter.*
:::
 

Ces relations fondamentales sont vraies pour tous les types d'ondes. Par exemple, pour les vagues d'eau, $v_{w}$ est la vitesse d'une onde de surface ; pour le son, $v_{w}$ est la vitesse du son ; Et pour la lumière visible, $v_{w}$ est la vitesse de la lumière. L'amplitude $A$ est complètement indépendante de la vitesse de propagation $v_{w}$ et ne dépend que de la quantité d'énergie dans l'onde.

:::::{admonition} Géologie : Physique des ondes sismiques 
:class: dropdown weblink


:::{figure} figures/Eartquake.jpg
:name: Eartquake
:align: center
:width: 50%
*L'effet destructeur d'un tremblement de terre est une preuve palpable de l'énergie transportée par les ondes sismiques. L'évaluation des tremblements de terre sur l'échelle de Richter est liée à la fois à leur amplitude et à l'énergie qu'ils transportent. (Maître de 2e classe Candice Villarreal, U.S. Navy)*
:::
Les géologues s'appuient fortement sur la physique pour étudier les tremblements de terre, car les tremblements de terre impliquent plusieurs types de perturbations des vagues, notamment la perturbation de la surface de la Terre et les perturbations de la pression sous la surface. Les ondes sismiques de surface sont similaires aux ondes de surface sur l'eau. Les ondes sous la surface de la Terre ont à la fois des composantes longitudinales et transversales. Les ondes longitudinales d'un tremblement de terre sont appelées ondes de pression (ondes $\text{P}$) et les ondes transversales sont appelées ondes de cisaillement (ondes $\text{S}$). Ces deux types d'ondes se propagent à des vitesses différentes, et la vitesse à laquelle elles se déplacent dépend de la rigidité du milieu dans lequel elles se déplacent. Pendant les tremblements de terre, la vitesse des ondes $\text{P}$ dans le granit est significativement plus élevée que la vitesse des ondes $\text{S}$. Les deux composantes des tremblements de terre se déplacent plus lentement dans des matériaux moins rigides, tels que les sédiments. Les ondes $\text{P}$ ont des vitesses de $4$ à $7\,\text{km/s}$ et les ondes $\text{S}$ ont des vitesses de $2$ à $5\,\text{km/s}$, mais les deux sont plus rapides dans des matériaux plus rigides. L'onde $\text{P}$ s'éloigne progressivement de l'onde $\text{S}$ au fur et à mesure qu'elle traverse la croûte terrestre. Pour cette raison, la différence de temps entre les ondes $\text{P}$ et $\text{S}$ est utilisée pour déterminer la distance à leur source, l'épicentre du tremblement de terre.

Nous savons, grâce aux ondes sismiques produites par les tremblements de terre, que certaines parties de l'intérieur de la Terre sont liquides. Les ondes de cisaillement ou transversales ne peuvent pas traverser un liquide et ne sont pas transmises par le noyau de la Terre. En revanche, les ondes de compression ou longitudinales peuvent traverser un liquide et elles traversent le noyau.

Toutes les ondes transportent de l'énergie, et l'énergie des ondes sismiques est facile à observer en fonction de la quantité de dommages laissés après que le sol a cessé de bouger. Les tremblements de terre peuvent faire trembler des villes entières, effectuant le travail de milliers de boules de démolition. La quantité d'énergie dans une onde est liée à son amplitude. Les tremblements de terre de grande amplitude produisent de grands déplacements de sol et des dommages plus importants. Au fur et à mesure que les ondes sismiques se propagent, leur amplitude diminue, de sorte qu'il y a moins de dommages à mesure qu'elles s'éloignent de la source.

::::{admonition} Vérifiez votre compréhension
:class: dropdown exohome
Quelle est la relation entre la vitesse de propagation, la fréquence et la longueur d'onde des ondes $\text{S}$ lors d'un tremblement de terre ?
1. La relation entre la vitesse de propagation, la fréquence et la longueur d'onde est $v_{\text{w}} = \lambda\cdot f$
2. La relation entre la vitesse de propagation, la fréquence et la longueur d'onde est $v_{\text{w}} = \frac{f}{\lambda}.$
3. La relation entre la vitesse de propagation, la fréquence et la longueur d'onde est $v_{\text{w}} = \frac{\lambda}{f}.$
4. La relation entre la vitesse de propagation, la fréquence et la longueur d'onde est $v_{\text{w}} = \sqrt{\lambda\cdot f}.$
:::{admonition} *solution*
:class: dropdown exohomesol
Réponse 1. La relation entre la vitesse de propagation, la fréquence et la longueur d'onde est $v_{\text{w}} = \lambda\cdot f$ 
:::
::::
:::::

:::::{admonition} P*h*ET simulation
:class: dropdown simulation
**Corde vibrante**
%%HTML [--isolated]
<div align="center">
<iframe src="https://phet.colorado.edu/sims/html/wave-on-a-string/latest/wave-on-a-string_fr.html" width="600" height="450" scrolling="no" allowfullscreen></iframe>
</div>

Dans cette animation, regardez comment une corde vibre au ralenti en choisissant le réglage `Ralenti`. Sélectionnez les options `Pas d'extrémité` et `Manuel`, et faites bouger l'extrémité de la ficelle avec la souris pour faire des vagues vous-même. Passez ensuite au réglage `Osciller` pour générer automatiquement des ondes. Ajustez la `Fréquence` et l'`Amplitude` des oscillations pour voir ce qui se passe. Expérimentez ensuite le réglage de l'`Amortissement` et de la `Tension`.

::::{admonition} Vérifiez votre compréhension
:class: dropdown exohome
Lequel des paramètres - amplitude, fréquence, amortissement ou tension - modifie l'amplitude de l'onde lorsqu'elle se propage ? Qu'est-ce que cela fait à l'amplitude ?

1. La fréquence diminue l'amplitude de l'onde au fur et à mesure qu'elle se propage.
2. La fréquence augmente l'amplitude de l'onde au fur et à mesure qu'elle se propage.
3. L'amortissement diminue l'amplitude de l'onde au fur et à mesure qu'elle se propage.
4. L'amortissement augmente l'amplitude de l'onde au fur et à mesure qu'elle se propage.
:::{admonition} *solution*
:class: dropdown exohomesol
Réponse 3. L'amortissement diminue l'amplitude de l'onde au fur et à mesure qu'elle se propage.
:::
::::
:::::

:::::{admonition} Calculer la vitesse de propagation des vagues : Goéland dans l'océan
:class: exores
Calculez la vitesse des vagues de l'océan dans la figure précédente si la distance entre les crêtes des vagues est de $10.0\,\text{m}$ et que le temps nécessaire à une mouette pour monter et descendre est de $5.00\,\text{s}$
::::{admonition} *stratégie*
:class: dropdown strategie
Les valeurs de la longueur d'onde : $\lambda = 10.0\,\text{m}$ et la période $\text{T} = 5.00\,\text{s}$ sont données et on nous demande de trouver $v_{w}$ Par conséquent, nous pouvons utiliser $v_{w} = \frac{\lambda}{T}$ pour trouver la vitesse de l'onde.
::::
::::{admonition} *solution*
:class: dropdown solution
Entrez les valeurs connues dans $v_{w} = \frac{\lambda}{T}$ :
:::{math}
v_{w} = \frac{10.0\,\text{m}}{5.00\,\text{s}} = 2.00\,\text{m/s}
:::
::::
::::{admonition} *discussion*
:class: dropdown discussion
Cette vitesse lente semble raisonnable pour une vague océanique. Notez que dans la figure, la vague se déplace vers la droite à cette vitesse, ce qui est différent de la vitesse variable à laquelle la mouette se déplace de haut en bas.
::::
:::::

:::::{admonition} Calculer la période et la vitesse d'onde d'un ressort jouet
:class: exores
La femme de la {numref}`ressort1` crée deux vagues par seconde en secouant le ressort du jouet de haut en bas.
1. Quelle est la période de chaque vague ?
2. Si chaque onde se déplace de $0.9$ mètre après un cycle complet d'onde, quelle est la vitesse de propagation de l'onde ?
::::{admonition} *stratégie*
:class: dropdown strategie
Stratégie pour 1.
: Pour trouver la période, nous résolvons $T = \frac{1}{f}$, étant donné la valeur de la fréquence $f = 2\,\text{Hz}$

Stratégie pour 2.
: Étant donné qu'une définition de la longueur d'onde est la distance parcourue par une onde après un cycle complet -ou une période - les valeurs de la longueur d'onde ($\lambda = 0.9\,\text{m}$) ainsi que la fréquence sont données. Par conséquent, nous pouvons utiliser $v_{w} = \lambda\cdot f$ pour trouver la vitesse de l'onde.
::::
::::{admonition} *solution*
:class: dropdown solution
Solution pour 1.
: Entrez la valeur connue dans $T = \frac{1}{f}$
  :::{math}
  T = \dfrac{1}{2\,\text{Hz}} = 0.5\,\text{s}
  :::

Solution pour 2.
: Entrez les valeurs connues dans $v_{w} = \lambda\cdot f$
  :::{math}
  v_{w} = \lambda\cdot f = (0.9\,\text{m})(2\,\text{Hz}) = 1.8\,\text{m/s}
  :::
::::
::::{admonition} *discussion*
:class: dropdown discussion
Nous aurions également pu utiliser l'équation $v_{\text{w}} = \frac{\lambda}{T}$ pour résoudre la vitesse de l'onde, puisque nous connaissons déjà la valeur de la période $\text{T} = 0.5\,\text{s}$ à partir de notre calcul dans la partie 1, et nous aurions obtenu la même réponse.
::::
:::::

## Problèmes

::::{admonition} Exercice 1
:class: exohome
La fréquence d'une onde est de $10\,\text{Hz}$. Quelle est sa période ?

1.  La période de l'onde est de $100\,\text{s}$
2.  La période de l'onde est de $10\,\text{s}$
3.  La période de l'onde est de $0.01\,\text{s}$
4.  La période de l'onde est de $0.1\,\text{s}$
:::{admonition} *solution*
:class: dropdown exohomesol
Réponse 4. La période de l'onde est de $0.1\,\text{s}$

$T=\dfrac{1}{f}=\dfrac{1}{10}=0.1\,\text{s}$
:::
::::

::::{admonition} Exercice 2
:class: exohome
Quelle est la vitesse d'une onde dont la longueur d'onde est de $2\,\text{m}$ et dont la fréquence est de $5\,\text{Hz}$ ?

1.  $20\,\text{m/s}$
2.  $2.5\,\text{m/s}$
3.  $0.4\,\text{m/s}$
4.  $10\,\text{m/s}$
:::{admonition} *solution*
:class: dropdown exohomesol
Réponse 4. $10\,\text{m/s}$

$v=\lambda\cdot f=2\cdot 5=10\,\text{m/s}$
:::
::::

## Vérifiez votre compréhension

::::{admonition} Questions 1
:class: question
Quelle est l'amplitude d'une onde ?

1. Un quart de la hauteur totale de la vague
2. La moitié de la hauteur totale de la vague
3. Deux fois la hauteur totale de la vague
4. Quatre fois la hauteur totale de la vague
:::{admonition} *réponse*
:class: dropdown questionsol
Réponse 2. La moitié de la hauteur totale de la vague
:::
::::

::::{admonition} Questions 2
:class: question
Qu'entend-on par la longueur d'onde d'une onde ?

1. La longueur d'onde est la distance entre les parties identiques adjacentes d'une onde, parallèle à la direction de propagation.
2. La longueur d'onde est la distance entre les parties identiques adjacentes d'une onde, perpendiculaire à la direction de propagation.
3. La longueur d'onde est la distance entre une crête et le creux adjacent d'une onde, parallèle à la direction de propagation.
4. La longueur d'onde est la distance entre une crête et le creux adjacent d'une onde, perpendiculaire à la direction de propagation.
:::{admonition} *réponse*
:class: dropdown questionsol
Réponse 1. La longueur d'onde est la distance entre les parties identiques adjacentes d'une onde, parallèle à la direction de propagation.
:::
::::

::::{admonition} Questions 3
:class: question
Comment pouvez-vous exprimer mathématiquement la fréquence des ondes en termes de période d'onde ?

1.  $f = \frac{1}{T}$
2.  $f = \left(\frac{1}{T}\right)^{2}$
3.  $\text{f} = \text{T}$
4.  $f = \left(T\right)^{2}$
:::{admonition} *réponse*
:class: dropdown questionsol
Réponse 1.  $f = \frac{1}{T}$
:::
::::

::::{admonition} Questions 4
:class: question
Quand la longueur d'onde est-elle directement proportionnelle à la période d'une onde ?

1.  Lorsque la vitesse de l'onde est réduite de moitié
2.  Lorsque la vitesse de l'onde est constante
3.  Lorsque la vitesse de l'onde est doublée
4.  Lorsque la vitesse de l'onde est triplée
:::{admonition} *réponse*
:class: dropdown questionsol
Réponse 2.  Lorsque la vitesse de l'onde est constante ($v=\frac{\lambda}{T}$)
:::
::::

:::{admonition} YouTube
:class: dropdown admonition-youtube
Quelques liens de vidéo utiles sur le même sujet :
1. **ONDE MÉCANIQUE 👉 Célérité et retard**
%%HTML [--isolated]
<div align="center">
 <iframe width="600" height="400" src="https://www.youtube.com/embed/CFfODZUUqJ4" allowfullscreen></iframe>
</div>

2. **Calculer la célérité d'une onde mécanique**
%%HTML [--isolated]
<div align="center">
 <iframe width="600" height="400" src="https://www.youtube.com/embed/4x4jEgoxINU" allowfullscreen></iframe>
</div>

:::

