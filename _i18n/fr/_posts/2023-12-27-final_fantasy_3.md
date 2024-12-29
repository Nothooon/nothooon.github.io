---
layout: post
title:  "(WIP) Final Fantasy III - Le plus grand RPG de la NES"
tags: final-fantasy
category: "Final Fantasy Marathon"
date: "2023-12-27"
lang: fr
image:
  path: /assets/img/posts_preview_images/ff3_logo.jpg
  alt: Final Fantasy 3 Logo # or base64 URI
---

On arrive déjà à la fin de l'ère NES de Final Fantasy. Et ça fini extrèmement bien.
Retour sur le meilleur jeu jusqu'ici, mais aussi peut être de l'ère "classique" ?

----

{% if site.lang == "fr" %}
  {% capture english_link %}{{ site.url }}/en{{ page.url }}{% endcapture %}
  <a href="{{ english_link }}" >{% t pages.english_article %}</a>
{% elsif site.lang == "en" %}
  {% capture french_link  %}{{ site.url }}{{ page.url }}{% endcapture %}
 <a href="{{ french_link }}" >{% t pages.french_article %}</a>
{% endif %}

## Préambule

La date d'écriture de l'article est un peu mensongère. J'ai pris des notes pendant toute ma partie et j'ai ensuite mis en page ces notes à la date de publication de l'article. Cependant, vous pouvez voir que la dernière mise à jour est bien plus tardive. Alors pourquoi ? Déjà parce que je jouais aux autres jeux de la série et ensuite parce qu'écrire, c'est compliqué vous savez.   

En tout cas, je me rends bien compte que mon avis sur le jeu a pas mal évolué, tout comme il avait évolué pour [Final Fantasy II]({{ site.url }}/posts/final_fantasy_2). Plus le temps passe et plus j'apprécie ce 3ème opus, quand bien même je l'avais déjà beaucoup aimé lorsque j'y ai joué pour la première fois. Mais l'héritage qu'il porte dans la suite de la licence est bien plus marqué et personnellement, il me touche bien plus.

Pour résumer ma pensée avant d'entrer dans les détails, Final Fantasy 3 est beau. Je ne parle pas d'une beauté visuelle ou musicale, même s'il dispose de ces deux qualités aussi, mais d'une beauté plus abstraite, sentimentale. 

Cet article devrait être un peu plus personnel, même si on va respecter la tradition et commencer par expliquer comment le jeu fonctionne.

<!-- ## Ressources pour l'écriture:

Manuel en Jap: https://archive.org/details/finalfantasyiiifchiresscans/Final%20Fantasy%20III%20-%20Manual%20%28Searchable%29/page/n43/mode/2up 
Manuel traduit (mais mise en page à chier): https://www.retrogames.cz/manualy/NES/Final_Fantasy_III_-_NES_-_Manual.pdf
Article d'Eurogamer: http://web.archive.org/web/20121025152943/https://www.lostlevels.org/200312/200312-ffan2.shtml
Page Wikipédia: https://en.wikipedia.org/wiki/Final_Fantasy_III

-->

## Histoire et enjeux

Final Fantasy III est sorti en Avril 1990 sur Famicom (l'équivalent de notre NES), exclusivement au Japon (comme les deux opus précédents). Il a été développé par globalement la même équipe que les deux premiers jeux de la série: dirigé et écrit par Hironobu Sakaguchi (et Kenji Terada pour l'écriture), au gameplay designé par Hiromichi Tanaka, avec des personnages designés par le légendaire Yoshitaka Amano et de la musique composée par le non moins légendaire Nobuo Uematsu. 

Ce jeu est le dernier de la licence à être développé pour la Famicom. L'équipe travaillant sur le jeu est bien déterminée à créer le plus grand RPG de l'ère Famicom en tirant les leçons de leurs deux premiers jeux. 

Il a d'ailleurs été dévéloppé et est sorti à une époque où la grande majorité des studios s'attelaient à prendre en main la nouvelle console de Nintendo, la Super Famicom (l'équivalent de la Super NES par chez nous) qui sortira à la fin de l'année 1990. La conception de Final Fantasy IV avait d'ailleurs déjà démarré !   

C'est aussi pour cette raison que Final Fantasy III ne recevra pas de version internationale, contrairement à ce qui était prévu. Hiromichi Tanaka, développeur et game designer sur FF3, l'expliquait en 2007 dans l'article ["Fantasy Reborn"](https://web.archive.org/web/20100626022240/http://www.eurogamer.net/articles/fantasy-reborn-interview) de Rob Fahey pour Eurogamer:

> "De nos jours, nous savons que quand une console comme la PlayStation sort, il y aura une PlayStation 2 puis une PlayStation 3 [...], nous pouvons plus ou moins prévoir que ça arrivera dans le futur. Mais à l'époque, c'était la première fois qu'on voyait une nouvelle génération de consoles, et c'était vraiment très difficile de prédire ce qui allait ce passer. Nous travaillions si dur pour maitriser cette nouvelle technologie que nous n'avions simplement pas assez de main d'oeuvre pour travailler sur une version anglaise de Final Fantasy III"  
> &mdash; <cite> Hiromichi Tanaka, game designer sur Final Fantasy III </cite>

Cette difficulté à sortir le jeu du Japon suivra Square pendant longtemps. Cela s'explique non seulement par la date de sortie du jeu, en fin de vie de la Famicom, mais aussi à cause des ambitions du jeu. En effet, Final Fantasy III poussera la NES dans ses retranchements. Le jeu est énorme pour l'époque, et a dû être publié sur des cartouches de 512Ko, soit la deuxième plus grande taille de cartouche gérée par la Famicom. 

> Quand nous avons développé FF3, il y avait tellement de contenu dans le jeu que la cartouche était presque complètement remplie. Et lorsque les nouvelles plateformes ont débarquées, il n'y avait tout simplement pas assez de place pour y amener Final Fantasy III car on aurait dû refaire les graphismes, la musique et tout le reste du contenu [pour avoir une qualité équivalente aux autres jeux]. Donc même si plusieurs opportunités de redévelopper Final Fantasy III se sont présentées, nous ne pouvions pas le faire.   
> &mdash; <cite> Hiromichi Tanaka </cite>

Aujourd'hui, 512Ko est une taille absolument ridicule. Une musique téléchargée de nos jours pèse environ 4Mo, soit 8 fois plus que l'intégralité de Final Fantasy III. Gardez donc bien en tête que tout ce dont on va parler tient dans un huitième d'un fichier mp3 aujourd'hui. 
Ce jeu existe donc grâce au travail absolument fabuleux des équipes de développement de Square. En tant que développeur moi-même, je ne peux qu'être admiratif des développeurs de cette époque, capables de nous offrir de merveilleuses aventures malgré toutes les contraintes inhérentes à ces plateformes.   

> C'est environ 15 ans après la sortie originale du jeu que nous avons décider d'enfin nous lancer dans un remake complet du jeu. Nintendo nous a demandé de développer le jeu pour leur nouvelle console, la Nintendo DS. Le défi était intéressant, alors nous avons accepté.   
> &mdash; <cite> Hiromichi Tanaka </cite>

C'est cette taille, cette envergure qui repoussera encore et encore la sortie internationale du jeu, jusqu'au remake 3D sorti sur Nintendo DS en 2006 au Japon et 2007 dans le reste du monde. Final Fantasy III était alors le seul jeu Final Fantasy jamais sorti chez nous.   

Par conséquent, beaucoup de gens ne connaissent le jeu que grâce à ce remake 3D, mais c'est bien de la version Pixel Remaster que nous allons parler.  
Alors qu'est ce que tous ces moyens et toutes ces ambitions ont produit ? Réponse courte: un excellent jeu, mais je vais développer. 

## Scénario

Final Fantasy III nous met dans la peau de quatre orphelins vivant sur une île dans le ciel. 
Un jour, un tremblement de terre (sur une ile dans les airs, oui oui) ouvre un passage vers une grotte jusque là scellée.  
A l'intérieur, notre fraterie trouve un Cristal de Lumière qui leur octroie des pouvoirs et leur demande de s'en servir pour restaurer l'équilibre du Monde.  

En effet, cet équilibre est menacé par Xande, l'un des trois apprentis de l'Archimage Noah, qui menace de s'emparer des autres cristaux pour faire sombrer le monde dans le chaos !
Nos guerriers de la Lumière partent donc à l'aventure, aidant leur prochain dans leur quête pour stopper le maléfique sorcier, caché au fond de sa Tour de Cristal.

Un scénario très simple en apparence, mais qui suffit à offrir plus de world-building que les opus précédents de la série. Le scénario et l'objectif de nos héros est très simple, mais elle est soupoudrée de mystères dès le début. Qui est Noah ? Qui sont les deux autres apprentis ? Pourquoi Xande veut-il détruire le monde ? Qu'est ce que la tour de Cristal ? Où est-elle ? 

Je me suis posé toutes ces questions et c'est une première pour la licence. Jusqu'ici, on n'avait que très peu de mystères à élucider. Le méchant était méchant, nous jouions les gentils et ça n'allait pas plus loin. Final Fantasy III nous accroche très vite et ça va nous aider à supporter un scénario qui, je le répète, est très simple et terre à terre.

## L'appel de l'aventure 

J'ai envie de parler un peu plus longuement de la première partie du jeu. Elle commence comme  tous les autres, on est très vite jeté dans notre aventure puisque même notre petite île, perdue au milieu des cieux, subit quelques problèmes.

Mais assez vite, j'ai été perturbé par la taille de la carte. Celle-ci était en effet... minuscule.

![Carte de l'île volante de Final Fantasy III](/assets/img/articles/final_fantasy_3/ff3_sky_island_map.png)

Une cascade, un désert, une forêt, quelques grottes et deux ou trois villages. La musique très entrainante ne suffisait pas à dissiper ce sentiment d'être à l'étroit. 
On débloque très vite l'aéronef, ce qui donne l'impression d'une carte encore plus petite. En plus, par le passé, l'aéronef était une réservé à la seconde partie du jeu. Définitivement, quelque chose n'allait pas.

Puis, Cid m'apprend que ma fraterie ne vient pas de notre île, mais de la terre en dessous et m'invite à partir l'explorer.
J'avance alors par delà les limites de l'île volante à bord de mon aéronef et je comprends enfin que le jeu m'a eu, que je suis tombé dans son piège. La petite carte, la musique [*Eternal Wind*](https://open.spotify.com/track/0h3d5omX65lyQYIvJBSeIi?si=df692d516ea14e26) qui nous motive à avancer et nous donne envie d'avancer, c'était pour **ce** moment.

Nous quittons enfin notre berceau, nous voici sur la vraie map de Final Fantasy III. Devant moi, un océan qui semble infini. Je me balade quelques temps avec mon aéronef puis je pose la manette et je me laisse bercer par [*The Boundless Ocean*](https://open.spotify.com/track/3Z57dPFQ8jJ0ZY4CZqRDG4?si=9753b4b691d24bae).

Il y a de ces moments absolument magiques dans les jeux vidéos, où tous les éléments s'alignent pour créer un moment magique. A titre personnel, la découverte du vrai monde de FF3 en fait partie. La beauté de l'océan, le changement total de paysage et d'envergure, le tout sublimé par une musique qui encapsule parfaitement cette beauté sereine, celle d'un monde qui a tant d'histoires à nous raconter et tant de mystères à nous dévoiler. 

Je pourrais décrire cette scène de mille façons, voici la plus courte: cette scène est belle, c'est la première mise en scène cinématographique du gameplay de la licence, un moment "wow !" si vous préférez.

Après avoir repris ma manette, j'ouvre ma carte. Une seule île ? Tu ne m'auras pas deux fois, Final Fantasy III !
A la sortie du seul donjon qui nous est accessible, on se retrouve avec de nouvelles questions sur les cristaux, mais surtout, un deuxième moment magique.

![Carte du monde de Final Fantasy III après avoir quitté l'ile volante](/assets/img/articles/final_fantasy_3/ff3_full_map.png)

La révélation de l'océan m'avait rassurée sur l'envergue de ce jeu. Par contre, compléter le premier donjon m'a fait complètement revoir mes attentes pour ce dernier, mais je ne vous dirais pas pourquoi. 

Il n'y aura pas plus de spoilers dans cet article ! Jouez au jeu par vous même !


## Retour sur la technique (WIP)

Le jeu est plus vivant, les PNJs peuvent vous suivre, ils bougent plus souvent, ils ont des designs plus variés &mdash; de même pour les monstres &mdash; et les environnements sont plus distingués.

Notamment, les villes et villages ont tous une identité propre. Cette identité est construite non seulement grâce à la taille des villes, bien plus variée, mais aussi car chaque village est unique. Pour le dire grossièrement, il n'y a plus juste quelques villages, il y a "le village des bardes", "la grande ville centrale", "le village des invocateurs", etc...

Grâce à cette attention aux détails, le monde de FF3 gagne en crédibilité et en mémorabilité. C'est une grosse amélioration de l'expérience du joueur, qui s'orientera plus facilement mais aussi pour le jeu en lui-même, qui restera plus durablement dans les mémoires.

On notera quelques ajouts visuels plus discrets, comme la transparence lorsqu'on passe sous un pont ou derrière un batiment, ou encore la possibilité pour les ennemis d'apparaitre d'un côté ou l'autre de l'écran. 

Final Fantasy 2 avait mis le pied à l'étrier en donnant une voix à nos personnages et Final Fantasy 3 persiste dans cette direction. Nos personnages parlent, expriment des doutes, des regrets, de la joie. Les PNJs bénéficient également de ce traitement avec plus de traits reconnaissables, plus d'animations, plus de personnalité et surtout, plus de clarté. On a de plus en plus l'impression de lire des dialogues plutôt que des discours d'exposition. Il reste encore beaucoup de progrès à faire, notamment parce qu'aucun personnage n'a de développement, mais chaque chose en son temps. 

La qualité de l'écriture a été beaucoup améliorée à tous les niveaux et c'est ce qui compte. Encore une fois c'est une amélioration plutôt mineure, mais cumulée avec toutes les autres améliorations, on se retrouve avec un jeu bien plus clair, bien plus compréhensible. Pour la première fois, je n'ai pas eu besoin de lire une soluce pour finir le jeu (mieux vaut tard que jamais) !
L'histoire se paie aussi le luxe d'avoir de vraies cinématiques et pas uniquement des scènes de dialogues avec quelques mouvements en plus. Ici, pour la première fois, la caméra quitte les personnages principaux pour nous montrer ce qu'il se passe. Encore une bonne idée pour développer l'histoire de façon plus convaincante. 

## Le système de combat se cherche (WIP)

Cette fois, les jobs sont très nombreux (22 au total !) et on peut les changer à volonté, n'importe où, n'importe quand. En plus du niveau de vos personnages, les jobs disposent aussi de leur propre niveau. Augmenter le niveau d'un job vous donnera divers avantages: plus d'emplacements de sorts (très bonne idées), plus de dégats, de précision, de nouvelles techniques uniques à chaque job.
Ma critique principale envers FF1 étant la gestion des emplacements de sorts, j'étais ravi de voir ces améliorations dès le début du jeu.
Chaque job a accès à différentes armes, différents poids d'armure et différents sorts. On notera aussi quelques subtilités comme le Karatéka qui frappe plus fort lorsqu'il n'a pas d'arme. 
Enfin, avec autant de jobs, on a aussi bien plus de variété. c'est dans Final Fantasy 3 que l'invocateur, l'érudit, le chevalier noir, le chevalier dragon et d'autres apparaissent. L'invocateur amène avec lui les.. invocations,  un troisième type de magie en plus de la magie noire et la magie blanche. Le Géomancien est un mage dont les sorts dépendant de l'environnement (et sont donc aléatoires), le Barde soutient l'équipe avec ses chansons, le chevalier oignon pue la merde.

Cependant, les améliorations s'arrêtent ici pour le système de combat et les défauts présents dans FF1 et 2 subsistent. L'ordre d'actions n'est toujours pas connu (bien que manipulable avec le Barde dans une certaine mesure) et il est toujours possible de se faire arnaquer par les bosses, qui peuvent balancer une grosse AOE en dernier dans le tour, puis la même AOE en première action du tour suivant, ce qui n'offre aucune parade et résulte souvent en un game over.
En parlant d'AOE, vous n'aurez aucun sort de zone pour la très grande majorité du jeu . Les seuls sorts de zones sont les invocations et les sorts de niveau 8 (le plus haut niveau de sort du jeu), et même si certains jobs ont une action de job qui inflige des dégats de zone, ces jobs ne seront accessibles que dans la seconde moitié du jeu. C'est un peu moins gênant dans cet opus que dans le précédent, puisque les groupes de monstres dépasseront rarement les quatre ennemis, mais je ne comprends quand même pas pourquoi les options de dégats de zones sont aussi limitées.

On en arrive à la progression au sein du jeu. La grande variété de jobs disponibles et la flexibilité avec laquelle le joueur peut changer son équipe s'accompagnent d'une plus grande variété d'ennemis. Certains résistent à la magie, se soignent quand vous les frappez avec le mauvais éléments, changent leurs résistances au milieu du combat, j'en passe et des meilleures. Tous ces éléments pointent vers un désir de pousser le joueur à expérimenter, à varier ses compositions d'équipes pour les adapter aux divers combats. Cependant, comme dit plus haut, beaucoup de bonus viennent du niveau de votre job. Si vous voulez en changer régulièrement, il faudra donc farmer, farmer, farmer. Je ne pense pas que ce soit un défaut en soit, mais je préfère soulever ce point au cas où votre lecture vous donnerait envie de (re)jouer à FF3.

Il y a de toute façon de grandes chances pour que vous passiez du temps à farmer à un moment du jeu. Certains bosses sont vraiments corriaces et vous écraseront sans pitiés, plusieurs fois. Alors dans ce cas, pas le choix, il faut pex ! Farm de niveau, de gils, de niveau de jobs, tout le monde y passe ! Et pour ça, on dit merci à l'option xp et gils x4 proposée par le pixel remaster. Et si ma dernière phrase vous a choqué, je vous répondrais que j'ai encore 17 ou 18 jeux de la licence à découvrir, donc hein, pouet !

## L'exploration se peaufine


Final Fantasy 3 nous pousse à l'exploration avec une technique vieille comme le monde: nous mettre sous le nez des endroits inaccessibles dans un premier temps. En dissémninant sur la carte ses points d'intérêts de la sorte, le joueur va beaucoup se balader et ainsi apprendre la carte, retenir où sont les différentes grottes, où se situent les endroits qu'il n'a pas pu atteindre. Le tout est accompagné de dialogues de PNJs nous indiquant plus ou moins subtilement l'emplacement de trésors qui lui aurait échappé. Enfin, cerise sur le gateau, la plupart des lieux se distinguent par un PNj particulier, un monument ou une ambiance. Dans le monde de Final Fantasy 3, vous ne trouverez pas "Village 1" ou "Village 2", vous trouverez "Le village des invocateurs", "Le manoir doré" ou "L'immense ville du milieu de la carte". Créer autant de lieux reconnaissables permet au joueur de s'investir dans ce monde et lui permet également de se repérer bien plus rapidement pour pouvoir enchainer les missions sans se perdre. L'objectif pour cet opus me semble clair: casser la linéarité de la progression et rendre le jeu immersif autant que faire se peut. 

J'ai émis quelques critiques envers le système de combat, mais je n'en ai aucune contre le terrain de jeu proposé par Square. La copie est impécable à ce niveau et c'est même la découverte de la carte qui provoque le premier effet "WOW" de la licence jusqu'ici. Je ne pensais pas qu'il était possible de faire rentrer autant de choses dans une cartouche de NES (titre).

## L'héritage de la licence se construit

Avec un scénario centré autour des cristaux, on retrouve évidemment le leitmotiv de la licence (présent dans FF1 mais pas dans le 2 si ma mémoire est bonne). On retrouve également des thèmes musicaux qui ont fait leur petit bonhomme de chemin jusqu'à FF14 notamment (coucou Eternal Wind, coucou les musiques de la Tour de Cristal). J'admet avoir eu quelques frissons en reconnaissant ces mélodies qui me sont si familières grâce à leur intégration dans divers aspects de Final Fantasy XIV. Mais même sans cet aspect "nostalgique" qui est propre à mon expérience de jeu, les musiques sont excellentes. Nobuo Uematsu nous propose aussi bien des balades calmes et envoutantes que des musiques exprimant la gravité du mal qui s'abat sur le monde. Que ce soit la version original en 8-bits ou la version remasterisée du Pixel Remaster, je ne peux que vous recommander d'y jeter une oreille. Je ne peux pas conclure cette partie sur la musique sans vous donner une petite liste de morceaux à écouter: `The Prelude`, `Eternal Wind`, `Chocobos!`, `The Crystal Tower`, `Forbidden Land` et `This is the Last Battle`.

## Conclusion
