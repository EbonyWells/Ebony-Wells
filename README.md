# Ebony-Wells
An adult site that allows blac k women from around the world to give advice, do shows, live tutorials, etc.
Ebony Wells — Account System Starter
A server-backed starter for the Ebony Wells 18+ community platform. The project keeps the brown/tan/green identity and the new garden logo.
Included
Persistent JSON database for the starter build
Owner first-run setup
User and Advisor registration/login/logout
Secure password hashing with Node scrypt
Session cookies
500-advisor capacity setting
Advisor approval workflow
Exactly 5 S.A.A. seats supported
Owner account administration: approve, suspend, activate, assign S.A.A.
Advisor Garden profiles with photo/video/backdrop/song fields
Advisor content counters and limits
User follow limit of 50 advisors
User blocking with automatic advisor-block red flag
Complaint/safety queue for S.A.A. and Owner
Golden Tree fruit wallet
50 free apples for new users
Fruit tip ledger with the requested fruit/tree/payout values
Advisor stash tracking and $300 alert flag
Owner-controlled external payment-link settings
Owner can manually credit fruit after confirming an external payment
Audit log foundation
New Ebony Wells garden logo embedded in the site
Run locally
Install Node.js 18 or newer.
Open a terminal in this folder.
Run npm start.
Visit http://localhost:3000.
On the first visit, create the Owner account.
Payment setup
The basket and advisor monthly payment links are intentionally blank. The Owner dashboard lets you paste the external payment URLs you choose. The starter does not claim that an external payment happened automatically; after confirming a payment, the Owner can credit the user's fruit basket.
Identity and age verification
This starter does not store raw ID or birth-certificate files. For production, connect a dedicated identity/age-verification provider and store only the minimum verification result needed by Ebony Wells.
Production next steps
Before a public launch, replace the JSON starter database with a managed database, use a production session store, add HTTPS/security headers/rate limiting/CSRF protections, connect a dedicated identity and age verification service, add real payment processing and payout compliance, and implement secure media storage and moderation.
