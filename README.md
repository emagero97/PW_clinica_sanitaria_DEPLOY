# PW_clinica_sanitaria_DEPLOY
Comandi per startare l'app in self

# Si effettua la copia delle variabili di ambiente nel file -env
cp .env.example .env

# Eseguiamo il comando del docker compose per far partire la build
docker compose up --build
