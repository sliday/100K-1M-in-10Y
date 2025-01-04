# Risk Management Framework

## Risk Profile Evolution
```
Portfolio Risk Allocation Over Time:

$100k-$140k Phase:
Risk Level │ Allocation  │ Max Drawdown
High       │[████████] 40%│    -45%
Medium     │[████████] 40%│    -35%
Low        │[████] 20%    │    -20%

$140k-$250k Phase:
Risk Level │ Allocation  │ Max Drawdown
High       │[██████] 30% │    -40%
Medium     │[████████] 40%│    -30%
Low        │[██████] 30% │    -15%

$250k-$415k Phase:
Risk Level │ Allocation  │ Max Drawdown
High       │[████] 20%   │    -35%
Medium     │[████████] 40%│    -25%
Low        │[████████] 40%│    -10%

$415k+ Phase:
Risk Level │ Allocation  │ Max Drawdown
High       │[██] 10%     │    -30%
Medium     │[██████] 30% │    -20%
Low        │[████████████] 60%│ -5%
```

## Position Size Management
```
Maximum Allocation Per Position:
                                        MAX
Asset Type  │0%─────25%─────50%─────75%─100%│
ETF Core    │[██████████] 20%               │
ETF Sector  │[█████] 10%                    │
BTC/ETH     │[██████████] 20%               │
Alt L1      │[███] 6%                       │
DeFi Proto  │[██] 4%                        │
Fixed Income│[███] 5%                       │

Rebalancing Triggers:
                     WARNING    CRITICAL
Asset Type  │ Target │ +/-     │ +/-
ETF Core    │ 20%    │[███] 5% │[█████] 10%
ETF Sector  │ 10%    │[███] 3% │[████] 8%
BTC/ETH     │ 20%    │[████] 7%│[██████] 15%
Alt L1      │ 6%     │[███] 5% │[█████] 10%
DeFi Proto  │ 4%     │[██] 3%  │[████] 8%
Fixed Income│ 5%     │[██] 3%  │[███] 5%
```

## Risk Metrics Dashboard
```
Daily Monitoring Thresholds:
Metric          Normal Range        Warning         Critical
Volatility   [──────|─────] 15-25% [─────] 25-35% [──] >35%
Beta         [────|─────] 0.8-1.2  [────] 1.2-1.5 [──] >1.5
Sharpe Ratio [────|─────] 1.5-2.0  [────] 1.0-1.5 [──] <1.0
Drawdown     [──────|─────] 0-25%  [─────] 25-35% [──] >35%

Correlation Heat Map:
        ETF   BTC   ETH   L1    DeFi  Bond
ETF   │ 1.0   0.3   0.3   0.4   0.2   0.1 │
BTC   │ 0.3   1.0   0.8   0.7   0.6   0.2 │
ETH   │ 0.3   0.8   1.0   0.8   0.7   0.2 │
L1    │ 0.4   0.7   0.8   1.0   0.8   0.3 │
DeFi  │ 0.2   0.6   0.7   0.8   1.0   0.3 │
Bond  │ 0.1   0.2   0.2   0.3   0.3   1.0 │

Risk Level Indicators:
LOW RISK    [_█_] Current Level
MEDIUM RISK [_█_] Target Level
HIGH RISK   [_█_] Warning Level
            0   5   10   15   20
```

## Stop-Loss Framework
```
Dynamic Stop-Loss System:

ETF Positions:
Entry Price     [████████████████████] 100%
Warning Level   [██████████████████] -10%
Trailing Stop   [████████████████] -15%
Hard Stop      [████████████████] -20%

Crypto Core (BTC/ETH):
Entry Price     [████████████████████] 100%
Warning Level   [██████████████] -25%
Trailing Stop   [████████████] -30%
Hard Stop      [██████████] -40%

Alt L1 Positions:
Entry Price     [████████████████████] 100%
Warning Level   [████████████] -30%
Trailing Stop   [██████████] -35%
Hard Stop      [████████] -45%

DeFi Positions:
Entry Price     [████████████████████] 100%
Warning Level   [███████████] -20%
Trailing Stop   [█████████] -25%
Hard Stop      [███████] -30%
```

## Risk Management Actions

## Overview
Total Portfolio: $100,000 initial + $2,000 monthly
Risk Categories: Market, Technical, Operational, Counterparty

## Position Size Limits

### ETF Allocation ($30,000)
1. Individual ETF Limits
   - Core ETFs (VGT, QQQ): Max $10,000 each
   - Specialized ETFs (SOXX, ARKK): Max $5,000 each
   - New ETF positions: Start at $2,000
   - Leveraged ETFs: Max $1,500 (5% of ETF allocation)

2. Sector Concentration
   - Technology: Max $20,000 (67% of ETF allocation)
   - Single sector: Max $12,000 (40% of ETF allocation)
   - Emerging themes: Max $6,000 (20% of ETF allocation)
   - International: Max $9,000 (30% of ETF allocation)

### Crypto Allocation ($40,000)
1. Core Holdings
   - Bitcoin: Max $20,000 (50% of crypto)
   - Ethereum: Max $10,000 (25% of crypto)
   - Combined minimum: $24,000 (60% of crypto)
   - Hot wallet max: $8,000 (20% of crypto)

2. Alternative Chains
   - Single L1: Max $3,000 (7.5% of crypto)
   - Total L1s: Max $8,000 (20% of crypto)
   - New positions: Max $1,000
   - Infrastructure: Max $4,000 (10% of crypto)

### DeFi Allocation ($15,000)
1. Protocol Limits
   - Single protocol: Max $4,500 (30% of DeFi)
   - Single chain: Max $9,000 (60% of DeFi)
   - New protocols: Max $750 (5% of DeFi)
   - Minimum in stables: $7,500 (50% of DeFi)

2. Strategy Limits
   - Lending: Max $7,500 (50% of DeFi)
   - Liquidity pools: Max $4,500 (30% of DeFi)
   - Yield farming: Max $3,000 (20% of DeFi)
   - Single pool: Max $3,000 (20% of DeFi)

## Stop Loss Framework

### ETF Stop Losses
1. Core Holdings
   - Trailing stop: 10% ($1,000 on $10,000 VGT)
   - Hard stop: 15% ($1,500 on $10,000 QQQ)
   - Review trigger: 7% drop ($700)
   - Reset period: 30 days

2. Specialized Holdings
   - Trailing stop: 15% ($750 on $5,000 SOXX)
   - Hard stop: 20% ($1,000 on $5,000 ARKK)
   - Review trigger: 10% drop ($500)
   - Reset period: 14 days

### Crypto Stop Losses
1. Bitcoin/Ethereum
   - Trailing stop: 20% ($4,000 on $20,000 BTC)
   - Hard stop: 30% ($6,000 on $20,000 BTC)
   - Review trigger: 15% drop ($3,000)
   - Volume confirmation needed

2. Alternative Chains
   - Trailing stop: 30% ($900 on $3,000 SOL)
   - Hard stop: 40% ($1,200 on $3,000 SOL)
   - Review trigger: 20% drop ($600)
   - Liquidity check required

### DeFi Position Management
1. Lending Positions
   - Health factor minimum: 1.5
   - Buffer zone: 1.5-1.7 triggers review
   - Liquidation threshold: 80% maximum
   - Collateral requirement: 140% minimum

2. Liquidity Positions
   - IL threshold: 5% triggers review
   - Maximum IL tolerance: 10%
   - Minimum liquidity depth: $1M
   - Exit if volume drops 50%

## Risk Monitoring System

### Daily Checks
1. Portfolio Health
   - Total value vs previous day
   - Individual position sizes
   - Stop loss distances
   - Risk metrics update

2. Technical Checks
   - DeFi health factors
   - Liquidity pool status
   - Gas prices for actions
   - Network conditions

### Weekly Analysis
1. Risk Metrics
   - Volatility per position
   - Correlation matrix
   - Beta to benchmarks
   - Sharpe ratio update

2. Position Reviews
   - Size vs limits check
   - Stop loss updates
   - Strategy alignment
   - Rebalancing needs

## Emergency Procedures

### Market Events
1. -10% Portfolio Drop
   - Review all positions
   - Check correlations
   - Verify stop losses
   - Prepare cash reserves

2. -20% Portfolio Drop
   - Implement hedges
   - Reduce risk positions
   - Increase stable allocation
   - Document all actions

### Technical Events
1. DeFi Issues
   - Check health factors
   - Prepare exit transactions
   - Monitor gas prices
   - Have stables ready

2. Exchange Issues
   - Use backup exchanges
   - Keep withdrawal limits high
   - Maintain exchange list
   - Document procedures

## Recovery Framework

### From Losses
1. -10% to -20% Loss
   - Review what happened
   - Adjust position sizes
   - Update stop losses
   - Document lessons

2. -20% to -30% Loss
   - Full strategy review
   - Reduce risk temporarily
   - Increase monitoring
   - Plan recovery path

### From Technical Issues
1. Smart Contract Risk
   - Exit affected protocol
   - Review similar exposure
   - Update risk limits
   - Document incident

2. Platform Risk
   - Move to verified platforms
   - Reduce position sizes
   - Update security
   - Review procedures

## Common Mistakes

### Risk Assessment Mistakes
1. Position Size Violations
   - Example: Letting $10,000 VGT grow to $15,000 (50% of ETF allocation)
   - Impact: Over-concentration, amplified losses
   - Better Approach: Rebalance at $12,000 (40% threshold)
   - Real Numbers: Sell $3,000 to return to target

2. Stop Loss Negligence
   - Example: Not setting stops for $40,000 crypto allocation
   - Impact: Potential 80% drawdown ($32,000 loss)
   - Better Approach: Tiered stops (20%, 30%, 40%)
   - Real Numbers: Max loss limited to $12,000 (30%)

### Technical Risk Mistakes
1. Collateral Management
   - Example: Setting 90% LTV on $4,500 Aave position
   - Impact: Easy liquidation, 10% penalty ($450 loss)
   - Better Approach: Max 70% LTV, 1.5 health factor
   - Real Numbers: Keep $1,350 safety buffer

2. Platform Concentration
   - Example: $9,000 on single DeFi protocol
   - Impact: Complete loss if protocol fails
   - Better Approach: Max $4,500 per protocol
   - Real Numbers: Split $9,000 across 3 protocols

### Recovery Strategies
1. From Size Violations
   - Step 1: List all oversized positions
   - Step 2: Calculate target sizes
   - Step 3: Plan reduction schedule
   - Timeline: Rebalance within 7 days

2. From Stop Loss Failures
   - Step 1: Document current positions
   - Step 2: Set proper stops
   - Step 3: Create monitoring system
   - Timeline: Implement within 24 hours

### Prevention Framework
1. Size Control Rules
   - Weekly size checks
   - Rebalance at 120% target
   - Never exceed maximums
   - Document all changes

2. Stop Loss Rules
   - Set stops immediately
   - Review weekly
   - Adjust for volatility
   - Keep records updated

Remember: Risk management is about surviving to invest another day. A 50% loss requires a 100% gain to break even.

## Resources

### Risk Tools
- [Portfolio Visualizer](https://www.portfoliovisualizer.com)
- [TradingView Alerts](https://www.tradingview.com/alerts/)
- [Coinglass](https://www.coinglass.com)
- [DeFi Safety](https://www.defisafety.com)

### Risk Education
- [Investopedia Risk Management](https://www.investopedia.com/risk-management-4689652)
- [CFA Institute Risk](https://www.cfainstitute.org/en/membership/professional-development/refresher-readings/risk-management)
- [Risk.net](https://www.risk.net)
- [DeFi Risk Tools](https://defillama.com/risk) 