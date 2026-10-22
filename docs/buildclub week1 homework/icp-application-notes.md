# ICP application notes — CryptoSure

*Companion to `a16z-do-you-really-know-your-icp-transcript.md`. Applies the
episode's framework to CryptoSure as it exists today (pre-revenue, contracts
compiled, carrier-backed PA-first posture, Build Club submission stage).*

---

## 1. What the episode actually teaches

Four ideas do the real work:

1. **ICP is the central nervous system.** Conversion rates, sales-cycle
   length, expansion, churn — nearly every KPI is an ICP report card. If
   everything looks like a separate problem (pipeline, marketing, roadmap),
   the root cause is usually ICP misalignment.
2. **A good ICP says who AND why, with defensible differentiation.** Unique
   (what competitors can't do), comparative (what we do better), holistic
   (what's different about us as a company). It must be written in
   *searchable, measurable qualities* — you cannot market to a feeling.
3. **ICP ≠ segment ≠ persona.** Segment is a market group ("crypto
   companies"). ICP is narrow: type, size, pain, why-us. Personas are the
   people inside those companies — the buying circle, not a single buyer.
4. **ICP is stack-ranked and alive.** ElevenLabs runs a dozen defined ICPs
   with clear priority. Focus is concentric circles: a slam-dunk center,
   opportunistic rings around it, "proceed with caution" at the edge. And it
   evolves at inflection points — it is never set-and-forget.

---

## 2. The uncomfortable first insight: CryptoSure has TWO ICPs

The episode assumes a normal seller→buyer pipeline. CryptoSure is
carrier-backed: **a licensed carrier issues the policies, holds reserves,
and bears the risk.** Without a carrier saying yes, there is no product to
sell to anyone.

So the first ICP to nail is not the policyholder — it's the
**carrier/MGA/underwriter partner**. Our pitch docs already frame them as
the audience for the evidence trail ("every insured wallet traces to a
verified person through lawful process"). That IS their ICP-fit test: the
thing a carrier's underwriters and regulators need to hear.

| | ICP #1 — the gatekeeper | ICP #2 — the insured |
|---|---|---|
| Who | Carriers, MGAs, reinsurers, program administrators willing to write novel crypto risk | Companies that hold or custody crypto |
| Why us | ZK compliance evidence + defined scope + human underwriter gate = a standard they can defend to regulators | Provable coverage without surrendering identity/wallet disclosure |
| Their pain | Crypto premium demand they can't underwrite; no evidence trail they trust | Uninsurable treasuries; boards and auditors demanding coverage |
| Buying circle | Chief underwriting officer, actuarial, compliance/regulatory affairs, reinsurance partners | CFO/treasurer (economic buyer), CISO/security lead (champion), compliance officer, board/auditor (influencer) |

**Homework takeaway:** the week-1 exercise should probably be done twice —
once for the carrier partner, once for the insured business. The current
pitch materials implicitly target both but never separate them.

---

## 3. Draft ICP — the insured business (center circle)

Applying the episode's "narrow and searchable" standard to what the major
synopsis already declares ("business customers first"):

**Draft ICP statement:**

> US-domiciled companies in licensed jurisdictions (PA first) that custody
> crypto on behalf of users OR hold material crypto on their balance sheet,
> with an existing compliance function (KYC/AML program, SOC 2 or equivalent
> audit posture), a board or auditor actively asking about asset protection,
> and no existing crime/specie policy that covers self-custody loss events
> we define.

**Searchable qualities** (the episode's hard requirement — things we can
actually build a list from):

- Registered custodians, exchanges, payment platforms with PA nexus
- Public-company 10-K/10-Q digital-asset disclosures (literal text search)
- Firms already carrying crime/specie/D&O policies via brokers like Aon/Marsh
- SOC 2 Type II reports / existing auditor relationships
- Companies that have publicly disclosed a wallet loss or near-miss

**Why they'd need us specifically (defensible differentiation):**

- *Unique:* coverage where the insurer never holds the customer's identity
  or wallet inventory — the exact thing the most-wanting customers refuse
  to hand over. Nobody else can make this offer.
- *Comparative:* scope hash bound to the policy — "what was covered" is a
  fact at claim time, not a dispute.
- *Holistic:* Midnight-native ZK stack, DIDz ecosystem tooling, forensic
  recovery pipeline — the posture of a company built for this asset class,
  not a carrier bolting crypto onto a property form.

---

## 4. Stack-ranked ICPs (concentric circles, ElevenLabs-style)

Per the episode, define all of them — then be explicit about which is the
center *right now*:

| Ring | Segment | Why it's there |
|---|---|---|
| **Center** | Carrier/MGA partner + mid-size crypto custodians & platforms (PA) | Without ring 1 there is no product; custodians have concentrated pain, rational buyers, existing compliance |
| Ring 2 | Companies holding crypto treasury (operating businesses, funds) | Large losses, but longer sales cycles; buying circle less crypto-fluent |
| Ring 3 | Retail self-custody via fixed tiers ($500–$50k) + EDU gating | Explicitly "light retail to prove the end-to-end flow" — validation and habit-building, not revenue |
| Edge / caution | Everyday consumer goods insurance (CryptoSure.pro world) | Different buyer, different channel, different everything — real risk of the "we sell to everyone" trap |

**The episode's warning applied to us:** the private repo spans everyday
insurance AND wallet insurance AND retail AND commercial. That's four ICPs
wearing one name. The Build-Club repo already made the right narrowing call
(wallet insurance, business customers). The notes in `05-major-synopsis.md`
agree — business first, retail as validation. Keep it that way in every
pitch and product decision until the center ring is proven.

---

## 5. The five gut-test questions (answered honestly at our stage)

The episode's founder test, applied now:

1. **Which customers get the most value?** Unknowable pre-launch —
   substitute: which LOST the most historically? Custodians and
   high-value self-custody holders (Bybit-scale events aside, the long tail
   of address-poisoning and key-compromise losses is our evidence base).
2. **What traits do they share?** Material on-chain balances, existing
   compliance programs, counterparty/auditor pressure to insure.
3. **What objections lose deals?** Anticipated: "your coverage cap is too
   small," "crypto premiums are too expensive," "I don't trust a new
   program," regulator wariness on the carrier side. Log every one.
4. **Who's easiest to upsell?** Predicted: EDU-certified wallets moving
   from low to high tiers — the curriculum is the upsell path by design.
5. **What do competitors' customers share?** Lloyd's-coverholders and
   crypto crime policies already exist for institutions — their customers
   are exactly our ring 1–2: companies with compliance teams who accepted
   full identity/wallet disclosure. Our wedge: the ones who *refused*.

---

## 6. Saying no (the discipline the episode demands)

Written down now so it's cheaper later:

- **No bespoke coverage** for a whale waving cash before the standard is
  written — cash-rich, strategy-poor (the episode's exact example).
- **No undefined/unprovable loss**, ever — already a "what we will not do"
  commitment; it's also an ICP boundary.
- **No retail-first pivot** if retail tiers show early traction — early
  retail volume is the validation loop doing its job, not a signal to
  chase ("curse of early success").
- **No jurisdictions we can't serve honestly** — the GeoZ gate is an ICP
  filter, not just a compliance check.

## 7. Feedback loop / instrumentation (the RevOps point)

Pre-revenue, so the "CRM" for now is:

- Every carrier/MGA/broker conversation logged with objections tagged —
  this is the underwriting-standard feedback loop.
- Demo telemetry: which mock flows people try, where they drop.
- Waitlist/inbound segmented by the searchable qualities above, so ICP
  hypotheses get tested against real inbound rather than theory.
- When policies bind: bind rate by tier, EDU completion → activation
  conversion, claims by covered-event type. These are the conversion-rate
  signals the episode says to treat as an ICP report card.

## 8. Open questions for John

1. Is the carrier partner formally ICP #1 for week-1 purposes, or does
   Build Club want the end-customer ICP only?
2. The synopsis marks BOTH "companies holding crypto" and "companies
   custodying crypto" as First. The episode would push us to pick ONE
   center. Custodying seems stronger (aggregation pain + existing
   compliance) — agree?
3. Does the everyday-goods product (CryptoSure.pro) get its own ICP
   exercise later, or is it formally parked for Build Club scope?

---

*Episode: "Do You Really Know Your ICP? Why It Matters and How to Find Out" —
a16z Guide to Growth, May 7, 2025. Emma Janaskie with Joe Morrissey, Michael
King, Mark Regan.*
