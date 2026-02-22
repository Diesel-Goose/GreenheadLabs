# XRP Wallets Overview - Greenhead Labs
**Last Updated:** February 2026  
**Purpose of this Document:** Document all XRP-related wallets, their intended tasks/use cases, addresses, and **strict security rules** to ensure safety, auditability, and proper segregation of duties/risks.  

**Core Principles (Apply to ALL Wallets):**
- **Not your keys, not your coins** — Maintain full self-custody; never use custodial services for core holdings.
- Never share private keys, seed phrases, or recovery info with anyone — ever.
- Store seed phrases/recovery offline (metal plate, safe deposit box, split locations).
- Regularly verify balances and transactions on xrpl.org/explorer or bithomp.com.
- Use destination tags correctly when required (e.g., exchanges); double-check every time.
- Enable multi-signature (multi-sig) where practical for higher-value or shared wallets.
- Keep wallet software/firmware updated from official sources only.
- Beware of phishing — verify URLs, avoid unsolicited links/messages.

## 1. Main Wallet - Key for Vanity Address
**Task/Purpose:**  
Primary personal/control wallet. Used to generate and manage vanity addresses (custom prefix). Holds master keys or emergency reserves. Minimal daily use.

**Address:**  
`r.............................................` (replace with actual)

**Rules (Never Break These):**
1. Treat as **cold/high-security** wallet — keep offline/air-gapped when not in use.
2. Only sign transactions on a dedicated, clean device (no internet except when needed).
3. Seed phrase stored **offline only** (never digital/photo/cloud). Use metal backup.
4. No automatic connections/apps; manual import only when required.
5. Never connect to dApps, bots, or third-party services directly from this wallet.
6. Use multi-sig setup if holding > [your threshold, e.g., 100,000 XRP].

## 2. Main Vanity Wallet
**Task/Purpose:**  
Public-facing company/branding wallet with vanity address. For public audits, transparency, donations, or official Greenhead Labs receipts/payments. Subject to periodic third-party audits.

**Address:**  
`r.............................................` (vanity address here)

**Rules (Never Break These):**
1. Enable **multi-signature** (e.g., 2-of-3 or 3-of-5) with keys held by different parties/devices for audit trust.
2. Publish transaction history and audit reports publicly when possible.
3. Only receive funds; outgoing transfers require multiple approvals and documentation.
4. Monitor closely for incoming suspicious transactions (dust attacks, scams).
5. Seed phrases/keys split among trusted parties/locations — never single point of failure.
6. Use only official XRPL tools (Xaman, Ledger Live, etc.) for signing.

## 3. Trading Wallet - Greenhead Labs Trade Bot Access
**Task/Purpose:**  
Low-balance, hot/active wallet. Provides limited funds for automated trading via Greenhead Labs AI agents/bots. Risk-isolated from main holdings.

**Address:**  
`r.............................................`

**Rules (Never Break These):**
1. Keep balance **low** (e.g., only what is needed for 1–7 days of trading activity).
2. Bot/API access uses **read-only + trade permissions only** — no withdraw rights.
3. Regularly sweep profits back to cold storage (Main or Long-Term wallet).
4. Use a fresh address for each major trading cycle if possible.
5. Monitor bot activity logs and wallet transactions daily.
6. If compromised suspected → immediately stop bot, move remaining funds, rotate keys.

## 4. Long Term Tangem Card via Xaman
**Task/Purpose:**  
Cold storage for **long-term HODL** XRP. Uses Tangem NFC hardware card (seedless, chip-based) linked to Xaman app for secure, air-gapped signing. Ideal for holdings not needed short/medium term.

**Address:**  
`r.............................................`

**Rules (Never Break These):**
1. Tangem card private key **never leaves the chip** — no digital exposure.
2. Only sign transactions by physically tapping the card to phone (Xaman).
3. Store card(s) in secure, fireproof location (safe, multiple geographic copies if high value).
4. Backup card setup follows Tangem official process (backup cards created at setup).
5. Minimal transactions — only for adding to long-term or rare rebalancing.
6. Verify Xaman app is official (xaman.app) and device is secure (no malware).

## 5. FLR EVM Wallet
**Task/Purpose:**  
EVM-compatible wallet on **Flare Network** for XRP DeFi activities: holding/using FXRP (wrapped XRP), stXRP (staked/liquid staking), liquidity provision, lending, etc. Bridge from XRPL → Flare via official portal.

**Address:**  
`0x.............................................` (EVM/Flare address)

**Rules (Never Break These):**
1. Use a dedicated EVM wallet (e.g., MetaMask, Bifrost Wallet, or Ledger on Flare) — separate from XRPL keys.
2. Only bridge/mint FXRP via official Flare portal (flare.network) or integrated tools.
3. Keep native FLR for gas fees; never bridge more than intended for DeFi use.
4. Approve smart contracts carefully — use simulation tools if available; revoke approvals regularly.
5. High-risk DeFi → limit exposure (small % of portfolio); monitor for exploits.
6. When bridging back to XRPL → use trustless/unwrapped process; sweep to cold storage.

**Additional Notes / To-Do:**
- Add QR codes or explorer links for each address (optional).
- Schedule quarterly reviews: verify balances, test small recoveries, update rules.
- Consider adding reserve XRP (min 10–20 XRP per wallet for XRPL activation).
- For high-value setups, explore XRPL multi-sig or hardware like Ledger + Xaman.

Stay safe — security is layered and ongoing.
