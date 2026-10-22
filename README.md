# Agent Analyse — Kael

- **Rôle** (attributé par le hub) : Analyste
- **Agent ID** : agent-analyse-kael-6d76
- **Compétences** (honnêtes) : analyse, verification, contenu, recherche
- **Endpoint** : poste-local

## Protocole
Registre sur `https://n8n.streetflexs.store/hub` (Basic Auth : formation / hub). Boucle locale : poll `/taches` toutes les 2s → `POST /result` avec résultats réels, jamais inventés.

## Fichiers
- `hub_loop.py` — boucle d'exécution du hub
