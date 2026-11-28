# gsauteret.com — V5 modulaire

## Déployer sur GitHub Pages
1. Sauvegarder le dépôt actuel (branche ou commit de référence).
2. Ouvrir Settings → Pages pour vérifier la branche et le dossier réellement publiés (racine `/`, `/docs`, ou workflow Actions).
3. Décompresser l’archive. Copier **le contenu du dossier `site/`** dans le dossier publié, sans créer un sous-dossier `site` sur le site final. `index.html`, `style.css`, `script.js`, `interviews.html`, `talentbusterz.html` et `assets/` doivent rester au même niveau.
4. Conserver les fichiers existants CNAME, mentions légales, politique de confidentialité, vérifications de domaine, robots.txt, sitemap et éventuels réglages de déploiement. Ne pas les écraser.
5. Si le dépôt utilise un framework ou une compilation, ne pas écraser le code source : intégrer ces fichiers au dossier statique réellement publié après vérification.
6. Valider un commit « V5 modulaire – site, interviews et TalentBusterZ ». Attendre la fin du déploiement Pages. Vérifier l’accueil, les deux nouvelles pages, les menus, le simulateur et les liens de contact.

## Organisation
- `index.html` : accueil V5, six piliers, contenus approfondis, simulateur OETH, CTA.
- `style.css` : feuille de style commune, palette bleu et or et responsive.
- `script.js` : menu mobile, progression, simulateur OETH, ouverture des détails TBZ. Les fonctions propres à une rubrique sont conditionnelles.
- `interviews.html` : page de la série, agenda, démarche et emplacement des épisodes.
- `talentbusterz.html` : deux offres, conditions, sécurité, modèles et données.
- `assets/` : favicon et futurs médias.

La page d’accueil conserve toutes les informations de la V5 validée et contient deux liens supplémentaires vers les pages spécialisées. Ces pages reprennent volontairement les rubriques correspondantes pour faciliter les liens directs et les enrichissements futurs. En cas de modification d’une offre, mettre à jour les deux occurrences concernées.

## Ajouter une interview
Dans `interviews.html`, repérer le commentaire `Ajouter ici les cartes des épisodes validés`. Ajouter une carte contenant titre, entreprise, fonction de l’intervenant, date, synthèse et lien vers la vidéo publiée. N’ajouter que du contenu autorisé. Les médias volumineux peuvent rester hébergés ailleurs.

## Avant publication
Le statut TIH, l’éligibilité OETH et la disponibilité des solutions TBZ restent conditionnels comme dans la V5. Aucun service d’abonnement ni espace de connexion n’est implémenté. La page statique n’effectue pas de collecte de données de candidats. Les liens mailto ouvrent le logiciel de messagerie du visiteur. Le fichier juridique ci-joint est un aide-mémoire, pas une page à publier en l’état. Conserver les pages juridiques existantes et vérifier leurs liens dans le pied de page avant publication.
