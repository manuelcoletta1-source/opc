# OPC — Opponibility Policy Controller (STRONG)

**OPC** è il **motore di policy computabile** dell’ecosistema **HERMETICUM B.C.E.**  
Decide in modo automatico e **fail-closed** se una prova digitale è **opponibile (ALLOW)** oppure **rigettata (DENY)**.

OPC **non genera prove**:  
👉 **valida**, **verifica** e **decide**.

---

## Ruolo nell’Ecosistema

OPC opera come **gate logico-giuridico** tra:

- **UNEBDO** → genera il manifest e la prova crittografica  
- **OPC** → verifica e decide (ALLOW / DENY)  
- **GitJoker** → automatizza audit ed enforcement (CI)

Schema:

Evento → UNEBDO (proof) → OPC (policy) → ESITO

---

## Modalità Attiva: OPC STRONG

OPC è configurato in **STRONG mode**.

### Regola fondamentale
> **ALLOW solo se TUTTO è valido**  
> Qualsiasi errore, mancanza o incoerenza → **DENY**

### Controlli eseguiti
- Presenza dei campi minimi del manifest UNEBDO
- Verifica **hash SHA-512** del manifest canonicalizzato
- Verifica **firma Ed25519** sul manifest canonicalizzato
- Coerenza strutturale dei dati

---

## Output (Audit)

OPC produce un **report di decisione** auditabile:

```json
{
  "decision": "ALLOW",
  "reasons": [],
  "checked_at": "2026-01-21T12:00:00Z"
}

In caso di errore:

{
  "decision": "DENY",
  "reasons": ["signature_invalid"],
  "checked_at": "2026-01-21T12:00:00Z"
}


---

Fail-Closed by Design

Nessun default permissivo

Nessuna assunzione implicita

Nessun auto-apprendimento normativo


Se qualcosa non torna → DENY.


---

Implementazione

L’implementazione esecutiva di OPC è integrata nel software UNEBDO:

🔗 https://manuelcoletta1-source.github.io/unebdo/software/

Il codice vive nel repository unebdo, insieme a:

UNEBDO Core

CLI

test

GitJoker (CI/Audit)


Questo repository OPC è una vetrina documentale.


---

Stato

🟢 ATTIVO — OPC STRONG
Policy computabile operativa
Verifica crittografica attiva
Fail-closed enforcement


---

Autore e Fondatore

Manuel Coletta
OPC · HERMETICUM B.C.E.

---


