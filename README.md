# OKX spot fees: Maker and taker rates, VIP tiers, fee calculation, and ways to reduce trading costs

When people search for **OKX spot fees**, they usually want a straightforward answer: how much does OKX charge when buying or selling crypto, whether limit orders are cheaper than market orders, and what it takes to qualify for lower rates.

The short version is that OKX uses a tiered maker-and-taker fee model. Your rate depends on your account tier, recent trading volume, asset balance, trading pair, and jurisdiction. A regular U.S. account on standard spot pairs may pay **0.200% maker and 0.350% taker**, while higher VIP tiers can receive much lower rates, including negative maker fees at the top levels.

This guide explains how OKX spot fees work, how the fee is calculated, what “maker” and “taker” actually mean, and which details matter before placing an order.

> **Important:** OKX fee schedules are jurisdiction-specific. The main table below uses the current U.S. spot fee framework published by OKX. Your actual rate may differ if your account is registered in another region or if the trading pair belongs to a different fee group.

## OKX spot fees at a glance

OKX charges a trading fee when a spot order is filled. The fee is based on:

- Your maker or taker status
- Your OKX fee tier
- The amount of crypto bought or sold
- The specific spot pair
- Whether the pair has a special or zero-fee schedule

For ordinary order-book trading, the basic formula is:

text
Trading fee = fee rate × filled trading amount


For example, if your taker fee is 0.350% and you buy $1,000 worth of crypto, the trading fee is approximately $3.50 before considering the exact fill amount and currency used to collect the fee.

The fee is charged when the trade executes. Simply holding crypto, placing an order that remains unfilled, or cancelling an unfilled order does not create a spot trading fee.

## Current OKX spot fee tiers

The following table covers the regular account and VIP 1 through VIP 9 levels listed in the current U.S. fee framework. A user can qualify through either the required asset balance or 30-day trading volume, depending on the applicable OKX rules.

| OKX tier | Asset balance requirement | 30-day trading volume | Maker fee | Taker fee | Purchase link |
| --- | ---: | ---: | ---: | ---: | --- |
| Regular user | $0–$20,000 | $0–$100,000 | 0.200% | 0.350% | [ Open OKX with the invite link](https://okx.com/join/CASH20) |
| VIP 1 | $20,001–$25,000 | $100,001–$250,000 | 0.100% | 0.200% | [ Check OKX spot trading access](https://okx.com/join/CASH20) |
| VIP 2 | $25,001–$50,000 | $250,001–$500,000 | 0.075% | 0.150% | [ Join OKX and review your fee tier](https://okx.com/join/CASH20) |
| VIP 3 | $50,001–$100,000 | $500,001–$1,000,000 | 0.060% | 0.125% | [ Start trading on OKX](https://okx.com/join/CASH20) |
| VIP 4 | $100,001–$250,000 | $1,000,001–$2,500,000 | 0.050% | 0.100% | [ View OKX trading options](https://okx.com/join/CASH20) |
| VIP 5 | $250,001–$500,000 | $2,500,001–$5,000,000 | 0.045% | 0.080% | [ Access OKX spot markets](https://okx.com/join/CASH20) |
| VIP 6 | $500,001–$1,000,000 | $5,000,001–$10,000,000 | 0.040% | 0.070% | [ Open an OKX trading account](https://okx.com/join/CASH20) |
| VIP 7 | $1,000,001–$2,000,000 | $10,000,001–$20,000,000 | 0.025% | 0.040% | [ Review OKX VIP trading access](https://okx.com/join/CASH20) |
| VIP 8 | $2,000,001–$5,000,000 | $20,000,001–$50,000,000 | 0.010% | 0.035% | [ Trade spot crypto on OKX](https://okx.com/join/CASH20) |
| VIP 9 | $5,000,001 or more | $50,000,001 or more | 0.000% | 0.030% | [ Join OKX through the available invite](https://okx.com/join/CASH20) |

The published U.S. schedule also lists separate zero-fee-pair treatment. Standard rates should not be assumed to apply identically to every asset or market. OKX notes that its symbol groups and fee rates can be reviewed and changed, so the rate shown inside your logged-in account is the one to use before trading.

## What is a maker fee?

A maker order adds liquidity to the order book. In practical terms, your order is placed on the book and waits until another trader matches it.

A typical example is a limit order placed below the current market price when buying. If the order does not execute immediately and later matches with another order, it may be treated as a maker trade.

Maker fees are usually lower than taker fees because the order contributes liquidity to the market. At higher OKX VIP levels, maker fees can reach 0% or become negative. A negative maker fee means the fee schedule may provide a rebate on eligible maker volume rather than charging a positive commission. The exact treatment depends on the account, pair, and applicable fee group.

Using the regular U.S. rates as an example:

- A $1,000 maker trade at 0.200% costs about $2.00.
- A $1,000 taker trade at 0.350% costs about $3.50.

That difference looks small on one trade. It becomes more noticeable when you trade frequently or turn over a larger position.

## What is a taker fee?

A taker order executes against liquidity that is already available on the order book. Market orders are normally taker orders because they are designed to fill immediately at the best available prices.

A limit order can also be charged the taker rate. The order type alone does not determine the fee. If a limit order immediately matches an existing order, it may be classified as taker. If it rests on the order book and is filled later, it may be classified as maker.

This is one of the most common sources of confusion around OKX spot fees. Many traders assume that every limit order receives the lower maker rate. That is not how the system works. The execution behavior matters.

Before submitting an order, check the maker and taker rates shown in the order panel. After execution, you can confirm the exact amount and fee currency in your order history.

## How OKX calculates a spot trading fee

For spot and margin trading, OKX states that the fee is calculated using the rate multiplied by the amount of crypto bought or sold when the order fills.

Suppose your account has these rates:

- Maker: 0.200%
- Taker: 0.350%

### Buying crypto

If you buy 0.1 BTC and the order value is $6,000:

- Maker fee: $6,000 × 0.200% = $12
- Taker fee: $6,000 × 0.350% = $21

When buying through the order book, the fee may be deducted from the crypto you receive. That means the amount credited to your account can be slightly lower than the amount shown in the order size.

### Selling crypto

If you sell crypto for $6,000:

- Maker fee: $6,000 × 0.200% = $12
- Taker fee: $6,000 × 0.350% = $21

For a sale, the fee is generally reflected in the proceeds. The exact fee currency depends on the trade direction, product, and fill details, so the transaction record is more reliable than trying to infer the deduction from the order screen.

### Partial fills

An order can be filled in several parts. Some fills may receive different execution treatment depending on how they match against the order book. The final fee is therefore based on the actual fills, not simply the original order size or the price you first saw.

That matters especially in volatile or thin markets. The quoted fee rate may be clear, but the final cost can still differ slightly because the order filled at multiple prices or in multiple pieces.

## How to check your personal OKX spot fee rate

The public fee page is useful for understanding the structure, but the rate that matters is the one attached to your account and trading pair.

On the OKX website, the fee information can be checked through the account area under **Assets** and **My trading fees**. In the app, OKX directs users to the profile or account settings area to view the trading fee tier.

You can also check the order placement panel for a particular spot pair. OKX says the panel displays the maker and taker fee rate that currently applies to your account for that pair. This is important because a fee rate shown while logged out may not represent your actual tier.

A practical checking routine looks like this:

1. Log in to your OKX account.
2. Open the spot market you want to trade.
3. Check the displayed maker and taker rates in the order panel.
4. Confirm whether the pair belongs to a special fee group.
5. Place a small test order if you need to verify the execution behavior.
6. Review the completed fill in order history.

The last step is useful because it shows whether the trade was charged as maker or taker and which currency was used for the fee.

## Does a limit order always have a lower fee?

No.

A limit order only specifies the maximum price you are willing to pay or the minimum price you are willing to accept. It does not guarantee that the order will rest on the book.

A limit buy order placed above the best available sell price can execute immediately. In that case, it may be treated as a taker order. A limit sell order placed below the best available buy price can behave similarly.

To improve the chance of receiving the maker rate, the order generally needs to add liquidity rather than immediately match existing orders. Even then, market conditions can change quickly, and the final classification should be confirmed in the fill details.

This is why “use limit orders to lower OKX spot fees” is incomplete advice. The more accurate version is: **use orders that actually add liquidity, and verify the execution classification afterward.**

## Spot fees versus Convert and Buy/Sell pricing

OKX spot order-book fees should not be confused with the cost of using Convert or an express Buy/Sell flow.

For order-book spot trading, you normally see a separate maker or taker fee. For Convert or certain direct purchase flows, OKX may present an all-in quote instead of a separate trading commission. The cost can be reflected in the quoted conversion rate or spread.

That creates two different ways to evaluate cost:

- **Order book:** Compare the execution price plus the maker or taker fee.
- **Convert or instant purchase:** Compare the quoted buy and sell prices, including the spread.

A screen that says “zero trading fee” does not automatically mean the transaction has no cost. The quote may still differ from the broader market price. For serious spot traders, the order book is usually easier to analyze because the execution price and fee are shown separately.

## Do zero-fee pairs count toward VIP qualification?

Not necessarily.

OKX states that some spot pairs with both maker and taker fees at 0% may be excluded from the 30-day spot trading volume calculation. That means zero-fee volume may not always help you move toward a higher tier.

This detail matters for traders who choose a pair mainly because it advertises zero trading fees. If your goal is to qualify for VIP status, check whether that pair contributes to the relevant volume calculation.

Zero-fee campaigns can also have their own conditions, eligible products, and expiry dates. A pair that is free today may later move into a different fee group. Checking the live fee information in your account is more dependable than relying on an old comparison article.

## How OKX VIP tiers reduce spot trading costs

OKX uses a tiered structure. The tier can be influenced by:

- Total eligible asset balance
- 30-day trading volume
- Product-specific trading activity
- Account and jurisdiction rules

OKX says the account’s tier is reviewed based on recent activity and asset holdings, and different products can have different fee schedules.

For most casual traders, the main question is not whether VIP 9 exists. It is whether the next tier is realistic and whether the potential savings justify changing trading behavior.

For example, moving from the regular U.S. rate to VIP 1 changes the published standard spot rates from:

- Maker: 0.200% to 0.100%
- Taker: 0.350% to 0.200%

On $10,000 of taker volume, that difference is approximately $15 per side. On $100,000 of monthly volume, the difference becomes more meaningful. Still, trading more purely to reach a lower fee tier can create more market risk than it saves in commissions.

Fee savings should be a result of trading activity you already intend to perform, not a reason to manufacture unnecessary trades.

## How to reduce your OKX spot fees

There are several practical ways to keep costs under control.

### Check the pair before placing the order

Do not assume that BTC/USDT, stablecoin pairs, and smaller altcoin pairs use the same rate. OKX organizes instruments into fee groups, and special pair schedules may apply.

### Avoid accidental taker execution

If reducing fees is more important than immediate execution, review the order book and use a price that allows the order to rest. A limit order that executes immediately may still be charged the taker rate.

### Compare the full cost, not only the headline fee

A lower commission does not compensate for a poor fill, wide spread, or slippage. The relevant calculation is:

text
Total trading cost = trading fee + spread + slippage


For liquid pairs, the fee may be the largest visible cost. For less liquid assets, spread and slippage can dominate.

### Review your actual fills

The order history shows what happened, not what you intended to happen. Check whether the order was filled as maker or taker and whether the fee was deducted in the purchased asset or sale proceeds.

### Use the invitation link when opening an account

The supplied invite link is associated with the code **CASH20** and advertises a 20% rebate. Eligibility, region, campaign rules, and the final rebate terms should be confirmed during registration because referral benefits can vary by account and market.

[👉 Open OKX with the CASH20 invite link](https://okx.com/join/CASH20)

### Consider VIP status matching if you already qualify elsewhere

OKX has published information about VIP status matching for eligible users who can provide evidence of trading volume or assets held on another exchange. The available benefit depends on the region and review outcome, but this can be more efficient than building volume from scratch.

## Are OKX spot fees competitive?

The answer depends on which fee schedule applies to your account.

For a standard U.S. account, the published 0.200% maker and 0.350% taker rates are materially different from the standard rates shown in some other OKX jurisdictions. OKX’s European schedule, for example, uses a separate regional framework, and the rate can also depend on whether the user has opened a derivatives account.

The important comparison is therefore not simply “OKX versus another exchange.” You should compare:

- Your local OKX regular rate
- The fee for your preferred trading pair
- Your expected maker-to-taker ratio
- Deposit and withdrawal costs
- Spread and liquidity
- Whether referral or promotional benefits apply
- Whether your volume qualifies for a lower tier

A platform with a lower headline taker rate may still be more expensive for a particular trade if its spread is wider or liquidity is thinner.

## Common questions about OKX spot fees

### Does OKX charge a fee for holding crypto?

No spot trading fee is charged merely because you hold crypto in your account. The trading fee applies when a buy or sell order is filled.

### Are cancelled orders charged?

An order that is cancelled before any portion is filled generally does not create a trading fee. If part of the order already filled, the completed portion can still incur a fee.

### Is a market order always charged the taker fee?

Market orders usually execute against existing order-book liquidity, so they are normally charged the taker rate. The fee is based on the actual execution.

### Can a limit order be charged the taker fee?

Yes. A limit order that immediately matches an existing order can be treated as taker. The order type does not guarantee maker treatment.

### Does OKX charge a funding fee on spot trades?

Funding fees belong to perpetual futures and similar derivatives products. They are separate from ordinary spot trading fees.

### Where can I see the exact fee after a trade?

Open your order history and view the details for the completed fill. OKX provides the applied fee amount and related calculation information there.

## Final assessment

OKX spot fees are built around a tiered maker-and-taker system rather than one universal commission. For a regular U.S. account, the published standard rates are **0.200% maker and 0.350% taker**, while VIP levels reduce those rates progressively. High-volume tiers can reach 0% maker fees or negative maker rates, but those thresholds are far beyond what most occasional traders will reach.

For everyday users, the biggest practical steps are simple:

- Check the fee shown for your own account and pair.
- Understand whether your order is likely to execute as maker or taker.
- Include spread and slippage when comparing costs.
- Do not assume every limit order receives the maker rate.
- Review the completed fill instead of relying only on the order preview.
- Confirm regional restrictions and referral conditions before opening an account.

[👉 Start with OKX and check the available CASH20 offer](https://okx.com/join/CASH20)
