# 👮 Simulatore Quiz - Vice Ispettori PS 2026

Un simulatore web leggero e reattivo progettato per la preparazione al concorso per **Vice Ispettori della Polizia di Stato**. Il software permette di esercitarsi sulla banca dati ufficiale (5000 quesiti) del 2025 direttamente dal browser, sia su PC che su dispositivi mobili.

## 🚀 Funzionalità Principali

- **Doppia Modalità di Studio**:
  - **Esercitazione**: Correzione immediata dopo ogni risposta per un apprendimento rapido.
  - **Simulazione Esame**: 100 quesiti misti (20 Costituzionale, 40 Penale, 40 Procedura Penale) con timer di 90 minuti.
- **Sistema di Punteggio Reale**: 
  - `+0,30` per ogni risposta corretta.
  - `-0,10` per ogni risposta errata.
  - `0` per le risposte omesse.
- **Ottimizzazione Mobile**: Interfaccia adattiva con pulsanti larghi per un uso agevole da smartphone.
- **Caricamento Automatico**: Il software legge automaticamente il file `banca_dati_quesiti.json` presente nel repository.


## 📱 Uso su Smartphone

Per un'esperienza simile a un'app nativa:
1. Apri il link del simulatore sul browser dello smartphone.
2. Seleziona **"Aggiungi alla schermata Home"** dal menu del browser (Safari su iOS o Chrome su Android).
3. L'icona apparirà sul tuo telefono per un accesso rapido.

## 📝 Note Tecniche

Il simulatore mescola casualmente l'ordine delle domande e la posizione delle risposte ad ogni sessione. Poiché nella banca dati originale la risposta corretta è sempre la "A", il software provvede a rimescolarle dinamicamente per garantire l'efficacia dell'allenamento.

---
*Progetto sviluppato per scopi didattici e di preparazione concorsuale.*
