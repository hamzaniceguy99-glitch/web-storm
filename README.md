# Web-Storm — web-storm bv

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `web-storm.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/web-storm.mjs`).
> To change the content, edit that file and run `node build.mjs web-storm` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@web-storm.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($€[AMOUNT] / $€[AMOUNT] / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
We are Web-Storm, based in Aarschot in Flemish Brabant since 2022, providing hosting, data processing and IT consultancy. Hosting carries a legal position worth explaining to anyone whose site or data sits with us, because it protects both sides and is widely misunderstood. A host is not obliged to monitor what its customers store, and is not required to go looking for unlawful material. That is a deliberate choice in European law rather than an oversight, and it is what stops a provider reading through everything you keep. The exemption from liability holds only while the host has no actual knowledge of something unlawful, which is where notice and action comes in: anyone must be able to report content through an accessible mechanism, and a sufficiently precise and reasoned report creates that knowledge. From that moment we have to act expeditiously, and we do, rather than letting it sit in a queue. The other half is owed to customers. Where we restrict or remove anything, a clear and specific statement of reasons goes with it, because a service cut off without explanation is the thing that destroys trust in a host faster than any outage. Site: web-storm.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
