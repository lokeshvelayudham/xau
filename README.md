**Stablecoin backed by synthetic gold - *gUSD***

<aside>
💡 **creating a trustless and truly decentralised gold-backed stablecoin (gUSD).**

</aside>

**Table of contents**

> Mint **gUSD,**
 a USD-pegged stablecoin backed by synthetic gold. Users can use any token as collateral that is backed by gold. By locking other USD-pegged stablecoins, we can benefit from better risk management and hedge against inflation.
> 

> **Vs. Competitors:** 
gUSD can be minted at a 102% collateral-to-loan ratio, where it is 110% in LUSD (liquidity) and 135% in DAI (maker tier B), and these issuers back the collateral with ETH pricing, risking volatility and bad debt risks.
> 

---

# Problem :

- DAI and LUSD are minted by locking up ETH at the current USD value up to 110% of the collateral to loan ratio. The debt is liquidated as the ETH becomes bearish and volatile. And defi users who want to hedge the inflation and volatility have no option but to move towards **PAXG, PMGT, and GLC** tokens, which are backed by physical gold reserves that are centralized, not trustless, and pose the threat of physical damage to uninsured issuers, or the issuers can double spend the reserved gold.

# Solution :

- Mint **gUSD**, a stablecoin backed by synthetic gold. Users can use any token as collateral, and the value is converted into gold pricing.So technically, the collateral is now gold, where the maximum fluctuation per day is less than 0.5%. So users can take safe leverage up to 50x on gold at a 102% collateral-to-loan ratio, which means that for every dollar locked, we can mint 0.9803 dollars, netting 50x leverage after looping the same process.

So thereby, the following *actions :*

1. Users can lock their ETH/ BTC/  or any token at the value of gold to not lose value or hedge against the dollar by locking any other USD-pegged stablecoin.
2. Users can take a maximum loan of 0.9803$ for 1$ locked, which nets 50x maximum leverage (after loops) at 102% collateral to loan value.
3. Users can take advantage of managing the risk of their troves, as gold is a low-volatile commodity.

The gUSD minted in the above user actions are minted or burned according to the action, making the gUSD trustless and truly decentralized.

## Action :

1. ACTION 1 : useful for institutions and whales to lock the volatile ERC20 tokens at gold pricing to mitigate volatility risk, and some whales can lock the collateral of USD/EURO pegged stables to hedge inflation as their collateral is technically backed by gold.
2. ACTION 2 : Traders and institutions can trade the XAU/USD pair as perpetuals with max leveraging at 50x (we, as a Dapp, will provide this feature, or any other frontends can make use of our smart contracts).
3. ACTION 3 : Users who do not trust the USDT, USDC, or BUSD because they can be frozen by issuers, or who do not trust the DAI or LUSD due to ETH volatility and unliquidated bad debts, may see their currency depegged from the US dollar (a very small possibility due to well-tested protocols).These users can hold gUSD, which is a trustless, decentralized, and gold-backed stablecoin.

# Roadmap :

1. Creating an LP pool of baskets containing ETH, WBTC, XAU*, and gUSD, similar to a GLP pool (GMX protocol), and earning a 0.3% fee from LP providers.
2. single or multiple stores of values like WBTC, ETH, and silver in addition to the current gold option.

## Q1 :

1. MVP (Stablecoin minting, borrowing, and stability pooling) is live on the Goerli Testnet.
2. Adding more oracles, such as chainlink, tellor, UMA, band, DIA, and our own backend Oracle, will result in a more robust price feed.
3. self-auditing contracts.

## Q2 :

1.  MVP live on mainnet.
2. create bonding mechanisms to generate yields.
3. Governance Token Generation Event.
4. Host public smart contract auditing contests.
5. Release SDK to opensource the UI building.

## Q3 :

1. Deploying on 5+ chains with native stable-coin bridges
2. Going on multichain with a single vault pool using Layer 0, the cosmWasm SDK 
3. Implement new contracts to mint BTC-backed stablecoins.
4. Create LP pools for Dex pairs and triPools on all chains.

## Q4:

1. going live on other fiats like the gEUR, gGBP, and gCNY stables.
2. Build a PERP/options dex with our stablecoins as collateral tokens.
3. Implement OTC/centralized services for institutions

## Long-Term goal:

1. gUSD into multi-chain interoperability
2. Creating gold bonds for yield
3. Developing gEUR, gCNY, gGBP, and other multi-fiat gold-backed coins
4. Creating a DeX on these products
5. WBTC-backed stablecoin -- bitcoin standard

# **Competitors:**

1. Direct Competitors:
    1. Maker DAO - DAI
    2. Liquity- LUSD
    3. Reflexer- RAI
2. Indirect Competitors:
    1. Tether- USDT
    2. Circle- USDC

### Competitive Advantage:

- Less volatile as a result of gold backing
- Our collateral-to-loan ratio is 102% with a maximum leverage of 50x v/s LUSD, (LUSD) collateral-to-loan ratio is 110% with a maximum leverage of 11x.
- The novelty of the gold standard

# Distribution Strategy - GTM :

1. Vesting the governance token for an initial $1 billion trading volume.
2. Early LP providers earn high APRs as they hold more weight in the pool for the same amount of fees generated.
3. On top of our own governance token, we prioritise Maker MKR and LQTY token holders to receive increased rewards and votes in governance.
4. It is marketed as a gold-backed stablecoin that can be borrowed at 102% interest-free.

### Target Audience:

> Institutions & Investment DAOs
> 

> Investors seeking Arbitrage
> 

> LP providers
> 

> Individual Crypto Investors
> 

# Market Size :

<aside>
💡 Total Available Market: 137 Billion USD

</aside>

<aside>
💡 Serviceable Available Market: 20 Billion USD

</aside>

<aside>
💡 Serviceable Obtainable Market: 5 Billion USD

</aside>

# Team XaU Labs:

1. Nuthan Prasad - Smart contract Developer.
2. Lokesh P Velayudham - Full stack developer & Business.
3. Gathin - Full-stack Blockchain Developer
