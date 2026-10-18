# VeroraChat

VeroraChat is currently a static HTML prototype.

## Deploy on Vercel

The site entry point is `index.html` at the repository root, so Vercel can serve it without a build command or framework preset.

1. Import `Beltahtech1/VeroraChat` into Vercel.
2. Set the **Root Directory** to the repository root.
3. Choose **Other** as the framework preset (or let Vercel detect static HTML).
4. Leave **Build Command** and **Output Directory** empty.
5. Deploy.

Pushes to the connected production branch will trigger deployments automatically.

## Important prototype limitations

The chat earnings, payout ticker, receipt examples, activation countdown, and Daraja API log are front-end demonstrations. They do not verify real earnings, charge a phone, or send/confirm M-Pesa payments. Do not treat the displayed receipts or payout claims as real transactions. Real payments require a secured server-side integration with Safaricom Daraja, verified callbacks, and server-side secrets; never put credentials in browser JavaScript.
