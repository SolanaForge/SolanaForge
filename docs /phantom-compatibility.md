# Phantom Wallet Compatibility

## Overview

SolanaForge is designed to support transparent and user-controlled interactions with Phantom Wallet.

The platform follows non-custodial wallet interaction principles and aims to provide clear transaction visibility before approvals occur.

---

## Supported Wallet Flow

Typical SolanaForge workflow:

1. User clicks “Connect Wallet”
2. Phantom wallet approval popup appears
3. User reviews and approves connection
4. User configures token settings
5. Transaction simulation and fee preview are displayed
6. User reviews transaction details
7. User explicitly approves transaction inside Phantom

All wallet actions are initiated by the user.

---

## No Automatic Wallet Connections

SolanaForge does NOT:
- auto-connect wallets on page load
- trigger hidden signatures
- request background approvals
- perform automatic transactions

Wallet interactions occur only after explicit user action.

---

## Transaction Transparency

Before signing transactions, SolanaForge may display:
- estimated fees
- rent costs
- metadata costs
- platform fees
- revoke authority settings
- estimated totals

Simulation is informational only.

Simulation does not execute blockchain transactions.

---

## Non-Custodial Architecture

SolanaForge is a non-custodial platform.

This means:
- users control their wallets
- users approve transactions directly
- SolanaForge does not custody user funds

---

## Security Principles

SolanaForge emphasizes:
- transparent transaction visibility
- user-controlled signatures
- visible fee breakdowns
- beginner-friendly onboarding
- educational security guidance

SolanaForge will NEVER request:
- seed phrases
- private keys
- wallet recovery phrases

---

## Mobile Compatibility

SolanaForge aims to support Phantom mobile browser compatibility where possible.

Wallet interactions remain user-confirmed across supported devices.

---

## Official Links

Website:
https://solanaforge.app

GitHub:
https://github.com/SolanaForge

X/Twitter:
https://x.com/solanaforgeapp

Support:
support@solanaforge.app
