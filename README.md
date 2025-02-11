# db-freerider

## 📌 Projektbeschreibung
**db-freerider** ist ein Projekt, das mit **Docker** und **Docker Compose** arbeitet. Es enthält eine Datenbankkonfiguration, die in einer containerisierten Umgebung läuft.

## 📦 Inhalt des Repositories
- `.env.sh` - Shell-Skript für Umgebungsvariablen.
- `.gitignore` - Git-Ignore-Datei zum Ausschließen unerwünschter Dateien.
- `Dockerfile` - Docker-Konfigurationsdatei zum Erstellen eines Containers.
- `docker-compose.yaml` - Docker-Compose-Datei zur Verwaltung mehrerer Container.
- `db.mnt/` - Verzeichnis (vermutlich für persistente Datenbank-Speicherung).

## 🚀 Installation & Nutzung

### 🔹 Voraussetzungen
- **Docker** und **Docker Compose** müssen installiert sein.
  - [Docker installieren](https://docs.docker.com/get-docker/)
  - [Docker Compose installieren](https://docs.docker.com/compose/install/)

### 🔹 Repository klonen
```sh
git clone https://github.com/Seymakarakurt/db-freerider.git
cd db-freerider
```

### 🔹 Docker-Container starten
```sh
docker-compose up -d
```

### 🔹 Container stoppen
```sh
docker-compose down
```

## ⚙️ Entwicklung
Falls Änderungen im `Dockerfile` gemacht werden, sollte das Image neu gebaut werden:
```sh
docker-compose up --build
```

Entwickelt von Seyma Karakurt
