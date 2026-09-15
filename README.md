# Doublier

Anyone can now build an agent that sounds like you. Nobody can prove it is you.

Feed a model enough of your writing and it will answer as you, in your cadence, with your opinions, to anyone who asks. Dozens of products do this well. Not one of them can give the person on the receiving end a way to check.

That gap is the entire design problem, and it is about to matter a great deal. A digital twin is only useful where it acts while you are absent — answering, committing, representing. The moment it acts unsupervised, the person receiving it needs two things established that no current system establishes: that this twin genuinely originates from the person it claims, and that what it just said is something that person would stand behind.

Without both, a twin is an impersonation that happens to be authorised. The authorisation is invisible to everyone except the impersonator.

Doublier is an attempt at the verified case — a twin whose provenance the recipient can check, rather than one whose authenticity the maker merely asserts.

---

## Provenance

The twin cannot be the authority on whether it is genuine. This sounds obvious and is violated everywhere: almost every agent today vouches for itself, which is the same security model as a stranger showing you a badge they printed.

Verification has to resolve against something the principal controls and the twin cannot forge, and it has to be checkable by the recipient without the principal's involvement — otherwise you have reinvented the phone call the twin was supposed to replace.

---

## Scope

A twin holds a defined authority: what it may speak to, what it may commit, where it must defer. The boundary is visible to the receiving party rather than buried in the principal's settings. Someone should be able to see that a twin has no authority on a subject without having to test it and find out.

Outside that scope the twin declines. It does not extrapolate what the principal would probably think.

This is the constraint people push back on hardest, and it is the one worth defending. A twin that guesses well is more dangerous than one that guesses badly — because the bad guesser gets caught immediately and the good one accumulates commitments nobody made until the day one of them is expensive.

---

## Revocation

The principal withdraws the twin and every outstanding representation drops with it, immediately and completely.

A twin that survives its own revocation in somebody's cache is not a twin. It is a leak that used to have permission.

---

## Status

The specification is complete — verification model, authority boundary, revocation path — and internally consistent, at full implementation-book stage.

It has not been built. The specification is the artefact, and that is the whole of the claim.

---

Written by Mahmoud Ezz · [ezz.ae](https://ezz.ae) · [AIMAS](https://github.com/ezz-ae/aimas-protocol)

All rights reserved. See [LICENSE](LICENSE).
