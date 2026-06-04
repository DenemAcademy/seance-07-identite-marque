# Séance 07 - Identité de marque - Moments importants

Transcription complète disponible dans `seance-07-identite-marque-transcription.txt`.
Segments horodatés disponibles dans `seance-07-identite-marque-segments.json`.

## Fil pédagogique

Je crée une identité de marque simple, utilisable tout de suite. Le but n'est pas de construire une charte graphique complète, mais de produire un logo propre, de le comparer entre Gemini et ChatGPT / GPT Image, puis de le ranger dans `~/Desktop/mon-business/00-brand/`.

## Repères chronologiques

| Timestamp | Moment | Décision pédagogique |
| --- | --- | --- |
| 00:00:01 | Démarrage de la séance 7 | Je passe au design et je crée un logo pour un profil freelance ou une agence. |
| 00:00:16 | Rappel de la séance 6 | Le QG existe déjà et le dossier `00-brand` attend les assets de marque. |
| 00:00:47 | Sortie attendue | Je veux un logo et un mini brandbook avec nom, couleur et chemin du logo. |
| 00:01:19 | Limite volontaire | Le design est subjectif, donc je montre une méthode simple plutôt qu'une théorie longue. |
| 00:01:43 | Les 3 infos | Je prépare nom de marque, couleur principale et style. |
| 00:02:35 | Gemini / Nano Banana | Je lance la génération d'image dans Gemini pour obtenir une V1. |
| 00:03:12 | Prompt logo | Je colle un prompt en français avec contraintes : minimal, vectoriel, plat, pas de 3D, pas de photo. |
| 00:05:21 | Première génération | J'attends le logo, puis je juge police, symbole et lisibilité. |
| 00:07:39 | Itération couleur | J'ajoute du vert sans repartir de zéro. |
| 00:10:00 | Sauvegarde Gemini | Je vérifie le fond blanc et l'éventuel marquage de génération. |
| 00:10:58 | Focus ChatGPT / GPT Image | Je colle le même prompt dans ChatGPT pour comparer proprement. |
| 00:11:47 | Résultat ChatGPT | La version est exploitable ; je regarde l'icône comme futur favicon. |
| 00:12:46 | Choix final | Même si la couleur n'est pas exactement celle demandée, je peux garder la version verte si elle sert mieux la marque. |
| 00:13:18 | Rangement | J'enregistre dans `mon-business/00-brand/` et je renomme le fichier clairement. |

## Prompts à reprendre

### Logo professionnel

```text
Crée un logo professionnel pour une marque appelée "[NOM_DE_MARQUE]".

Style : minimal, vectoriel plat, lignes nettes, pas de 3D, pas de photo.
Type de logo : icône + texte.
Couleur principale : [COULEUR_PRINCIPALE] ou [CODE_HEX].
Fond blanc.
Typographie sans serif moderne, graisse medium-bold.
Composition centrée, espace blanc.
Format carré.

Contraintes :
- pas de dégradé
- pas de clipart
- pas d'effet 3D
- pas de mockup
- pas de photo

Ne génère qu'une seule version, propre et aboutie.
```

### Itération couleur

```text
Garde la même idée de logo, mais ajoute une palette jaune + vert.
Garde le style minimal, vectoriel plat, le fond blanc et le nom de marque.
Ne génère qu'une seule version propre.
```

### Mini brandbook

```text
Crée un fichier brandbook-mini.md pour ma marque.

Ajoute :
- nom de marque
- secteur
- cible
- style visuel
- couleur principale
- couleurs secondaires
- chemin du logo
- règles à respecter
- règles à éviter
- prompt utilisé pour générer le logo
```

## Points de vigilance

- Je ne multiplie pas les variantes : une V1, une correction, une comparaison, puis je décide.
- Je vérifie le nom lettre par lettre, surtout si le logo contient du texte.
- Je regarde le symbole en petit format, comme un favicon.
- Je ne laisse pas l'image dans Téléchargements.
- Je range le fichier dans `00-brand` et je note le chemin dans le mini brandbook.

## Décision finale attendue

À la fin, je dois avoir :

- `logo-agence-restia.png` ou un nom équivalent, rangé dans `~/Desktop/mon-business/00-brand/`
- un prompt conservé
- un mini brandbook prêt à être utilisé dans les prochaines séances
- une seule version officielle du logo
