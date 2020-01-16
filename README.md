# J04_projet_THP
Crée donc un repo GitHub dans lequel tu auras la structure suivante :

ton_dossier
├── lib
│   ├── 00_journalists.rb
│   └── 01_cryptocurrencies.rb
└── README.md
2.2. Big data
Avec ton groupe, vous avez entendu parler d'un concept qui marche bien nommé le Big Data. Vous vous êtes chauffés pour vous lancer dedans et proposer des prestations de conseil facturées à des prix indécents. Grâce à vos super compétences en réalisation de Landing Pages, vous avez déjà votre premier client : une entreprise de Growth Hacking. Cette dernière a obtenu une liste de plusieurs centaines de comptes Twitter qu'ils voudraient analyser.

À partir de ce array, code un programme ruby qui répondra aux questions suivantes :

Combien y a-t-il de journalistes dans ce array ?
Combien d'handle contiennent un numéro ?
Combien d'handle contiennent les 4 lettres du prénom "Aude" à la suite (sans prendre en compte les majuscules) ?
Combien commencent par une majuscule (première lettre juste après le @) ?
Combien contiennent une majuscule ?
Combien y a-t-il de underscore _ dans tous les pseudos confondus ?
Trie la liste de handle par ordre alphabétique.
Quels sont les 50 handles les plus courts de ce array ?
Quelle est la position dans l'array de la personne @epenser ?
Si tu as bien compris, quand tu lances le script, les réponses aux questions s'affichent sur ton écran de Terminal via des puts. N'hésite pas à ajouter un peu de pep’s à ton programme en écrivant des phrases, en ajoutant des blagues, voir en faisant un menu (pour les plus chauds) où l'utilisateur peut choisir, dans une liste, la question à laquelle le programme va répondre.

2.3. Blockchain
Après le succès de votre firme, vous vous êtes dits que vous pourriez mélanger deux fois plus de buzzwords et faire une firme qui fait de la big data sur de la blockchain. Votre idée est en train de disrupter le consulting et tous les grands groupes en quête de digitalisation veulent faire appel à vos services. Vous venez de signer un contrat pour Carrefour.io et vous allez devoir analyser des données de cryptomonnaies.

Maintenant on va travailler avec des hash. Voici deux arrays, un qui contient des noms de devise, un qui contient des prix.

Associe chaque devise à son montant pour obtenir un hash du genre :

my_hash = {Bitcoin: $6558.07, Ethereum: $468.95, XRP: $0.487526, etc.}
Hint : Il est entièrement possible de le faire "à la main" via une boucle, mais je t'invite à chercher s’il n'existe pas une méthode Ruby spécialement pour ça 😉.

Une fois cette association réalisée, code un programme Ruby pour donner :

La ou les crypto qui ont la plus grosse valeur.
La ou les crypto qui ont la plus petite valeur.
Le nombre de crypto contenant le mot "coin".
Les devises, dont le cours est inférieur à 6000 (Indice : on peut comparer en valeur 2 integers mais pas 2 strings. Pense bien à enlever le $ et éventuellement utiliser .to_i pour faire cet exercice).
La devise la plus chère parmi celles dont le cours est inférieur à 6000.
