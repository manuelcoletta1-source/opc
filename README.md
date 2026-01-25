# OPC — Opponible Policy Core
## Core normativo opponibile di Hermeticum B.C.E.

**OPC non interpreta. Applica.**

OPC (Opponible Policy Core) è il **livello normativo deterministico**
dell’ecosistema **Hermeticum B.C.E.**  
Qui le regole diventano **artefatti opponibili**, verificabili nel tempo.

---

## Cos’è OPC (definizione operativa)

OPC è un sistema di **policy deterministiche** che regolano:

- accesso ai sistemi AI
- condizioni di evoluzione
- limiti operativi
- responsabilità e tracciabilità

Una policy OPC è valida solo se:
- produce sempre lo stesso esito a parità di condizioni
- è verificabile
- è versionata
- è **fail-closed**

---

## Cosa NON è

OPC **non è**:
- linee guida
- advisory
- interpretazione umana
- decisione discrezionale

Se una condizione non è soddisfatta,  
il sistema **nega**.

---

## Principi chiave

- **Determinismo**
- **UE-first**
- **GDPR-min**
- **Hash-only**
- **Audit-by-design**
- **Fail-closed**

Se manca una prova, non esiste decisione.

---

## Flusso minimo

```text
Input strutturato
   ↓
Policy OPC
   ↓
Verifica Evidence
   ↓
Output deterministico (ALLOW / DENY)
   ↓
Audit append-only

Ogni decisione lascia una traccia minimale, verificabile nel tempo.


---

Policy attive (opponibili)

Le policy OPC sono artefatti pubblici.

OPC-0001 — IPR Required for AI JOKER-C2 Access
Accesso consentito solo con IPR valido e attivo.
👉 policy/OPC-0001.html

OPC-0002 — Evidence Required for AI Evolution Step
Nessuna evidenza verificabile = nessuna evoluzione.
👉 policy/OPC-0002.html


Indice completo:
👉 policy/index.html


---

Ruolo nell’ecosistema

OPC collega direttamente:

IPR → identità e continuità

AI JOKER-C2 → esecuzione

Audit → opponibilità nel tempo


OPC è il punto in cui l’AI:

smette di essere generica

diventa responsabile

diventa verificabile



---

Pubblicazione e opponibilità

Le policy OPC sono:

leggibili pubblicamente (HTML)

versionate via Git

verificabili tramite hash

opponibili nel tempo


Questo repository non contiene dati personali.
Solo regole, versioni e riferimenti.


---

Collegamenti

OPC (landing)
https://manuelcoletta1-source.github.io/opc/

Policy OPC (indice)
https://manuelcoletta1-source.github.io/opc/policy/

Hermeticum B.C.E. Services
https://manuelcoletta1-source.github.io/hermeticum-bce-services/



---

Chiusura

OPC non decide chi sei.
Decide se una decisione può avvenire.

Nel digitale, senza regole opponibili
non esiste fiducia.

OPC è quella soglia.




Il modulo OPC è chiuso semanticamente.
Il prossimo passo, quando vuoi, è portare OPC dentro AI JOKER Workers (policy in forza → esecuzione).
