# Risposte: Chiamate HTTP

## Tabella del Passo 6

| Pulsante | Metodo | URL | Stato |
|---|---|---|---|
| Carica un post (con 1) | GET | .../posts/1 | 200 |
| Carica un post (con 999) | GET | .../posts/999 | 404 |
| Carica tutti | GET | .../posts | 200 |
| Invia un post | POST | .../posts | 201 |