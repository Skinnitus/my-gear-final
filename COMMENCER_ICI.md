# MY GEAR — Equipment Studio 2.0

Archive complète pour un NOUVEAU dépôt GitHub et un NOUVEAU site Cloudflare Pages. Ne pas remplacer la production.

## Fichiers à publier

Publier à la racine du dépôt tous les fichiers applicatifs de cette archive : index.html, app.js, gear.js, store.js, style.css, sw.js, manifest.webmanifest, _headers, inventaire-fourni.csv ET le dossier assets avec tous ses sous-dossiers, images et polices.

**assets est indispensable : ne pas l’exclure.** Conserver les chemins. Les dossiers DOCUMENTATION et CAPTURES n’ont pas besoin d’être publiés. Ils contiennent la notice, l’audit, le rapport détaillé, les résultats et les captures réelles.

Cloudflare Pages : aucun framework, aucune compilation ; répertoire de sortie à la racine du dépôt puisque index.html y est placé. Utiliser une nouvelle adresse de test.

## Données

L’application démarre vide. Elle n’accède pas aux données de l’ancienne adresse. Avant restauration, exporter le JSON complet depuis l’ancienne application et le conserver hors du téléphone. Le CSV fourni ne contient que quatre articles, sans photos, sacs ni listes.

## Vérifications restant à effectuer

Les tests logiques et les parcours locaux sont documentés ; installation et mode avion Samsung ne sont pas déclarés réussis. Sur la nouvelle adresse HTTPS Cloudflare :
1. Données & sauvegardes → Vérifier le cache : aucune ressource manquante.
2. Importer une sauvegarde de test ou le CSV fourni et vérifier les valeurs.
3. Installer depuis Chrome, fermer, passer en mode avion puis rouvrir depuis l’icône.
4. Vérifier images et données, modifier une note, fermer puis rouvrir.
5. Rétablir le réseau, exporter le JSON et conserver ce fichier.

La qualification finale de la PWA reste conditionnée à ces vérifications. L’accord de livraison n’est pas présenté comme un résultat de test. Ne pas supprimer l’ancienne application avant validation et sauvegarde externe.
