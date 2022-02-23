## Sūrya's Description Report

### Files Description Table


|  File Name  |  SHA-1 Hash  |
|-------------|--------------|
| dist/AmazingERC20.dist.sol | 59e1e94b7242e9441fc8b24f88226082cbe3d940 |


### Contracts Description Table


|  Contract  |         Type        |       Bases      |                  |                 |
|:----------:|:-------------------:|:----------------:|:----------------:|:---------------:|
|     └      |  **Function Name**  |  **Visibility**  |  **Mutability**  |  **Modifiers**  |
||||||
| **Context** | Implementation |  |||
| └ | _msgSender | Internal 🔒 |   | |
| └ | _msgData | Internal 🔒 |   | |
||||||
| **IERC20** | Interface |  |||
| └ | totalSupply | External ❗️ |   |NO❗️ |
| └ | balanceOf | External ❗️ |   |NO❗️ |
| └ | transfer | External ❗️ | 🛑  |NO❗️ |
| └ | allowance | External ❗️ |   |NO❗️ |
| └ | approve | External ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | External ❗️ | 🛑  |NO❗️ |
||||||
| **SafeMath** | Library |  |||
| └ | tryAdd | Internal 🔒 |   | |
| └ | trySub | Internal 🔒 |   | |
| └ | tryMul | Internal 🔒 |   | |
| └ | tryDiv | Internal 🔒 |   | |
| └ | tryMod | Internal 🔒 |   | |
| └ | add | Internal 🔒 |   | |
| └ | sub | Internal 🔒 |   | |
| └ | mul | Internal 🔒 |   | |
| └ | div | Internal 🔒 |   | |
| └ | mod | Internal 🔒 |   | |
| └ | sub | Internal 🔒 |   | |
| └ | div | Internal 🔒 |   | |
| └ | mod | Internal 🔒 |   | |
||||||
| **ERC20** | Implementation | Context, IERC20 |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | name | Public ❗️ |   |NO❗️ |
| └ | symbol | Public ❗️ |   |NO❗️ |
| └ | decimals | Public ❗️ |   |NO❗️ |
| └ | totalSupply | Public ❗️ |   |NO❗️ |
| └ | balanceOf | Public ❗️ |   |NO❗️ |
| └ | transfer | Public ❗️ | 🛑  |NO❗️ |
| └ | allowance | Public ❗️ |   |NO❗️ |
| └ | approve | Public ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | Public ❗️ | 🛑  |NO❗️ |
| └ | increaseAllowance | Public ❗️ | 🛑  |NO❗️ |
| └ | decreaseAllowance | Public ❗️ | 🛑  |NO❗️ |
| └ | _transfer | Internal 🔒 | 🛑  | |
| └ | _mint | Internal 🔒 | 🛑  | |
| └ | _burn | Internal 🔒 | 🛑  | |
| └ | _approve | Internal 🔒 | 🛑  | |
| └ | _setupDecimals | Internal 🔒 | 🛑  | |
| └ | _beforeTokenTransfer | Internal 🔒 | 🛑  | |
||||||
| **ERC20Burnable** | Implementation | Context, ERC20 |||
| └ | burn | Public ❗️ | 🛑  |NO❗️ |
| └ | burnFrom | Public ❗️ | 🛑  |NO❗️ |
||||||
| **IERC165** | Interface |  |||
| └ | supportsInterface | External ❗️ |   |NO❗️ |
||||||
| **IERC1363** | Interface | IERC20, IERC165 |||
| └ | transferAndCall | External ❗️ | 🛑  |NO❗️ |
| └ | transferAndCall | External ❗️ | 🛑  |NO❗️ |
| └ | transferFromAndCall | External ❗️ | 🛑  |NO❗️ |
| └ | transferFromAndCall | External ❗️ | 🛑  |NO❗️ |
| └ | approveAndCall | External ❗️ | 🛑  |NO❗️ |
| └ | approveAndCall | External ❗️ | 🛑  |NO❗️ |
||||||
| **IERC1363Receiver** | Interface |  |||
| └ | onTransferReceived | External ❗️ | 🛑  |NO❗️ |
||||||
| **IERC1363Spender** | Interface |  |||
| └ | onApprovalReceived | External ❗️ | 🛑  |NO❗️ |
||||||
| **Address** | Library |  |||
| └ | isContract | Internal 🔒 |   | |
| └ | sendValue | Internal 🔒 | 🛑  | |
| └ | functionCall | Internal 🔒 | 🛑  | |
| └ | functionCall | Internal 🔒 | 🛑  | |
| └ | functionCallWithValue | Internal 🔒 | 🛑  | |
| └ | functionCallWithValue | Internal 🔒 | 🛑  | |
| └ | functionStaticCall | Internal 🔒 |   | |
| └ | functionStaticCall | Internal 🔒 |   | |
| └ | functionDelegateCall | Internal 🔒 | 🛑  | |
| └ | functionDelegateCall | Internal 🔒 | 🛑  | |
| └ | _verifyCallResult | Private 🔐 |   | |
||||||
| **ERC165Checker** | Library |  |||
| └ | supportsERC165 | Internal 🔒 |   | |
| └ | supportsInterface | Internal 🔒 |   | |
| └ | getSupportedInterfaces | Internal 🔒 |   | |
| └ | supportsAllInterfaces | Internal 🔒 |   | |
| └ | _supportsERC165Interface | Private 🔐 |   | |
| └ | _callERC165SupportsInterface | Private 🔐 |   | |
||||||
| **ERC165** | Implementation | IERC165 |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | supportsInterface | Public ❗️ |   |NO❗️ |
| └ | _registerInterface | Internal 🔒 | 🛑  | |
||||||
| **ERC1363** | Implementation | ERC20, IERC1363, ERC165 |||
| └ | <Constructor> | Public ❗️ | 🛑  | ERC20 |
| └ | transferAndCall | Public ❗️ | 🛑  |NO❗️ |
| └ | transferAndCall | Public ❗️ | 🛑  |NO❗️ |
| └ | transferFromAndCall | Public ❗️ | 🛑  |NO❗️ |
| └ | transferFromAndCall | Public ❗️ | 🛑  |NO❗️ |
| └ | approveAndCall | Public ❗️ | 🛑  |NO❗️ |
| └ | approveAndCall | Public ❗️ | 🛑  |NO❗️ |
| └ | _checkAndCallTransfer | Internal 🔒 | 🛑  | |
| └ | _checkAndCallApprove | Internal 🔒 | 🛑  | |
||||||
| **Ownable** | Implementation | Context |||
| └ | <Constructor> | Public ❗️ | 🛑  |NO❗️ |
| └ | owner | Public ❗️ |   |NO❗️ |
| └ | renounceOwnership | Public ❗️ | 🛑  | onlyOwner |
| └ | transferOwnership | Public ❗️ | 🛑  | onlyOwner |
||||||
| **TokenRecover** | Implementation | Ownable |||
| └ | recoverERC20 | Public ❗️ | 🛑  | onlyOwner |
||||||
| **ERC20Mintable** | Implementation | ERC20 |||
| └ | mintingFinished | Public ❗️ |   |NO❗️ |
| └ | mint | Public ❗️ | 🛑  | canMint |
| └ | finishMinting | Public ❗️ | 🛑  | canMint |
| └ | _finishMinting | Internal 🔒 | 🛑  | |
||||||
| **IPayable** | Interface |  |||
| └ | pay | External ❗️ |  💵 |NO❗️ |
||||||
| **ServicePayer** | Implementation |  |||
| └ | <Constructor> | Public ❗️ |  💵 |NO❗️ |
||||||
| **AmazingERC20** | Implementation | ERC20Mintable, ERC20Burnable, ERC1363, TokenRecover, ServicePayer |||
| └ | <Constructor> | Public ❗️ |  💵 | ERC1363 ServicePayer |
| └ | _mint | Internal 🔒 | 🛑  | onlyOwner |
| └ | _finishMinting | Internal 🔒 | 🛑  | onlyOwner |


### Legend

|  Symbol  |  Meaning  |
|:--------:|-----------|
|    🛑    | Function can modify state |
|    💵    | Function is payable |
