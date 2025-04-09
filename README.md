# 📘 Registro Alunni - Gestione in Python (senza import)

Questo è un semplice programma in Python che permette di gestire un **registro di alunni** salvato in un file CSV. È pensato per essere **auto-contenuto**, ovvero **senza usare librerie esterne** o moduli `import`.

## ✨ Funzionalità

- ✅ Aggiunta di alunni con voti
- ✅ Visualizzazione dell'intero registro
- ✅ Modifica dei voti di un alunno
- ✅ Eliminazione di un alunno
- ✅ Modifica di nome o cognome
- ✅ Salvataggio automatico su file `CSV`
- ✅ Calcolo della media dei voti (arrotondata a due decimali)

## 📂 Struttura del File

Il registro viene salvato in:

08_aprile_2025/registro.csv


Ogni riga rappresenta un alunno nel formato:

Nome,Cognome,Voto1-Voto2-Voto3...,Media


## ▶️ Avvio del Programma

Assicurati di eseguire il file Python (`.py`) con un interprete Python 3.


Apparirà un menu interattivo con varie opzioni.
🧠 Note Tecniche

    Nessuna libreria esterna viene utilizzata.

    La media viene calcolata tramite una funzione personalizzata.

    I voti sono separati da un trattino - nel file CSV per renderli facilmente leggibili.

    I dati vengono gestiti tramite semplici operazioni su stringhe e file.

🛡️ Requisiti

    Python 3.x

    Sistema operativo con supporto ai file .csv (qualsiasi sistema moderno)

📌 Esempio di Uso

--- MENU ---
1. Aggiungi alunno
2. Mostra registro
3. Modifica voti alunno
4. Elimina alunno
5. Modifica nome/cognome
6. Esci

🧑‍💻 Autore

Giacomo Visciotti
Progetto didattico Python


