1. Git Bash für Windows:  https://git-scm.com/

2. SSH-Schlüssel erstellen:  ssh-keygen -C "deine_email@example.com"  Ersetze "deine_email@example.com" durch die E-Mail-Adresse, die mit deinem GitHub-Konto verknüpft ist.

3. SSH-Schlüssel zu deinem GitHub-Konto hinzufügen:
      -Melde dich bei deinem GitHub-Konto an.

      -Klicke auf dein Profilbild in der oberen rechten Ecke und wähle "Einstellungen" aus.

      -Klicke in der linken Seitenleiste auf "SSH and GPG keys" (SSH- und GPG-Schlüssel).

      -Klicke auf "New SSH key" oder "SSH-Schlüssel hinzufügen" und vergebe einen Titel (z. B. "Mein Git Bash-Schlüssel").

      -Öffne die öffentliche Schlüsseldatei (standardmäßig ~/.ssh/id_ed25519.pub) mit einem Texteditor.

      -Füge den kopierten Schlüssel in das Feld "Key" auf GitHub ein und klicke auf "SSH-Schlüssel hinzufügen".

4. Visual Studio Code konfigurieren, um Git Bash als Standardterminal zu verwenden:

      -Gib "Select Default Shell" ein und wähle "Git Bash" aus den Optionen aus. (https://www.youtube.com/watch?v=PzJCwfYfIzY&t=53s)

      -Verwende den Befehl git clone, gefolgt von der Repository-URL, um sie zu klonen. Zum Beispiel: $git clone git@github.com:TechstarterGmbH/aws-23-07.git
      
5. Erstellen oder aktualisieren File:

      -in Git directory einen File erstellen oder aktualisieren und speichern.

6.     Hinweis: Bevor du einen Commit durchführst, stelle sicher, dass du deinen Benutzernamen und deine E-Mail-Adresse in Git festgelegt hast, indem du die folgenden Befehle verwendest (du musst dies nur einmal tun):

       -git config --global user.name "Your Name"
       -git config --global user.email "your_email@example.com"

7. Änderungen mit Git Bash-Befehlen committen und pushen:

        Öffne ein neues Terminal in Visual Studio Code, indem du auf Terminal > Neues Terminal klickst (oder verwende das integrierte Terminal, wenn es bereits sichtbar ist).

          Gib die folgenden Befehle ein:
          git add .            # Änderungen für das Commit vorbereiten
          git status           # (Optional) Den Status der Änderungen anzeigen
          git commit -m     "Deine Commit-Nachricht"   # Änderungen committen und eine aussagekräftige Nachricht hinzufügen
          git push             # Änderungen zum GitHub-Repository pushen

Stelle sicher, dass du "Deine Commit-Nachricht" durch eine beschreibende Nachricht ersetzt, die die gemachten Änderungen erklärt.

Damit kannst du effektiv mit Git, GitHub und Visual Studio Code arbeiten, um deine Codeprojekte zu verwalten