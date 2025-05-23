# ActiveTrust

**Trust, how it’s meant to be.**

## Overview

ActiveTrust is a dynamic trust access protocol rooted in **relational intelligence**, **contextual presence**, and **signed intent**.  
It connects users to systems not just by **who they are**, but by **how they show up**.

## The Stack

This protocol is **natively designed** to integrate with the systems I've built:

### 1. **Dust5D**  
> Trust relationships flow like time—across relational dimensions.  
ActiveTrust anchors temporal interactions using **context-aware identity references** in Dust5D’s graph memory layer.

### 2. **Banano Wallet MFA**  
> Every request is a signed message.  
No passwords. No secrets.  
Just presence, proof, and propagation.

- Wallet address = identity hash
- Signed message = trust handshake
- Transactional activity = behavioral validation

### 3. **Dynamic Identity Graphs (Access Control Lists)**  
> Roles are not fixed. They emerge from the shape of interaction.  
Trust levels adapt based on:
- Enterprise Grade Fine-Grained Access Control out of the box. 
- Frequency of signed interactions
- Co-signed context (e.g. shared projects)
- Confirmation by trusted peers

### 4. **Relational Trust Fabric**  
> This is a fabric, not a firewall.  
Trust is mapped as a **multi-dimensional graph** of:
- Individual intent  
- Shared purpose  
- Proven presence

Node-to-node interactions are logged as cryptographically verifiable links in the trust lattice.

---

## Protocol Flow

```mermaid
graph TD
A[Page Load] --> B{Valid Token?}
B -- Yes --> C[Allow Access]
B -- No --> D[Redirect to Wallet Signature]
D --> E{Valid Signature?}
E -- Yes --> F[Generate TTL Token + Grant Access]
E -- No --> G[Access Denied]


⸻

Identity Principles
	•	Sovereignty First
You own your access. You decide your exposure.
	•	Proof Over Profile
What you prove in presence matters more than your static credentials.
	•	Alignment Over Authority
Access is granted by coherence, not hierarchy.

⸻

Coming Soon
	•	Wallet co-signature coordination
	•	Cross-domain wallet relays
	•	Dust5D identity relink with ribbon-based TTL
	•	UI module for AccessGraph™ traceability

⸻

“You don’t need to ask permission from systems you’ve outgrown.”
— Callum Maystone
