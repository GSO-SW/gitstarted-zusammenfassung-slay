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