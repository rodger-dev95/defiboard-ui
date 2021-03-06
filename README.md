![defiboard-green-logo](https://user-images.githubusercontent.com/102347045/169810777-01d0325c-e4f1-40ef-a563-f5e9b5bf2c43.png)

# Description

DefiBoard is mange portafolio, Budget Manger, Multiswap and multi-chain analytic dashboard, a tool for Investors, Cryptocurrence holders to visualize, analyse data on various blockchains and decentralization exchanges on one platform.

Building a platform that helps users to remain on one platform that provides all the tools needed by Investors, Cryptocurrency holders, traders, etc.

This project provided a simple way to track, analyze and visualize all data assets.With the usage of COVALENT API we are able to bringing visibility to billions of blockchain data points on this Dashboard- Covalent API Reference Contrived for investors and the financially diligent, who lack the ability to manage their finances privately and securely, Defiboard is a self-hosted and open-source solution that allows them to track their income and investments through a unified interface featuring a website, cross-platform desktop app, and Android mobile app. User data is encrypted on the client-side using military-grade AES-256 encryption.

Users can utilize the app to budget their monthly income, record everyday transactions, track their stock and cryptocurrency investments, record their trading activity, and easily manage or backup their data through intuitive import and export functionalities. Furthermore, users can discover new assets they may want to invest in, and keep track of ones they’re interested in.

DefiBoard showcase

How it's made APIs Cryptocurrency Market Data: CoinGecko

Stock Market Data: Yahoo Finance


# Bounty List 

## Transak : 
Using Transac use can buy any cryptocurrency right from DefiBoard application below is the demo video please click below to watch quick demo



[![Transak Video](https://user-images.githubusercontent.com/102347045/169801750-1a7fad4c-8272-4f72-b2b7-3716708de1aa.png)](https://vimeo.com/712807831 " - Click to Watch!")




## Covalent: 
using covalent api for fetch data that used to track different currency, exchange and liquidity and more.. click below to watch quick demo


```
async function fetchPools(chainId, dexName) {
return request(
    "GET",
    "https://api.covalenthq.com/v1/${chainId}/xy=k/${dexName}/pools/?quote-currency=USD&format=JSON&key=${API_KEY}"
  );
} 	
```


[click here to see the code](https://github.com/defiboard/defiboard-ui/blob/e01bcba399cfef34a6f8d9488539e53b35b136cb/web/assets/js/functions/pools.js)

[![Covalent Video](https://user-images.githubusercontent.com/102347045/169799533-5343c22d-a0a1-4289-99b1-99eb17f3184d.png)](https://vimeo.com/712816681 "- Click to Watch!")



## Coinbase: 
by connecting coinbase you can make transactions.. click below to watch quick demo

```
    options: {
      appName: "Coinbase",
      networkUrl: `https://mainnet.infura.io/v3/f0fd1047ce8742fdb72ae697111b9d64`,
      chainId: 1,
    }
```
[click here to see the code](https://github.com/defiboard/defiboard-ui/blob/a4e719b61cea015c49c396d69f4272f2e7050bd1/web/assets/js/wallet/wallet.js)
 
![conbase short](https://user-images.githubusercontent.com/102347045/169817411-6688a191-3adf-4dd9-bb58-153d847f8b14.gif)


```
    options: {
      appName: "Coinbase",
      networkUrl: `https://mainnet.infura.io/v3/f0fd1047ce8742fdb72ae697111b9d64`,
      chainId: 1,
    }
```

[click here to see the code](https://github.com/defiboard/defiboard-ui/blob/a4e719b61cea015c49c396d69f4272f2e7050bd1/web/assets/js/wallet/wallet.js)

## WalletConnect :

![wallet connect demo (1)](https://user-images.githubusercontent.com/102347045/169815897-f10dde31-9049-47b2-988e-4483eeeda6d6.gif)


```
  walletconnect: {
    package: WalletConnectProvider,
    options: {
      infuraId: "f0fd1047ce8742fdb72ae697111b9d64",
    },
  }
```

[click here to see the code](https://github.com/defiboard/defiboard-ui/blob/a4e719b61cea015c49c396d69f4272f2e7050bd1/web/assets/js/wallet/wallet.js)

## Swing :

![swing demo](https://user-images.githubusercontent.com/102347045/169872942-5be7c90f-4e29-42fb-91cf-c1a41d69ccbb.png)



```
 async function fetchSwingData(params) {
  return request(
    "GET",
    `https://swap.dev.swing.xyz/v0/transfer/quote?${formatParams(params)}`
  );
}
```

[click here to see the code](https://github.com/defiboard/defiboard-ui/blob/aa8e738e2fe2d0e85914b6f32aedaba3f507f18d/web/assets/js/wallet/swing.js)

uniswap for widget swap

Tech Stack Database: SQLite

App API: Node.js, TypeScript, GraphQL

Chat Bot API: Node.js, TypeScript, Socket.IO, Natural Language Processing

Web App: HTML, CSS, JavaScript

Desktop App: Electron, EJS, HTML, CSS, JavaScript
