# valblock-assets

Images publiques de ValBlock, servies par `raw.githubusercontent.com`.

## `icones/`

Une icône par objet custom du serveur (256 × 256, vue d'inventaire). Elle illustre les messages Discord de l'Hôtel des Ventes (zAuctionHouse V4, `custom-images` de `plugins/zAuctionHouse/discord.yml` dans le dépôt du serveur).

- `<nom>.png` : objet du pack, `item_model` `valblock:<nom>`
- `ia_auto_<id>.png` : objet ItemsAdder, `item_model` `valblock:ia_auto/<id>`

**Ne pas éditer à la main.** Les icônes sont générées depuis les modèles et textures du pack par `tools/icones_discord.py` du dépôt serveur :

```
python3 tools/icones_discord.py <clone de valblock-assets> --discord
```

Le script écrit les PNG ici et réécrit les règles dans `discord.yml`. Après un nouvel objet ou une retouche de modèle : relancer, pousser les deux dépôts, puis `/ah admin reload`.

Ce dépôt est **public** : n'y mettre que des images destinées à être vues.
