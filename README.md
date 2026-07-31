# Open Core License (OCL) — README

> **This document is not legal advice.** It is a plain-language explanation of the Open Core License (OCL) for convenience only. It does not modify, supplement, or override the actual license text, and it may simplify or omit details that matter for your specific situation. If you need to know how this license applies to you or your project, consult a qualified attorney.

## What this license is

The OCL is a **delayed open-source license** (sometimes called a "source-available" or "eventually open" license), similar in spirit to the Business Source License (BUSL) or similar timed-conversion licenses. The core idea:

1. **Today**, you can use, modify, and share the software — but with commercial restrictions (see below).
2. **On a future date** (the "Conversion Date," set by the Licensor), most of those restrictions disappear, and the software behaves much more like a permissive open-source license.

Until that date arrives, this is **not** an open-source license in the OSI sense, even though the source code is visible and modifiable.

## What you *can* do (from day one)

Under Section 0, you're granted a broad license to:

- Use the software
- Copy it
- Modify it
- Run it
- Merge it with other software
- Publish and redistribute it
- Create Derivative Works
- Publicly perform/display it

This is royalty-free and worldwide.

## What you *cannot* do (until the Conversion Date)

Section 1 carves out four "Non-Permitted Purposes":

| Restriction | Plain meaning |
|---|---|
| **(a) Selling** | You can't charge money for a product/service whose value comes mainly from this software's functionality. |
| **(b) Competing** | You can't use it to build something that competes with the software itself, or with other products/services the Licensor already offers. |
| **(c) Leasing** | You can't rent out temporary access to it for a fee. |
| **(d) Relicensing derivatives** | If you build on top of it, your derivative generally has to stay under this same license (with the same Conversion Date) — you can't fork it into a differently-licensed product. |

There's also a **Section 2 restriction**: you can't bypass license keys, DRM, or other technical protection measures — including ones protecting third-party content bundled with the software.

**Important nuance:** you *can* bundle this software with other, differently-licensed software to form "Larger Software" (Section 1(e)) — that doesn't force your other software under this license. But the OCL-covered component itself stays fully restricted until conversion.

## The Conversion Date

This is the load-bearing concept of the whole license. It's a specific date (set in **Appendix B**) after which:

- The "no selling / no leasing / no sublicensing" restrictions in Section 1 **disappear**
- The "no bypassing DRM" restriction in Section 2 **disappears**
- You gain new rights to **decompile and recompile** the software (Section 8), with some exceptions for bundled "Larger Software" and for third-party DRM, which stays enforceable independently under other law
- Patent rights (Section 3) expand to include selling, leasing, and sublicensing

Everything else in the license — attribution requirements, the disclaimer, trademark limits, the moral rights waiver, etc. — **stays in effect** even after conversion.

**Check the actual Appendix B in your copy of the license for the real date.** Templates like this one ship with a placeholder (`${YYYY-MM-DD}`), and the Licensor could set it years or decades out.

## If you contribute code

If you submit a contribution (a PR, patch, or similar), Section 7 automatically licenses it back to the Licensor under this same license — there's no separate contributor agreement to sign.

Two things worth knowing:

- **Your contribution gets "unlocked" early.** The Section 1/2 restrictions stop applying to your specific contribution as soon as it's accepted — potentially long before the general Conversion Date applies to everyone else's code.
- **Attribution defaults to anonymous-ish.** Per **Appendix C**, your contribution is credited in the NOTICE file as generic "Copyright © Contributor" unless you specifically ask to be named. This only affects the *public notice* — you still have to be identifiable by a real name, legal entity, or pseudonym for purposes of ownership, licensing, and enforcement. It's not a way to contribute untraceably.

## No warranty

Section 5 disclaims all warranties and liability, in the standard all-caps open-source-license way ("AS IS," no merchantability/fitness/non-infringement warranty, no liability for damages).

## Quick reference: what changes at the Conversion Date

| Area | Before Conversion Date | After Conversion Date |
|---|---|---|
| Selling / sublicensing | Prohibited | Allowed |
| Leasing | Prohibited | Allowed |
| Competing products | Prohibited | Allowed |
| Bypassing TPM/DRM | Prohibited | Allowed (except third-party DRM, which remains subject to other law) |
| Decompiling | Not addressed | Expressly allowed |
| Attribution/notice requirements | Required | Still required |
| Patent license scope | Use/modify/distribute only | Expands to include sell/lease/sublicense |

## Where to look in the actual license text

- **Appendix A** — instructions for applying the license to a project
- **Appendix B** — the actual Conversion Date
- **Appendix C** — the default contributor copyright notice
- **Section 8** — everything that changes at conversion
- **Section 1** — the restrictions that apply before conversion

---

*Again: this README is a summary for orientation purposes only. The actual LICENSE file governs, and if anything here conflicts with that text, the LICENSE file controls. For anything with real stakes — commercial use, distribution, relicensing, or disputes — talk to a lawyer.*
