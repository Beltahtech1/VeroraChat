# VeroraChat

VeroraChat is a static HTML front-end prototype, deployable on Vercel without a framework build step.

## Deploy on Vercel

1. Import `Beltahtech1/VeroraChat` into Vercel.
2. Set **Root Directory** to the repository root.
3. Choose **Other** as the framework preset.
4. Leave **Build Command**, **Output Directory**, and **Install Command** empty.
5. Deploy.

The root `index.html` is the site entry point. Pushes to the connected production branch can trigger deployments automatically.

## Account and payout prototype

The interface includes signup/login screens, a profile dashboard, and fields for M-Pesa, PayPal, cryptocurrency public receiving addresses, and bank transfers. In this prototype, account records and payout preferences are stored in the current browser's local storage. They are not synchronized across devices and this is not production-grade authentication or secure payment-data storage. The password handling in this demo is not a substitute for server-side authentication.

The form only saves a preferred payout destination; it does **not** initiate or verify payments. Real payouts require a backend, verified provider callbacks, appropriate compliance and fraud controls, and secrets kept server-side. Never request or store mobile money PINs, PayPal passwords, crypto private keys, or seed/recovery phrases.
