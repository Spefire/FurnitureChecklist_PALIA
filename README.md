# FurnitureChecklist_PALIA

Checklist non officielle des meubles collectés dans le jeu Palia.
Angular 21, service worker (sans installation PWA), pas de SSR.

## Commandes

| Commande | Description |
| --- | --- |
| `npm run start` | Serveur de développement sur `http://localhost:4200/` |
| `npm run build` | Build de production dans `dist/furniture-checklist-palia/browser` |
| `npm run lint` | ESLint (TypeScript et templates) |
| `npm run prettier` | Formatage du code |

## Environnement

Le build de production nécessite `src/environments/environment.prod.ts` (ignoré par Git), généré par `node generate-env-script.js`.
