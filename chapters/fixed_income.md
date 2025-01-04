# Fixed Income Strategy

## Overview
Total Allocation: 25% of portfolio ($25,000 initial + $500 monthly)

The fixed income portion of our portfolio serves as a stability anchor, providing steady income and capital preservation. This strategy employs a barbell approach, balancing safety and yield through a mix of government bonds (10% of total portfolio) and term deposits (15% of total portfolio). The allocation is structured to maintain liquidity while capturing favorable interest rates across different durations.

## Barbell Strategy Overview
```
Portfolio Structure:

Government Bonds ($10,000 - 40% of fixed income):
[████] 2-year Treasury    │ 4.5% yield  │ $3,000
[████] 5-year Treasury    │ 4.7% yield  │ $3,000
[████] 10-year Treasury   │ 5.0% yield  │ $4,000

Term Deposits ($15,000 - 60% of fixed income):
[████] 6-month CD        │ 4.8% yield  │ $5,000
[████] 12-month CD       │ 5.0% yield  │ $5,000
[████] High-Yield Save   │ 4.5% yield  │ $5,000

Risk-Return Profile:
Treasuries  [██] Risk     [████████] Safety
Term Deps   [█] Risk      [█████████] Safety
High-Yield  [_] Risk      [██████████] Safety
```

## Yield Analysis
```
Current Yield Curve:

Yield
6% │           10Y Treasury
5% │      5Y    ┌────
4% │  2Y  ┌─────┘
3% │  ┌───┘
2% │  │
1% │  │
0% └──┴───────────────────
    3m  2y  5y  10y  30y

Weighted Average Yield: 4.75%
Total Annual Income: $1,187.50 ($25,000 × 4.75%)
Monthly Income: $98.96
```

## Allocation Breakdown
```
Fixed Income Portfolio ($25,000):

By Instrument Type:
Treasury Bonds   [██████] $10,000  40%
Term Deposits    [████████] $15,000  60%
High-yield Save  [██] $5,000       20%

By Duration:
Short-term   [████████] $10,000  40%
Medium-term  [████████] $15,000  60%
Long-term    [██] $5,000         20%

By Risk Level:
Ultra-Safe   [████] $3,000     12%
Very Safe    [████████] $10,000 40%
Safe         [████████] $12,000 48%
```

## Duration Management
```
Interest Rate Sensitivity:

Impact of 1% Rate Change:
2Y Treasury  │[██] -2% ($80 on $4,000)
5Y Treasury  │[████] -4% ($160 on $4,000)
10Y Treasury │[██████] -6% ($240 on $4,000)
Term Deps    │[█] -0.5% ($40 on $8,000)
High-Yield   │[_] 0% ($0 on $4,000)

Duration Targets:
                     Current
0y──────5y──────10y──────15y
   [█] 2Y Treasury
        [█] 5Y Treasury
             [█] 10Y Treasury

Duration Rebalancing Triggers:
2Y    │ Target: 2y  │ Range: 1.5-2.5y
5Y    │ Target: 5y  │ Range: 4.5-5.5y
10Y   │ Target: 10y │ Range: 9-11y
```

## Income Projection
```
Monthly Income Stream:

Treasury Income:
2Y  [███] $15 ($180/year at 4.5%)
5Y  [███] $16 ($188/year at 4.7%)
10Y [███] $17 ($200/year at 5.0%)

Term Deposit Income:
6M  [████] $16 ($192/year at 4.8%)
12M [████] $17 ($200/year at 5.0%)

High-Yield Income:
HYS [███] $15 ($180/year at 4.5%)

Monthly Summary:
Total Income:    $95 ($1,140/year)
Real Yield:      2.25% (4.75% - 2.5% inflation)
Risk-Adj Yield:  4.0% (after volatility adjustment)
```

## Risk Management
```
Fixed Income Risk Matrix:

Risk Type   │Impact │Mitigation
Interest    │[███]  │Duration ladder
Credit      │[█]    │Treasury focus
Inflation   │[███]  │Rate adjustments
Liquidity   │[█]    │High-yield buffer
Reinvestment│[██]   │Staggered maturities

Quality Distribution:
US Treasury [██████] 50%
FDIC Banks  [██████] 50%
<AA+        [0%]

Liquidity Profile:
Immediate   [████] 17% ($4,000 High-yield)
<6 months   [████] 17% ($4,000 6M CD)
6-12 months [████] 17% ($4,000 12M CD)
1-2 years   [████] 17% ($4,000 2Y Treasury)
2-5 years   [████] 17% ($4,000 5Y Treasury)
5+ years    [████] 17% ($4,000 10Y Treasury)
```

## Implementation Actions

### Initial Deployment ($25,000)
1. Week 1: Treasury Setup ($10,000)
   - Buy 2Y Treasury: $3,000
   - Buy 5Y Treasury: $3,000
   - Buy 10Y Treasury: $4,000

2. Week 2: Term Deposit Setup ($15,000)
   - Open 6M CD: $5,000
   - Open 12M CD: $5,000
   - Open High-Yield Savings: $5,000

3. Week 3: High-Yield Setup ($5,000)
   - Set up auto-sweep
   - Configure alerts

### Monthly Contributions ($500)
1. Treasury Allocation ($250)
   - 2Y Treasury: $80
   - 5Y Treasury: $80
   - 10Y Treasury: $90

2. Term Deposits ($150)
   - 6M CD ladder: $75
   - 12M CD ladder: $75

3. High-Yield ($100)
   - Emergency buffer: $100
   - Rebalance at $4,500

## Risk Management

### Position Limits
1. Treasury Limits
   - Single maturity: Max $4,000
   - Duration exposure: Max 10 years
   - Total allocation: Max $10,000

2. Bank Limits
   - Single bank: Max $4,000
   - Early withdrawal option required
   - FDIC insurance mandatory
   - Minimum rate threshold: Top 10%

### Safety Measures
1. Credit Risk
   - US Treasury only for bonds
   - FDIC-insured banks only
   - Regular bank rating checks
   - Quarterly limit reviews

2. Interest Rate Risk
   - Duration laddering
   - Yield curve monitoring
   - Rate sensitivity analysis
   - Monthly rebalancing check

## Monitoring System

### Weekly Checks
1. Rate Analysis
   - Treasury yield changes
   - CD rate comparisons
   - High-yield rate tracking
   - Spread analysis

2. Risk Assessment
   - Duration exposure
   - Bank health metrics
   - Market rate trends
   - Liquidity needs

### Monthly Reviews
1. Performance Tracking
   - Yield calculations
   - Duration adjustments
   - Income verification
   - Rebalancing needs

2. Strategy Alignment
   - Ladder structure
   - Maturity schedule
   - Rate optimization
   - Bank diversification

## Common Mistakes to Avoid

### Strategy Errors
1. Duration Risk
   - Example: All $12,000 in 10Y Treasury
   - Impact: -6% on 1% rate rise ($720 loss)
   - Better: $4,000 each in 2Y, 5Y, 10Y
   - Real Numbers: Max $4,000 per maturity

2. Bank Concentration
   - Example: $8,000 at one bank
   - Impact: Exceeds safety threshold
   - Better: Max $4,000 per bank
   - Real Numbers: Split across 2+ banks

### Implementation Mistakes
1. Yield Chasing
   - Example: Unproven bank offering +0.5%
   - Impact: Increased risk for $20/year
   - Better: Stick to top-tier banks
   - Real Numbers: Max 0.3% yield sacrifice

2. Liquidity Lock
   - Example: All $8,000 in 5-year CDs
   - Impact: High early withdrawal fees
   - Better: Ladder maturities
   - Real Numbers: Max $4,000 per term

## Resources

### Research Tools
- [Treasury Direct](https://www.treasurydirect.gov)
- [FDIC BankFind](https://banks.data.fdic.gov/bankfind-suite/bankfind)
- [Bankrate CD Rates](https://www.bankrate.com/banking/cds/cd-rates/)
- [High Yield Savings Comparison](https://www.bankrate.com/banking/savings/rates/)

### Analysis Tools
- [Treasury Yield Curve](https://www.treasury.gov/resource-center/data-chart-center/interest-rates/Pages/TextView.aspx?data=yield)
- [CD Ladder Calculator](https://www.bankrate.com/calculators/cd/cd-ladder-calculator.aspx)
- [Bond Duration Calculator](https://www.calculatorsoup.com/calculators/financial/bond-duration-calculator.php)
- [FDIC Insurance Calculator](https://edie.fdic.gov) 