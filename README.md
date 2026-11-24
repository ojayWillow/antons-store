# Antons Store: sample perfume shop

A clickable mockup of a small perfume e-shop (19 scents), made to show the client how the store could look and work. **Not a production shop:** brand, products, prices and payments are placeholders, and nothing is charged.

## What you can click through

1. **Landing page**: hero, brand story, three bestsellers, "how to choose", discovery set, perks, newsletter.
2. **Shop**: all 19 scents, filter by family (Fresh, Floral, Woody, Amber), sort by price.
3. **Product page**: notes (top / heart / base), choose 50 or 100 ml, choose quantity, add to bag, express pay, "try it first" 2 ml sample.
4. **Bag**: change quantities, free-delivery progress bar, checkout.
5. **Checkout**: 1 Account (sign in, create account or continue as guest) → 2 Details (email, name, address; phone optional; newsletter opt-in; every field validated) → 3 Delivery (+ gift wrap) → 4 Payment (terms required).
6. **Payment screen** (demo of the provider's page): card with 3-D Secure, Apple Pay, PayPal or bank link → processing → payment successful. Express Apple Pay / PayPal on the product page and bag skip the checkout form.
7. **Order confirmation**: order number, summary, what happens next.

**Account pages**: sign in (email or Google / Apple), create account, forgot password, My account (orders, saved address, preferences). Guests are offered an account after paying. Demo only: stored in the browser.

Extras: **scent finder quiz** (3 questions → 2 suggestions → add both as samples) and **gift wrap + handwritten card** at checkout.

## Controls at the bottom of the page

- **A / B / C**: three design directions for the same store (A Index, B Motion, C Colour). Link straight to one with `#a`, `#b` or `#c`.
- **Notes**: shows or hides the yellow explainer notes that describe each step for the client.
- **+ Comment**: click anywhere on the page to pin feedback from the client. **List** shows all comments and copies them as text. Comments are saved in that browser only.

## Tech

One static `index.html` (HTML, CSS, vanilla JS). No build step. Deployed on Vercel.

## Product photos

Every scent has a framed photo box (shop list, cards, colour bands, product page). Add `images/01.jpg` … `images/19.jpg` (4:5, 1200 × 1500) and they replace the drawn bottles automatically. See `images/README.md`.

## Link preview

`index.html` has Open Graph and Twitter tags (title "Antons Parfume Shop", description, `og.png` 1200×630), so shared links show a card in WhatsApp, Messenger, Slack, etc. Update `og.png` when real photos arrive.
