# 👮‍♂️ Simulatore Quiz Vice Ispettori PdS 2025

Questo progetto è un simulatore web leggero e reattivo progettato per aiutare i candidati a prepararsi per il concorso **Vice Ispettori della Polizia di Stato** utilizzando la banca dati ufficiale 2025.

## 🚀 Caratteristiche Principali

* **Banca Dati Integrata**: Accesso immediato a oltre 5.000 quesiti ufficiali suddivisi per materia.
* **Modalità Simulazione Esame**: 100 domande miste (20 Costituzionale, 40 Penale, 40 Procedura Penale) con timer di 90 minuti, riflettendo le reali condizioni d'esame.
* **Modalità Esercitazione**: Filtra i quiz per singola materia e scegli il numero di domande per sessioni di studio mirate.
* **Sistema "Da Ripetere"**: Salva automaticamente i quesiti errati in una lista di ripasso dedicata tramite `localStorage`.
* **Calcolo Punteggio Reale**: Algoritmo di punteggio concorsuale (+0.30 per le corrette, -0.10 per le errate).
* **Interfaccia Adattiva**: Supporto completo alla modalità Chiara e Scura per non affaticare la vista durante lo studio prolungato.

## 🛠️ Architettura Tecnica

Il progetto è stato ottimizzato per garantire velocità e stabilità, risolvendo i problemi di caricamento di grandi moli di dati nel browser:
* **Separazione Dati/Logica**: La banca dati risiede in un file esterno `database.js` per una gestione efficiente della memoria.
* **Zero Dipendenze**: Sviluppato in puro HTML5, CSS3 e JavaScript (Vanilla JS), non richiede installazione o server complessi.
* **Client-Side**: Tutti i dati rimangono nel browser dell'utente, garantendo privacy e velocità istantanea.

## 📖 Come Utilizzarlo

1.  Clona o scarica il repository.
2.  Assicurati che i file `index.html` e `database.js` siano nella stessa cartella.
3.  Apri `index.html` con qualsiasi browser moderno (Chrome, Edge, Safari, Firefox).

## 📝 Note sulla Configurazione
Per caricare correttamente i quesiti, il file `database.js` deve contenere la variabile `bancaDatiUfficiale` formattata come array di oggetti JSON.

---
*Disclaimer: Questo strumento non è un'applicazione ufficiale del Ministero dell'Interno ma un supporto didattico creato per facilitare lo studio.*
