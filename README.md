# Blocks

An interactive, single-file HTML/CSS/JS mockup of a Pay by Bank (Open Banking PIS) checkout flow, wrapped in a pure-CSS iPhone frame.

Flow: method selection → Pay by Bank plan → bank selection → review → bank login → bank PIS authorisation → success.

Each of the 10 supported banks (Barclays, HSBC, Lloyds, NatWest, Nationwide, Santander, Monzo, TSB, Virgin Money, Tesco) gets its own branded login and authorisation screen, using that bank's real logo and primary brand color.

## Running it

Just open `index.html` in a browser — no build step, no dependencies to install.

- Press **R** to restart the flow.
- Append `?step=<name>` to the URL to jump straight to a screen (`method`, `pbb`, `bankselect`, `review`, `login`, `bankreview`, `bankauth`, `success`).
- Click the gear icon (bottom-right) to open the animation tuner and adjust transition timings live.

## Stack

Vanilla HTML/CSS/JS, Tailwind via CDN, Font Awesome via CDN. All bank/UI assets are exported SVG/PNG stored locally under `assets/`.
