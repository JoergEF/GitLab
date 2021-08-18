# GitLab

Gitlab-Installation mit den offiziellen Docker-Images

### Voraussetzungen:
1. installierter Docker, Benutzer in der docker-Gruppe
2. installiertes docker-compose

### Benutzung
1. Anpassen der /etc/hosts:
    - in der Zeile 127.0.0.1 zusätzlich den Eintrag gitlab anhängen
2. Terminal öffnen
      ```bash
      cd
      git clone https://github.com/JoergEF/gitlab
      cd github
      docker-compose up -d
      ```
  
