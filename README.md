# Open Core License, Rev. 1.0 — README

> **This document is not legal advice.** It is a plain-language explanation of the Open Core License, Rev. 1.0 (the "OCL") for convenience only. It does not modify, supplement, or override the actual license text, and it may simplify or omit details that matter for your specific situation. If you need to know how this license applies to you or your project, consult a qualified attorney.

## What this license is

The OCL is a **delayed open-source license** (sometimes called a "source-available" or "eventually open" license), similar in spirit to the Business Source License (BUSL) and other timed-conversion licenses. The core idea:

1. **Today**, you can use, modify, and share the software — but with commercial restrictions (see below).
2. **On a future date** (the "Conversion Date," set in **Appendix A**), the license **automatically and irrevocably converts to the Apache License, Version 2.0** (reproduced in full in **Appendix B**), optionally supplemented by the additional permissions in **Appendix C**.

Until that date arrives, this is **not** an open-source license in the OSI sense, even though the source code is visible and modifiable.

## What you *can* do (from day one)

Section 1 grants you a worldwide, royalty-free, non-exclusive copyright and patent license, effective until the Conversion Date, to:

- Use and run the software
- Reproduce (copy) it
- Modify and merge it
- Publish and distribute it, with or without modification, in any medium
- Import and export it

The patent grant covers only claims necessarily infringed by a contributor's contribution alone or combined with the software it was contributed to. It does **not** extend to your modifications or to other combinations. If you (or your affiliates) start patent litigation claiming the software infringes a patent, all patent licenses you received under this license terminate automatically.

## What you *cannot* do (until the Conversion Date)

Section 2 lists six "Non-Permitted Purposes":

| Restriction | Plain meaning |
|---|---|
| **(a) Selling** | You can't provide a product or service for a fee whose value derives entirely or substantially from this software's functionality — including paid hosting and paid consulting/support around the software. |
| **(b) Competing** | You can't use it to build, market, or support a commercial product or service that substitutes for the software, substitutes for other products/services the Licensor offers using it, or offers substantially similar functionality. |
| **(c) Leasing** | You can't rent out temporary possession or use of it for a fee. Internal use by your employees or contractors is not leasing. |
| **(d) Relicensing derivatives** | If you redistribute a derivative work, it must stay under this same license with the same Conversion Date. This applies **only when you redistribute** — private use, private modifications, and private development are unaffected. |
| **(e) Bypassing TPMs** | You can't remove, disable, or circumvent license keys, DRM, or other technological protection measures — including ones protecting bundled third-party content. |
| **(f) Sublicensing** | You can't sublicense the software. Each recipient automatically receives their license directly from each contributor when you convey it. |

## Other terms that apply before conversion

- **No trademark license** (Section 3): you get no rights to contributors' names, trademarks, or product names beyond what the notice requirements demand.
- **Distribution requirements** (Section 4): when you distribute the software — modified or not, source or executable — you must include a copy of the license and retain all copyright, patent, trademark, and disclaimer statements.
- **No warranty** (Section 5): the software is provided "AS IS," with all warranties disclaimed and liability excluded, in the standard all-caps way.
- **Severability** (Section 7) and **jurisdictional exceptions** (Section 8): if your local law carves out an exception (e.g. permits certain acts regardless of license terms), you're not liable for exercising it in your jurisdiction — but you must use reasonable diligence and reasonable measures to avoid distributing affected copies into jurisdictions where that would violate the license.

## The Conversion Date

This is the load-bearing concept of the whole license. On the date set in **Appendix A** (at midnight UTC), per Section 6:

- **All provisions of the OCL cease to apply automatically** — no action needed by anyone.
- The software is thereafter governed solely by the **Apache License, Version 2.0** (the exact text in Appendix B).
- The **additional permissions in Appendix C are optional** — after conversion you may rely on plain Apache 2.0 alone.
- Conversion applies equally to **derivative works created before the Conversion Date**.
- **No successor can stop it.** The license is drafted so that mergers, acquisitions, bankruptcy, IP transfers, or the death of a contributor cannot suspend, delay, or renegotiate the conversion (see the "Successor" definition in Section 0 and the anti-avoidance language in Section 6).

**Check Appendix A in your copy of the license for the real date.** Templates like this one ship with a placeholder (`${YYYY-MM-DD}`), and the Licensor could set it years or decades out.

## Appendix C: the License Exception

Appendix C is an optional set of **additional permissions layered on top of Apache 2.0** after conversion. It only adds rights; it never narrows Apache 2.0. Highlights:

- **Survival upon succession**: the Apache grants run with the IP and bind every successor (acquirers, heirs, estates, entities emerging from bankruptcy, etc.). A successor cannot revoke, narrow, or add restrictions to licenses already granted, and an attempted statutory termination triggers an automatic regrant.
- **Moral rights**: contributors waive moral rights (attribution/integrity and similar personality rights) to the fullest extent allowed, and agree not to assert them where waiver isn't legally possible.
- **Exception to Apache Section 4(b)**: you are excused from the Apache requirement to mark modified files with prominent change notices.
- **Design rights grant**: an express license to design rights (industrial designs, IC layout-designs/topographies) embodied in the work, with its own litigation-termination clause.

## Where to look in the actual license text

- **Section 0** — definitions (including "Successor" and "Conversion Date")
- **Section 1** — the copyright and patent grants
- **Section 2** — the six restrictions that apply before conversion
- **Section 6** — the automatic conversion to Apache 2.0
- **Appendix A** — the actual Conversion Date
- **Appendix B** — the full Apache License, Version 2.0 text
- **Appendix C** — the optional License Exception / additional permissions

---

*Again: this README is a summary for orientation purposes only. The actual license file ([Open-Core-Election-License.MD](Open-Core-Election-License.MD)) governs, and if anything here conflicts with that text, the license file controls. For anything with real stakes — commercial use, distribution, relicensing, or disputes — talk to a lawyer.*
