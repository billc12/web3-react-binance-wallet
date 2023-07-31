web3-react-binance-wallet
Support web3-react(https://github.com/Uniswap/web3-react)

# How to use it

1. Install web3-react first.
2. download the code or npm install web3-react-binance-wallet
3. import it

# Example

```javascript
import { initializeConnector } from "@web3-react/core";
import { BinanceWallet } from "web3-react-binance-wallet";

export const [BinanceWallet, hooks] = initializeConnector<BinanceWallet>((actions) => new BinanceWallet({ actions }));
```
