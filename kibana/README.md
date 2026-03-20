# Kibana dashboard

Importe le fichier [`elk-minimal-dashboard.ndjson`](./elk-minimal-dashboard.ndjson) dans Kibana:

1. Ouvre `Stack Management > Saved Objects`.
2. Clique sur `Import`.
3. Sélectionne `kibana/elk-minimal-dashboard.ndjson`.
4. Ouvre ensuite le dashboard `ELK Demo - Minimal Dashboard`.

Le pack contient:

- un data view `elk-demo-*`
- un tableau de logs récents
- un compteur de volume total
- une répartition par service
- une répartition par niveau de log
- une répartition par type d'événement

Un second pack orienté incidents est aussi disponible:

- [`elk-incidents-dashboard.ndjson`](./elk-incidents-dashboard.ndjson)

Il contient:

- un flux de logs filtré sur les incidents
- un compteur des événements critiques
- un compteur des signaux de crash serveur
- un compteur des timeouts et pannes de connectivité côté client
- une répartition des incidents par service
- une répartition des incidents par type
- une répartition des incidents par niveau de sévérité
