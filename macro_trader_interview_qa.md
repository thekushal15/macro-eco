# Macro Trader: Interview Concepts, Questions and Answers

Study material for macro and rates trading interviews, organised by experience level. Answers are written from a practitioner's perspective. They are not trading advice. Verify market levels, policy settings and historical details against current primary sources.

**Structure:** Each level has six categories: (1) Instruments and pricing, (2) Macro and policy, (3) Funding and plumbing, (4) Volatility and convexity, (5) Risk and portfolio construction, (6) Positioning, flows and execution.

**Level mapping (synthesised from job postings, not an industry standard):**

| Level | Typical title | Experience |
|---|---|---|
| Fresher | Analyst, intern | 0–1 yr |
| 2 yr | Junior analyst / trader | 1–3 yrs |
| 5 yr | Senior trader / associate PM | 3–6 yrs |
| 7 yr (VP) | VP / PM track | 6–9 yrs |
| 10 yr (ED) | Executive Director | 9–12 yrs |
| 15 yr (MD) | Managing Director / capital-allocating PM | 13–18 yrs |
| 20 yr+ (Expert) | Senior PM / CIO / allocator | 20+ yrs |

---

## Level 1: Fresher (0–1 yr)

### Instruments and pricing

**Q1. How does a bond's price move relative to its yield?**
A. Inversely. Price is the present value of cash flows discounted at the yield, so higher yields mean lower prices. The relationship is convex, so price gains from a yield fall are larger than losses from an equal rise.

**Q2. What does duration measure, and what is DV01 on a 10-year Treasury?**
A. Duration is the approximate percentage price change for a 1% yield change. DV01 is the dollar change for a 1 bp move, calculated as modified duration × price × 0.0001. A 10-year with modified duration near 8 has a DV01 of about $800 per $1 million face.

**Q3. What is the difference between spot and forward FX, and what are forward points?**
A. Spot settles in about two business days. A forward is an agreed rate for a future date. Forward points are the forward-minus-spot difference in pips, set by the interest rate differential, so the higher-yielding currency trades at a forward discount.

**Q4. What do contango and backwardation mean for a crude oil future?**
A. Contango means futures are above spot, typically when storage is plentiful. Backwardation means spot is above futures, signalling physical tightness. Long positions earn positive roll yield in backwardation and negative roll yield in contango.

**Q5. What is an interest rate swap, and why would a corporate use one?**
A. A swap exchanges fixed payments for floating payments on a notional amount, with no principal exchanged. A company with floating-rate debt that wants certainty can pay fixed and receive floating.

### Macro and policy

**Q6. What does CPI measure, and why does core inflation get more attention?**
A. CPI tracks the price change of a fixed consumer basket. Core excludes food and energy, which are volatile, so it better shows underlying inflation pressure.

**Q7. How does the Fed's dual mandate shape rate expectations?**
A. The Fed targets maximum employment and stable prices. Inflation above target pushes toward tightening, and a weakening labour market pushes toward easing. Traders price this through fed funds futures and OIS.

**Q8. What usually happens to yields and the dollar when growth surprises to the upside?**
A. Yields tend to rise as the expected policy path is revised up, and the dollar often firms against lower-yielding currencies. The response depends on whether inflation is the main concern.

**Q9. What does an inverted yield curve signal?**
A. Short rates above long rates, meaning the market expects future cuts. It has preceded recessions historically, but its timing record is poor.

**Q10. Why does a stronger US dollar typically pressure emerging market assets?**
A. Many EM governments and companies borrow in dollars, so a stronger dollar raises the local-currency cost of debt service. It can also trigger capital outflows.

### Funding and plumbing

**Q11. What is SOFR, and how does it differ from LIBOR?**
A. SOFR is the overnight secured rate based on Treasury repo transactions. LIBOR was an unsecured rate partly based on bank estimates. SOFR is transaction-based and carries no bank credit component.

**Q12. What is a repo trade?**
A. A sale of securities with an agreement to buy them back at a higher price later. Economically it is a collateralised loan, and the price difference sets the repo rate.

**Q13. What does the Fed funds rate target?**
A. The overnight unsecured interbank lending rate. The FOMC sets a target range, and the Fed steers the effective rate with its administered tools.

**Q14. What is covered interest rate parity?**
A. The forward rate adjusts so that a hedged investment earns the same return in any currency. Persistent deviations are measured as the cross-currency basis.

**Q15. What is a basis point, and why does it matter in carry trades?**
A. One hundredth of a percentage point. Carry is quoted in basis points and compared with the expected currency move, which is the real risk.

### Volatility and convexity

**Q16. What is the difference between implied and realised volatility?**
A. Implied is the volatility priced into options today. Realised is what the asset actually did. The gap is the volatility risk premium, a key source of return for option sellers.

**Q17. What are the payoffs of a call and a put?**
A. A call pays the amount by which the underlying exceeds the strike, floored at zero. A put pays the amount by which the strike exceeds the underlying, floored at zero.

**Q18. What is delta?**
A. The sensitivity of an option's price to a small move in the underlying. Call deltas run from 0 to 1, put deltas from −1 to 0.

**Q19. What is a straddle used for?**
A. A long call and long put at the same strike and expiry. It profits from a large move either way, and expresses a view that volatility will exceed what is priced.

**Q20. What is a swaption?**
A. An option to enter an interest rate swap at a set fixed rate on a future date. A payer swaption gains when rates rise.

### Risk and portfolio construction

**Q21. What is a stop loss, and how would you set one?**
A. A predetermined exit to cap losses. It should be set where the trade thesis is invalidated, not from an arbitrary pain threshold.

**Q22. What is Value at Risk, and what are its main limitations?**
A. The loss not exceeded over a horizon at a given confidence level. It understates tail losses and says nothing about the size of losses beyond the threshold.

**Q23. What is correlation, and why does it matter across positions?**
A. It measures how two positions move together. Trades that look diversified can share one macro driver.

**Q24. How would you size a position against a risk budget?**
A. Start from the loss you accept if the stop is hit, divide by the distance to the stop in price terms, and scale by the instrument's volatility.

**Q25. How do gross and net exposure differ?**
A. Gross is the sum of absolute long and short positions. Net is longs minus shorts. A book can be net flat but grossly leveraged.

### Positioning, flows and execution

**Q26. What drives a bid-offer spread?**
A. Inventory risk, adverse selection and processing costs. It widens in volatile markets, in less liquid instruments, and when the counterparty is uncertain.

**Q27. What is the difference between a market order and a limit order?**
A. A market order executes now at the best available price, with certainty of execution but not price. A limit order guarantees price but not execution.

**Q28. What does open interest tell you about a futures market?**
A. Rising open interest with rising prices suggests new money entering. Falling open interest suggests positions are closing.

**Q29. What is the CFTC Commitment of Traders report?**
A. A weekly report of aggregated futures positions by trader category. Used to gauge crowding, with a publication lag.

**Q30. Why keep a trade journal, and what should it contain?**
A. Record the thesis, entry, stop, target and reasons before the outcome is known. Reviewing it shows whether losses came from bad ideas, sizing or execution.

---

## Level 2: 2 Years

### Instruments and pricing

**Q1. How would you price a 2s10s Treasury butterfly and explain the trade?**
A. A view on curvature: long or short the 2-year and 10-year against the 5-year, DV01-neutral. Judge whether the middle point is cheap or rich relative to its neighbours.

**Q2. What is convexity, and why does it matter for a long bond position?**
A. The curvature of the price–yield relationship. Positive convexity gains more from a yield fall than it loses from an equal rise, which matters for large moves.

**Q3. How does a cross-currency basis swap work?**
A. Floating payments are exchanged in two currencies with principal exchanged at start and end. The spread on one leg is the basis, reflecting the cost of synthetic funding.

**Q4. Given two spot rates on a curve, how do you derive the forward rate?**
A. With annual compounding, the forward from year one to year two is (1+r₂)²/(1+r₁) − 1. For precision, use discount factors.

**Q5. What drives the gap between on-the-run and off-the-run Treasuries?**
A. On-the-run issues are more liquid and trade rich. Off-the-run issues carry a liquidity premium that widens in stress.

### Macro and policy

**Q6. What does the Taylor rule say, and where does it break down?**
A. It sets the policy rate from the neutral rate, inflation versus target, and the output gap. It breaks down when the neutral rate is unknown, the output gap is poorly measured, and supply shocks dominate.

**Q7. How would you judge whether the Fed is behind the curve?**
A. Compare the policy rate with a Taylor-style estimate, watch inflation expectations and wages, and check whether the market prices moves the Fed is not delivering.

**Q8. How do terms of trade affect a commodity exporter's currency?**
A. Higher commodity prices improve export revenue and the current account, supporting the currency. The effect is strongest when exports are concentrated.

**Q9. Why do real rates matter for gold?**
A. Gold pays no yield, so its opportunity cost is the real rate. Falling real rates tend to support gold.

**Q10. How do fiscal deficits transmit into long-end yields?**
A. More issuance can lift term premia, especially if the market doubts inflation control or central bank independence.

### Funding and plumbing

**Q11. Why does the SOFR–Fed funds spread matter?**
A. A persistent positive spread suggests reserves or collateral are scarce, a sign of funding stress.

**Q12. What is the market impact of month-end repo spikes?**
A. Banks shrink balance sheets around reporting dates, reducing cash supplied to repo and pushing rates up. Spikes usually reverse within days.

**Q13. How does reserve scarcity affect funding markets?**
A. Banks compete harder for overnight cash, and repo rates rise relative to policy. The effect is nonlinear near the scarcity threshold.

**Q14. What does a negative cross-currency basis signal?**
A. Borrowing dollars synthetically costs more than borrowing them directly, signalling strong non-US demand for dollars, often in stress.

**Q15. At a high level, how does the Treasury futures basis work?**
A. Long the cash bond against short futures, financed in repo, earning the basis as the two converge. Its risk depends heavily on financing terms.

### Volatility and convexity

**Q16. How do vega, theta and gamma behave in a long straddle?**
A. Vega is positive, theta is negative, and gamma is positive. The position gains from volatility and large moves, and pays time decay.

**Q17. What is volatility skew, and why do puts often trade rich?**
A. Implied volatility varies with strike. Puts are bid because investors pay for crash protection, which tends to happen fast.

**Q18. How would you hedge a long bond position with options?**
A. Buy payer swaptions or puts on bond futures. They gain when yields rise, offsetting the loss on the bond, at a premium cost.

**Q19. What is the difference between normal and lognormal volatility quotes?**
A. Lognormal is a percentage of the rate level and becomes unstable near zero. Normal is in basis points of rate change and is preferred when rates are low or negative.

**Q20. What is a risk reversal?**
A. A long call and short put, or the reverse, at different strikes. It expresses a view on skew.

### Risk and portfolio construction

**Q21. How would you stress-test a macro book against a 2013 taper-tantrum scenario?**
A. Shock front-end and long-end yields as they moved in 2013, widen EM currencies and bonds, and test DV01, FX exposure and whether hedges hold when correlations shift.

**Q22. What is a DV01-neutral trade?**
A. A combination with zero total sensitivity to a 1 bp move. It expresses a view on the curve's shape, not its level.

**Q23. How do you measure carry-adjusted return?**
A. Total return minus financing cost, compared with the risk taken, often as return divided by volatility.

**Q24. What is a drawdown limit, and how do PMs enforce it?**
A. The maximum loss allowed from a peak before risk is cut. Enforced through mandatory reductions at set loss levels.

**Q25. How would you estimate FX beta to rates?**
A. Regress currency returns on yield-spread changes over a regime-appropriate window, and check stability across periods.

### Positioning, flows and execution

**Q26. How do you read an extreme positioning reading in CFTC data?**
A. Extreme net positioning signals crowding. It is most useful combined with price action, since crowded positions can persist.

**Q27. How does liquidity vary across the Treasury curve?**
A. Greatest in the on-the-run 2-, 5- and 10-year. It thins around auctions and in stress.

**Q28. How do you measure execution quality and slippage?**
A. Compare fills with the arrival-price midpoint and track it across venues and dealers over time.

**Q29. What do tail and bid-to-cover mean in a Treasury auction?**
A. The tail is the gap between the accepted yield and the pre-auction level, a measure of weak demand. Bid-to-cover is total bids divided by amount sold.

**Q30. How do you write a trade ticket with entry, stop, target and thesis?**
A. State the view, the catalyst, and what would prove it wrong. A ticket without an invalidation level is not finished.

---

## Level 3: 5 Years

### Instruments and pricing

**Q1. Walk through bootstrapping a discount curve from OIS and swap rates.**
A. Solve for each discount factor in turn from the shortest instrument outward, interpolating where needed, and check that the curve reprices every input.

**Q2. How is the cheapest-to-deliver bond identified in a Treasury futures contract?**
A. The deliverable bond with the lowest implied repo rate after conversion factors. The CTD can switch as rates move, creating embedded optionality.

**Q3. How does an NDF differ from a deliverable forward, and when does the fixing matter?**
A. An NDF is cash-settled in a major currency because the local currency cannot be freely delivered. The fixing source and timing set the settlement price.

**Q4. What drives roll yield in commodity futures, and how does it differ between oil and natural gas?**
A. The curve shape as contracts roll. Oil is often backwardated when physically tight. Natural gas has strong storage seasonality, so long positions can bleed roll yield during injection season.

**Q5. How would you value the basis leg of a cross-currency swap?**
A. Project each floating leg on its own collateral curve, add the basis to the non-dollar leg, and discount. Basis moves reprice the swap directly.

### Macro and policy

**Q6. How would you nowcast US payrolls?**
A. Combine jobless claims, private payroll data, surveys, hours worked, and their historical relationship to official data, weighting each by recent forecast accuracy.

**Q7. How would you map a fiscal impulse into the term premium?**
A. Estimate the change in duration supply and the expected policy path. More duration to absorb, without central bank buying, usually lifts the term premium.

**Q8. How do terms-of-trade shocks feed into a commodity importer's CPI?**
A. Import prices pass into headline CPI quickly and into core more slowly. The size depends on import share, the currency, and central bank credibility.

**Q9. When does the "Fed put" stop working?**
A. When inflation is too high for easing, or when the stress is a supply shock that easing would worsen.

**Q10. How would you assess misalignment in a real effective exchange rate?**
A. Compare the REER with its long-run average, adjusted for productivity, terms of trade and net foreign assets. It is a medium-term value signal, not a timing tool.

### Funding and plumbing

**Q11. How do repo rates reprice at quarter-end, and what is the mechanism?**
A. Banks shrink balance sheets for regulatory ratios, lending less cash. With demand unchanged, repo rates rise temporarily.

**Q12. What is the Treasury basis trade, and why did it matter in March 2020?**
A. Long cash Treasuries against short futures, financed in repo. In March 2020, leveraged positions were forced to unwind as margin rose and dealer capacity fell, dislocating the cash market.

**Q13. What does the Standing Repo Facility do to the repo rate floor?**
A. It lets eligible counterparties borrow overnight from the Fed against Treasury collateral, capping how high repo can spike.

**Q14. How does collateral scarcity affect swap spreads?**
A. Scarce high-quality collateral can make Treasury repo rich, moving the gap between swap and Treasury yields.

**Q15. How do dealer balance-sheet constraints affect cross-currency basis?**
A. Dealers intermediate FX swaps, so constrained balance sheets mean they charge more for dollar funding and the basis widens.

### Volatility and convexity

**Q16. What do the SABR parameters control, and how is the model used?**
A. The at-the-money vol level, vol-of-vol, the rate–vol correlation, and smile curvature. Calibrated to quotes to price across strikes and estimate skew.

**Q17. What do calendar spreads on the vol surface express?**
A. A view on the term structure of volatility, such as whether near-term vol is expensive relative to longer-dated.

**Q18. How would you hedge gamma exposure around an FOMC meeting?**
A. Reduce gamma beforehand so a surprise does not force large delta hedging into a moving market.

**Q19. How does a variance swap differ from a volatility swap?**
A. A variance swap pays realised variance, which is convex in volatility. A volatility swap pays realised volatility. Variance swaps are easier to replicate with options.

**Q20. How do you price a payer swaption, and what does it hedge?**
A. Use Black or Bachelier with the forward swap rate, strike, expiry, annuity and implied vol. It hedges rising rates for a future fixed-rate payer.

### Risk and portfolio construction

**Q21. How would you aggregate DV01 across currencies into one risk number?**
A. Convert each DV01 to a common currency at spot and sum by curve bucket, presenting key-rate detail so a single figure does not hide offsets.

**Q22. Why do regulators prefer expected shortfall to VaR?**
A. It measures the average loss beyond the VaR threshold, capturing how bad tail losses are.

**Q23. How would you size positions using volatility targeting?**
A. Scale each position so its risk contribution is a fixed share of a target volatility, shrinking positions automatically as realised volatility rises.

**Q24. How would you test for correlation breakdown in a crisis?**
A. Measure correlations in stress windows such as 2008 or March 2020 separately from normal periods, and stress the book with those.

**Q25. How does scenario VaR differ from historical VaR?**
A. Historical VaR uses past returns. Scenario VaR applies specified shocks to current positions, which suits events with no close historical analogue.

### Positioning, flows and execution

**Q26. How would you identify a crowded trade using flow data?**
A. Combine positioning surveys, options skew and flow speed with price action. A trade is crowded when positioning is extreme, returns are fading, and the exit would be hard.

**Q27. Why do traders care about clean versus dirty price?**
A. Dirty price includes accrued interest and is what the buyer pays. Confusing the two corrupts P&L, carry and hedge ratios.

**Q28. How do you manage futures roll dates?**
A. Roll before liquidity migrates, usually before first notice or delivery, and compare the calendar spread with the roll cost.

**Q29. How would you measure the market impact of a large order?**
A. Compare execution with arrival price and subsequent drift, separating own impact from normal market movement, across several horizons.

**Q30. What do Treasury dealer inventories tell you?**
A. Large inventories mean dealers hold more than they want, often signalling weak end-user demand. They can precede weaker prices.

---

## Level 4: 7 Years (VP)

### Instruments and pricing

**Q1. How would you hedge a local-currency EM bond position using NDFs and cross-currency swaps?**
A. Split the position into rate, FX and basis components. Use NDFs for currency, and cross-currency swaps to convert the coupon stream where possible. Check convertibility risk, which the hedge may not cover in stress.

**Q2. How does the real yield on inflation-linked bonds differ from breakeven, and how would you trade the breakeven?**
A. Breakeven is nominal yield minus real yield, a market inflation estimate. Trade it DV01-matched against nominal bonds, watching seasonality, indexation lags and liquidity.

**Q3. When would you use the Bachelier model instead of Black for swaptions?**
A. Bachelier assumes normal rates and suits low or negative rate regimes, where lognormal assumptions break down. Black suits rates well above zero.

**Q4. What drives the Brent–WTI spread?**
A. Quality, location and logistics. It widens when US stocks build, export capacity is constrained, or transport costs rise.

**Q5. How would you structure a curve steepener with DV01 and convexity considered?**
A. Long front against short long end, DV01-neutral, then adjust the ratio for the convexity mismatch so the trade is not a hidden level bet.

### Macro and policy

**Q6. How would you map a central bank's reaction function to inflation surprises versus the output gap?**
A. Estimate a Taylor-style relation and test whether the bank responds more to inflation surprises than to the output gap.

**Q7. What does the current deviation from the Taylor rule tell you?**
A. A large positive deviation means policy is tighter than the rule implies, a downside risk to rates if growth is the bank's concern. The signal depends on the rule's inputs being reliable.

**Q8. How does a fiscal-dominance regime change the policy mapping?**
A. The bank may keep rates below the rule to contain financing costs, making it less responsive to inflation and steepening the curve.

**Q9. How would you assess fair value using REER and terms of trade together?**
A. A currency with strong terms of trade may justify a higher equilibrium. Joint use separates cheap currencies from those cheap for a good reason.

**Q10. How would you separate supply from demand in an oil price move?**
A. Supply shocks show sharp price moves with curve backwardation and falling inventories. Demand shocks show falling consumption and inventory builds.

### Funding and plumbing

**Q11. How would you forecast SOFR spikes around tax dates and Treasury settlements?**
A. Track the Treasury General Account, reserves, and the calendar of tax and settlement flows, and estimate the drain relative to reserves.

**Q12. How does a shift in the reserve regime change repo volatility?**
A. Abundant reserves keep repo near policy and calm. Scarce reserves make the system sensitive to flows, and the transition is nonlinear.

**Q13. How would you trade the basis between CDS and cash bonds?**
A. Buy the bond and buy protection when the CDS is cheap relative to the bond, earning the basis, with attention to funding, counterparty risk and cheapest-to-deliver effects.

**Q14. How do you tell whether the cross-currency basis reflects stress or a technical factor?**
A. Stress comes with widening credit spreads and falling dealer capacity, and persists across tenors. Technical moves are date-driven and reverse quickly.

**Q15. How does the leverage ratio constrain dealer intermediation?**
A. It caps balance sheet size relative to capital regardless of risk, so dealers cut low-margin, high-balance-sheet activity near the limit. That makes funding markets more fragile in stress.

### Volatility and convexity

**Q16. How would you structure a convexity hedge for a mortgage-heavy book?**
A. Buy payer and receiver swaptions or long-gamma structures across expiries to offset negative convexity, sized to the expected range of rate moves.

**Q17. How does gamma scalping work in a rates options book?**
A. Delta-hedge as the underlying moves, buying low and selling high. It profits when realised volatility exceeds the implied volatility paid.

**Q18. How would you measure vega exposure across tenors?**
A. Bucket vega by option expiry and underlying tenor, since a single total can hide offsetting positions.

**Q19. What is the relationship between the realised–implied volatility risk premium and the cycle?**
A. The premium is largest when tail fears are high and small or negative in calm periods. It reverses sharply in stress.

**Q20. How would you use skew to express a view on a central bank cut?**
A. Buy receiver options at strikes that gain on cuts, choosing strikes so the trade does not pay up for skew.

### Risk and portfolio construction

**Q21. How would you allocate a risk budget across rates, FX and commodities?**
A. Allocate by expected return per unit of risk and diversification, measured in a common framework such as volatility or expected shortfall.

**Q22. How would you set stop losses for a set of correlated trades?**
A. Set a combined limit on the shared factor, not only per trade, since one adverse move can trigger every stop at once.

**Q23. How would you stress-test liquidity: how long would it take to exit the book?**
A. Position size divided by daily tradable volume at a set participation rate, adjusted for stress when volumes fall.

**Q24. How would you design a scenario-based options hedge?**
A. Start from the scenarios that matter, buy options whose payoffs offset losses in those scenarios, and compare premium cost with expected loss reduction.

**Q25. How would you set risk limits for a discretionary PM?**
A. Limits on DV01, gross and net exposure, stop levels and expected shortfall, with a drawdown trigger for review, reflecting track record and instrument liquidity.

### Positioning, flows and execution

**Q26. When do cross-asset flow signals mislead?**
A. When flows reflect hedging rather than views, are concentrated in a few accounts, or come just before a regime change.

**Q27. How would you execute a large cross-border FX trade with minimal market impact?**
A. Split across time and venues, track volume, avoid known liquidity events, and respect fixing schedules and local market hours.

**Q28. How would you infer the expected policy path from the futures curve?**
A. Convert fed funds or SOFR futures into implied rates, adjusting for term premium and technical distortions, then compare with your own path.

**Q29. How would you monitor changes in market depth during volatile events?**
A. Track order book depth, spreads and the size that moves prices. A thinning book is an early warning that exits will be costly.

**Q30. How would you evaluate a broker's execution quality?**
A. Compare fills with arrival and benchmark prices, speed, fill rates and routing impact, across calm and stressed conditions.

---

## Level 5: 10 Years (Executive Director)

### Instruments and pricing

**Q1. Walk through a dollar funding stress trade using FX swaps and cross-currency basis.**
A. When the basis is very negative, a trader lends dollars synthetically and borrows the other currency to earn the premium, betting on normalisation. Risks are funding and counterparty.

**Q2. How would you value an MBS and manage prepayment convexity?**
A. Use an option-adjusted spread model simulating rates and prepayments, and hedge negative convexity with swaptions.

**Q3. How would you hedge commodity term-structure exposure with calendar spreads and options?**
A. Calendar spreads hedge curve shape, options hedge the level. Combine them so each risk is hedged separately, and check behaviour when the curve shape changes.

**Q4. How would you trade a sovereign CDS-to-bond basis?**
A. Take the cheaper leg and hedge the other, watching reference obligation differences, cheapest-to-deliver features and bond funding cost.

**Q5. How do swap spreads reflect balance sheet constraints?**
A. Constrained dealers are less willing to hold the swap leg, so swap spreads can turn negative. They indicate intermediation capacity.

### Macro and policy

**Q6. How would you build a regime model that changes sizing across inflation and growth regimes?**
A. Define regimes from inflation and growth trends, estimate asset returns in each, size by expected return and volatility, and shift allocations with a confirmation rule.

**Q7. How would you tell whether a central bank is responding to a supply shock or a demand shock?**
A. Demand shocks move inflation and output together, supply shocks move them oppositely. Check communication, labour data and inflation expectations.

**Q8. How would you price political risk into EM sovereign bonds?**
A. Estimate event probability and impact, and compare the expected loss with the spread, adjusted for risk appetite.

**Q9. How would you forecast the term premium from supply, quantitative tightening and official demand?**
A. Model it as a function of duration supply, central bank balance sheet changes, and official holdings. QT removes a buyer and tends to raise the premium.

**Q10. What does the long end signal when the front end is anchored?**
A. Long-end moves mainly reflect term premium, growth or long-run inflation. Steepening can point to fiscal concern.

### Funding and liquidity

**Q11. How would you estimate the cost of dollar funding for a non-US bank at a given basis?**
A. Dollar rate plus basis, adjusted for balance sheet cost, capital charges, collateral and haircuts.

**Q12. How would you model unwind risk in the Treasury basis trade under margin stress?**
A. Stress margin with volatility, compute the cash needed for margin calls, assume dealers cut financing, and estimate the forced selling in cash markets.

**Q13. How would you map liquidity across tri-party and bilateral repo?**
A. Compare rates, volumes and haircuts across both, noting that tri-party is more concentrated and bilateral more opaque, and find where stress appears first.

**Q14. How does a central bank liquidity backstop change basis trade pricing?**
A. A credible backstop lowers forced-unwind probability, narrowing the basis. The announcement alone can move the basis.

**Q15. How would you forecast when reserves become scarce?**
A. Compare reserves with demand from tax flows, Treasury issuance and the Fed balance sheet, and find the point where repo rises faster than policy.

### Volatility and convexity

**Q16. How would you calibrate a multi-factor rates model to a full swaption matrix?**
A. Use enough factors to capture the vol term structure, calibrate to reprice the expiry–tenor matrix, and judge the model by calibration error.

**Q17. How would you hedge option convexity in a bank's rates book?**
A. Measure gamma and vega by expiry, hedge critical buckets with options, and use dynamic delta hedging for short-term risk.

**Q18. How would you trade the gap between realised and implied volatility around a policy pivot?**
A. Before the pivot implied vol is often high. If realised is expected to undershoot, sell vol in a controlled way, sizing to the estimated pivot probability.

**Q19. How would you use the volatility surface to express a tail view?**
A. Buy far out-of-the-money options on the tail side, comparing cost with expected payoff and picking strikes where skew makes the tail cheap.

**Q20. What is the carry cost of a long-gamma position?**
A. Theta, the daily time decay paid to hold options. The position pays only when realised volatility exceeds implied.

### Risk and portfolio construction

**Q21. How would you manage correlations across the funds in a multi-strategy macro platform?**
A. Measure cross-fund correlations and factor exposures, and set limits on combined exposure to each factor, checking for hidden shared drivers.

**Q22. How would you run a crowding-based stress test?**
A. Estimate how many funds hold similar positions, assume a simultaneous exit, and measure price impact and losses.

**Q23. How would you size exposure to event risk such as elections, wars or sanctions?**
A. Estimate outcome probabilities and price impacts, and cap the position so the worst plausible outcome fits the loss limit, allowing for uncertain probabilities.

**Q24. How would you determine risk-off hedge ratios when option costs are high?**
A. Balance hedge cost against expected loss prevented. A partial hedge, cheaper structure or different instrument may be better.

**Q25. How would you measure carry drag against convexity gain?**
A. Compare the funding cost of holding a position with the payoff from large moves, across the scenario range.

### Positioning, flows and execution

**Q26. How would you infer dealer positioning from auction and financing data?**
A. Auction allocations and financing volumes show dealer holdings. Rising financing and inventory mean dealers are taking more risk.

**Q27. How would you assess liquidity quality in an EM local bond market?**
A. Spreads, trade size, turnover, active dealer count, and how fast liquidity returns after a shock. The stress behaviour is the real test.

**Q28. How would you read trading crowding from the options skew?**
A. A steep skew or unusual risk-reversal moves can show investors paying up on one side. Confirm with price and flow.

**Q29. How would you manage liquidity through a flash crash?**
A. Avoid market orders, keep limits near mid, reduce size before volatility, and decide exits in advance.

**Q30. How would you structure execution across venues and dealers in stressed markets?**
A. Diversify counterparties, use venues that stay active, split orders to what the market absorbs, and track fills and slippage live.

---

## Level 6: 15 Years (Managing Director)

### Instruments and pricing

**Q1. How would you price and hedge a multi-currency cross-currency swap book with basis and collateral discount curves?**
A. Build discount curves per collateral currency, value each swap on the appropriate basis curve, and hedge by bucket: rate DV01, FX delta and basis sensitivity.

**Q2. How would you value an inflation swap, including its seasonality?**
A. Use the index ratio with its lag and adjust for seasonal patterns, since ignoring seasonality misprices the swap.

**Q3. How does collateral optionality under a CSA affect discounting?**
A. The posting party can choose the collateral currency, making the effective discount rate depend on the cheapest-to-deliver collateral. Ignoring this misstates value.

**Q4. How would you trade the EM local-currency basis across forward and cash curves?**
A. Compare the forward-implied rate with the local cash rate and trade the difference, watching capital controls, convertibility and fixing mechanics.

**Q5. How would you identify and extract the cheapest-to-deliver optionality in futures?**
A. Value the delivery option by simulating rates and CTD switches, then own or sell it depending on its price against expected value.

### Macro and policy

**Q6. How would you forecast fiscal dominance and its effect on the curve?**
A. Track debt dynamics, interest-to-revenue and central bank independence. Dominance keeps rates below the rule and raises inflation risk, typically steepening the curve.

**Q7. How would you assess a central bank's response to exchange-rate pass-through?**
A. Estimate pass-through to inflation. A bank that reacts strongly to currency-driven inflation will tighten after depreciation.

**Q8. How would you build a view on the neutral rate?**
A. Estimate r-star from real rates, growth, productivity and demographics, and check it against the policy path and financial conditions.

**Q9. How would you price geopolitical supply shocks, such as sanctions or chokepoints, into oil?**
A. Model lost barrels and time to replace them with spare capacity and stock draws. Impact depends on share affected and how fast rerouting offsets it.

**Q10. How would you map reserve managers' behaviour into currency trends?**
A. Track reserve composition, intervention and official holdings. Gradual diversification weighs on a reserve currency, while intervention caps moves in managed currencies.

### Funding and plumbing

**Q11. How do bank capital rules, such as the leverage ratio and G-SIB surcharge, shape cross-currency basis?**
A. Both limit balance sheet capacity, so dealers intermediate less funding. The effect is largest for low-margin, high-balance-sheet trades, and the basis widens as capacity falls.

**Q12. How would you forecast the Fed balance sheet path and the reserve level?**
A. Combine the runoff schedule, the TGA, currency demand and reinvestment policy into a set of flows that drive reserves.

**Q13. How does central clearing change the margin and leverage of the Treasury basis?**
A. Margin on previously bilateral positions reduces leverage and can force deleveraging in stress.

**Q14. How would you read repo stress signals across tenors?**
A. A widening between overnight and term repo signals funding stress that overnight data alone misses.

**Q15. How would you structure hedges for a dollar liquidity crisis?**
A. Hold dollar-liquid assets, use options on the dollar and basis instruments, and maintain access to central bank facilities, designing the hedge to work when correlations break.

### Volatility and convexity

**Q16. How would you handle model risk in rates smiles, comparing SABR and local vol?**
A. SABR is intuitive but can break at very low rates. Local vol fits the surface exactly but can give unrealistic dynamics. Use both, compare their hedges, and know where each fails.

**Q17. How would you hedge a book's vanna and volga exposure?**
A. Use options across strikes and expiries that offset the cross-sensitivities, and monitor them as vol and spot move together.

**Q18. How would you trade volatility around a change in policy regime?**
A. Look for mispricing in skew and term structure, and size for a regime change that happens faster or sharper than the market expects.

**Q19. How would you construct a convexity-efficient payer or receiver structure?**
A. Combine options and swaps for the desired payoff at least premium, allocating convexity where the view is strongest and using spreads to finance premium.

**Q20. How would you set vol risk-premium expectations across cycles?**
A. Estimate the implied–realised spread over the cycle; the premium is larger when investors are fearful.

### Risk and portfolio construction

**Q21. How would you combine discretionary views with systematic overlays?**
A. Use systematic signals for sizing and timing, and discretion to set the view and override when regimes change.

**Q22. How would you design a drawdown-recovery plan for a multi-year book?**
A. Cut risk as losses grow, define rebuild conditions, and make the rebuild slower than the cut so the book does not re-risk into the same loss.

**Q23. How would you allocate capital across correlated macro books?**
A. By marginal contribution to portfolio risk, sharing limits across correlated books and favouring those that diversify in stress.

**Q24. How would you judge tail-hedge cost-efficiency across cycles?**
A. Compare premium paid over time with payoffs in stress, measuring cost per unit of crisis protection.

**Q25. How would you define leverage across a derivatives-heavy book?**
A. Use notional, DV01 and expected shortfall together, since notional alone can mislead.

### Positioning, flows and execution

**Q26. Which cross-market liquidity signals would you watch before a regime change?**
A. Bid-offer spreads, depth, related-instrument basis and order-flow speed. Liquidity often deteriorates before prices move.

**Q27. How would you structure execution in a crisis when correlations break?**
A. Assume hedges fail, use liquid instruments, reduce size, set exits in advance, and accept worse prices to get out.

**Q28. How would you compare the market-implied policy path with your house view?**
A. Convert futures and OIS into an implied path and compare with your inflation and growth forecast. Size the trade by confidence in the view.

**Q29. How would you design a positioning dashboard across macro factors?**
A. Exposures by factor (duration, curve, FX, credit, vol) alongside positioning, flows and sentiment, highlighting concentrations that one event could hit across factors.

**Q30. How would you assess crowding relative to hedge fund peers?**
A. Use holdings data, prime broker information and positioning surveys, and weigh the liquidity of the positions, since shared exits are dangerous.

---

## Level 7: 20+ Years (Expert)

These answers reflect judgement built over several full cycles. Historical examples are from general market knowledge.

### A. Instruments and pricing

**Q1. How would you bootstrap a sovereign curve when the collateral-specific discount rate differs from OIS?**
A. Bootstrap separate curves per collateral type and examine the difference. The gap is a real funding cost, and ignoring it misprices every swap and bond referenced to the curve.

**Q2. How would you value the CSA optionality in a cross-currency book?**
A. Simulate the cheapest-to-deliver collateral over rates and basis paths, and include the option in discounting rather than treating it as an afterthought.

**Q3. How would you hedge negative convexity in a mortgage-heavy portfolio?**
A. Buy payer and receiver options across expiries. Negative convexity forces buying duration into rallies and selling into selloffs, and the hedge has a premium that must be justified by the expected loss.

**Q4. How would you calibrate SABR parameters across two different rate regimes?**
A. Calibrate separately, because the rate–vol correlation can change sign across regimes. A single set misprices the wings.

**Q5. How would you estimate the storage economics that set a commodity's contango range?**
A. Storage capacity, carry cost and convenience yield set the bounds. Contango is capped by storage cost; when storage is full, the curve can distort beyond it.

### B. Macro and policy

**Q6. How would you judge whether the Fed's reaction function has changed nonlinearly near the zero bound?**
A. Look for changes around the period rates hit the lower bound, and separate balance sheet and forward guidance as additional channels.

**Q7. How would you assess whether a yield-curve-control regime is sustainable?**
A. It holds while inflation is contained and the central bank accepts the balance sheet cost. Japan showed such regimes can end when the inflation outlook shifts.

**Q8. How would you analyse the fiscal dominance risk in a high-debt sovereign?**
A. Examine interest burden, debt maturity, central bank independence and the ability to finance through inflation. Short-dated debt with a captive central bank is most exposed.

**Q9. What lessons would you draw from 1994 for the current long end?**
A. A policy surprise hit leveraged bond positions and the long end sold off as funding and positioning unwound together. Crowded positioning with tight funding is the danger.

**Q10. What were the main transmission channels in the 1992 ERM episode?**
A. Speculative attacks forced interest rate defences while fundamentals diverged, with reserves and political commitment as the other channels. A peg is only as strong as its fiscal and political support.

### C. Funding, plumbing and liquidity

**Q11. How would you distinguish a cross-currency basis move caused by stress from one caused by technical factors?**
A. Stress comes with widening credit spreads, rising CDS, falling dealer capacity and persistence. Technical moves are date-driven and reverse.

**Q12. How would you measure the leverage and haircut risk embedded in the Treasury basis trade?**
A. Measure notional leverage, repo haircuts and futures margin, then stress haircuts and margin upward and compute the cash needed to hold the position.

**Q13. How would you estimate reserve scarcity points in the repo market?**
A. Find the reserve level where repo rises faster than policy. The threshold shifts with the distribution of reserves across banks.

**Q14. How does the SLR reform change dealer capacity in swap and repo markets?**
A. Easing the constraint increases capacity and narrows basis and swap-spread dislocations. Tightening does the reverse.

**Q15. How would you read dealer balance sheet constraints from market data?**
A. When basis, swap spreads, repo volumes and dealer terms deteriorate together, dealers are constrained and the market absorbs less flow.

### D. Volatility and convexity

**Q16. How would you hedge vanna and volga exposure in a stressed market?**
A. Use options across strikes that offset the cross-sensitivities and re-hedge more often, accepting higher costs to keep risk within limits.

**Q17. How do dealer hedging flows feed back into spot near large option expiries?**
A. Short-gamma dealers buy into rallies and sell into falls, amplifying moves. Strike concentration can pin prices or accelerate them. Watch open interest by strike.

**Q18. How would you identify pinning and gamma-driven price moves?**
A. Price clustering around large strikes near expiry, with rising volume. Pinning occurs when dealers are long gamma; acceleration when they are short.

**Q19. How would you measure correlation regime change, and how fast does it happen?**
A. Track rolling cross-asset correlations against long-run averages. Regimes can shift within days in a crisis, so measurement must be fast.

**Q20. How would you calculate liquidity-adjusted VaR and an exit horizon?**
A. Add the cost of exiting over the horizon, from bid-offer spread and market impact at the position size. The exit horizon grows sharply in stress.

### E. Risk and portfolio construction

**Q21. How would you price the cost of tail protection through a full cycle?**
A. Track premium over time against crisis payoffs. Protection is cheap when complacent and expensive after shocks, so buy when calm.

**Q22. How would you size exposure to an election or sanctions event?**
A. Size so the worst plausible scenario fits the loss limit, allowing for uncertainty in probabilities and for markets repricing before the event.

**Q23. How would you measure the historical reliability of positioning-based crowding measures?**
A. Test extreme positioning against subsequent reversals in past episodes. Reliability varies by instrument and regime.

**Q24. How would you use central bank reserve flows as a signal for currency trends?**
A. Reserve managers move slowly, so flows are a background trend. A sustained shift in composition supports a currency move; a single intervention is usually temporary.

**Q25. How do dealers provide liquidity when their balance sheets are constrained?**
A. They reduce inventory, widen spreads, match client flow, and favour the most profitable clients. Liquidity becomes available to some counterparties and not others.

### F. Positioning, flows and execution

**Q26. How would you route execution across venues in a dislocation?**
A. Use venues that stay active, split orders across them, and re-route as depth changes. Completing the trade with acceptable impact matters more than chasing quotes.

**Q27. How would you judge whether a macro regime is ending before the data shows it?**
A. Watch changes in cross-asset relationships, in the market's sensitivity to data, and in positioning and flows. These usually move before headline data.

**Q28. How would you decide when a policy pivot is credible?**
A. When the bank backs its communication with costly-to-reverse actions and the data supports it, with fiscal and political backing, and a history of pivoting when needed.

**Q29. How would you use the sovereign CDS-to-bond basis to read stress?**
A. A widening basis can signal funding stress or cheapest-to-deliver effects, and is informative when it moves independently of fundamentals.

**Q30. How would you set a long-run framework for when to cut risk, not just size it?**
A. Define in advance the signals of regime change, such as correlation breakdown, rising funding stress or lost liquidity. When several occur together, reduce exposure before losses force the decision.
