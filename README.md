# OPC
## Opponible Policy Core — Policy Engine di Hermeticum B.C.E.

**OPC (Opponible Policy Core)** è il **nucleo delle policy opponibili** dell’ecosistema **Hermeticum B.C.E.**.

OPC definisce **regole esplicite, versionate e verificabili** che vincolano i moduli IPR e rendono l’enforcement **dimostrabile nel tempo**.  
OPC non esegue azioni: **stabilisce le condizioni che rendono un’azione lecita o illecita** (ammissibile/non ammissibile).

---

## Funzione

OPC serve a:

- definire **policy operative opponibili**
- rendere le regole **esplicite, citabili e versionate**
- fornire base normativa computabile a **UNEBDO**
- guidare decisioni ex-ante (**IPR-GATE**)
- supportare valutazioni ex-post (**IPR-COMPLY**)
- imporre **fail-closed** come requisito di policy

Senza OPC, l’enforcement è opaco.  
Con OPC, l’enforcement diventa **verificabile**.

---

## Cosa fa / Cosa non fa

### Fa
- definisce policy e vincoli operativi
- versiona policy in modo deterministico
- rende le regole opponibili nel tempo
- abilita audit della regola applicata (policy provenance)
- impone default **fail-closed** (se manca certezza → blocco)

### Non fa
- enforcement root (→ **UNEBDO**)
- definizione identità (→ **IPR-CORE**)
- custodia documentale (→ **IPR-VAULT**)
- tracciamento eventi (→ **IPR-TRACE**)
- controllo ex-ante (→ **IPR-GATE**) *[OPC lo guida, non lo sostituisce]*
- valutazione conformità (→ **IPR-COMPLY**) *[OPC fornisce criteri]*
- scambio di valore (→ **IPR-EXCHANGE**)
- orchestrazione C2 (→ **GitJoker-C2**)

---

## Posizione nello stack Hermeticum B.C.E.
OPC (Policy Core) ↓ UNEBDO (Layer 0 — Enforcement) ↓ IPR + moduli CORE · VAULT · TRACE · GATE · COMPLY · EXCHANGE ↓ GitJoker-C2 / IPR-AIJOKER-C2
OPC è **a monte** dell’enforcement:  
se la policy non è definita, **non può essere applicata né verificata**.

---

## Principi operativi

- Policy **esplicite**, non implicite
- Versioning **obbligatorio**
- Opponibilità **nel tempo**
- Audit-by-design
- Fail-closed come default
- UE-first (standard normativo di riferimento)

Regola: se una policy non è tracciabile, **non è opponibile**.

---

## Ambito UE

OPC è progettato in coerenza con:
- AI Act UE (governance tecnica, tracciabilità)
- NIS2 / CER (responsabilità e auditabilità)
- eIDAS / ETSI (integrità e continuità)
- Horizon Europe (metodologia, verificabilità e maturità tecnica)

---

## Autore

**Manuel Coletta**

---

## Sigillo editoriale

**Esoterologia Edizioni**

---

## Stato

🟢 **ATTIVO — Policy Core di Hermeticum B.C.E.**
