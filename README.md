# leonkabel-apps-legal

Rechtstexte (Datenschutzerklärung, Nutzungsbedingungen, Impressum) für die Apps von Leon Kabel als statische HTML-Seiten, ohne Build.

| Seite | Datei |
|---|---|
| Übersicht | `index.html` |
| Impressum (für alle Apps) | `impressum.html` |
| zitter nicht. | `zitter-nicht/datenschutz.html` |
| Gravo | `gravo/datenschutz.html`, `gravo/nutzungsbedingungen.html` |

## Noch zu erledigen (Gravo)
- GitHub Pages aktivieren (Settings, Pages, Branch `master`, Ordner `/`) und die Seiten prüfen.
- URLs in der App eintragen (`PRIVACY_POLICY_URL`, `TERMS_URL` in `env/*.json` im Repo `gravo`).
- Auftragsverarbeitungsvertrag (AVV/DPA) mit Supabase abschließen; Region ist West EU (Irland).
- Mindestalter (derzeit 16) bestätigen; Texte rechtlich prüfen lassen.

Die ausführliche Checkliste steht im Repo `gravo` unter `docs/MANUAL_CHECKS.md`, Abschnitt 11.
