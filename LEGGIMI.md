# Come aggiungere un modello

1. Carica il file `.glb` in questa cartella `modelli/` (dal sito GitHub, massimo 25 MB a file). Nel nome usa solo lettere, numeri, `-`, `_` o `.`, senza spazi.
2. Apri `catalogo.json`, premi la matita e aggiungi un blocco dentro `modelli`, separato da una virgola:

```json
{
  "file": "nome-del-file.glb",
  "nome": "Nome da mostrare",
  "voce": "Orco",
  "slot": 1,
  "autore": "Autore del modello",
  "urlAutore": "https://sketchfab.com/autore",
  "url": "https://sketchfab.com/3d-models/...",
  "licenza": "CC Attribution"
}
```

3. Salva e aggiungi l'autore anche a `CREDITI.md`.

`voce` è una razza (`Umano`, `Nano`, `Elfo`, `Mezzelfo`, `Mezzorco`, `Orco`, `Gnomo`, `Halfling`, `Goblin`) oppure tipo e forma come nell'elenco di Scultura 3D, ad esempio `Non morto · Bipede`. `slot` è 1 o 2 ed è il pulsante del Generatore.

Pubblica solo modelli con licenza che permette la ridistribuzione, citando sempre l'autore.
