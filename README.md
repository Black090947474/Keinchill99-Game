# Flachwitz-Jury für keinchill99

Live: https://keinchill99.netlify.app

- `index.html` – das komplette Spiel
- `netlify/functions/rate.mjs` – KI-Bewertung über die NVIDIA-API
- `netlify.toml` – Netlify-Einstellungen

## Einrichtung auf Netlify
1. Repository mit der Netlify-Seite verbinden (Build command leer, Publish directory `.`).
2. Unter *Environment variables* `NVIDIA_API_KEY` eintragen (Schlüssel von build.nvidia.com).
   Optional: `NVIDIA_MODEL` (Standard: `meta/llama-3.3-70b-instruct`).
3. Neu deployen und in den Spiel-Einstellungen „🔧 KI testen“ drücken.

**Den API-Schlüssel niemals in eine Datei dieses Repositorys schreiben – es ist öffentlich.**
