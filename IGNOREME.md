# Hinweis: Nur dann folgen, wenn die Arbeit mit BlueJ nicht verfügbar ist, um direkt im GitHub Web-Editor zu arbeiten. Ansonsten bitte README folgen.

> Willkommen zu Ihrem ersten Github-Projekt. Bitte folgen Sie den aufgelisteten Schritten mit dem Ziel, am Ende einen Kartenmanager zu erstellen, der unterschiedliche Sortierverfahren mit Listen zur Auswahl bietet.
### Schritt 0: GitHub-Zugangsdaten vorbereiten
- Notieren Sie die URL dieser Internetseite. Dies ist die Adresse zu Ihrem Repository.
- Notieren Sie Ihr GitHub-Pseudonym auf dem Arbeitsblatt.

### Schritt 1: Code im GitHub Web-Editor öffnen
- Navigieren Sie in Ihrem Repository zu `Kartenmanager_SuS.java`
- Klicken Sie auf das **Stift-Symbol** (`Edit in place`), um den Web-Editor zu öffnen

### Schritt 2: Code aktualisieren und ins Repository übertragen
- Der vorhandene Code ist veraltet. Ersetzen Sie ihn komplett durch Ihren eigenen Code aus dem letzten Projekt mit Listensortierverfahren.
- Sie können Ihren Code aus einer lokalen Datei kopieren oder direkt im Editor schreiben.
- Bestätigen Sie die Änderung mit `Commit changes...` und geben Sie eine aussagekräftige Commit-Nachricht ein (z.B. *"Eigenen Code implementiert"*).
- Wählen Sie `Commit directly to the main branch` und klicken Sie auf `Commit changes`.

### Schritt 3: Auf Code aus älteren Versionen zugreifen
- Es gibt ein Problem: Die ursprüngliche Version enthält die Bubble-Sort-Methode, die Sie auch für den Endprototyp benötigen. Ihre Version hat sie aber wahrscheinlich nicht.
- Klicken Sie auf `History` (rechts oben bei der Dateiansicht).
- Öffnen Sie die Version mit "*initial commit*".

### Schritt 4: Einen Branch für die ursprüngliche Version erstellen
- Wenn Sie den ursprünglichen Code mit der Bubble-Sort-Methode sehen, klicken Sie auf `Edit file` (Stift-Symbol).
- Klicken Sie auf `Commit changes...` und wählen Sie unten die Option `Create a new branch for this commit...`.
- Nennen Sie diesen Branch "**bubble**" und klicken Sie auf `Propose changes`.
- Klicken Sie auf `Create pull request`, aber schließen Sie diesen noch nicht ab.

### Schritt 5: Bubble-Sort in Ihren Code integrieren
- Gehen Sie zurück zum `main`-Branch (über das Branch-Auswahlmenü oben links).
- Öffnen Sie erneut `Kartenmanager_SuS.java` und klicken Sie auf das Stift-Symbol.
- Wechseln Sie in einem neuen Tab zum `bubble`-Branch und kopieren Sie die Bubble-Sort-Methode.
- Kehren Sie zum Editor im `main`-Branch zurück und fügen Sie die Bubble-Sort-Methode an der passenden Stelle ein.
- Bestätigen Sie mit `Commit changes...` -> *"Bubble-Sort aus ursprünglicher Version integriert"* -> `Commit changes`.

### Schritt 6: Git-Begriffe definieren
- Wenn Sie dies noch nicht getan haben, leiten Sie passende Definitionen für **Git-Repository**, **Push-** bzw. **Pull-Anfragen** aus Ihrer aktuellen Arbeitserfahrung ab.
- Füllen Sie das ausgeteilte Arbeitsblatt aus.
- Wenn Sie damit fertig sind und die Arbeitsphase noch nicht abgelaufen ist, fahren Sie mit Schritt 7 fort. Andernfalls kehren Sie zu Ihren analogen Arbeitsplätzen zurück.

### Schritt 7: Einen Branch für Ihre Sortiermethode anlegen
- Gehen Sie zu Ihrem Repository zurück und öffnen Sie `Kartenmanager_SuS.java` im Web-Editor.
- Bearbeiten Sie die Datei so, dass nur Ihre eigentliche Sortiermethode (*Insert-*, *Selection-* oder *Mergesort*) dort verbleibt.
- Gehen Sie zu `Commit changes...` und wählen Sie `Create a new branch for this commit...`.
- Nennen Sie diesen Branch "**sort**" und klicken Sie auf `Propose changes`.

### Schritt 8: Andere Repositories besuchen
- Sie müssen nun andere Sortiermethoden von Ihren Mitschülern sammeln, damit Ihr Kartenmanager-Prototyp jeweils ein Insertsort, ein Selectsort und ein Mergesort-Verfahren zusätzlich zum Bubblesort enthält.
- Klicken Sie dafür im Browser auf `Grundkurs-Informatik`, das rechts oben neben dem Namen Ihres Repositories stehen sollte.
- Besuchen Sie die Repositories mit den Sortierverfahren, die Ihnen noch fehlen:
  - _Emil, Silas, Simon_: **Merge-Sort**
  - _Zoe, Justus, Nico, Mats, Ago, Filip_: **Select-Sort**
  - _Dorian, Annabelle, Evan, Christian, Mohamad, Jannes_: **Insert-Sort**
- Nachdem Sie ein anderes Repository geöffnet haben, wechseln Sie zum Branch `sort`, indem Sie auf `main` klicken und aus der Liste `sort` auswählen.
- Kopieren Sie die benötigte Methode aus `Kartenmanager_SuS.java`.
- Kehren Sie zu Ihrem Repository zurück, öffnen Sie `Kartenmanager_SuS.java` im Web-Editor und fügen Sie die kopierte Methode ein.
- Bestätigen Sie mit `Commit changes...` -> *"[Methodenname] von [Mitschüler] hinzugefügt"* -> `Commit changes`.

### Schritt 9: Eine Release im Repository erstellen
- Nachdem Sie alle benötigten Sortiermethoden in Ihrem Code zusammengeführt haben, ist es Zeit, eine Version zu veröffentlichen.
- Gehen Sie zu Ihrem Repository und klicken Sie auf den Tab `Releases` auf der rechten Seite.
- Klicken Sie auf `Create a new release`.
- Geben Sie einen Titel (z.B. "Kartenmanager v1.0"), einen Tag (z.B. "v1.0") und eine kurze Beschreibung ein.
- Klicken Sie auf `Publish release`, um Ihren Kartenmanager offiziell zu veröffentlichen.

---

**Hinweis für die nächste Stunde:** In der kommenden Stunde werden wir den Code aus GitHub in BlueJ importieren und die GUI-Elemente zum Auswählen der verschiedenen Sortiermethoden implementieren.