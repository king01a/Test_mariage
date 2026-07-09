# Site d'invitation - Mariage Valderine & Jenner

## Structure
- invitation.html   -> la page à ouvrir (via ?id=XXXX)
- assets/billet.jpg -> l'image du faire-part
- assets/music.mp3  -> À AJOUTER : la composition musicale du mariage
- data/guests.json  -> liste des invités (id -> nom + date d'expiration)

## Déploiement sur GitHub Pages
1. Créer un nouveau dépôt sur GitHub (ex: "invitation-mariage"), public ou privé.
2. Uploader tout le contenu de ce dossier "site/" à la racine du dépôt.
3. Ajouter le fichier assets/music.mp3 (la composition du mariage).
4. Dans le dépôt : Settings > Pages > Source: "main" branch, dossier "/ (root)".
5. GitHub donne une URL du type: https://VOTRE-PSEUDO.github.io/invitation-mariage/

## Lien de test (invité: Mme & M. OYONO OVONO)
https://VOTRE-PSEUDO.github.io/invitation-mariage/invitation.html?id=fnPXzM4gPqbflsXs

Remplacer VOTRE-PSEUDO par votre nom d'utilisateur GitHub une fois déployé.

## Ajouter d'autres invités
Éditer data/guests.json et ajouter une entrée par invité avec un identifiant
aléatoire différent (16 caractères), par exemple:

{
  "fnPXzM4gPqbflsXs": { "name": "Mme & M. OYONO OVONO", "expires": "2026-07-10T17:00:00+01:00" },
  "UN_AUTRE_TOKEN_ICI": { "name": "Nom du prochain invité", "expires": "2026-07-10T17:00:00+01:00" }
}

Je peux générer automatiquement tous les tokens et le fichier guests.json
complet dès que vous me donnez la liste complète des invités.
