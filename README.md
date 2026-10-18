# VeroraChat

VeroraChat is a responsive static HTML front-end prototype. The root `index.html` is designed to deploy on Vercel without a framework build step.

## Deploy on Vercel

1. Import `Beltahtech1/VeroraChat` into Vercel.
2. Set **Root Directory** to the repository root.
3. Choose **Other** as the framework preset.
4. Leave **Build Command**, **Output Directory**, and **Install Command** empty.
5. Deploy.

## Included prototype screens

- Responsive landing page and signup/login interface.
- Browser-local demo account profile and payout preferences.
- Discovery page with sample conversation categories and illustrative profile cards.
- Profile detail pages and an activation-checkout preview with example access-fee amounts.
- Payout preference fields for M-Pesa, PayPal, crypto receiving addresses, and bank transfers.

## Production readiness — important

This is **not yet a production account or payments service**:

- Demo accounts and profile/payout preferences use the current browser's local storage. They are not securely stored server-side, shared across devices, or protected by production authentication.
- Discovery profiles are illustrative samples, not verified real or active members.
- Access fees shown on sample profiles are placeholders. No payment is collected, no STK Push is initiated, no manual transaction code is verified, and chat access is not unlocked by this prototype.
- No guaranteed earnings are represented. Any future chat compensation must be real, documented, and accurately disclosed before users pay an access fee.
- Do not request or store M-Pesa PINs, PayPal passwords, crypto private keys, or recovery phrases.

Before launch, implement server-side authentication and a database, consent/age verification and moderation, a real Safaricom Daraja STK Push integration with signed/verified callbacks and server-side transaction checks, and a support/refund process. Keep provider credentials on the server. A manual M-Pesa receipt or transaction code must be checked with the payment provider before any account is activated.
