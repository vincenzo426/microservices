# Agenda App 

## Descrizione
Applicazione a microservizi containerizzata per la gestione di contatti ed eventi.

## Architettura

Il sistema è composto dai seguenti componenti principali:

- **API Gateway**: Punto di ingresso centralizzato che gestisce e instrada le richieste ai servizi appropriati
- **Contact Service**: Gestisce le operazioni relative ai contatti
- **Event Service**: Gestisce le operazioni relative agli eventi
- **Database PostgreSQL**: Archivia i dati per entrambi i servizi
  
## Tecnologie Utilizzate

- **Backend**: Java/Quarkus
- **Database**: PostgreSQL 14
- **Container**: Docker
- **Orchestrazione**: Kubernetes (k3s)
- **Ingress**: Traefik

## Microservizi

- [API Gateway](https://github.com/vincenzo426/api-gateway)
- [Contact Service](https://github.com/vincenzo426/contact-service)
- [Event Service](https://github.com/vincenzo426/event-service)
