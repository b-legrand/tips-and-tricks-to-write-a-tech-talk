# Comment rédiger, préparer et assurer sa conférence ?



## Introduction


### Benjamin Legrand

<img src="/images/snowcamp-benjilegnard.jpg" style="max-height: 80vh; width: 40%; float:left;"/>

- Tech lead / Archi 🅰️ngular
- Onepoint depuis mai 2022<!-- .element: class="fragment" -->
- 🦻 Malentendant<!-- .element: class="fragment" -->
- 🤐 Introverti<!-- .element: class="fragment" -->
- 😬 Angoissé<!-- .element: class="fragment" -->
- 📣 Speaker ?<!-- .element: class="fragment" -->

Notes:
- je sais coder, je sais architecturer, mais il y a un truc que j'ai appris sur le tard et avec les années, c'est comment communiquer et comment enseigner
- je suis loin d’être un cador là-dedans, mais partons du postulat qu'on est tous nuls de base (parce que spoiler : on est tous et toutes nulles de base)
- story time etech day.
- pas naturel pour moi, introversion


### Mon petit palmarès de conférences
```markdown
- Devfest Nantes
- Snowcamp
- Meetup Nantes.JS
- Very Tech Trip
- Camping des Speakers
- Voxxed Days Luxembourg
- Sunny Tech
- Riviera Dev
- Volcamp
- BDX.io
- Devfest Strasbourg
- Angular Devs France
```
Notes:
- j'en ai fait plein certes en tant que speaker, ce slide est pas là pour me vanter
- mais du coup j'en ai vu encore plus en tant que public
- et c'est de ça que je veux parler aujourd'hui, comment faire une conf qui moi m'aurait intéressé


### Comment qu'on fait ?


### Comment je fais ?
- partir du plan, raconter une histoire<!-- .element: class="fragment" -->
- rédiger ses slides<!-- .element: class="fragment" -->
- embellir<!-- .element: class="fragment" -->
- assurer<!-- .element: class="fragment" -->

Notes:
- comment rédiger ses slides pour qu'ils soient efficaces
- comment avoir un discours et une histoire à raconter
- comment faire en sorte d'enseigner quelque chose à son auditoire
- le jour J, que faire. 



## Partir du plan, partir du fond

- partir du planfond ?<!-- .element: class="fragment" -->
- partir du plan<!-- .element: class="fragment" -->
- rajouter des sous-parties<!-- .element: class="fragment" -->


### Abstract !== Plan 
- organisation en grandes parties
- plus ou moins 7

Notes:
- synthétisez votre discours (vous l'avez déjà fait si vous avez un abstract)
- si on vous a fait le retour en revue, c'est pas pour rien
- votre plan est votre contenu
- Quantités de partie dépends de longueur


### Techniques de story-telling

- J'ai pas la science infuse
- Néanmoins:<!-- .element: class="fragment" -->


#### Le voyage du héros

<img src="/images/campbell-12-steps-journey.png"/>

Notes:
- reconnaissance 
- star wars et dirty dancing sont la même histoire
- le voyage du héros olivier croisier
- permets de structurer


#### Dan Harmon's story circle

<img src="/images/dan-harmon-story-circle.png"/>

Notes:
- Dan harmon ( community, rick & morty )

- In A Zone of Comfort
- They Desire Something
- Enter An Unfamiliar Situation
- Adapt to The Situation
- Get What They Desired
- Pay a Heavy Price for Winningh
- A Return to Their Familiar Situation
- They Have Overall Changed


#### En vrai: OSEF

- thèse
- antithèse
- synthèse
- foutaises<!-- .element: class="fragment" -->

Notes:
- en vrai, OSEF des deux autres, il n'y a pas que ça, trouvez votre structure
- ca se voit


#### Inception

```markdown
- introduction
- partir du plan
- développer
- embellir
- répéter
- assurer
- conclusion
```

Notes:
- voici le plan de cette conférence et comment j'ai fait pour tenir 45 minutes avec:
- j'aime bien ( personnellement ) partir du plan général, puis rajouter en tapant au kilomètre le contenu


#### MOAR

```markdown
- introduction
  - moi
  - crédibilité / palmarès
  - sujet
- partir du plan
  - story telling
  - meta
  - frappe kilometre
- développer
  - démo revealjs
  - ma méthode
- embellir
  - type de slides
  - polish
  - erreurs à ne pas faire
  - code / schemas / illustrations
- répéter
  - pourquoi s'entrainer ?
  - techniques
  - confiance
- assurer
  - gérer son stress
  - son temps
  - anecdotes de conférencier
  - rassurer
- conclusion
```
Notes:
- on prends les grosses parties, puis tapage au kiloétre


#### We can go deeper

```markdown
- introduction
  - moi
    - présentation
    - handicaps 
  - crédibilité / palmarès
    - liste des confs
  - sujet
    - de quoi on parle
- partir du plan
  - story telling
    - voyage du héros
    - dan harmon
    - on s'en fout
  - meta
  - frappe kilometre
```



### Reveal.js
- aparté sur revealjs
- <https://revealjs.com>


#### Format html

```html
<section>
  <section>
    <h1>Titre de presentation</h1>
  </section>
  <section>
    <h2>Titre de slide</h2>
    <ul>
      <li>Liste</li>
      <li>à</li>
      <li>puces</li>
    </li>
    <aside class="notes">
        Mes notes de speaker
    </aside>
  </section>
</section>
```

Notes:
- Reveal.js permet de transformer / styler une page web en slides
- souplesse du web, animations, scss
- pas évident si vous êtes pas à l'aise


#### Format markdown

```markdown
# Titre de présentation

## Titre de slide
- liste
- à
- puces
N​otes:
Mes notes de speaker
```

Notes:
- avantages, écriture au kilomètres
- séparateur markdown


#### index.html

```html
<div class="reveal">
  <div class="slides">
    <section
      data-markdown="votre-fichier.md"
      data-separator="^\n\n\n"
      data-separator="^Notes:\n"
    ></section>
  </div>
</div>
```


#### Speaker view
<img 
  src="/images/speaker-view.png"
/>

Notes:
- touche S
- super important car : timer intégré
- vous permets d'écrire ce que vous allez dire
- voir le slide suivant : improviser des transitions


#### C'est comme vous le sentez

- Microsoft Powerpoint
- Google Slides
- Apple Keynote

Notes:
- chose importante: être a l'aise
- apprenez pas reveal.js juste parce que je vous l'ai dit
- on a un template



### Développer, Développer, Développer
<img src="/images/steve-ballmer-microsoft.gif" width="70%"/>
Notes:
- bon on a le plan, comment on rédige nos slides
- comment on développe notre sujet


#### Ma méthode

- 📋 Liste à puces<!-- .element: class="fragment" -->
- 🥰 Emojis<!-- .element: class="fragment" -->
- 🚭 Pas plus de trois<!-- .element: class="fragment" -->
- 👻 Apparition !<!-- .element: class="fragment" -->
- 🤥 J'ai menti<!-- .element: class="fragment" -->


Notes:
- pas plus de trois idées par slide
- j'y reviendrais
- c'est ma technique, pas universel


#### schéma de la communication
<img src="/images/communication-schema.png" />

Notes:
  - vous êtes le messsager
  - vos slides sont le renforcement


#### Règle des trois points par slide 

- Règle du plus ou moins sept ( Miller, 1956 )

Notes:
- nombre d'objets pouvant tenir dans la mémoire
- même vous pour retenir ce qu'il y a dans une partie ca aide
- ne pas surcharger l'auditoire
- régle réfutée, en fait c'est plutôt 3/4


#### Show don't tell

- show don't tell...
- no, fuck you, show AND tell<!-- .element: class="fragment" -->

Notes:
- l'exercice de la conférence permet de faire les deux
- trouver l'équilibre entre slides surchargés et "one punchline"


#### Johnny Harris Formula
<img
  src="/images/harris-formula.png" 
/>
<img
  src="/images/harris-thumbnail.png"
  width="30%"
  style="float: left"
/>
<p style="font-size:50%;">
https://www.youtube.com/watch?v=dIKsEhX-vyU
</p>
Notes:
- faire des slides et des conférences = content creation
- l'idée c'est d'alterner les deux concept et que ll'une complémente l'autre


#### élager, supprimer

- préparer vous à supprimer des slides
Notes:
- surtout pour les quickies
- d'ou l'intéret de répeter tot
- des choses à dire.
  - avoir quelqu'un qui vous review
  - ne pas hésiter à supprimer des sujets, mettre des poids d'importance
- vaut mieux supprimer des slides pas chiadés



### Embellir, Enseigner, émerveiller
Notes:
- titre de partie pompeux, mais assumé


#### schéma de la pédagogie
<img src="/images/pedagogie-trapeze.png" />
La taxonomie de BLOOM
Notes:
- c'est important à garder en tête
- vous avez une mission
- les meilleurs talks sont ceux ou on apprends qelque chose
- 


#### techniques de pédagogie
<img
  src="/images/benjilegnard-tweet-deux-types.png"
/>
Notes:
  - considérer public = noob
  - apprendre quelque chose à son auditoire, ne pas le perdre
  - y'a deux types de conférences.


#### techniques de rédactions de slide 
- slides !== speaker notes
- illustrations


#### technique de spectacle
- attention à l'humour 
Notes:
- petites blagues ( attention à l'humour )
- discussions, standup vs prof'


#### slides vs discours
<img
  src="/images/tpierrain-textless-slides.jpeg"
  width="80%"
/>
Notes:
- choisir des illustrations.
- technique du slideless


#### schémas techniques, attention !
<img 
  src="/images/beware-schema.jpeg"
  width="80%"
/>
Notes:
- Attention à vos schémas
- lisibilité
- faites des zooms  


#### screenshot de code, attention !
<img
  src="/images/too-much-code.jpg"
  width="80%"
/>
Notes:
- taille de police
- gros bloc imbitables
- attention à la police
- lire du code c'est chiant
- le rendez pas encore plus chiant


#### highlight du code
- highlight.js
- mettez en valeur certaines lignes
```markdown
​`​`​`​markdown[|1-4|5|7]
```
Notes:
- ca ou pointeur laser


#### animations = attention
- perte d'attention
- les gifs animés
Notes:
- attention à ne pas détourner l'attention


#### Jolis slides
- le vernis, c'est la couche finale.
Notes:
- pour conclure sur l'embelllir
étape finale de la rédaction, pas la première
- gif animé = polish
- le fond doit être solide



### Répeter, Répeter, Répeter

- répéter à l'oral le plus tôt possible
- ( même avant les slides finaux )
Notes:
- même avec juste le plan: aide à rédiger
- faire un run à vide du plan, sans illustrations, sans rien, ça peut aider à : se chronométrer, trouver du contenu ou des idées


#### Enregistrez-vous ?
<img src="/images/repeat-stream-setup.png" />
Notes:
- ca c'est moi avec un logiciel de stream
- intéret :  
- faire son auto-critique
- apprendre son talk


#### Mieux
- répéter devant quelqu'un
<img
  src="/images/mon-chat.jpeg"
  width="80%"
/>
Notes:
- c'est aussi le but de l'atlantique day
- avoir du feedback avant l'extérieur


#### maitriser son temps
Notes:
- répeter vous permets de savoir grosso modo quel temps vous allez mettre
- Si vous êtes trop rapide, il faut assurer les questions.
  - compteurs de temps slide
  - do not stress


#### Faites pas du par coeur
- mais quand même
- confiance++



## Assurer
- Imaginez que vous êtes sélectionné(e) déjà.
- le jour J arrive, comment j'assure ?


### Marché au poissons

<img
  src="/images/riviera-dev-marche-aux-poissons.jpg" 
  width="80%"
/>

Notes:
- toutes les confs ne le font pas
- soyez prêt à l'exercice
- si vous avez un abstract court et percutant, le boulot est fait


### Soyez présents

- Identifiez l'orga
Notes:
- généralement c'est pas dur, ils ont des pulls


### gérer son temps ( avant )
<img 
  src="/images/feedback-screen.jpeg"
  width="80%"
/>
- arrivez avant le top départ
Notes:
- profitez de la pause pour vous installer
- question de respect pour l'audience
- anectode talk jamstack voxxedd


### gérer son temps ( pendant )
<img
  src="/images/feedback-timer.jpeg"
  width="80%"
/>
- feedback de l'orga / la tech / filmé
- écrans ou speaker view
- compteurs
Notes:
- selon l'argent dispo coté conf
- 


### gérer son temps ( après )
- soyez sympas pour les suivants
- laissez la place


### gérer son stress / angoisse
- don't drink and drive
- c'est que des pixels bro
- boire de l'eau
Notes:
- n'abusez pas des soirées speaker ( ou onepoint )
- (pire journée le lendemain )
- promis si vous avez répété, le stress disparait au bout de 30 secondes.


### utiliser l'espace ?
<img 
  src="/images/qwik-rapidement-03.jpeg"
  width="80%"
/>
Notes:
- si vous avez la place, marchez. position corporelle
- mieux que rester derrière son pc, regarder l'audience
- ne marche que si on connait par coeur son propos


### feedback en live
- hecklers / interrupteur
Notes:
- silence de mort = pas bon
- captez l'audience


### gérer la parole en public
- faites des pauses ( dans votre discours )
- respirez
- buvez de l'eau
Notes:
- osef, yolo, profite
  - si c'est préparé, ça se passera bien. ne la jouez pas trop à l'arrache


### gérer les questions du public
Notes:
- ne pas les gérer
- ne pas répondre
- se préparer à répondre, et aussi. les gens viendront te parler dehors


### Ayez un plan B
- on sait jamais
Notes:
- anectode bdx.io talk sur le RGPD
- fini son talk au whiteboard



## Conclusion
Notes:
- chacun est différent, mes conseils peuvent ne pas s'appliquer à vos sujets
- j'espère qu'il y a un max d'astuces et de trucs pour vous aider, vous débloquer, levez vos angoisses
- ce n'est pas très compliqué tout ça, il faut juste avoir envie d'en parler


## Sources

- [Campbell's]()
- [Dan Harmon story circle]()
- [Taxonomie de Bloom](https://c2ip.insa-toulouse.fr/fr/pedagogies/concepts-de-base-en-pedagogie/la-taxonomie-de-bloom.html)
- [Johnny Harris Formula]()
- [Le nombre sept, plus ou moins deux](https://fr.wikipedia.org/wiki/Le_nombre_magique_sept,_plus_ou_moins_deux)


## Merci

- questions ? ( et parlez fort svp )

