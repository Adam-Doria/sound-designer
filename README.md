# sound-designer


<h2> Le Projet </h2>
Avant d'être apprenant à Ada Tech School, Clément Badin était ingénieur son pour le cinéma. 
N'ayant jamais créé de portfolio sur son travail, il a profité de cette reconversion pour le faire. 
<a href="https://website-sound-designer.vercel.app/" target="_blank"> 
  <br/>Cliquez ici </a> pour voir le rendu du projet. 

Pour info Clément aussi est à la recherche d'une entreprise où faire son alternance .
<br/> <a href="mailto:clementbadin@gmail.com" target="_blank"> 📧 Pour le contacter </a>  <br/>
<a href="https://github.com/clem0316" target="_blank"> 💻 Pour voir son travail</a> <br/>
<a href="https://www.linkedin.com/in/cl%C3%A9ment-badin/" target="_blank"> 🕵️‍ Pour le Stalker</a>  


<h2> Mon rôle </h2>

Mon rôle a été de faire du pair-review sur ce projet.<br/>
J'ai ainsi pu proposer une solution alternative au code ayant été écrit, permettant de limiter les répétitions et faciliter les modifications. <br/>
Pour cela un module contenant une base de donnée a été créé.<br/>
Puis l'affichage des données pertinentes se fait à l'aide des méthodes .filter() et .map().

Les + :

- Réduction du code JS  ( ~400 lignes => ~60 lignes)
- Réduction du CSS (même classe utilisée)
- Utilisation des flexbox facilitant la responsivité du site.
- Facilitation des modifications. Il n'y a plus que le module servant de base de données à modifier.

Les - :
- La sous-navigation se fait par manipulation du DOM, l'intégralité du dom doit être à nouveau rendu à chaque fois.
- Ecouteurs d'évènements en grande quantité,leur propagation n'est pas stoppée possibilité de conflits.
- L'accessibilité est à travailler

Ce que j'ai appris :

- Reprise d'une code base 
- Echange technique avec un pair, explication du choix de l'architecture et des méthodes utilisées.
- Reflexion sur la scalabilité, et la transmibilité du code.
- Clean code, intéret dans l'architecture logiciel. 

<h2> Evolutions possibles </h2>

-Passer le site en NextJS/NuxtJS => Réactivité de React/VueJS, Dom vituel pour render uniquement les parties qui nous intéressent, limitation du nombre d'Eventlisteners, meilleur SEO et gestion de la BDD possible.
<br/>-CSS : passage sur tailwind ou Emotion pour un meilleur suivi du CSS. 

