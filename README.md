# Vlog Islanda

Diario video giornaliero. I file MP4 stanno su Google Drive; questo sito li mostra divisi per giorno e li riproduce con il player di Drive.

## Aggiungere un video

1. Carica l'MP4 nella cartella di Drive.
2. Condividilo con "Chiunque abbia il link – Visualizzatore".
3. Aggiungi una voce a `videos.json`:

```json
{
  "day": "2026-11-05",
  "title": "Titolo del video",
  "note": "Due righe su cosa ho fatto",
  "drive": "https://drive.google.com/file/d/ID_DEL_FILE/view",
  "vertical": true
}
```

- `day`: data nel formato AAAA-MM-GG
- `drive`: link di condivisione di Drive oppure solo l'ID del file
- `vertical`: `true` per i video girati in verticale (facoltativo)

## Pubblicazione

GitHub Pages: Settings → Pages → Source "Deploy from a branch" → branch `main`, cartella `/ (root)`.
