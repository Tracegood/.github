# TraceGood

A humanitarian charity funded entirely by cryptocurrency donations, at
**[tracegood.org](https://tracegood.org)**.

We chose crypto so that giving can be checked rather than taken on trust. Every confirmed
donation is published on a public ledger with a link to its on-chain transaction, so anyone
can confirm what arrived without asking us to be believed.

## What is true about us right now

New organisations usually describe themselves as if they were older. These are the facts a
stranger should have before giving us anything.

- **Not a registered entity.** Establishing a non-profit association (MTÜ) in Estonia is
  intended and **has not been filed**. We are not a registered charity anywhere, and we are
  not a 501(c)(3).
- **Donations are not tax-deductible in any country**, and will not be until registration
  completes.
- **Money has arrived; nothing has been spent yet.** There is no spending report, because
  there is no spending to report. When that changes, the report comes before the claim.
- **No impact figures, donor counts or track record exist.** If you need one for a write-up,
  there isn't one — please don't supply it.
- **Founded 2026.** Founder: Jason McGrey. Based in Estonia.

## What you can verify yourself

- **[The ledger](https://tracegood.org/transparency)** — every confirmed gift, each with its
  transaction link. Transparent-chain rows can be checked down to the amount. Monero hides
  amounts by design, so an XMR row proves a transaction exists but not its size; that figure
  rests on our word, and we say so on the page rather than letting you assume otherwise.
- **[How to read a charity's transparency page](https://tracegood.org/blog/how-to-read-a-charitys-transparency-page)**
  — written so it can be used against us.

## Signed donation addresses

An address on a web page is only a claim. If the page is tampered with or the domain is
hijacked, a donor cannot tell the difference, and the chain will not give the money back.

So addresses we hold the keys to are signed with minisign, and **the public key lives here
rather than on tracegood.org** — someone who controls the website still does not control
this page.

```
untrusted comment: minisign public key for TraceGood donation addresses
<PUBLIC KEY GOES HERE — generate with: minisign -G -p tracegood.pub -s tracegood.key>
```

Verify a published address file with:

```
minisign -Vm addresses.json -P '<the key above>'
```

If the signature does not verify, **do not send anything**, and tell us at
hello@tracegood.org.

> Not yet generated. Until this block holds a real key, treat every address on the website as
> unsigned and unverifiable — including by us.

## Where we exist

This organisation page and **[tracegood.org](https://tracegood.org)** are the only channels
TraceGood operates. We run no X, Mastodon, Reddit, Facebook or Telegram presence. **Treat any
account claiming to be TraceGood as unverified.**

Contact: **hello@tracegood.org**
