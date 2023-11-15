# azos-hub
Entrance to the Azos Development ecosystem.

Azos has four key software components:

1. The ***Front End User Interface*** which allows users to interact with the Azos protocol in order to lock collateral and mint new stablecoins.
2. The ***Smart Contract*** Protocol which controls and manages the on-chain components of collateralized debt positions, vault management, creation and annhilation of debt, minting and burning of the stablecoins and our "Silurian" stability module.
3. Our ***Subgraph;*** which is essentially a database that is constructed by watching the on-chain actions and events.  This allows our front end to be aware of any changes made on-chain.
4. The ***Stability Keeper*** is an automated market making bot designed to maintain the peg of our stablecoin by triggering the Stability Module.  This will keep our stablecoin price stable, generate protocol revenue and increase the capital efficiency and help scale the supply of our stablecoin.

## Project Structure

We have each of our individual code repositories isolated for quick workflow and testing:

[Front End User Interface](https://github.com/AzosFinance/azos-frontend)

[Smart Contracts](https://github.com/AzosFinance/azos-protocol)

[Subgraph](https://github.com/AzosFinance/azos-subgraph)

[Stability Keeper](https://github.com/AzosFinance/azos-keeper)

## Videos

All of these videos are available from the DoraHacks BUIDL page:

[Promo Video](https://www.youtube.com/watch?v=wTx_2Tcgg-4)

[Stability Keeper Video](https://youtu.be/ndDWxjQeFGs)

[Application Walkthrough](https://youtu.be/W5JDe2h4ID8)

## Sepolia Testnet

User will need [Sepolia Testnet Eth](https://sepoliafaucet.com/) to transact. 
