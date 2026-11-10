# The Bybit Manual: A Feature Map, and Six Doors 90% of People Never Open

Most people use about 20% of Bybit: open a position, close a position, get liquidated.
The other 80% has been sitting in the menu untouched since the day they registered.

This article doesn't teach you to tap "Next". It does something more useful —
it turns Bybit's menu into a map: what you must understand first, what's worth using, and what to stay away from.

**Bybit referral code: BYOFFICIAL**
**Registration link: https://partner.bybit.com/b/BYOFFICIAL**
Register with BYOFFICIAL for up to **50% trading fee rebate**.

---

## 1. Registration: the Only Irreversible Step in This Whole Article

Let's settle the most important thing first.

Your rebate relationship on Bybit is **bound at the moment of registration**. Once the account is created and the email is verified, that relationship is fixed. If you remember three weeks later that you "should have entered a code", there is no entry point anywhere to add it.

So registration means exactly three things, in order:

1. Enter through the registration link and confirm the referral field actually displays **BYOFFICIAL**
2. Register with a real email address (not a disposable one — you'll need it for KYC and withdrawal confirmations later)
3. Complete identity verification to the highest level in one go

On point three: Bybit's verification has tiers, and the tier determines your withdrawal limit. Plenty of people skip it at signup, then discover the problem when they try to withdraw a larger amount. Fixing it that day means waiting in a review queue. Doing it on day one costs you nothing.

**Two switches that should also be handled on registration day:**

- **Google Authenticator** — not SMS codes. SIM-swap cases never stopped happening.
- **Anti-phishing code** — once set, every genuine Bybit email carries that word. Any email without it is fake.

---

## 2. The First Task Isn't Depositing. It's Understanding Two Accounts.

This is the first and most common confusion new users hit on Bybit:

> "My money clearly went in. Why does the futures page show a zero balance?"

Because Bybit has two accounts, and money does not walk from one to the other by itself.

**Funding Account**
Deposits and withdrawals both happen here. Money arriving from your bank card, an on-chain transfer, or P2P lands in this account first.

**Unified Trading Account (UTA)**
Where you actually place orders. Spot, perpetuals, dated futures, and options all live in this single account with shared margin.

So the correct sequence of actions is:
**Deposit → lands in Funding Account → manually transfer to UTA → only then can you trade**

That internal transfer is free and instant, but it does not happen automatically. If you see "balance 0" on your first day, nine times out of ten you skipped this step — the money isn't lost.

**While we're here, the two UTA margin modes — plenty of experienced users can't explain the difference either:**

| Mode | How margin is calculated | Who it suits |
|---|---|---|
| Single-asset margin | Each coin calculated separately, PnL doesn't offset across coins | People trading one instrument who want clean accounting |
| Cross-asset margin | All assets converted into one total, margin shared | Multi-instrument traders who want capital efficiency |

Cross-asset mode uses capital more efficiently, but it also means **one losing position eats the margin behind your other positions**. Beginners should start with single-asset, and only switch once they genuinely understand how liquidation price is calculated.

---

## 3. Six Underestimated Entries

These six are the low-profile, high-value parts of the Bybit menu. Ordered by "which a beginner should use first".

### 1. Demo Trading — the one you should use first, and the one most people skip

It lives in your profile area. You get a pool of virtual funds, and the interface, order types, and liquidation calculations are identical to the live account.

Its value isn't "practice". It's **verifying at zero cost whether you can actually calculate a liquidation price**. Learning that with real money is expensive. Learning it on demo costs nothing.

Suggestion: before risking a single dollar, open ten positions on demo and hand-calculate the liquidation price on each one, then compare against the number the system shows. When they match, move to live.

### 2. Copy Trading — a tool when used well, an accelerant when used badly

The copy-trading leaderboard shows each trader's full history: ROI, maximum drawdown, average holding days, number of copiers, and assets under management.

The number that matters is **maximum drawdown**, not ROI. A trader with 300% annualized and 80% max drawdown means you will watch your account halve at the worst point — most people don't survive long enough to see the 300%.

Two things to set before copying anyone:
- A **per-trade copy limit** (as a percentage of total capital)
- A **maximum loss threshold** that stops copying

Without those two, you've handed away your brake pedal. Copy-trading capital is transferred separately from your main account — don't move everything into it.

### 3. Trading Bot (Grid / DCA) — convenient, not guaranteed

Three common bots:
- **Spot grid**: buys low and sells high inside a range; happiest in sideways markets
- **Futures grid**: a grid with leverage; earns more when ranging, bleeds faster in a trend
- **DCA bot**: buys in batches by time or by drawdown

Grid bots are the most commonly misunderstood as "passive income". Their real return structure is: **profit when ranging, stack into a losing position in a downtrend, sell out too early and miss the move in an uptrend**.
Before launching one, answer this: if price drops below the lower bound of your range, what do you do? If you don't have an answer, don't launch it.

### 4. Earn — the only correct place for idle capital

USDT sitting still earns zero. Earn offers roughly three categories:
- **Flexible savings**: withdraw anytime, low rate, no lockup
- **Fixed-term / on-chain yield**: higher rate, locked for a period and immovable
- **Dual-asset investment**: high yield, but may settle in the other currency, carrying price risk

Beginner path: touch flexible savings only. Once you can explain clearly "at what price dual-asset converts my coins", consider the rest.

### 5. P2P — lowest fees, one iron rule

P2P means buying directly from merchants with fiat, usually noticeably cheaper than card purchases.

The iron rule is one line: **leave the transfer remark blank**.
Writing "USDT", "Bitcoin", or "buy crypto" in the remark can get the merchant's receiving card frozen by their bank's risk controls. The merchant then refuses to release the coins, and your appeal fails — because those very words are printed on your payment proof.
One more baseline: only pay from an account in **your own legal name**. Never use a relative's card.

### 6. Sub-accounts + API — not for beginners, but worth knowing they exist

- **Sub-accounts**: separate books for different strategies or purposes, with isolated risk controls. Used by people running quant or multi-strategy setups
- **API keys**: connect your own program to place orders. When creating one, **tick only the permissions you need — never tick "withdrawal"**

You don't need these today. Knowing they're in the menu means you won't be stuck the day you do.

---

## 4. What the 50% Rebate Actually Consists Of

"Up to 50%" is easy to misread. Break it apart and it's simple.

**Bybit base rates (USDT perpetuals and spot):**

| Instrument | Maker | Taker |
|---|---|---|
| Perpetual futures | 0.020% | 0.055% |
| Spot | 0.010% | 0.060% |

The rebate returns a percentage of **the fee you actually paid**. Register with BYOFFICIAL for up to 50%, which means:

| Instrument | Base rate | Effective cost after rebate |
|---|---|---|
| Futures maker | 0.020% | **0.010%** |
| Futures taker | 0.055% | **0.0275%** |
| Spot maker | 0.010% | **0.005%** |
| Spot taker | 0.060% | **0.030%** |

A few things that need saying clearly:

- **The rebate does not change the fee rate displayed on your order screen.** Your fee page still shows the base rate; the rebate settles separately and arrives separately. So don't see "0.055%" and assume it didn't work
- **Rebates usually settle daily**, and every entry is visible on the rebate records page
- **"Up to 50%" depends on your tier and current campaigns** — not everyone gets the maximum. Your rebate page states the exact rate
- **The rebate only flows between you and the referrer.** It doesn't affect fund safety, withdrawals, or any permission on your account

---

## 5. Three Things Not to Touch

### 1. Jumping straight to 20x leverage as a beginner

The math of leverage is brutal: at 100x, a 1% move against you is your entire principal.
More realistically, most people aren't beaten by being wrong — they're beaten by **volatility**. Right direction, wicked through on the way.

Start at 2–3x and get comfortable calculating liquidation price. Talk about multiples once you can actually hold a profit.

### 2. Copying blindly, with no cap and no stop

The biggest risk in copy trading isn't picking the wrong trader. It's **having no brake when the pick goes wrong**.
No per-trade cap, no max-loss threshold, and one trader's losing streak drags your account straight to the bottom.

### 3. Martingale bots

Strategies that "add on every loss to average down" produce backtest curves that look almost too good.
Their real structure is: **trade a very small probability for one total wipeout**.
One trend that never comes back, and dozens of small wins are returned in a single blow — plus interest.
Don't touch it. On any platform.

---

## 6. Closing

Bybit's value isn't "you can trade futures" — every platform lets you trade futures.
Its value is in the pile of features you never opened: demo lets you fail for free, copy trading lets you borrow someone's discipline, grid bots give you something to do in a range, and Earn keeps idle money working.

And the starting point of all of it is the code you typed correctly at registration.

**Code: BYOFFICIAL**
**Link: https://partner.bybit.com/b/BYOFFICIAL**
Up to 50% fee rebate, bound at registration, not changeable afterwards.

---

## Disclaimer

This article is a platform feature overview and operating guide only. It is not investment advice. Digital asset prices are highly volatile, and futures trading involves leverage that can result in the total loss of your principal. Rates and rebate percentages quoted here may change with platform policy — always verify against Bybit's official pages. Make decisions according to your own risk tolerance, and use only funds you can afford to lose.
