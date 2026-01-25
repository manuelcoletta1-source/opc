# OPC — Opponible Policy Core
## Core normativo opponibile di Hermeticum B.C.E.

**OPC non interpreta. Applica.**

OPC (Opponible Policy Core) è il **livello normativo deterministico**
dell’ecosistema **Hermeticum B.C.E.**  
Qui le regole diventano **artefatti opponibili**, verificabili nel tempo.
![OPPONIBLE](https://img.shields.io/badge/OPPONIBLE-7cf6c8?style=flat-square)
![FAIL-CLOSED](https://img.shields.io/badge/FAIL--CLOSED-enforced?style=flat-square)
![UE-FIRST](https://img.shields.io/badge/UE--FIRST-003399?style=flat-square)
![GDPR-MIN](https://img.shields.io/badge/GDPR--MIN-compliant?style=flat-square)
![AUDIT-BY-DESIGN](https://img.shields.io/badge/AUDIT--BY--DESIGN-enabled?style=flat-square)
![POLICY-ACTIVE](https://img.shields.io/badge/POLICY-ACTIVE?style=flat-square)

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

