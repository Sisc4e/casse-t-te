# La Main et l'Œil

Casse-tête coopératif pour deux joueurs, sur deux écrans, au gameplay asymétrique.

- **La Main** est enfermée dans le coffre : elle voit et manipule les mécanismes (labyrinthe, fioles, lumières, serrure) mais n'a aucun plan. Elle détient la table qui traduit les runes du cadran.
- **L'Œil** a tous les plans de l'horloger mais ne voit pas le coffre. Il manipule le cadran à distance, dont il ne peut pas lire les runes seul.

Seule la parole relie les deux joueurs.

## Jouer

Ouvrez `index.html` dans un navigateur (ou publiez le dépôt avec GitHub Pages). Chaque joueur ouvre la page sur son appareil, saisit **le même code de partie** et choisit un rôle différent. Le code génère la même énigme des deux côtés, sans serveur : vérifiez que le *sceau* affiché est identique.

## Les mécanismes

| Mécanisme | Ce que voit la Main | Ce que sait l'Œil |
|---|---|---|
| Labyrinthe | Sa position, l'étoile, deux anneaux, pas de murs | 4 plans avec murs ; les anneaux identifient le bon |
| Fioles | Symbole du chaudron, fumée, 4 fioles (dont une parfois fêlée) | Grimoire : ordre des couleurs par symbole + règles |
| Lumières | Panneau 4×4 (chaque pression bascule la croix) | Motif cible, dessiné vu de derrière (miroir) |
| Cadran / Serrure | Table runes → chiffres selon la lampe | Le cadran : runes, lampe, roues à chiffres ; révèle le mot |

Difficultés : Détendu (sans chrono), Normal (15 min, 5 alarmes), Expert (9 min, 3 alarmes).
