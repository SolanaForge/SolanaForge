# Revoke Authorities Guide

## Understanding Solana Token Authorities

When creating a Solana SPL token, several authorities may exist that control different parts of the token configuration.

SolanaForge allows users to manage and optionally revoke these authorities during token creation.

---

## Mint Authority

Mint authority controls the ability to create additional token supply after launch.

If mint authority remains active:
- more tokens can be minted later

If mint authority is revoked:
- no additional supply can ever be created

Many projects revoke mint authority to improve transparency and supply trust.

---

## Freeze Authority

Freeze authority controls the ability to freeze token accounts.

If freeze authority remains active:
- certain token accounts may potentially be frozen

If freeze authority is revoked:
- freezing functionality becomes permanently disabled

Some creators revoke freeze authority to improve decentralization and user trust.

---

## Update Authority

Update authority controls metadata updates such as:
- token name
- symbol
- logo/image
- description

If update authority remains active:
- metadata may still be modified later

If update authority is revoked:
- metadata becomes permanently locked

Projects focused on immutability may revoke update authority.

---

## Important Considerations

Revoking authorities is permanent.

Once revoked:
- the authority cannot be restored

Users should carefully review authority settings before signing transactions.

---

## SolanaForge Transparency

SolanaForge displays revoke settings clearly before transaction approval.

Users always review:
- token configuration
- authority selections
- estimated costs
inside their wallet before signing.

No hidden approvals or automatic signatures occur.

---

## Beginner Guidance

Common approaches include:

### Meme Coins
Often revoke:
- mint authority
- freeze authority

### Community Projects
Often revoke:
- mint authority
- freeze authority
- sometimes update authority

### Development Projects
May temporarily keep update authority active during testing.

---

## Security Reminder

Always verify transaction prompts carefully before signing.

SolanaForge will NEVER request:
- seed phrases
- private keys
- wallet recovery phrases

---

## Official Links

Website:
https://solanaforge.app

GitHub:
https://github.com/SolanaForge

X/Twitter:
https://x.com/solanaforgeapp

Telegram:
https://t.me/SolanaForgeChannel

Support:
support@solanaforge.app
