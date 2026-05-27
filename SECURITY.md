🔐 Security Policy

Supported Platform

SolanaForge is a non-custodial Solana application designed to provide transparent and secure wallet interactions across supported browser and wallet environments.

⸻

Security Architecture (Important)

SolanaForge is built with a fully non-custodial, client-side execution model:

* All wallet connections are handled using the official Solana Wallet Adapter
* All transactions are created and signed locally in the user’s browser
* The backend (if applicable) does not sign, modify, intercept, or broadcast transactions
* SolanaForge does not store, access, or transmit private keys or seed phrases
* Users retain full ownership and control of their wallets and assets at all times

SolanaForge does not custody user funds under any circumstance.

⸻

Execution Flow (Transparency)

All on-chain actions follow this explicit flow:

1. User connects wallet manually via official wallet provider
2. User initiates a token creation or interaction action
3. Transaction instructions are generated on the frontend
4. Wallet prompts the user to review and approve the transaction
5. User signs the transaction locally in their wallet
6. Signed transaction is submitted to the Solana network via RPC

At no point does SolanaForge have access to signing authority or user credentials.

⸻

Security Principles

SolanaForge is designed around the following principles:

* Non-custodial architecture
* Transparent wallet interactions
* Explicit user-approved transaction signing
* Client-side transaction construction
* Educational onboarding for blockchain users
* User-controlled execution of all on-chain actions

Users always maintain full control of their wallets and assets.

⸻

Important Safety Reminder

SolanaForge will NEVER request:

* Private keys
* Seed phrases
* Wallet recovery phrases

Users should never share wallet credentials with any person, website, or service under any circumstance.

⸻

Transparent Wallet Behavior

SolanaForge does NOT:

* Auto-connect wallets on page load
* Perform hidden or background signatures
* Request unauthorized permissions
* Intercept or modify wallet transactions
* Execute actions without explicit user interaction

All wallet interactions occur only after clear user initiation and approval.

⸻

Code Transparency

Key parts of the system can be reviewed directly in the repository:

* GitHub Repository: https://github.com/SolanaForge/SolanaForge
* Wallet integration: /src/... (Solana Wallet Adapter implementation)
* Transaction logic: /src/... (frontend transaction construction)
* Token creation flow: /src/... (SPL token interaction logic)

⸻

Reporting Security Issues

If you discover:

* Security vulnerabilities
* Phishing concerns
* Wallet interaction issues
* Suspicious or unexpected behavior
* Impersonation attempts

Please report them responsibly.

📧 Security contact: support@solanaforge.app

⸻

Responsible Disclosure

We strongly encourage responsible disclosure of any security issues.

Please avoid public disclosure of vulnerabilities before they are reviewed and resolved, as this helps protect users and maintain platform integrity.

⸻

Wallet Safety Guidelines

Before signing any transaction:

* Carefully review wallet prompts
* Verify transaction details before approval
* Understand estimated network fees
* Ensure you are using official SolanaForge links only

All blockchain actions require explicit user approval via wallet signature.

⸻

Official Links

* Website: https://solanaforge.app
* GitHub: https://github.com/SolanaForge/SolanaForge
* X (Twitter): https://x.com/solanaforgeapp
* Support: support@solanaforge.app
