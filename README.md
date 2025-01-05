# PersistenceIsFutile: CTF - Programmazione Sicura

## Descrizione
Questo repository documenta la risoluzione di una sfida CTF (*Capture The Flag*) chiamata **PersistenceIsFutile**, sviluppata come progetto per l'esame di Programmazione Sicura. La sfida consiste nel ripristinare la sicurezza di un server compromesso identificando e rimuovendo otto backdoor malevole.

### Scopo del Progetto
- Analizzare un server compromesso per identificare backdoor e processi sospetti.
- Rimuovere le minacce e ripristinare la funzionalità del server.
- Implementare misure di mitigazione per prevenire futuri attacchi.

## Struttura del Progetto
Il progetto è organizzato nelle seguenti fasi:
1. **Analisi del Problema**
   - Descrizione della CTF e obiettivi principali.
   - Identificazione delle backdoor.
2. **Metodologia**
   - Uso di comandi Linux (es. `netstat`, `ps auxf`, `crontab -l`) per individuare attività sospette.
   - Strumenti come `vim`, `grep` e `ls` per analisi approfondite.
   - Utilizzo di ambienti e piattaforme come **Kali Linux** e **Hack The Box**.
3. **Workflow**
   - Implementazione delle tecniche per eliminare le minacce:
     - Analisi delle connessioni di rete.
     - Revisione dei processi attivi e dei file di configurazione.
     - Identificazione di cron job e permessi SetUID sospetti.
   - Ripristino dei file di configurazione compromessi.
4. **Considerazioni Finali**
   - Raccomandazioni per migliorare la sicurezza del sistema:
     - Configurazioni di rete e SSH sicure.
     - Limitazione dei privilegi.
     - Backup regolari.

## Strumenti Utilizzati
- **Linux Tools:** `netstat`, `ps`, `crontab`, `grep`, `vim`, `ls`
- **Ambienti:** **Kali Linux**, **Hack The Box**
- **Protocollo SSH:** Accesso sicuro per analisi e ripristino.

## Risultati
La sfida è stata completata con successo:
- Identificazione e rimozione di otto backdoor.
- Ripristino della configurazione del sistema.
- Miglioramento delle difese di sicurezza.

## Conclusioni
Sono state implementate misure per prevenire attacchi futuri:
- Disabilitazione del login root via SSH.
- Monitoraggio dei processi e delle connessioni di rete.
- Configurazioni sicure e backup regolari.

## Autori
- **Mattia d’Argenio**
- **Alessandro Aquino**
- **Alberto Montefusco**

Se hai suggerimenti o vuoi saperne di più, non esitare a contattarci.

---
