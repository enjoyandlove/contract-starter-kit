## Sūrya's Description Report

### Files Description Table


|  File Name  |  SHA-1 Hash  |
|-------------|--------------|
| dist/SampleContract.dist.sol | a40ac8159bc68e9f3c80a918b1d8a989d9dc137d |


### Contracts Description Table


|  Contract  |         Type        |       Bases      |                  |                 |
|:----------:|:-------------------:|:----------------:|:----------------:|:---------------:|
|     └      |  **Function Name**  |  **Visibility**  |  **Mutability**  |  **Modifiers**  |
||||||
| **IERC20** | Interface |  |||
| └ | transfer | External ❗️ | 🛑  |NO❗️ |
| └ | approve | External ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | External ❗️ | 🛑  |NO❗️ |
| └ | totalSupply | External ❗️ |   |NO❗️ |
| └ | balanceOf | External ❗️ |   |NO❗️ |
| └ | allowance | External ❗️ |   |NO❗️ |
||||||
| **Ownable** | Implementation |  |||
| └ | \<Constructor\> | Internal 🔒 | 🛑  | |
| └ | owner | Public ❗️ |   |NO❗️ |
| └ | isOwner | Public ❗️ |   |NO❗️ |
| └ | renounceOwnership | Public ❗️ | 🛑  | onlyOwner |
| └ | transferOwnership | Public ❗️ | 🛑  | onlyOwner |
| └ | _transferOwnership | Internal 🔒 | 🛑  | |
||||||
| **TokenRecover** | Implementation | Ownable |||
| └ | recoverERC20 | Public ❗️ | 🛑  | onlyOwner |
||||||
| **SampleContract** | Implementation | TokenRecover |||
| └ | \<Constructor\> | Public ❗️ | 🛑  | |
| └ | creator | Public ❗️ |   |NO❗️ |
| └ | creatorDoesWork | Public ❗️ | 🛑  | onlyCreator |
| └ | ownerDoesWork | Public ❗️ | 🛑  | onlyOwner |


### Legend

|  Symbol  |  Meaning  |
|:--------:|-----------|
|    🛑    | Function can modify state |
|    💵    | Function is payable |
