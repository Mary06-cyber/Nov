# I Walked a Total Beginner Through OKX in 90 Minutes: The Full Log, and the 7 Pitfalls He Hit

Tutorials have one chronic flaw: they read like manuals, yet people still get stuck following them.
Because a manual never tells you "where exactly a person's attention drifts".

So I took a friend who had never touched an exchange (call him K) through OKX,
from opening the signup page to completing his first trade, with a stopwatch running. What follows is the real log of those 90 minutes —
including where he stalled, what he nearly got wrong, and the things I only thought to warn him about afterwards.

**OKX referral code: OKOFFICIALLY**
**Registration link: https://www.okx.com/join/OKOFFICIALLY**
Register with OKOFFICIALLY for up to **20% trading fee rebate**.

---

## 00:00–00:10 · The Signup Page: We Nearly Lost It in the First Minute

K opened the link. I stopped him before he typed anything, told him to scroll to the top of the page and find the referral field.

**Pit #1: Submitting without confirming the referral field.**
The signup form may auto-fill the referral code or leave it blank — it depends on how you entered. On K's page the field was empty, and he hadn't noticed at all. Had he typed his phone number and hit next, this account would be permanently cut off from the rebate.

Only after confirming **OKOFFICIALLY** was fully in the field (match the complete code, not just the first few characters) did we move on: phone number, SMS code, password.

> The lesson: the first thing you do on the signup page is not fill in information. It's verifying the referral code. This is the only irreversible step in the entire process.

## 00:10–00:25 · KYC: He Only Wanted the Lowest Tier

During identity verification, OKX splits it into tiers. K saw that basic verification was enough and wanted to skip the advanced tier.

**Pit #2: Stopping KYC at Lv.1.**
I stopped him. Lv.1 comes with very limited withdrawal amounts and feature scope. Go back to complete advanced verification when you actually need to withdraw a real amount, and your documents join a review queue. Spending five extra minutes then to finish Lv.2 (ID document + facial check) resolved every limit question in one shot.

Three rules for document photos: even lighting, all four corners visible, name matching the registration info exactly. K's first photo had glare; one retake and it passed.

## 00:25–00:40 · Security: He Said "I Won't Need This"

This was the segment he resisted most, and the one where I was least flexible.

**Pit #3: Treating SMS codes as the only line of defense.**
I set him up with three things:

1. **Google Authenticator** (two-factor) — SMS codes can be bypassed through SIM-swap attacks; authenticator apps can't
2. **Anti-phishing code** — once set, every official OKX email carries that word. No word, delete the email
3. **Withdrawal address whitelist** — withdrawals only to pre-saved addresses, new addresses enter a cooldown period. This is the last line of "even if the account is stolen, the money can't leave"

He muttered something about it being excessive. My answer: these three switches take under ten minutes combined, and they mean that even after a successful phishing attack, the money stays put. That trade never loses.

## 00:40–00:55 · Depositing: The Most Dangerous Three Minutes Live Here

Time to fund the account. I gave him three routes; he picked on-chain deposit.

**Pit #4: Choosing the wrong deposit network.**
This is the most dangerous step of the whole process. He was withdrawing USDT from another platform, and I watched over his shoulder as he copied the address — an OKX USDT address on TRC20 looks nothing like one on ERC20. The sending platform must select **the same network**. Mismatch the two, and the money lands at an address neither platform controls. It is essentially unrecoverable.

The rule is one line: **copy the address from the app, manually confirm both sides show the same network, and never pick whatever "looks familiar".**

We also compared the three deposit routes while we were there — each has its use case:

| Method | Cost | Best for |
|---|---|---|
| P2P purchase | Usually the cheapest | Larger amounts, not urgent |
| On-chain deposit | Depends on network; TRC20/OKTC are cheap | Transferring from another wallet or platform |
| Express buy (card / third-party payment) | The most expensive | Small amounts, convenience first |

## 00:55–01:10 · Demo Trading: He Thought It Was for Kids

Money in. K wanted to open a position immediately. I held him back and took him into **Demo Trading** first.

**Pit #5: Skipping demo and going straight to live funds.**
OKX's demo account grants a pool of virtual funds; the order interface, contract parameters, and liquidation calculations are identical to live. In fifteen minutes he did three things:

- Opened a long, hand-calculated the liquidation price, and checked it against the number the system displayed
- Got startled by the fill price of a market order (see Pit #6)
- Discovered, the moment fees were deducted from his balance on closing, that "fee rate" is a living number

Those fifteen minutes on demo cost zero. On live, every one of those lessons is paid in real money.

**Pit #6: Market order slippage.**
His first demo trade was a market order, and the fill price was noticeably worse than the order book he'd seen when clicking. That's not an OKX flaw — it's the natural property of market orders in every market. From then on I drilled in one habit: if it's not urgent, use a limit order and wait for the fill. Limit orders have a bonus: OKX's futures maker rate is far below the taker rate — we'll do that math shortly.

## 01:10–01:25 · The First Live Trade: Limit Order, Small Size, Spot

Out of the demo account, his first live trade was deliberately boring: spot, limit order, a small BTC buy.

The order filled after four minutes of waiting. Then I took him to look at two numbers:

1. **The fee in the order details** — spot rates are 0.10% taker / 0.08% maker; his limit order was charged as maker
2. **The rebate records page** — confirming the account really is registered under OKOFFICIALLY and the rebate relationship is live

I insisted on doing #2 on the spot. Rebates generally settle on a cycle after trades, and the fee page still shows the base rate (0.10%, 0.08%) — the rebate comes back separately. If you never personally visit the rebate page, you'll spend months believing you're not receiving it.

## 01:25–01:30 · The Last Switch: OKB Fee Deduction

**Pit #7: The OKB deduction switch was never turned on.**
This is the highest-return single action on OKX: hold a small amount of OKB, enable "pay fees with OKB", and spot and futures fees get discounted directly — the rate drops from the 0.10%/0.08% tier to the 0.09%/0.072% tier... wait, let me state it cleanly in the table.

With the 20% rebate stacked on top, the actual cost looks like this:

| Instrument | Base rate | After OKB deduction | With 20% rebate on top |
|---|---|---|---|
| Spot maker | 0.080% | 0.072% | **0.0576%** |
| Spot taker | 0.100% | 0.090% | **0.072%** |
| Futures maker | 0.020% | — | **0.016%** |
| Futures taker | 0.050% | — | **0.040%** |

(OKB deduction mainly applies to spot rate tiers; the exact tier depends on the live page in the app.)

K bought a small amount of OKB and flipped the switch. From that moment, every trade he makes is billed at the right-hand column of that table.

---

## 90 Minutes Up: The Complete List of 7 Pitfalls

1. **Submitting without confirming the referral field** — irreversible; the rebate is gone for good
2. **Stopping KYC at Lv.1** — limits frozen; going back means a queue
3. **SMS as the only defense** — SIM-swap never went away; two-factor is mandatory
4. **Not verifying the deposit network** — funds on the wrong chain are basically gone; the most dangerous three minutes of the day
5. **Skipping demo** — liquidation price, slippage, and fees all learned with real money
6. **Market order slippage** — limit orders when it's not urgent, and they're cheaper too
7. **OKB deduction left off** — one switch, a permanent fee reduction

Of the seven, the first four are irreversible or high-danger; the last three are the "you don't know, so you keep paying" kind. During those 90 minutes he only came close to hitting the first four — the last three I added on his behalf.

## One Line to Close

Exchanges aren't hard. What's hard is having no one beside you to say "pause" during the three minutes that matter.
Enter the right code, finish full KYC, enable two-factor, verify the network, practice on demo first, use limit orders when it's not urgent, turn on OKB deduction —
seven actions, 90 minutes, done once.

**Code: OKOFFICIALLY**
**Link: https://www.okx.com/join/OKOFFICIALLY**
Up to 20% trading fee rebate, bound at registration, not changeable afterwards.

---

## Disclaimer

This article is a personal operating log and platform feature walkthrough, not investment advice. Digital asset prices are highly volatile, and futures trading involves leverage that can result in the total loss of principal. Fee rates, discounts, and rebate percentages mentioned here may change with platform policy — always refer to OKX's official pages for live figures. Make decisions according to your own risk tolerance and use only funds you can afford to lose.
