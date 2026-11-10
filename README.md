# Stimmgerät mit Metronom

Web-App zum Stimmen von Instrumenten, läuft im Browser auf Handy, Tablet und Computer.

- Kammerton per Referenzton übernehmen (z. B. ein Ton vom Klavier) oder von Hand einstellen
- Nadel von −50 bis +50 Cent, bleibt ohne Ton beim letzten Ergebnis stehen
- Hintergrund: grün = innerhalb der Toleranz, rot = daneben, grau = kein Ton
- Metronom 30–240 BPM ohne Betonung, mit Tempo-Tippen

Das Mikrofon funktioniert nur über `https://` oder `localhost`. Lokal starten:

```
python3 -m http.server 8000
```
