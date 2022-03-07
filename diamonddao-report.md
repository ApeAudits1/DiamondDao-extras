## Sūrya's Description Report

### Files Description Table


|  File Name |
|-------------|
| DiamondDao.sol |


### Contracts Description Table


|  Contract  |         Type        |       Bases      |                  |                 |
|:----------:|:-------------------:|:----------------:|:----------------:|:---------------:|
|     └      |  **Function Name**  |  **Visibility**  |  **Mutability**  |  **Modifiers**  |
||||||
| **DiamondDao** | Implementation | ERC721Enumerable, Ownable |||
| └ | <Constructor> | Public ❗️ | 🛑  | ERC721 |
| └ | _baseURI | Internal 🔒 |   | |
| └ | isWW | Public ❗️ |   |NO❗️ |
| └ | tokenURI | Public ❗️ |   |NO❗️ |
| └ | walletOfOwner | Public ❗️ |   |NO❗️ |
| └ | mint | Public ❗️ |  💵 |NO❗️ |
| └ | Airdrop | External ❗️ | 🛑  | onlyOwner |
| └ | TurnRevealMode | Public ❗️ | 🛑  | onlyOwner |
| └ | addWW | Public ❗️ | 🛑  | onlyOwner |
| └ | SetisPauseMode | Public ❗️ | 🛑  | onlyOwner |
| └ | SetisPresalesMode | Public ❗️ | 🛑  | onlyOwner |
| └ | setPrice | Public ❗️ | 🛑  | onlyOwner |
| └ | setPricePS | Public ❗️ | 🛑  | onlyOwner |
| └ | setBaseURI | Public ❗️ | 🛑  | onlyOwner |
| └ | setNotRevealedURI | Public ❗️ | 🛑  | onlyOwner |
| └ | withdraw | Public ❗️ |  💵 | onlyOwner |


### Legend

|  Symbol  |  Meaning  |
|:--------:|-----------|
|    🛑    | Function can modify state |
|    💵    | Function is payable |
