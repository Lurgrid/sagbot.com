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

Les anciennes versions étaient faites essentiellement avec **HTML/CSS/PHP/JS** et étaient souvent des sites web monopage (*SPA*). Et comme dit précédemment elles étaient fréquemment vide de contenu, voire contenaient encore des remplisseurs (*placeholder*) et même dans le pire des cas des liens menant à des pages *404*, car n'étant pas encore codé.

J'étais arrivé à un tel point que pendant des mois *SAGBOT.com* (avant de faire finalement ce site web), il ressemblait à ça, juste une page noire avec un simple &laquo; Welcome to SAGBOT.com &raquo; et une petite animation qui fait bouger le texte.

{{< figure src="/posts/sagbot.com/old_sagbot.com.gif" alt="Gif Old SAGBOT.com" position="center" caption="GIF de la dernière version de <i>SAGBOT.com</i>" captionPosition="center" >}}

## Version actuelle

La version actuelle n'est plus du tout basé sur les mêmes technologies et n'a plus le même bût. Le projet *SAGBOT* ayant évolué et devant plus personnel, il en vient que *SAGBOT.com* doit devenir un site web personnel. À ce jour, il devient un blog où je posterais des articles sur l'informatique ou même l'évolution du projet, comme celui.

### Conception

Avant toute chose, je suis me demander &laquo; Comment, je veux que *SAGBOT.com* soit ? &raquo;. Après réflexion, et même en discutant avec des proches, j'en ai conclu que *SAGBOT.com* devait devenir un blog sur ma passion ; l'informatique, pour être plus en adéquation avec mon projet professionnel qui est de devenir enseignant-chercheur (cf. [À propos](https://www.sagbot.com/fr/about)). Étant donné que dans le monde de la recherche la rédaction d'article est monnaie courante.

Après avoir obtenu le sujet, il fallait le mettre en forme. Tout d'abord, le monopage, c'est fini, par incompatibilité avec l'idée de blog. Il fallait que la rédaction soit simple à mettre en oeuvre. Devoir recoder une page **HTML** pour chaque article, aurait était un frein et le site aurait fini comme les autres, <u>vides</u>. Maitrisant le **LaTeX** et le **Markdown**, connaissant alors la puissance de leurs syntaxes, j'ai donc voulu mettre en place une création d'article à partir de ces langages.

L'un des plus grands avantages du **LaTeX**, est la liberté que l'on dispose, ainsi que les nombreux paquetages (*package*) permettant une mise en page personnalisé (*Tikz*, etc.). Malheureusement, son avantage peut devenir un défaut, rendant compliquer la compatibilité de l'ensemble des paquetages dans un générateur de page **HTML**. De par ces raisons, j'ai choisi d'utiliser le **Markdown**.

Étant admirateur du langage de programmation **Rust**, je voulais initialement faire ce site avec l'une des bibliothèques suivantes ; [markdown-rs](https://github.com/wooorm/markdown-rs), [mdx-rs](https://github.com/wooorm/mdxjs-rs). En me renseignant sur [**MDX**](https://mdxjs.com/), celui-ci me paraissait le candidat parfait pour faire les articles, car ce format de **Markdown** permet d'utiliser du **JS/JSX** dans un document **Markdown**. Mais en discutant avec des proches qui ont aussi des sites web, ils m'ont conseillé de ne pas utiliser **MDX**, mais de plutôt utiliser des outils de générateur de site web passant par du **Markdown** comme [**Hugo**](https://gohugo.io/) ou [**Zola**](https://www.getzola.org/). Correspondant bien plus à mon utilisation, sans même avoir besoin de tout refaire. L'un de mes proches avait même déjà un site web crée avec **Hugo** et en était très content.

Après la lecture des documentations de ces deux outils, **Hugo** me paraissait plus simple et plus en adéquation avec ce que je voulais faire. C'est pour cela que j'en suis arrivé à utiliser **Hugo**. Tout comme évoqué au début de cet article, n'ayant pas l'âme d'un artiste, j'utilise donc un thème [Hugo Terminal](https://themes.gohugo.io/themes/hugo-theme-terminal/) fait par [panr](https://radoslawkoziel.pl/) et mis à disposition de tout le monde, avec les couleurs généré par l'outil [Terminal.css](https://panr.github.io/terminal-css/).

### Les articles

Comme dit précédemment les articles qui vont se trouver sur *SAGBOT.com* auront comme sujet l'informatique, sur des notions diverses et varier qui me plaise. Le but sera d'en rédiger de temps en temps, en espérant que cela puisse intéresser des personnes. Pour rendre ces articles accessibles, ils seront tous traduits en anglais, du fait que c'est une langue internationale.

## Conclusion

La création de *SAGBOT.com* a été un véritable fils rouge depuis la découverte de l'informatique. Tout au long de mon apprentissage, que ce soit par le biais académique ou autodidacte. J'ai essayé de faire ressentir chaque brin de savoir sur ce site.

L'adoption de **Hugo** comme générateur de site web a été une décision importante, facilitant la gestion des articles et assurant une évolutivité. Cette transition témoigne de l'importance de choisir les bons outils pour une vision à long terme d'un projet. Pour finir, l'intégration de thèmes a permis de donner à *SAGBOT.com* une identité visuelle, malgré mon autoperçu manque d'aptitude artistique.

À l'avenir, *SAGBOT.com* continuera de grandir en tant que ressource dédiée à l'informatique et à l'évolution de mon plus grand projet *SAGBOT*. Je suis enthousiaste à l'idée de partager davantage de connaissances, réflexions et découvertes à une audience.

Je suis reconnaissant pour le soutien et les conseils reçus tout au long du développement, qui ont été déterminants pour surmonter les obstacles et concrétiser ce projet.

Il ne me reste plus qu'à écrire des articles !

---

### Remerciement

Je remercie [T. RENAUX VERDIERE](https://renauxv.fr/) et [Mirabelle S. P.](https://github.com/oiimrosabel) pour les conseils donné tout au long de la recherche et de la création de ce site web. Je remercie plus particulièrement T. RENAUX VERDIERE pour la relecture de cet article et des autres pages du site web.