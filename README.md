# Doublier

**Verified personal digital twins.**

> **Status:** Full implementation specification complete. Not yet built.

---

## The word that matters

There is no shortage of systems that will build an agent in your likeness. Feed them your writing and they produce something that sounds like you, answers as you, and represents itself as you to anyone who asks.

None of them can prove it.

That gap is the whole design problem. A digital twin is only useful where it acts without you present — answering, committing, representing. And the moment it acts unsupervised, the receiving party needs to know two things that no current system establishes: that this twin genuinely originates from the person it claims, and that what it just said is something that person would stand behind.

Without those, a twin is an impersonation you happened to authorise.

**Doublier** is an attempt at the verified case: a twin whose provenance is checkable by the person receiving it, not merely asserted by the person who made it.

---

## Design constraints

**Provenance is external.** The twin cannot be the authority on whether it is authentic. Verification has to be resolvable by the recipient against something the principal controls and the twin cannot forge.

**Authority is bounded and legible.** A twin holds a defined scope — what it may speak to, what it may commit, where it must defer. The bound is visible to the receiving party, not buried in the principal's settings. A recipient should be able to see that a twin is not authorised on a subject without having to test it.

**Silence over improvisation.** Outside its scope the twin declines. It does not extrapolate the principal's likely view. A twin that guesses well is more dangerous than one that guesses badly, because nobody catches it.

**Revocation is immediate and total.** The principal withdraws the twin and every outstanding representation drops with it. A twin that survives its own revocation in some cache is not a twin, it is a leak.

---

## Standing

This reached full implementation-book stage — the specification is complete and internally consistent, covering the verification model, the authority boundary and the revocation path.

It has not been built. The specification is the artefact, and it is described here as exactly that.

---

## Related

- [AIMAS](https://github.com/ezz-ae/aimas-protocol) — confidence as a first-class value, the same premise applied to intent

---

Architected by Mahmoud Ezz · [ezz.ae](https://ezz.ae)

All rights reserved. See [LICENSE](LICENSE).
