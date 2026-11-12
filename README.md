# GKI-Notebooks

Jupyter-Notebooks zum Kurs *Grundlagen der Künstlichen Intelligenz (GKI)*.

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/HamburgerFH/GKI-notebooks?quickstart=1)

## Start im Browser (GitHub Codespaces)

1. Mit dem eigenen (kostenlosen) GitHub-Konto anmelden.
2. Diesen Link öffnen und **Create codespace** klicken:
   <https://codespaces.new/HamburgerFH/GKI-notebooks?quickstart=1>
3. Beim ersten Start installiert der Codespace Python und alle Pakete. Das
   dauert einige Minuten.

## Notebook ausführen

1. Links im Explorer den Ordner `notebooks/` öffnen.
2. Ein Notebook anklicken, z. B. `03_01_weinplots.ipynb`.
3. Oben **Run All** wählen. Falls nach einem Kernel gefragt wird:
   **Jupyter Kernel... -> gki-venv** auswählen.

Das MNIST-Notebook trainiert ein neuronales Netz auf der CPU und braucht
einige Minuten. Erzeugte Grafiken landen in `figs/`.

## Codespace beenden

Kostenlose GitHub-Konten haben ein monatliches Kontingent an Rechenzeit.
Nach der Arbeit den Codespace stoppen: unten links auf **Codespaces** klicken
-> **Stop Current Codespace**. Inaktive Codespaces stoppen nach 30 Minuten
automatisch.

Eigene Änderungen bleiben im Codespace erhalten, bis er gelöscht wird
(spätestens nach 30 Tagen Inaktivität). Wichtige Dateien per Rechtsklick ->
**Download...** sichern.

## Aktualisierungen

Die Notebooks werden automatisch aus dem Kurs-Repository
[GKI-course-website](https://github.com/HamburgerFH/GKI-course-website)
übernommen. Neue Versionen im eigenen Codespace holen: im Terminal
`git pull` ausführen. Selbst veränderte Notebooks vorher unter neuem Namen
speichern, sonst kann `git pull` mit einem Konflikt abbrechen.

Für Lehrende: `notebooks/`, `data/processed/` und `requirements.txt` nicht
hier bearbeiten, sondern im Website-Repository; die Synchronisation
überschreibt diese Pfade.
