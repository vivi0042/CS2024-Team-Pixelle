# PIXELLE — Portable Photo Sticker Printer website

Agency project: a 17-page website for **PIXELLE Snap**, built in HTML, CSS, Bootstrap 5 and one vanilla JS file (`scrolling-animation.js`).

## Before you submit
1. **team.html**: replace `Group [00]`, `[T00]`, `[MEMBER NAME 1–3]` and the `member@e.ntu.edu.sg` emails.
2. **Site URL**: replace `YOUR-GITHUB-USERNAME` in `sitemap.xml`, `robots.txt` and the `<link rel="canonical">` tags (search & replace across files).
3. **Store links**: Shopee/Lazada buttons point to marketplace searches; swap in real store URLs if you have them.

## Publish on GitHub Pages
1. Create a public repository, e.g. `pixelle`.
2. *Add file → Upload files*: drag in **the contents of this folder** (`index.html` must be at the root, plus `style.css`, `scrolling-animation.js` and the `images` folder). Commit.
3. *Settings → Pages*: Source **Deploy from a branch**, Branch **main**, folder **/ (root)**, Save.
4. About a minute later the site is live at `https://YOUR-GITHUB-USERNAME.github.io/pixelle/`.

Note: file names are case-sensitive on GitHub Pages (`Specs.html` has a capital S, matching the links).

## Pages
| Page | File |
|---|---|
| Home | index.html |
| PIXELLE Snap overview | overview.html |
| Specs | Specs.html |
| Compare + cost calculator | compare.html |
| Shop (purchase) | purchase.html |
| Cart | cart.html |
| Checkout (PDPA consent) | checkout.html |
| Payment (demo) | payment.html |
| Order acknowledgement | acknowledgement.html |
| About Us | about.html |
| Where to Buy | our-stores.html |
| Service Centre (form) | service.html |
| FAQ | faq.html |
| Contact Us | contact-us.html |
| Contact form / voucher (CTA form) | contactform.html |
| Team | team.html |
| PDPA policy | pdpa.html |

**PIXELLE Club pop-up:** first-time visitors see a 10%-off member sign-up 6 seconds after answering the cookie banner (never on cart, checkout, payment, acknowledgement or PDPA pages). Closing it hides it for 7 days; a "10% OFF" tab reopens it. Code **PIXELCLUB10** works in the cart. To test it again, clear the site's data in your browser.

The cart is stored in the visitor's own browser (localStorage). Forms validate and show a confirmation, but nothing is sent or stored. The payment page is a clearly marked demo.
