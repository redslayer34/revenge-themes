# revenge-themes

Thèmes pour [Revenge](https://github.com/revenge-mod/revenge-bundle) (Discord mobile), au format Vendetta « spec 2 », le seul que Revenge lit entièrement (côté JS et côté natif).

## Catppuccin Mocha – Mauve

Basé sur [catppuccin/vendetta](https://github.com/catppuccin/vendetta) (licence MIT, voir `LICENSE`), mis à jour pour les couleurs du Discord mobile actuel avec le modèle de la [PR #59](https://github.com/catppuccin/vendetta/pull/59) (boutons, profil, textes, barre d'onglets), plus quelques corrections :

- coquilles de la PR corrigées (`BG_MOD_FAINT`, `MOBILE_CHANNEL_ITEM_BACKGROUND_SELECTED`)
- `BACKGROUND_MESSAGE_HOVER` et `BG_MOD_SUBTLE` ramenés à des fonds sombres
- ajout de `TEXT_BRAND`, `BACKGROUND_BRAND`, `CARD_BACKGROUND_DEFAULT`, `INTERACTIVE_ICON_DEFAULT`, `BORDER_SUBTLE`
- transposition de la nouvelle palette de Discord (`NEUTRAL_*`, `BLURPLE_*`, `BLUE_NEW_*`, `GREEN_NEW_*`, `RED_NEW_*`, `YELLOW_NEW_*`, `ORANGE_NEW_*`, `TEAL_NEW_*`, `PINK_*`, `OPACITY_*`) vers Catppuccin Mocha, d'après la table de couleurs du client Discord du 11/10/2026 : chaque teinte garde ses variantes claires et foncées
- `WHITE` repasse en couleur de texte (le thème d'origine le mettait en fond, ce qui masquait les icônes d'en-tête)
- texte et icônes des boutons pleins (primaire, critique, connecté) en foncé sur fond coloré

Dans Revenge : Paramètres → Thèmes → « + », puis colle :

```
https://raw.githubusercontent.com/redslayer34/revenge-themes/main/themes/catppuccin-mocha-mauve.json
```
