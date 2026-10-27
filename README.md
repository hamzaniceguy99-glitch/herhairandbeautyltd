# Her Hair and Beauty — her hair and beauty ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `herhairandbeautyltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/herhairandbeautyltd.mjs`).
> To change the content, edit that file and run `node build.mjs herhairandbeautyltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@herhairandbeautyltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Per item / $Per service / $Never) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Her Hair and Beauty Ltd provides hair and beauty services in Orpington and sells cosmetics through an online shop, trading since 2023. The shop is where most people underestimate what is involved. Every cosmetic placed on the UK market needs a Responsible Person established in the UK, a Cosmetic Product Safety Report for the product, and notification before it is sold, and a small retailer who imports stock directly becomes that Responsible Person whether or not they realise it. We work inside that rather than around it, and we will tell a customer which of those roles sits with us and which sits with the brand. We also make no medical claims: a product presented as treating a condition is a medicine in law, requiring authorisation nobody selling cosmetics holds. Fourteen-day right to cancel, with the hygiene exception stated honestly. Site: herhairandbeautyltd.shop
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
