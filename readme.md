# 🧠 Simulatore di Automi (DFA, NFA, e-NFA)

👋 Ciao! Questo è un progettino nato per smanettare e studiare in modo visivo gli Automi a Stati Finiti (super utile se stai preparando esami tipo *Theory of Computation* 📚). 

> 🤖 **Fun Fact:** Il codice di questa app è stato generato interamente tramite Intelligenza Artificiale (Gemini) partendo dai miei prompt!

## 🎯 Cosa fa?
È una web-app minimal e interattiva dove puoi disegnare il tuo automa e vedere *esattamente* cosa succede quando gli dai in pasto una stringa. Gestisce senza problemi:
* **DFA** (Deterministici)
* **NFA** (Non Deterministici - *sì, durante il test si colorano più stati di verde in parallelo, è il potere del non determinismo!*)
* **e-NFA** (Automi con mosse $\epsilon$)

## ✨ Features principali
* 🖱️ **Puro Drag & Drop:** Disegna stati e transizioni in un attimo.
* ⌨️ **UX fluida:** Seleziona, cancella con tastiera, setta stato iniziale (con freccina) e finali (doppio cerchio 🎯).
* 👻 **Epsilon Moves:** Tasto rapido per le transizioni a costo zero ($\epsilon$).
* 🕹️ **Simulazione Step-by-Step:** Guarda l'automa che "ragiona" passo dopo passo, o lancia la simulazione rapida per vedere subito l'esito (Accettata/Rifiutata).
* ⚡ **Zero sbatti:** Niente server, niente build. È tutto dentro un singolo file HTML!

## 🚀 Come si usa?
Letteralmente: scarica `simulatore.html` e fai doppio click per aprirlo nel browser. Fine. 
    
È perfetto anche da hostare al volo (e gratis) su **GitHub Pages**: basta caricare il file in una repo e attivare l'impostazione.

---
*Happy simulating!* 🧑‍💻