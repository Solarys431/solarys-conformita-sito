# Il marchio

Un foglio, due righe neutre e **una riga accesa**: il passaggio ritrovato. Da lì nasce
la spunta, che esce dal foglio. Dice in un gesto solo quello che il prodotto fa: la
conferma viene dal testo, non da un'opinione.

## Quale file usare

| File | Quando |
|---|---|
| `marchio.svg` | fondi chiari, da 48 px in su |
| `marchio-negativo.svg` | fondi scuri, da 48 px in su |
| `segno.svg` | fondi chiari, sotto i 48 px: sparisce il foglio, restano riga e spunta |
| `segno-negativo.svg` | fondi scuri, sotto i 48 px |

Sotto i 48 px il foglio diventa una macchia: per questo esiste il **segno**, che si
legge fino a 16 px. Non è un logo diverso, è lo stesso ridotto all'osso.

In `icone/` ci sono le versioni già pronte in PNG con fondo trasparente, dalle 16 alle
1024. Le misure 180 e 192 servono alle schermate iniziali dei telefoni.

## Colori

| | |
|---|---|
| Acceso, dall'alto in basso | `#fcb03c` → `#e25846` |
| Inchiostro (positivo) | `#14181f` |
| Inchiostro (negativo) | `#eae7e1` |
| Righe neutre | inchiostro al 28% |

Il gradiente è lo stesso del logotipo Solarys, che scende dal giallo al rosso: il
marchio nuovo e la scritta a blocchi appartengono alla stessa famiglia.

## L'icona dell'applicazione

`icona-app.svg` è il sorgente, `icona-app.icns` il file già pronto per macOS con
tutte e dieci le risoluzioni. Il riquadro segue la forma delle icone di sistema, con
il margine che serve perché nel Dock stia in riga con le altre; dentro, il marchio in
negativo sul fondo scuro dell'interfaccia.

Per rigenerare l'`.icns` dopo una modifica del sorgente servono le dieci misure in un
`Solarys.iconset` e poi `iconutil -c icns`.

## L'intestazione

`intestazione.html` compone marchio, logotipo e claim su fondo scuro; `intestazione.png`
è la versione già renderizzata a 1280 × 400. Per rigenerarla dopo una modifica basta
aprire il file HTML e catturarlo a quella misura.

## Regole

- Non ruotare il marchio, non alterare il gradiente, non aggiungere ombre esterne.
- Lasciare attorno uno spazio libero pari all'altezza della spunta.
- Su fondi accesi o fotografici usare la versione negativa dentro un riquadro scuro,
  mai il marchio nudo.
