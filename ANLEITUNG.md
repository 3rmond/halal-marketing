# Landingpage online stellen (GitHub Pages)

Kostenlos, ca. 5 Minuten. Du brauchst nur den Browser.

## 1. Änderungen übernehmen (Pull Request mergen)
1. Öffne https://github.com/3rmond/halal-marketing/pulls
2. Klick auf den Pull Request „Landingpage …“.
3. Unten auf **Merge pull request** und dann **Confirm merge** klicken.

## 2. GitHub Pages einschalten
1. Im Repo oben auf **Settings** (Zahnrad) klicken.
2. Links im Menü auf **Pages**.
3. Bei **Source**: „Deploy from a branch“ wählen.
4. Bei **Branch**: `main` und Ordner `/ (root)` wählen, dann **Save**.
5. 1–2 Minuten warten, Seite neu laden. Oben steht dann:
   „Your site is live at https://3rmond.github.io/halal-marketing/“

Hinweis: Bei einem privaten Repo geht GitHub Pages nur mit bezahltem Plan.
Dann unter Settings → General → ganz unten „Change visibility“ auf **Public** stellen.
Im Repo stehen keine geheimen Daten, nur die Webseite.

## 3. Platzhalter ersetzen
In diesen Dateien nach eckigen Klammern `[...]` suchen und ersetzen:
- `index.html`: `[BUSINESS-NAME]`, `[WHATSAPP-NUMMER]` (Format `49151...`, ohne + und Leerzeichen), `[E-MAIL]`
- `impressum.html`: deine echten Angaben (Pflicht in Deutschland, sobald du die Seite geschäftlich nutzt)
- `datenschutz.html`: Text aus einem kostenlosen Datenschutz-Generator

Bearbeiten direkt auf GitHub: Datei anklicken → Stift-Symbol (Edit) → ändern → **Commit changes**.
Die Seite aktualisiert sich nach 1–2 Minuten von selbst.

## 4. Später: eigene Domain (optional)
Domain kaufen (ca. 1–15 €/Jahr), dann Settings → Pages → **Custom domain** eintragen.
