+++
title = "SAGBOT.com"
date = 2024-09-21
author = "Lurgrid"
tags = ["SAGBOT", "Lurgrid", "Website"]
keywords = ["Lurgrid", "SAGBOT", "SAGBOT.com", "Hugo", "Markdown", "Website"]
cover = "image.png"
+++

## Histoire de *SAGBOT.com*

*SAGBOT.com* a vu le jour à la fin de l'année 2021. Depuis son lancement, le site a connu de nombreuses évolutions visuelles, chacune marquée par des mises à jour fréquentes. Cependant, un fil conducteur persiste à travers ces changements : le projet n'a jamais été totalement achevé. Souvent, je manquais de motivation pour travailler sur le front-end, n'ayant pas vraiment l'âme d'un artiste, ni la plume d'un écrivant, je ne savais pas quoi écrire pour enrichir le contenu.

Les anciennes versions étaient faites essentiellement avec **HTML/CSS/PHP/JS** et étaient souvent des sites web monopage (*SPA*). Et comme dit précédemment elles étaient fréquemment vide de contenu, voire contenaient encore des remplisseurs (*placeholder*) et même dans le pire des cas des liens menant à des pages *404*, car n'étant pas encore coder.

J'étais arrivé à un tel point que pendant des mois *SAGBOT.com* (avant de faire finalement ce site web), il ressemblait à ça, juste une page noire avec un simple &laquo; Welcome to SAGBOT.com &raquo; et une petite animation qui fait bouger le texte

{{< figure src="/posts/sagbot.com/old_sagbot.com.gif" alt="Gif Old SAGBOT.com" position="center" caption="GIF de la dernière version de <i>SAGBOT.com</i>" captionPosition="center" >}}

## Version actuelle

La version actuelle de *SAGBOT.com* n'est plus du tout basé sur les mêmes technologies et n'a plus le même bût. Le projet *SAGBOT* ayant évolué et devant plus personnel, il en vient que *SAGBOT.com* doit devenir un site web personnel. De ce fait maintenant *SAGBOT.com* est un blog où je posterais des articles sur l'informatique ou même l'évolution du projet, comme celui.

### Conception

Avant de coder il faut déjà se poser la question &laquo; Comment je veux que *SAGBOT.com* soit ? &raquo;. Après avoir réfléchi et même en discutant avec des proches, j'en ai conclu que *SAGBOT.com* doit devenir un blog sur l'informatique, pour être plus en adéquation avec mon projet professionnel qui est de devenir enseignant-chercheur (cf. [À propos](https://www.sagbot.com/fr/about)). Étant donné que dans le monde de la recherche la rédaction d'article est monnaie courante.

Maintenant que j'ai le sujet du site web, il faut savoir comment le mettre en forme. Déjà le monopage c'est fini, car pas vraiment compatible avec les blogs. Il faut qu'aussi la rédaction d'article soit simple et que je n'ai à pas devoir recoder une page **HTML** pour chaque article, car sinon ça sera un frein à la rédaction et le site finira comme les autres <u>vides</u>. Maitrisant le **LaTeX** et le **Markdown** et leurs syntaxes étant simple et étant centré sur la réaction, il fallait que je puisse générer une page **HTML** depuis un document d'un de ces deux langages. L'un des plus grands avantages du **LaTeX** c'est la liberté qu'on a et les nombreux paquetages (*package*) permettant une mise en page personnalisé (*Tikz*, etc.). Malheureusement son avantage peut devenir un défaut dans notre cas, car rendant compliquer la compatibilité de l'ensemble des paquetages dans notre générateur de page **HTML**. De ce fait, il ne reste qu'un véritable choix le **Markdown**.

Étant que j'admire du langage de programmation **Rust**, je voulais initialement faire le site avec et avec les bibliothèques [markdown-rs](https://github.com/wooorm/markdown-rs) ou [mdx-rs](https://github.com/wooorm/mdxjs-rs). En me renseignant sur le [**MDX**](https://mdxjs.com/), celui ci me paraissait le candidat parfait pour faire les articles, car ce format de **Markdown** permet d'utiliser du **JS/JSX** dans un document **Markdown**. Mais en discutant avec des proches qui ont aussi des sites web, ils m'ont conseillé de ne pas utiliser **MDX**, mais de plutôt utiliser des outils de générateur de site web avec du **Markdown** comme [**Hugo**](https://gohugo.io/) ou [**Zola**](https://www.getzola.org/), car correspondrait plus à mon utilisation et serait plus simple que de tout refaire. L'un de mes proches avait même déjà un site web crée avec **Hugo** et en était très content.

Après la lecture des documentations de ces deux outils, **Hugo** me paraissait plus simple et plus en adéquation avec ce que je voulais faire. C'est comme cela que j'en suis arrivé là à utiliser **Hugo**. Comme j'ai dit au début de cet article, je n'ai pas vraiment l'âme d'un artiste, ce qui fait que j'utilise donc un thème que [panr](https://radoslawkoziel.pl/) a mis à disposition de tout le monde &laquo; [Hugo Terminal](https://themes.gohugo.io/themes/hugo-theme-terminal/) &raquo; avec les couleurs généré à partir de son outil [Terminal.css](https://panr.github.io/terminal-css/).

### Les articles

Comme dit précédemment les articles qui vont se trouver sur *SAGBOT.com* seront des articles sur l'informatique, sur des sujets divers et varier qui me plaise. Le bût sera d'en rédigé de temps en temps, en espérant que ça puisse intéresser des personnes. Pour que les articles soient le plus disponible possible l'ensemble des articles seront traduit en anglais, car étant une langue internationale.

## Conclusion

La création de *SAGBOT.com* a été un véritable quête d'apprentissage et de persévérance. Malgré les nombreux défis rencontrés, ce projet a grandi pour refléter mes aspirations personnelles et professionnelles. En passant d'un simple site monopage à un blog, j'ai pu transformer une idée inachevée en une plateforme dynamique et utile.

L'adoption de **Hugo** comme générateur de site web a été une décision importante, facilitant la gestion des articles et assurant une évolutivité. Cette transition témoigne de l'importance de choisir les bons outils pour la vision à long terme d'un projet. De plus, l'intégration de thèmes a permis de donner à *SAGBOT.com* une identité visuelle, malgré mon autoperçu manque d'aptitudes artistiques.

À l'avenir, *SAGBOT.com* continuera de grandir en tant que ressource dédiée à l'informatique et à l'évolution du projet *SAGBOT*. Je suis enthousiaste à l'idée de partager davantage de connaissances, de réflexions et de découvertes avec une audience internationale grâce aux traductions en anglais. Ce site représente non seulement une vitrine de mes compétences techniques, mais aussi un espace d'expression et de partage dans le domaine de la recherche.

Je suis reconnaissant pour le soutien et les conseils reçus tout au long du développement, qui ont été déterminants pour surmonter les obstacles et concrétiser ce projet.

Il ne me reste plus qu'à écrire des articles !

---

### Remerciement

Je remercie [T. RENAUX VERDIERE](https://renauxv.fr/) et [Mirabelle S. P.](https://github.com/oiimrosabel) pour les conseils donner tout au long de la recherche et de la création de ce site web. Je remercie plus particulièrement T. RENAUX VERDIERE pour la relecture de cet article et des autres pages du site web.