# Gestionnaire de Ventes

Version prête à publier sur GitHub Pages. Le tableau de bord fonctionne 100% en front (localStorage) et utilise Tailwind CDN.

## Fichiers
- `index.html` : application complète.

## Publication rapide sur GitHub Pages
1) Crée un repo public `sales-manager` sur GitHub et coche "Add a README" (ou pousse celui-ci).
2) Dans ce dossier, exécute :
```bash
git init
git add .
git commit -m "Add sales manager dashboard"
git branch -M main
git remote add origin git@github.com:<ton-username>/sales-manager.git
git push -u origin main
```
3) Dans GitHub > Settings > Pages : Source = `main` / `/ (root)`, sauvegarde.
4) Attends 1-2 min, ton site sera sur `https://<ton-username>.github.io/sales-manager/`.

## Notes
- Données stockées en localStorage (par navigateur/appareil).
- Fonctionne hors ligne après le premier chargement.
- Si tu veux une URL plus jolie, garde `index.html` à la racine (déjà fait).
