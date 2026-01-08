Evan Bei Oil Paint Gallery

gallery.evanbei.com

A long-term, independent web gallery for the direct sale of digital oil artworks by the artist Evan Bei.

This repository hosts the public-facing website used as a contractual venue for artwork transactions, ownership transfer, and authenticity verification.

⸻

Overview

This site is designed with a clear and restrained purpose:
	•	Present original digital oil paintings
	•	Publish explicit prices and craft tiers
	•	Serve as a formal venue for direct artist-to-collector transactions
	•	Issue ownership certificates and cryptographic authenticity proofs
	•	Allow buyers to independently verify delivered files

The gallery is not a marketplace, not an NFT platform, and not an investment product.

⸻

Business Nature

The site functions as a contractual venue for direct sales of digital oil artworks by the artist.
	•	Artist: Evan Bei
	•	Artistic origin: United Kingdom (London)
	•	Pricing reference: GBP / ETH (explicit per artwork)
	•	Payments: received through international channels as payment rails

Payments methods and receiving accounts do not alter the artistic origin or business substance of the work.

This project prioritizes clarity, permanence, and independence over platform-based mediation.

⸻

What a Buyer Receives

Each completed purchase includes a standard Business Proof Pack, delivered digitally:
	1.	Proof of Sale / Receipt
Confirms artwork ID, title, price, and transaction date.
	2.	Ownership Certificate (PDF)
A bilingual (EN / 中文) certificate issued by the artist confirming transfer of ownership title.
	3.	Hash-based Authenticity Proof
A SHA-256 cryptographic hash generated from the delivered artwork file.

The certificate contains a direct verification link, allowing buyers to independently verify file integrity.

⸻

Authenticity Verification

The repository includes a standalone verification page:

/verify.html

Features:
	•	Runs fully in the browser (no file upload)
	•	Computes SHA-256 locally using Web Crypto API
	•	Supports auto-fill via URL fragment:

verify.html#hash=<SHA256>

Buyers can verify that their delivered file exactly matches the certified version.

⸻

Craft Tiers

Each artwork is classified using a transparent, process-based tier system:
	•	A.0 — Auto-led process (system dominant)
	•	4.0 — Semi-automatic, human refinement reaches art standard
	•	3.3 — Deeper manual intervention and hand-led decisions

Tiers describe the creation process, not value guarantees.

⸻

Repository Structure

/
├── index.html        # Gallery and transaction venue
├── verify.html       # SHA-256 authenticity verification
├── images/           # Artwork images (public display only)
└── README.md

Certificate generation and sales records are handled off-repository in a private operational environment.

⸻

What This Site Is Not
	•	Not a financial or investment service
	•	Not a tokenized asset platform
	•	Not a marketplace or escrow system
	•	Not dependent on third-party art platforms

⸻

Design Philosophy
	•	Minimal
	•	Explicit
	•	Verifiable
	•	Long-term oriented

The goal is to create a structure that remains valid and understandable years later, independent of trends or platforms.

⸻

License & Rights

All artworks remain © Evan Bei.

Ownership transfer refers to collectible ownership of the specific artwork instance. Copyright remains with the artist unless otherwise agreed in writing.

⸻

Contact

For inquiries related to artwork acquisition or verification:

Email: toptrust@gmail.com

⸻

© Evan Bei · London · 2026
