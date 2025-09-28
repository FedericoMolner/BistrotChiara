# BistrotChiara

Sistema Bistrot di Chiara - Progetto Corso BID
Studente: Federico Molner
 Cliente: Sig.ra Chiara Padelli - Bistrot vegetariano
 Obiettivo: Sistema per gestire menu e prenotazioni in 15 giorni
Come è organizzato il progetto

bistrot-chiara/

├── README.md (questo file)

├── docs/

│   ├── database-schema.md

│   └── come-usare-il-sistema.md

└── src/ (codice Java Spring Boot)

    ├── controller/
    
    ├── service/
    
    └── model/


## Timeline di Sviluppo

| Fase | Periodo | Attività |
|------|---------|----------|
| 🚀 | Giorni 1-2 | Kickoff e progettazione dettagliata |
| 📋 | Giorni 3-7 | Sviluppo modulo Menu |
| 📝 | Giorni 8-12 | Sviluppo modulo Prenotazioni |
| 🧪 | Giorni 13-15 | Test finali e go-live |
| 📊 | Giorno 16 | Presentazione finale |


BOARD - Le 10 Cose da Fare
## Status Board

| # | Task | Stato | Giorni | Descrizione |
|---|------|-------|--------|-------------|
| 1 | Setup Progetto | ⬜ | 1-2 | Preparare ambiente |
| 2 | Database Piatti | ⬜ | 3-4 | Tabelle menu |
| 3 | Gestione Menu | ⬜ | 5-7 | CRUD piatti |
| 4 | Menu Clienti | ⬜ | 7 | Pagina pubblica |
| 5 | Database Prenotazioni | ⬜ | 8-9 | Tabelle booking |
| 6 | Sistema Prenotazioni | ⬜ | 10-12 | Calendario e gestione |
| 7 | Prenotazioni Online | ⬜ | 12 | Form clienti |
| 8 | Dashboard Admin | ⬜ | 13 | Pannello controllo |
| 9 | Login e Sicurezza | ⬜ | 14 | Protezioni |
| 10 | Test e Deploy | ⬜ | 15 | Mettere online |

**Legenda:** ⬜ Da fare • 🟡 In corso • 🟢 Fatto • 🔴 Problema

## Dettagli Task

### 1. Setup Progetto (Giorni 1-2)
- [ ] Installare Java, MySQL, IDE
- [ ] Creare progetto Spring Boot
- [ ] Collegare database MySQL
- [ ] Pagina test "Hello World"
- [ ] Setup Git e primo commit

### 2. Database Piatti (Giorni 3-4)
- [ ] Tabella piatti (id, nome, prezzo, descrizione, disponibile)
- [ ] Tabella categorie (Antipasti, Primi, ecc.)
- [ ] Collegamento piatti → categorie
- [ ] Dati di prova (5-6 piatti)
- [ ] Test salvataggio/lettura

### 3. Gestione Menu (Giorni 5-7)
- [ ] Form "Aggiungi piatto"
- [ ] Lista piatti modificabile
- [ ] Bottone elimina piatto
- [ ] Toggle disponibile/non disponibile
- [ ] Gestione categorie

### 4. Menu Clienti (Giorno 7)
- [ ] Pagina /menu pubblica
- [ ] Menu per categorie
- [ ] Design responsive
- [ ] Solo piatti disponibili
- [ ] Prezzi visibili

### 5. Database Prenotazioni (Giorni 8-9)
- [ ] Tabella tavoli (id, numero, posti_max)
- [ ] Tabella prenotazioni (id, cliente, data, ora, persone, tavolo)
- [ ] Configurazione tavoli bistrot
- [ ] Test prenotazioni di prova

### 6. Sistema Prenotazioni (Giorni 10-12)
- [ ] Form "Nuova prenotazione"
- [ ] Controllo disponibilità tavoli
- [ ] Calendario mensile prenotazioni
- [ ] Modifica/cancella prenotazioni
- [ ] Lista prenotazioni giornaliere

### 7. Prenotazioni Online (Giorno 12)
- [ ] Form pubblico /prenota
- [ ] Controllo disponibilità real-time
- [ ] Conferma prenotazione
- [ ] Integrazione con pannello admin

### 8. Dashboard Admin (Giorno 13)
- [ ] Homepage navigazione
- [ ] Box "Prenotazioni oggi"
- [ ] Box "Piatti attivi"
- [ ] Collegamenti rapidi
- [ ] Design tablet-friendly

### 9. Login e Sicurezza (Giorno 14)
- [ ] Pagina login /admin/login
- [ ] Credenziali: admin/bistrot2025
- [ ] Protezione pagine admin
- [ ] Bottone logout
- [ ] Timeout sessione

### 10. Test e Deploy (Giorno 15)
- [ ] Test completo funzioni
- [ ] Test multi-device
- [ ] Correzione bug
- [ ] Deploy su server
- [ ] Training per Chiara

Tecnologie che uso
Backend: Java + Spring Boot (per imparare framework enterprise)
Database: MySQL (affidabile per ristoranti)
Frontend: HTML + CSS + JavaScript semplice (compatibile ovunque)
Deploy: Server Linux basic (economico per piccolo bistrot)
Cosa imparo durante il progetto
Spring Boot per backend robusto
Gestione database con JPA
JavaScript per calendario interattivo
CSS responsive per mobile
Deploy applicazione reale
File principali che creo
MenuController.java - gestisce richieste menu
PrenotazioneController.java - gestisce prenotazioni
menu-admin.html - pannello gestione piatti
calendario-prenotazioni.html - vista prenotazioni
menu-pubblico.html - menu per clienti
prenota.html - form prenotazione online
Note per ricordarmi
Fare backup database ogni giorno
Testare sempre su telefono, non solo computer
Tenere credenziali sicure (non metterle su Git!)
Chiedere feedback a Chiara dopo ogni settimana
Documentare quello che non funziona per imparare
Problemi che potrei avere
Calendario JavaScript: Potrebbe essere difficile, ma ci sono librarie pronte
Controllo disponibilità: Logica un po' complessa, devo ragionarci bene
Design responsive: Non sono bravo con CSS, ma Bootstrap mi aiuta
Deploy: Prima volta che metto online un'app, potrei aver bisogno di aiuto
Contatti progetto
Studente: Federico Molner - federico.molner@edu-its.it
 Cliente: Chiara Padelli - Bistrot vegetariano
 Repo GitHub: bistrot-chiara
 Deadline: 15 giorni lavorativi dal kickoff

Ultimo aggiornamento: [24/09/2025] - Stato: [completate X/10 attività]
