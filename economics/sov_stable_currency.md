# 💵 $SOV: The Sovereign Unit of Account
**Classification:** Over-Collateralized Stable Currency
**Peg Target:** 1 $SOV = $1.00 USD
**Collateral Backing:** The Bitopia BTC Endowment Fund

## 1. The Core Philosophy
A sovereign Network State cannot function if its daily unit of account fluctuates by 10% a day. Citizens need stability to buy coffee, pay for server hosting, or lease orbital bandwidth. `$SOV` serves as the frictionless medium of exchange within the Bitopia jurisdiction, pegged to the familiar unit of the US Dollar, but fundamentally backed by the hardest asset in human history: Bitcoin.

## 2. The BTC Endowment Fund (The Reserve)
Unlike terrestrial fiat, which is backed by the promise of future taxation, `$SOV` is backed by cryptographic truth. The Treasury maintains a multisig Bitcoin Endowment Fund. 

To ensure the peg never breaks (avoiding algorithmic "death spirals"), `$SOV` is strictly **over-collateralized**.

**The Collateralization Ratio (CR):**
The total USD value of the BTC in the reserve ($V_{BTC}$) must always exceed the total circulating supply of `$SOV` ($V_{SOV}$). The target minimum CR is 150%.

$$CR = \frac{V_{BTC}}{V_{SOV}} \ge 1.5$$

## 3. Minting and Burning Mechanics
* **Minting:** To mint new `$SOV` into circulation, a Citizen or the State must deposit and lock BTC into the Endowment Fund smart contract.
* **Burning:** A Citizen can always redeem their `$SOV` for the equivalent USD value of BTC from the Endowment Fund. The redeemed `$SOV` is cryptographically burned, removing it from circulation and maintaining the peg.
* **Liquidations:** If the price of BTC drops significantly and a specific vault's CR approaches the 110% danger zone, the protocol automatically liquidates a portion of the collateral to buy back and burn `$SOV`, defending the $1.00 peg at all costs.

## 4. Velocity and Utility
`$SOV` is the lifeblood of the Bitopia micro-economy. It is used for:
* Purchasing E-Watt computational power from the Bitaris swarm.
* Daily peer-to-peer commerce between Citizens.
* Paying minimal gas/transaction fees on the BLOCKS ledger.
* Compensating terrestrial subsidiaries for compliance and legal shielding.
