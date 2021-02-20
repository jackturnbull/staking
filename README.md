# ETH Staking
> I want to earn ETH on top of my ETH.  

The most lucrative way is through the [Curve.fi stETH pool](https://www.curve.fi/steth/deposit), and then placing your pool tokens either into the [harvest.finance CRV:STETH farm](https://harvest.finance/), or the [yearn.finance crvSTETH vault](https://yearn.finance/vaults).

## Sounds complicated?
Well, that’s how to _maximise rewards_ and currently offers around 25% APY on your ETH without lockup. If you don’t want to deal with all that, it would be easier to stake on a centralised service such as [Kraken](https://support.kraken.com/hc/en-us/articles/360052734432-Ethereum-2-0-staking-FAQ) for around 8% APY.

## What’s the process?
You need to combine multiple protocols in order to pull this together.

1. You don’t need to interact with this directly, but much of this relies on [Lido Finance](https://lido.fi/) to operate. It’s worth being aware that this is where your ETH ultimately gets staked, and they charge a 10% fee on staking profits. They manage the ETH2.0 staking on your behalf.
2. The most efficient way to get in is to ‘Deposit’ into the [Curve.fi stETH Pool](https://www.curve.fi/steth/deposit). Uncheck both the ‘Add all coins in a balanced proportion’ and ‘Use maximum amount of coins available’ boxes, then input the number of ETH that you wish to stake. Click ‘Deposit’ to begin the transaction and not ‘Deposit & stake in gauge’.
3. After depositing you’ll receive steCRV tokens that you can take to either the [harvest.finance CRV:STETH farm](https://harvest.finance/), or the [yearn.finance crvSTETH vault](https://yearn.finance/vaults).

## What are the risks?
Both [harvest.finance](https://news.bitcoin.com/defi-protocol-harvest-finance-hacked-for-24-million-attacker-returns-2-5-million/) and [yearn.finance](https://cointelegraph.com/news/yearn-finance-puts-expanded-treasury-to-use-by-repaying-victims-of-11m-hack) have seen hacks recently in which a vault was drained of its tokens and the user funds are at risk. Harvest did not cover the user deposits, Yearn is attempting to.

The risk of hacking is real and the more protocols and smart contracts you need to trust, the greater the risk. [Read more on these risks](https://hackmd.io/zVuiOwTBTZGT4Z8yV2ZQTw) before diving in.

If this seems too risky and you don’t wish to take it quite that far, you can simply trade your ETH for Lido stETH [on the trade interface](https://www.curve.fi/steth) of the pool. This isn’t quite as lucrative as it will only earn you the APY as shown on the [Lido Finance homepage](https://lido.fi/), rather than stacking all the additional pool rewards.

## Why would Yearn/Harvest earn more?
There are three/four additional sources of revenue when using a Yearn Vault or Harvest Farm:

1. When you deposit into the Curve pool you split your assets between the pair and act as a liquidity provider, even if you only deposit a single asset. Your share of the pool is then split 50:50 between (normal) ETH and (interest bearing) stETH. Curve shares the trading fees with you for providing liquidity.
2. As additional rewards, Curve provides LPs an amount of their own CRV tokens on a per-block basis. This is offered when you ‘Deposit & stake in gauge’. You don’t do this yourself, Yearn/Harvest will collect these for you.
3. On top of that, Lido supplies LPs a certain amount of their LDO token as incentive to become an LP. When you act as an LP your ETH2.0 staking rewards would be halved due to owning a 50:50 split of ETH:stETH, this rectifies that.
4. You also earn that 50% of the ETH2.0 staking rewards and will be redeemable when ETH2.0 launches.

