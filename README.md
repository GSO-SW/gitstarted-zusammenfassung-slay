# 🧠 Git & GitHub – Zusammenfassung und Nachschlagewerk

Diese Datei soll dir als Nachschlagewerk und Lernhilfe für die Arbeit mit Git und GitHub dienen. Sie enthält die wichtigsten Begriffe, Befehle und Arbeitsweisen für den Programmieralltag und die Zusammenarbeit im Team.🔧 Git – Lokal arbeiten



---

 ## 🔑 Wichtige Begriffe

| Begriff        | Erklärung |
|----------------|-----------|
| **Repository (Repo)** | Projektordner mit Git-Verwaltung. Lokal oder online (z. B. auf GitHub). |
| **Clone** | Eine Kopie eines Remote-Repos auf deinen Rechner laden. |
| **Commit** | Eine Version deiner Änderungen lokal speichern. |
| **Push** | Änderungen vom lokalen Repo ins Remote-Repo hochladen. |
| **Pull** | Änderungen vom Remote-Repo in dein lokales Repo holen. |
| **Branch** | Ein paralleler Arbeitszweig, um unabhängig zu arbeiten. |
| **Merge** | Zwei Branches zusammenführen. |
| **Merge-Konflikt** | Wenn zwei Branches dieselbe Stelle geändert haben – muss manuell gelöst werden. |
| **Staging Area** | Zwischenstation, bevor du Änderungen committest. |

---

## 🧰 Wichtige Git-Befehle (lokal)

| Befehl | Beschreibung |
|--------|--------------|
| `git init` | Neues Git-Repository im aktuellen Ordner erstellen |
| `git status` | Zeigt an, welche Dateien geändert wurden |
| `git add datei.md` | Datei zur Staging-Area hinzufügen |
| `git add .` | Alle Änderungen hinzufügen |
| `git commit -m "Nachricht"` | Änderungen dauerhaft speichern |
| `git log` | Verlauf der Commits anzeigen |
| `git diff` | Zeigt die Unterschiede der Änderungen |
| `git checkout branch-name` | In einen anderen Branch wechseln |
| `git branch` | Lokale Branches anzeigen |
| `git branch neuer-branch` | Neuen Branch erstellen |
| `git merge anderer-branch` | Branch in aktuellen Branch einfügen |
| `git merge --abort` | Merge abbrechen (bei Konflikten) |

---

## 🌍 Arbeit mit Remote-Repositories (GitHub)

| Befehl | Beschreibung |
|--------|--------------|
| `git clone <url>` | Repository von GitHub klonen |
| `git remote -v` | Zeigt verbundene Remotes (z. B. origin) |
| `git push` | Änderungen hochladen |
| `git pull` | Änderungen vom Server holen |
| `git push --set-upstream origin <branch>` | Neuen Branch zu GitHub pushen |
| `git fetch` | Holt alle Änderungen vom Remote, ohne sie einzufügen |

---

## :handshake: Zusammenarbeit im Team

- Arbeitet **nicht im Browser**, sondern lokal.
- Nutzt **eigene Branches** für Änderungen.
- Führt **häufige Commits** durch.
- Nutzt regelmäßig `git pull`, um auf dem neuesten Stand zu bleiben.
- Wenn ihr mit GitHub arbeitet:
  - Forkt ggf. das Repo (wenn nötig)
  - Erstellt einen Pull Request, wenn ihr fertig seid

---

## 📝 Markdown – kurz erklärt

Markdown ist eine einfache Auszeichnungssprache für Textformatierung. Wichtig für die `README.md`.

### Beispiele:

# Überschriften

# Überschrift 1
## Überschrift 2
### Überschrift 3

---

# Textformatierung

**Fett**: `**fett**`  
*Kursiv*: `*kursiv*`  
***Fett und kursiv***: `***fett und kursiv***`  
~~Durchgestrichen~~: `~~durchgestrichen~~`

---

# Listen

- Ungeordnete Liste (Aufzählung)  
  - Unterpunkt  
  - Noch ein Unterpunkt

1. Nummerierte Liste  
2. Punkt 2  
3. Punkt 3

---

# Links und Bilder

[Mehr Infos zu Markdown](https://oliverbrux.de/blog/markdown-was-ist-das-eigentlich)  

![Alternativtext](https://via.placeholder.com/150)  <!-- Beispielbild -->

---

# Code

Inline-Code: `` `Code` ``  

Codeblock (mit Syntax-Highlighting):

```bash
echo "Hallo Welt"
