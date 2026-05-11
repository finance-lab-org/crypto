# Krypto-Assets — Interaktive Lernwerkzeuge

Sammlung interaktiver Lernwerkzeuge zum Themenfeld **Krypto-Assets** an der **TH Köln**.

---

## Enthaltene Tools

| Datei | Thema |
|---|---|
| [`rsa-lernwebsite.html`](rsa-lernwebsite.html) | RSA-Kryptographie zum Anfassen — Schlüsselerzeugung, Verschlüsseln/Entschlüsseln, Signieren/Verifizieren, Angreifer-Modus mit Live-Faktorisierung |

Einstiegspunkt: [`index.html`](index.html)

---

## Technik

Jedes Tool ist eine **eigenständige HTML-Datei** mit inline-CSS und inline-JavaScript — keine serverseitige Logik, keine lokalen Abhängigkeiten. Externe Ressourcen werden nur per CDN geladen:

- **Google Fonts** — Inter (Text) & JetBrains Mono (Zahlen)

Die gesamte RSA-Mathematik (modulares Potenzieren, erweiterter euklidischer Algorithmus, Probedivision) läuft im Browser über native `BigInt`. Kein Backend.

---

## Lizenz & Nutzung

Die Tools stehen Studierenden der TH Köln zur Vorbereitung und Nachbereitung der Lehrveranstaltung zur Verfügung. Eine darüberhinausgehende Nutzung nur in Absprache.

---

**Prof. Dr. Marc Mehlhorn** · TH Köln · Fakultät für Wirtschafts- und Rechtswissenschaften
