# FiliDerma — Contenu du site web

Fiche de référence du contenu du site (`index.html`). À tenir à jour si le texte change.

## Identité

- **Nom de la clinique** : FiliDerma
- **Praticienne** : Dominique Filion, **infirmière-injectrice**
- **Ville** : Laval, Québec
- **Adresse** : à confirmer (affichée sur le site comme « Adresse exacte à venir »)
- **Téléphone / prise de rendez-vous** : (514) 212-9791
- **Fonctionnement** : sur rendez-vous uniquement, aucun accès sans rendez-vous — la cliente appelle et Dominique se rend disponible.

## Services (confirmés par Dominique, enregistrement audio du 22 juillet 2026)

1. **Neuromodulateurs** (relaxants musculaires, ex. Botox®) — détendent les muscles responsables des rides d'expression.
2. **Agents de comblement** (acide hyaluronique) — redonnent du volume, redessinent les lèvres, restaurent les contours du visage.
3. **Biostimulants** — stimulent la production naturelle de collagène pour une fermeté progressive.

Tout est orienté vers la **prévention du vieillissement de la peau**.

### Services complémentaires affichés (À CONFIRMER avec Dominique)

Le site affiche aussi une liste générique de soins courants en médico-esthétique (skin boosters, hydratation, harmonisation du visage, etc.) en attendant de savoir precisément ce que Dominique offre en plus. Section clairement marquée « Liste indicative » dans le code (`fd-other-services` dans `index.html`). **À remplacer dès que l'information est confirmée.**

## Philosophie / positionnement (issu de l'enregistrement audio)

- Le vieillissement se prévient, il ne se subit pas.
- Certaines clientes commencent une approche **préventive dès la mi-vingtaine**.
- D'autres souhaitent **corriger un détail précis dès 18 ans** (âge légal minimal).
- **Âge moyen de la clientèle : la quarantaine.**

Ce positionnement est repris textuellement dans la section « Notre approche » du site (3 cartes : 18 ans / 25 ans / 40 ans).

## Formation de Dominique Filion

Le site indique qu'elle est **infirmière clinicienne**, formée par des formateurs reconnus en médecine esthétique pour l'injection de neuromodulateurs, d'agents de comblement et de biostimulants. **Aucun nom d'établissement ou de formateur spécifique n'a été fourni** — à ajouter si Dominique souhaite le mentionner (ça renforce la crédibilité).

## Photos utilisées (toutes à remplacer par les vraies)

Toutes les images sont des **photos libres de droits (Unsplash)**, choisies comme placeholders, stockées dans `images/` :

| Fichier | Usage sur le site | À remplacer par |
|---|---|---|
| `dominique-placeholder.jpg` | Photo de Dominique (section À propos) | Vraie photo de Dominique Filion |
| `hero-clinique.jpg` | Image de fond de la section d'accueil | Photo de la vraie clinique, si disponible |
| `avant-apres-1.jpg`, `-2.jpg`, `-3.jpg` | Section « Avant / Après » — curseur interactif | Vraies photos avant/après de clientes de FiliDerma, **avec leur consentement explicite** |
| `services-deco.jpg` | Réserve (non utilisée pour l'instant) | — |

**Important — pourquoi ce ne sont pas de vraies photos avant/après** : présenter les résultats d'une autre clinique comme s'il s'agissait de ceux de Dominique serait trompeur pour les clientes et poserait un problème de droits d'auteur / vie privée envers les vraies patientes photographiées. Chaque carte « avant/après » utilise donc **la même image des deux côtés**, avec un ruban « Exemple » bien visible — le curseur fonctionne déjà, il suffit de remplacer les fichiers images quand les vraies photos seront disponibles (garder les mêmes noms de fichiers, ou mettre à jour les chemins `src` dans `index.html`).

## Structure technique du site

- `index.html` — structure de toutes les sections
- `css/styles.css` — habillage visuel (palette crème / charbon / terracotta)
- `js/script.js` — menu mobile, animations au défilement, curseur avant/après
- `images/` — toutes les photos

Site statique autonome (HTML/CSS/JS), sans base de données ni back-end — les modifications de texte, photos ou couleurs se font directement dans ces fichiers. Julien s'occupe des modifications sur demande de Dominique.

## À faire / en attente

- [ ] Adresse exacte de la clinique
- [ ] Vraie photo de Dominique Filion
- [ ] Vraies photos avant/après (avec consentement des clientes)
- [ ] Confirmer la liste des services complémentaires
- [ ] Confirmer les détails de formation (établissement, formateurs) si Dominique veut les mentionner
- [ ] Vrais témoignages de clientes
- [ ] Décider d'un nom de domaine et d'un hébergement pour mettre le site en ligne
