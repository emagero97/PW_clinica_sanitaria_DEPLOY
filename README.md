# Obiettivo del progetto
## Progetto realizzato per una tesi in Informatica con l'obiettivo di digitalizzare la gestione di una clinica sanitaria privata.

# Deploy - Portale Clinica Sanitaria Privata

Repository dedicata al **deploy dell'applicazione completa** (frontend + backend + database) tramite **Docker Compose**.

---

## Descrizione

Questa repository permette di avviare l'intero sistema della clinica sanitaria privata in modo semplice e automatico.

Il sistema include:
- Backend (FastAPI)
- Frontend (Angular)
- Database
- Server Nginx (per il frontend)

---

## Descrizione Docker Compose

- Download e build dei due applicativi Front-End e Back-End
- Creazione container con DB PostreSQL
- Eventuale extra con PgAdmin per accesso diretto alla gestione totale del Database

---

## Avvio del progetto

### Si effettua prima la copia delle variabili di ambiente nel file -env
```bash
cp .env.example .env
```

### Per avviare l'intera applicazione:
```bash
docker-compose up --build
```

### Per fermare  l'intera applicazione:
```bash
docker-compose down 
```

### Struttura Generale Progetto
- ScreenApp → cartella con gli screen dell'applicazione per i vari ruoli e generali
- docker-compose.yml → definisce i servizi (frontend, backend, database)
- .env.example → esempio di configurazione variabili d'ambiente
- UML_PW.jpg → diagramma UML
- USE_PW.jpg → diagramma dei casi d'uso
- FE_PW.jpg → struttura frontend
- swagger/2.png → screen swagger API test

### Author
©2026 Emanuele Geronzi 
