# Dodo Dumplings

A single-page "business card" site for Dodo Dumplings. Plain HTML + CSS, no build step,
no dependencies. Mobile-first — designed at phone width and centred as a card on desktop.

## Run it

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Files

```
index.html   markup + placeholder links (search for "REPLACE")
styles.css   all styling; colours are CSS variables at the top
assets/      logo + food photos (resized and compressed for mobile)
```

## Placeholders to fill in

Everything that needs real details is marked with a `REPLACE` comment in `index.html`:

- phone number (`tel:` links, appears twice) and WhatsApp number
- Instagram / TikTok handles and links
- email address
- trading hours, pickup suburb, delivery area
- the "Order now" button currently jumps to the contact section — point it at an
  order form or DM link if you have one

## Colours

Sampled from the logo, defined once in `styles.css`:

| Token | Value | Where it came from |
|---|---|---|
| `--blush` | `#eac2b4` | the pink disc |
| `--brown` | `#5b4340` | the banner / lettering |
| `--cream` | `#f6ece5` | page background |
| `--dough` | `#f3ece0` | the dumpling itself |
