# Agent de planning de révisions

Projet personnel en cours de développement.

Un programme en Python qui utilise un modèle d'IA pour construire un planning de révisions. On lui donne ses dates d'examens et ses disponibilités, et il propose un planning jour par jour.

## Principe

Le programme fonctionne comme un agent : l'IA reçoit la demande de l'utilisateur et choisit elle-même quels outils utiliser pour y répondre. Les outils sont des fonctions Python simples :

- `jours_restants` : calcule le nombre de jours avant chaque examen
- `lire_chapitres` : lit la liste des chapitres à réviser dans un fichier texte
- `enregistrer_planning` : enregistre le planning final dans un fichier

Exemple de demande :

```
J'ai un partiel de maths le 15 janvier et un partiel d'info le 20 janvier.
Je suis libre le soir et le week-end.
```

## Avancement

- [ ] Version 1 : programme en terminal qui envoie une demande au modèle et affiche sa réponse
- [ ] Version 2 : ajout des trois outils et de la boucle de l'agent
- [ ] Version 3 : enregistrement du planning dans un fichier et gestion des erreurs

## Technologies

- Python
- API d'un modèle de langage
