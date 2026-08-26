# Klima-Kompass

**Sehen. Verstehen. Gestalten.**

Der Klima-Kompass ist eine vollständig im Browser laufende, datensparsame HTML-App für Lehrkräfte. Sie unterstützt dabei, Situationen einzuschätzen, Muster im Klassenklima zu beobachten, aggregierte Entwicklungen zu verfolgen und das eigene Handeln zu reflektieren.

Die App benötigt keinen eigenen Server, keine Datenbank, keine Anmeldung und keine externen Bibliotheken.

## Inhalt dieses Pakets

| Datei | Zweck |
| --- | --- |
| `index.html` | Smartphone-Startseite mit drei Radar-Button-Varianten |
| `klima-kompass.html` | Vollständige Klima-Kompass-App |
| `.nojekyll` | Sorgt dafür, dass GitHub Pages die Dateien unverändert ausliefert |
| `README.md` | Diese Anleitung |

Beide HTML-Dateien enthalten ihr CSS und JavaScript vollständig eingebettet.

## Veröffentlichung mit GitHub Pages

### 1. Repository anlegen

1. Bei GitHub anmelden.
2. Über **New repository** ein neues Repository anlegen, beispielsweise `klima-kompass`.
3. Für GitHub Pages mit einem kostenlosen persönlichen Konto **Public** auswählen.
4. Keine zusätzliche README, `.gitignore` oder Lizenz erzeugen lassen – diese Dateien werden aus diesem Paket hochgeladen.

### 2. Dateien hochladen

1. Im neuen Repository **Add file → Upload files** wählen.
2. Den **Inhalt** dieses Ordners hochladen, sodass `index.html` direkt auf der obersten Ebene des Repositorys liegt.
3. Die Änderung mit **Commit changes** bestätigen.

Die Struktur muss anschließend so aussehen:

```text
klima-kompass/
├── .nojekyll
├── README.md
├── index.html
└── klima-kompass.html
```

### 3. GitHub Pages einschalten

1. Im Repository **Settings → Pages** öffnen.
2. Unter **Build and deployment** als Quelle **Deploy from a branch** auswählen.
3. Branch **main** und Ordner **/(root)** auswählen.
4. Mit **Save** bestätigen.

Nach der Veröffentlichung lautet die Adresse normalerweise:

```text
https://DEIN-BENUTZERNAME.github.io/klima-kompass/
```

Die offizielle Anleitung steht unter: <https://docs.github.com/en/pages/getting-started-with-github-pages>

## Auf dem Smartphone verwenden

1. Die GitHub-Pages-Adresse auf dem Smartphone öffnen.
2. Eine der drei Radar-Varianten antippen.
3. Optional einen Startbildschirm-Link anlegen:
   - **iPhone/iPad:** Safari → Teilen → **Zum Home-Bildschirm** → **Als Web-App öffnen**
   - **Android/Chrome:** Menü → **Zum Startbildschirm hinzufügen** → **Verknüpfung erstellen**

## Datenschutz und Speicherung

- Die App enthält keine Analyse-, Werbe- oder Trackingdienste.
- Es gibt keine App-eigene Cloud, kein Benutzerkonto und keine Übertragung von Klassenwerten an GitHub.
- GitHub Pages liefert lediglich die statischen Dateien aus. Die Seite und ihr Quelltext sind bei einem öffentlichen Repository öffentlich erreichbar.
- Klassenprofile dürfen nur anonyme Kürzel und Fächer beziehungsweise Kontexte enthalten.
- Im Modus **Flüchtig** bleibt nichts dauerhaft gespeichert.
- Im Modus **Klassenentwicklung** werden ausschließlich anonyme Profile und aggregierte Werte im lokalen Browserspeicher des jeweiligen Geräts abgelegt.
- Im Modus **Temporäre Diagnose** bleiben die Marker A–L nur im Arbeitsspeicher. Beim Beenden oder Neuladen werden sie gelöscht; speicherbar sind nur zusammengefasste Ergebnisse.
- Lokale App-Daten werden nicht zwischen Geräten synchronisiert. Das Löschen der Website-Daten im Browser entfernt auch die gespeicherten Verläufe.

Bitte niemals Namen, Initialen oder andere personenbezogene Angaben von Schüler*innen in Klassenkürzel oder Kontextfelder eintragen.

## Pädagogischer Hinweis

Der Klima-Kompass ist ein Wahrnehmungs- und Entscheidungsinstrument, keine diagnostische Software. Er ersetzt weder schulische Schutzkonzepte noch professionelle Fallberatung. Bei Machtasymmetrie und Wiederholung weist die App ausdrücklich darauf hin, keine automatische Konfliktmediation einzusetzen.

## Lokale Nutzung ohne GitHub

`index.html` und `klima-kompass.html` können auch gemeinsam in einem Ordner liegen und lokal geöffnet werden. Dauerhafte Speicherung bei direkt geöffneten `file:`-Dateien kann sich jedoch je nach Browser unterschiedlich verhalten. Für die Modi mit lokalem Verlauf ist eine feste HTTPS-Adresse zuverlässiger.

## Lizenz

Diesem Paket ist bewusst noch keine Lizenz beigefügt. Vor einer öffentlichen Weitergabe sollte entschieden werden, ob und unter welchen Bedingungen andere Personen die App verändern oder weiterverbreiten dürfen.

