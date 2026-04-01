# OcchiDB — Pixel Rainbow City

Scena in stile 8/16 bit: scorcio cittadino con arcobaleno animato che cambia colore, appare e scompare.

## Avvio rapido

Apri `index.html` in un browser.

## Come si procede (per imparare davvero)

1. **Osserva il risultato**: lascia girare la scena 30 secondi.
2. **Usa il pannello controlli**: cambia un parametro alla volta (pixel, tempi, velocità).
3. **Sperimenta preset**: capisci come cambia il mood visivo.
4. **Prova da console** con `window.setSceneParams({...})`.
5. **Seconda fase**: collega questi parametri a input esterni (form, API, websocket, sensori, ecc.).

## Esempio runtime

```js
window.setSceneParams({
  rainbowVisibleMs: 5000,
  rainbowHiddenMs: 500,
  rainbowHueSpeed: 0.09,
  skyTop: "#89b0ff",
  skyBottom: "#0f1a42",
  pixelSize: 6,
});
```
