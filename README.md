# Tapestry (TPR) Equity Research: Hold, $115 Target

This is a full stock pitch on Tapestry, the company behind Coach and Kate Spade. I built a three-statement model, a DCF and a peer comparison from the FY2026 10-K, then wrote a one-page research note and a pitch deck. My call is a **Hold** with a **$115** 12-month target, against a share price of $115.82 on October 8, 2026.

I picked Tapestry because I'm building a handbag brand myself, so I wanted to understand what actually drives value for a company like Coach. It's also a real debate right now: the stock fell about 30% from its August high even though the company beat earnings, and almost every analyst still rates it a Buy.

## I. The short version

Coach is doing great. Sales grew 24% in FY2026, Tapestry added about 11 million new customers (35% of them Gen Z), and handbag prices went up at a mid-teens rate, so the growth isn't coming from discounts. But at $115.82 the stock already assumes Coach keeps growing about 8% a year, every year, through FY2031. My Base case has Coach growing 5.4% a year on average, which is worth $104.60 a share.

The other big piece is interest rates. The 10-year Treasury hit 5.28% on October 7, its highest level since 2002, so my WACC comes out at 10.7%. The Street's average target of $166.50 would need a WACC under 8% in my Base case, and I can't justify that with a risk-free rate above 5%.

## II. How I built it

| Part | What I did |
|---|---|
| Historicals | Income statement, balance sheet and cash flow from the FY2026 10-K, plus the adjusted (non-GAAP) results from the August 13 earnings release |
| Projections | Five years (FY2027 to FY2031) built by brand: Coach and Kate Spade sales, then gross margin and operating margin |
| Three statements | The balance sheet balances in every year and case. Cash flow drives cash, buybacks and the share count, and EPS comes out of that |
| DCF | Unlevered free cash flow with a stub period from today to the end of FY2027. Stock-based comp is treated as a real cost, not added back |
| WACC | Cost of debt from the market price of Tapestry's own 2035 bonds, moved up by the rise in Treasury yields since June. Cost of equity from CAPM |
| Comps | Nine peers (Ralph Lauren, Capri, PVH, Levi's, LVMH, Kering, Prada, Moncler, Burberry). European peers report under IFRS 16, which adds rent back into EBITDA, so I compare on P/E and EV/EBIT instead |

## III. Cases

| | Bear | Base | Priced In | Bull |
|---|---|---|---|---|
| Coach growth | Stalls after FY2027 | About 8% fading to 4% | 7.9% every year | 9% fading to 6% |
| FY2031 operating margin | 20.5% | 24.5% | 24.5% | 26.0% |
| FY2028 EPS | $7.31 | $8.74 | $8.93 | $9.50 |
| Value per share | $73.21 | $104.60 | $115.75 | $123.66 |
| vs today's price | (36.8%) | (9.7%) | (0.1%) | 6.8% |

The Priced In case is a reverse DCF. I kept everything else from the Base case and solved for the Coach growth rate that makes the DCF equal today's price.

My Base case FY2027 numbers line up with Tapestry's own guidance: $8.45B of sales (guided $8.4B to $8.5B), $7.93 of EPS (guided $7.80 to $7.90) and $1.65B of free cash flow (guided "approaching $1.7 billion"). So I'm not more bearish than management about next year. The disagreement is about what happens after.

## IV. What I found

**The price already assumes the good news continues.** Coach grew 15% in Q4 against 24% for the full year, and FY2027 guidance implies about 8% for Coach, including an extra 53rd week. Paying $115.82 means believing that pace holds for five years straight.

**Rates matter more than people are giving them credit for.** Moving the WACC by one point either way moves my Base case from $92 to $121. Most of the bull case on the Street looks like it was built in a lower-rate world.

**Tapestry is really one brand now.** Coach is 86.5% of sales and earned a 36.8% segment margin, while Kate Spade lost money and closed stores (360 down to 326). China grew 32% and is now 17.5% of sales. That's great while it lasts, but it concentrates the risk.

**The strongest part of the bull case is cash.** Tapestry plans to return $1.7B in FY2027 through buybacks and a dividend raised 16%, about 7% of its market cap. That's why I don't think it's a Sell either.

**What would change my mind:** Coach growing 8% or more after FY2027 (Bull case $124), or rates falling enough to bring the WACC near 9.5% (Base case about $125). The first real test is Q1 FY2027 earnings in early November.

## V. Limitations

- Projections are on Tapestry's adjusted basis and assume no more one-time charges or tariff refunds.
- Rent stays in operating costs, so lease liabilities are left out of the DCF on purpose. The comps use EV with leases, to match the data source.
- Peer multiples come from one data source, on dates between September 29 and October 8, 2026.
- The beta (1.43) covers years when Tapestry was trying to buy Capri, which may make the stock look riskier than it is now. The Sensitivity sheet shows what a lower WACC does.

## VI. Sources

- Tapestry FY2026 Form 10-K: https://www.sec.gov/Archives/edgar/data/0001116132/000111613226000018/tpr-20260627.htm
- Tapestry Q4 FY2026 earnings release (Aug 13, 2026): https://www.sec.gov/Archives/edgar/data/0001116132/000114036126032624/ef20079840_ex99-1.htm
- Tapestry notes pricing term sheet (Dec 4, 2024): https://www.sec.gov/Archives/edgar/data/1116132/000114036124048369/ny20039258x2_fwp.htm
- U.S. Treasury daily par yield curve: https://home.treasury.gov/resource-center/data-chart-center/interest-rates/TextView?type=daily_treasury_yield_curve
- Share price, beta, peer multiples and consensus target: https://stockanalysis.com/stocks/tpr/
- Analyst target range: https://www.marketbeat.com/articles/coachs-momentum-powers-tapestry-despite-the-stocks-sharp-pullback/
- Damodaran implied equity risk premium, January 2026: https://bvresources.com/articles/bvwire/damodaran-posts-his-first-data-update-for-2026
- 10-year Treasury at a 24-year high: https://www.forbes.com/sites/garthfriesen/2026/10/07/why-the-10-year-treasury-yield-just-hit-a-24-year-high/

## Files

- `Tapestry_Valuation_Model.xlsx`: Instructions, Summary, Inputs, one sheet per case (Base, Bull, Bear, Priced In), WACC, Comps, Sensitivity, Historicals and Market Data
- `Tapestry_Research_Note.pdf`: one-page research note
- `Tapestry_Pitch_Deck.pdf`: the pitch deck

*Student research for educational purposes, not investment advice.*
