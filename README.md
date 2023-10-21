L’ainé apprend les additions et il en fait tout le temps. À table, au réveil… On a trouvé quelques jeux, mais j’avais envie d’écrire un jeu/programme pour changer un peu et l’encourager à faire des additions plus dures, plus vite, voir ce qui coince…



J’ai écrit le gros de cette app en 1h30, avec un gros coup de pouce de ChatGPT.

Le prompt suivant contient les spécifications du jeu que je voulais faire

```
create a javascript app that has 3 screens:
 - difficulty screen: you can select between 3 difficulties: "easy", "medium" and "difficult".
 - game screen:
   - Initialize the game by generate all pairs of numbers: (i, j) for (i, j) between 1 and 5.
   - until all pairs have been displayed:
    - display a random remaining pair of numbers
    - ask the result of the operation that was select
    - when "space" is hit on the keyboard, display the result, and 2 buttons, "success" and "failure". When success is hit, note that this pair was a success. When failure is hit, note that this pair was a failure
 - Result screen: when all pairs have been displayed, show the number of success and failures
```

ChatGPT a toussé un peu, et j’ai cru allait me laisser tomber

> Creating a complete JavaScript app with the described functionality is a complex task. I'll provide you with a simplified example of how you can structure the app and provide the basic code for each screen.

…mais finalement il a fourni d’un coup un fichier HTML avec les grandes lignes de l’app. Quelques trucs ne collaient pas, et je n’avais pas précisé certains éléments, mais j’avais une base fonctionnelle à partir de laquelle construire.

Par la suite, j’ai utilisé ChatGPT comme outil pour aller plus vite. Dessiner la table des opérations, etc. Au final le code est plutôt crado et bien en dessous de mes standards pro. C’est cathartique de faire ça, [vous devriez faire pareil](https://ntietz.com/blog/write-more-useless-software/). Mais rapidement j’avais une version complètement jouable, et on s’est bien amusés avec.

Comme le dit Simon Willinson, ChatGPT a augmenté mon courage. Seul, j’aurais pu faire ce programme, mais ça m’aurait pris plus de temps.