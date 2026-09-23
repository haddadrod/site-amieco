# Site vitrine AMIECO

Site statique (HTML + CSS, sans build) d'**AMIECO (Advice, Management, Import & Export) Ltd**,
société mauricienne d'intermédiation commerciale.

```
index.html             # page d'accueil (une page, sections ancrées)
mentions-legales.html  # mentions légales
styles.css             # feuille de style (thème clair + sombre)
vercel.json            # URL propres (/mentions-legales) et en-têtes de sécurité
```

## Voir le site en local

Ouvrir `index.html` dans un navigateur, ou `npx serve .` à la racine.

## Mettre en ligne (Vercel)

1. Sur vercel.com : « Add New… » → « Project » → choisir ce dépôt.
2. Framework Preset : « Other ». Ne rien renseigner d'autre.
3. « Deploy ». Puis Settings → Domains pour ajouter le nom de domaine ; HTTPS est automatique.

Chaque commit poussé sur `main` remet le site en ligne.

## À compléter avant la mise en ligne

1. **Coordonnées** : bloc `CONTACT` en bas de `index.html` (e-mail, téléphone, endpoint de formulaire).
   Dès qu'ils sont renseignés, les lignes E-mail / Téléphone apparaissent dans la section Contact.
   Sans endpoint de formulaire, le formulaire ouvre le client mail du visiteur avec le message pré-rempli.
2. **Hébergeur** : section « Hébergement » de `mentions-legales.html`.
3. **Textes à valider** : les engagements (rémunération au résultat, un seul interlocuteur,
   horaires 9h–18h) sont des formulations proposées, à ajuster à la pratique réelle.

## Ce qui vient des documents officiels

Raison sociale, BRN `C20170178`, n° de dossier `C170178`, date d'immatriculation (21/01/2020),
siège (5, Bissoondoyal Street, Port-Louis), forme (private / domestic), statut « Live » et
absence de constitution propre (Companies Act 2001) proviennent de l'extrait du Registrar of
Companies du 05/08/2026. Aucun chiffre d'activité, client ou témoignage n'a été inventé.
