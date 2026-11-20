# Bybit Referral Code BYOFFICIAL — November 2026 Practical Handbook: Calculate and Actually Claim the 50% Fee Rebate

Referral code: **BYOFFICIAL**
Registration link: https://partner.bybit.com/b/BYOFFICIAL
Core benefit: Register with BYOFFICIAL and get up to **50% trading fee rebate** on eligible trades (spot + futures; the actual tier is shown on your account's "Referral Rebate" page)

This guide does not follow the old "register → KYC → deposit → done" template. Instead, it starts by helping you understand the rebate math, then walks through the steps where most people silently lose money.

---

## 1. What "Up to 50% Fee Rebate" Actually Means

Many people assume 50% means the trading fee is cut in half at checkout. **It is not.** These are two separate mechanisms:

| Item | Fee Discount | Trading Fee Rebate |
|---|---|---|
| How it works | Charged at the lower rate upfront | Charged at full standard rate first, rebated later |
| Timing | Instant | Based on the rebate page / settlement cycle |
| Form | You just pay less | Rebate amount is credited to your account |
| Feel | Invisible | You only "feel" it when the rebate lands |

So the Fee column in your trade history will show the **full price** at first. Do not panic — the rebate is settled on a separate track.

Three more things to lock in:

1. **Rebate base = the fee you actually paid**, not your volume and not your PnL.
2. **50% is a ceiling, not a floor**. Bybit's affiliate documentation states VIP accounts cap total cashback at 50%; non-VIP accounts have no hard cap but the actual tier depends on the affiliate setting and campaign terms.
3. **Not binding the code at signup = basically unrecoverable**. Bybit's account FAQ is explicit: once the account is created, no referral code can be added or removed, and support will not change it for you.

**The only exception:** a main account that submitted the form with *no code at all* can add an affiliate code within 14 days via Account → Account Info → Join an Affiliate's Community. Once joined, it is locked too. Already-bound codes, day 15+, and sub-accounts are all excluded.

---

## 2. November 2026 VIP 0 Fee Baseline (Copy This Table)

| Product | Maker | Taker | With MNT Discount |
|---|---|---|---|
| Crypto spot | 0.1000% | 0.1000% | 0.0750% / 0.0750% |
| USDT perpetual | 0.0200% | 0.0550% | 0.0180% / 0.0495% |
| USDT futures | 0.0200% | 0.0550% | 0.0180% / 0.0495% |
| Fiat pairs | 0.1500% | 0.2000% | N/A |
| Pre-listing perp | 0.0400% | 0.1000% | Separate |
| Innovation Zone | 0.0400% | 0.1100% | Separate |
| Options | 0.0200% | 0.0300% | Separate |

MNT discount rules (November 2026):

- Spot saves **25%**, futures save **10%**
- MNT must sit in the **Unified Trading Account (UTA)**
- Spot and Futures toggles are **separate**
- Main account toggle does **not** inherit to sub-accounts
- Not applicable to: API orders, bots, copy-trader follower orders, liquidation orders, RFQ, Inverse contracts
- When MNT balance runs out, fees automatically fall back to USDT

VIP tier is based on **30-day volume or asset balance, whichever is higher**, refreshed daily at UTC 07:00.

---

## 3. Three Real Scenarios — What You Actually Pay

Assume BYOFFICIAL is bound, rebate tier is 50%, MNT discount is on.

**Scenario A: Spot 10,000 USDT market buy then market sell (two Takers)**

- Standard fee: 10 + 10 = 20 USDT
- After MNT: 7.5 + 7.5 = 15 USDT
- 50% rebate: get back 7.5 USDT
- **Net paid: 7.5 USDT** (37.5% of original)

**Scenario B: Futures 10,000 USDT position, market open + market close**

- Standard Taker: 5.5 + 5.5 = 11 USDT
- After MNT: 4.95 + 4.95 = 9.9 USDT
- 50% rebate: get back 4.95 USDT
- **Net paid: 4.95 USDT**

**Scenario C: Futures limit order as Maker, 10,000 USDT open + close**

- Standard Maker: 2 + 2 = 4 USDT
- After MNT: 1.8 + 1.8 = 3.6 USDT
- 50% rebate: get back 1.8 USDT
- **Net paid: 1.8 USDT**

See the pattern? **Limit order > MNT discount > rebate** — all three stack. If you want the lowest fee, always try to be Maker first, then MNT, then rebate.

One easy misunderstanding: MNT **reduces the fee first**, the rebate **returns a percentage afterward**. Whether the rebate is calculated on the original fee or the post-MNT fee can differ by tier — check your own rebate detail page, do not guess.

---

## 4. 10-Minute Pre-Registration Checklist

- A primary email: Gmail / iCloud / ProtonMail, **never used for Bybit before**
- Do NOT use Apple "Hide My Email" (@privaterelay.appleid.com) — you may lose access after switching devices
- Valid government ID: passport is safest, national ID / driver's license also work
- A phone number that can receive SMS (name must match KYC later)
- Google Authenticator, **cloud sync turned OFF**
- Stable network, **do not switch VPN nodes** during the whole flow
- Your real country/region of residence (cannot be changed after submission)
- A password manager: login password and funds password **must differ**

Three iron rules:

- One ID = one Bybit account. Duplicate accounts both get risk-flagged.
- Repeated registrations from the same device in a short window trigger risk control.
- Use **half-width alphanumeric** in every field to avoid encoding errors.

---

## 5. Binding BYOFFICIAL at Signup (The Only Irreversible Step)

1. Open https://partner.bybit.com/b/BYOFFICIAL in your browser
2. **Select your real country/region first** (this cannot be changed after submit)
3. Choose Email or phone registration (Email recommended — safer for account recovery)
4. Find the "Referral Code / Referral ID / Affiliate Invite Code" field and confirm it shows **BYOFFICIAL**
5. Complete captcha + email/SMS verification
6. Set password: 8–32 characters, upper + lower + digit + symbol
7. Submit and create the account

Three anomalies and how to handle them:

- **Field blank** → type BYOFFICIAL manually, all caps, no leading/trailing spaces
- **Field greyed out or showing someone else's ID** → cookie was hijacked by another promo link; clear cache or use incognito
- **Already submitted without the code** → go immediately to Profile → Referral Rebate and check the referrer field. If empty and you have not deposited or traded, you still have the 14-day affiliate-community window. Beyond that, the only official path is transferring KYC to a new account (once per 6 months, locks deposits/withdrawals for 24–48 hours)

**First thing after registering**: Avatar → Referral Rebate / My Referrals, confirm the referrer is populated. If not, start over with a clean email while the account is still empty — cost is zero. Once you deposit, you are stuck with the default fee rate for life.

---

## 6. KYC — Which Level Is Enough

Path: Avatar → Account & Security → Identity Verification

| Level | Unlocks | Use case |
|---|---|---|
| Lv.0 unverified | No deposit, no trading, no rebate | — |
| Lv.1 Standard | ID + face, unlocks spot/futures/P2P/basic withdrawal | Enough for daily trading |
| Lv.2 Advanced | Adds proof of address, raises fiat & withdrawal limits | Large deposits/withdrawals |
| Pro | Enhanced due diligence | Institutional size |

Lv.1 photo tips:

- **Physical ID only**, never a screenshot, never a filtered photo
- All four corners visible, no glare, no cropping
- Even lighting for face scan, hat off, thick glasses off
- Review usually 15 minutes to a few hours; complex cases up to 48 hours
- **5 rejections in 24 hours locks you out for 24 hours** — do not spam resubmit

Common rejection reasons: expired ID, corners cut, glare, face mismatch, ID already bound to another Bybit account.

Lv.2 proof of address accepted: utility bill, bank statement, or government letter within 3 months (must show name + address). Telecom bills, insurance statements, and medical bills are usually rejected.

---

## 7. Security Trio + Three Locks (Do This On Day One)

**Mandatory trio**

- **Google 2FA**: no cloud sync; write the recovery codes on paper offline
- **Funds password**: 6 digits, completely different from your login password, required for withdrawals and API creation
- **Anti-phishing code**: pick a string you control; every official email will carry it. Anything without it is phishing

**Three extra locks**

- **Passkey**: biometric or hardware key login
- **Withdrawal whitelist**: only pre-approved addresses
- **New-address lock**: cooling period after adding an address

Resetting the funds password, deleting a Passkey, or turning off the withdrawal lock can each trigger a **24-hour withdrawal freeze**. Do them all at once, not one by one.

**Never share**: login password, 2FA code, SMS code, seed phrase, API secret, funds password.

**100% scam scripts**: "support DM to unfreeze your account", "send coins to activate rebate", "remote help to fix your account", "external link in the P2P chat". Bybit staff will **never** DM you asking for a verification code or asking you to transfer coins.

---

## 8. Three Deposit Routes, Pick Without Regret

**Route A: P2P / C2C (best for beginners)**

- Bybit charges no platform fee; you pay the merchant spread, typically 0.5%–1.5%
- Path: Buy crypto → P2P → Buy USDT
- Filter: high trade count, 98%+ completion rate, gold-verified merchants
- **The payer name must equal your KYC legal name** — no third-party payments
- Only click "Paid" after the money has actually left your account; do not cancel before the merchant releases
- Chat only inside Bybit; never scan personal QR codes or click external links

**Route B: On-chain deposit (if you already hold coins)**

- Bybit charges **no deposit fee**; you only pay the source chain gas
- Assets → Deposit → pick coin → pick network
- **Same coin, same network** is the iron rule: ERC20 / TRC20 / BSC / Arbitrum mix-ups can permanently lose funds
- XRP / EOS / TON / XLM / ATOM require a **Memo / Tag** — missing it will hang your deposit
- First transfer: send 1–2 USDT as a test, then move the balance

**Route C: Bank card / third party**

- Requires Lv.1
- Card fee depends on issuer and region; non-EU Visa/Mastercard is commonly around 3.7%
- Good for small urgent top-ups, bad for large amounts

---

## 9. Turn On MNT Discount (Optional, Worth It If You Trade Often)

Prerequisite: MNT balance sitting in the Unified Trading Account.

Path:

- Web: trading page → Fee Rate → tick "Using MNT for fee discount"
- App: trading page → top-right menu → same option

Four reminders:

1. Toggle Spot once, toggle Futures once — **separately**
2. Main account toggle does not inherit to sub-accounts
3. When MNT runs out, fees fall back to USDT automatically
4. Do not stockpile MNT — token volatility can eat the entire discount

Market makers, institutional, Pro, and API users are not supported.

---

## 10. First Trade and Rebate Verification

**Start with spot. Do not jump into futures.**

1. Trade → Spot → BTCUSDT / ETHUSDT / SOLUSDT
2. Use a **limit order** to act as Maker (lowest fee)
3. Keep each trade at 5%–10% of your total capital
4. After filling, check the Fee column in order history (it will show **full price** — normal)
5. Open the Referral Rebate page and confirm the referrer exists and the active rate is non-zero

**What does NOT count toward rebate** (people assume it does):

- On-chain gas and withdrawal network fees
- Credit card / third-party coin purchase spreads
- Funding fee (paid between longs and shorts, not to Bybit)
- Liquidation-related fees
- P2P merchant spread
- Earn / structured products / copy-trading profit share
- The portion of API, bot, and copy-follower orders already discounted by MNT

---

## 11. Four Things to Read Before You Leverage Up

- Perpetuals have no expiry; price is pulled back to spot via **Funding Rate**
- Positive funding: longs pay shorts; negative funding: shorts pay longs; **only charged if you are holding at the settlement instant**
- BTCUSDT usually settles every **8 hours** (00:00 / 08:00 / 16:00 UTC); switches to hourly when the rate hits the cap
- Liquidation uses the **Mark Price**, not the last traded price; high leverage still blows up, and **the rebate does not hedge anything**

A 10,000 USDT position hitting 0.01% funding costs 1 USDT in real money — the rebate will not cover that.

---

## 12. Rebate Did Not Arrive? Four-Layer Check

1. Did the referral field actually show BYOFFICIAL **at the time of signup**
2. Profile → Referral Rebate — is a referrer listed
3. Is the active rebate rate **non-zero**
4. After trading, is there any rebate ledger entry

If any layer breaks:

- Within 14 days and no deposit/no trade → try the affiliate-community join
- Past 14 days or wrong code bound → official route is **KYC transfer to a new account** (once per 6 months, locks deposits/withdrawals 24–48 hours; empty the old account and close positions first)
- **Do not open a second account with the same ID** — both get flagged

---

## 13. Twelve Mistakes Beginners Make

- Submitting with the referral field blank
- Wrong country of residence, KYC dies instantly
- Registering through a VPN region hop
- Only SMS 2FA, SIM-swap hijacked
- Login password = funds password
- Treating "up to 50%" as a flat half-price on every fill
- Seeing the full-price fee and assuming the rebate is fake, quitting before settlement
- High-frequency trading to farm the rebate, losing more principal than rebate earned
- 100x leverage without understanding liquidation
- Clicking external links in P2P chat / scanning personal QR codes
- Wrong network on deposit (ERC20 vs TRC20 mix-up)
- Registering with Apple Hide My Email and losing the account after a device change

---

## 14. Seven-Day Action Plan (10–20 min/day)

| Day | Task | Time |
|---|---|---|
| Day 1 | Register via the BYOFFICIAL link, confirm the code is prefilled, check the referrer on the rebate page | 3 min |
| Day 2 | Turn on Google 2FA (write recovery codes offline) + funds password + anti-phishing code | 15 min |
| Day 3 | KYC Lv.1 (ID corners fully visible, even lighting) | 10 min + review |
| Day 4 | Add Passkey + withdrawal whitelist + new-address lock | 5 min |
| Day 5 | Small P2P deposit of 100–200 USDT to test the full flow | 10–30 min |
| Day 6 | Spot limit buy on BTCUSDT / ETHUSDT, 5%–10% of capital per order | 5 min |
| Day 7 | Turn on MNT discount (only if you hold MNT), check the rebate ledger | 5 min |

After seven days you will have three things: an account with the rebate locked in, a security setup that will not get you drained, and a fee spreadsheet you can actually reconcile.

---

## 15. Short FAQ

**Q: What is BYOFFICIAL?**
A: A Bybit referral code that establishes the rebate relationship at signup.

**Q: Do I always get 50%?**
A: No. 50% is the ceiling; the actual tier depends on the rebate center and campaign terms.

**Q: Can I add the code after registering?**
A: Official rule is no. Only a main account that bound nothing at all can join an affiliate within 14 days, and that lock is permanent too.

**Q: Does MNT conflict with the rebate?**
A: No. MNT reduces the fee first, then the rebate returns a percentage.

**Q: Do futures earn rebate?**
A: Yes, eligible futures trades count; the raw Taker rate is 0.055%.

**Q: Can I claim without KYC?**
A: No, identity verification is mandatory.

**Q: Can I open multiple accounts to farm rebate?**
A: No, one person one account; both accounts get risk-flagged.

**Q: Restricted regions?**
A: US unavailable; EEA (except Malta) routes to Bybit EU; UK allows spot and P2P only with no referral rewards; everything else is judged by the registration page.

**Q: Do sub-account trades count toward the main account rebate?**
A: The rebate is bound at the main-account level; sub-account volume normally rolls into the main account rebate, subject to the current platform rules.

**Q: Can the rebate rate drop later?**
A: The binding relationship is long-lived, but tiers can be adjusted by policy — always check the official announcement and your account page.

---

## 16. The Correct Order, In One Line

Open the BYOFFICIAL link → pick your real residence → confirm the code is prefilled → create account → immediately verify the referrer on the rebate page → Lv.1 KYC → 2FA + funds password + Passkey + anti-phishing code → small P2P deposit → spot limit micro-order → turn on MNT only if you hold MNT → reconcile the rebate ledger → only then consider futures leverage

**Referral code:** BYOFFICIAL
**Registration link:** https://partner.bybit.com/b/BYOFFICIAL
**Core benefit:** Up to 50% trading fee rebate (spot + futures)

Risk note: Crypto assets are highly volatile. The rebate is not yield and does not protect principal. Leverage, liquidation, funding, and slippage can all cause fast losses. Regional compliance and fee schedules change; depositing on the wrong network can permanently lose funds. Everything is ultimately governed by what your Bybit account displays. This article explains registration, fees, and rebate mechanics only — it is not investment advice. Decide independently according to your own risk tolerance; you bear all PnL.
