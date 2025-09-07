# Commodities

## 🛢️ Commodities Derivatives Product Types

| Name                      | Description                                                                 | OTC/Exchange         | Optionality (Y/N) | Example                                      | Specific Details                         |
|---------------------------|-----------------------------------------------------------------------------|-----------------------|-------------------|----------------------------------------------|------------------------------------------|
| Futures                   | Standardized contracts to buy/sell a commodity at a future date/price.      | Exchange              | N                 | Crude Oil Futures (NYMEX: CL)                | 1,000 barrels of WTI Crude per contract   |
| Options on Futures        | Right, not obligation, to enter a futures contract.                         | Exchange              | Y                 | WTI Crude Oil Call Option                    | Strike $80, Expiry Jan 2026               |
| Swaps                     | Exchange of cash flows based on commodity price.                            | OTC                   | N                 | Fixed-for-floating natural gas swap          | Notional: 10,000 MMBtu/month              |
| Commodity Options         | Vanilla options on commodity prices.                                        | OTC / Exchange        | Y                 | Call option on Gold                          | 100 oz Gold, Strike $2,000                |
| Forwards                  | Custom contracts to buy/sell at future date.                                | OTC                   | N                 | Forward contract for physical copper         | 25 metric tons of copper, settle in 3M    |
| Structured Products       | Custom derivatives with embedded optionality.                               | OTC                   | Y                 | Asian Barrier Option on Brent Crude          | Notional: $1 million, Knock-in at $85     |
| Spread Contracts          | Based on price differences (e.g., time/location).                           | Exchange / OTC        | N                 | Brent-WTI crude spread futures               | 1,000 barrels each leg, monthly expiry    |
| Index Derivatives         | Based on commodity indices (e.g., energy, ags).                             | Exchange / OTC        | N or Y (varies)   | Futures on S&P GSCI Energy Index             | Exposure to diversified energy basket     |
| Swaptions                 | Option to enter into a commodity swap.                                      | OTC                   | Y                 | Swaption on a natural gas swap               | Notional: 5,000 MMBtu/day, 6-month tenor  |
| Calendar Spread Options   | Options on price spread between two contracts.                              | Exchange / OTC        | Y                 | Option on Dec/Jan WTI spread                 | Dec vs Jan futures, 1,000 barrels         |
| Asian Options             | Option with payoff based on average price.                                  | OTC                   | Y                 | Asian option on Jet Fuel                     | Avg of monthly prices, Notional $500k     |
| Weather Derivatives       | Hedge against weather variables (e.g. HDD, rainfall).                       | OTC                   | Y                 | Heating Degree Day (HDD) swap                | $10,000 per HDD above threshold in NY     |

## Commodity Option pricing
Option Price = Intrinsic Value + Time Value

## Key Inputs Into Option Pricing

| Input                | Description                                                              | Effect on Option Price                  |
|----------------------|--------------------------------------------------------------------------|------------------------------------------|
| **Underlying Price** | Current market price of the commodity or asset                           | Call ↑ with asset ↑, Put ↑ with asset ↓  |
| **Strike Price**     | Agreed price to buy/sell the asset                                       | Affects intrinsic value                  |
| **Time to Expiry**   | Time remaining until the option expires                                  | More time = higher premium               |
| **Volatility**       | Expected price fluctuation of the underlying asset                       | More volatility = higher premium         |
| **Risk-Free Rate**   | Interest rate used to discount future cash flows                         | Small impact, mostly on long-dated options |
| **Dividends/Yield**  | Expected payouts from the asset (e.g., storage costs, carry costs)       | Affects value, mostly in equity/commodities |
| **Option Type**      | Whether it's a Call or Put                                               | Affects how price movement impacts value |
| **Settlement Type**  | Physical or cash settlement                                               | Operational effect, not price itself     |

