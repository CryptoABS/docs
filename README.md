# Ethereum Name Service Bid Documents

- Website: [ens.bid](https://ens.bid)
- Contract: [escrow contract](https://github.com/ens-bid/contracts)

## Why need ens.bid?
Ethereum Name Service<sup>[1]</sup> 將會是對 Ethereum 跨入應用階段前非常重要的基礎設施，鑒於目前所有的 Ethereum address 都是 non-human readable 的一串 hash，所以透過 ENS 將 `.eth` 解析後，變成一個人為能夠理解的網址是非常重要的。  
駭客透過竄改 ICO 網站的 Contract address，導致項目遭遇到嚴重的損失<sup>[2]</sup>，如果該 Contract address 是透過一個可以被人為閱讀的 `.eth` 這種駭客行為是可以很迅速被發現。

## What is ens.bid?
透過去中心化的理念，創造一個 ENS 交易平台，提供有興趣參與 ens 交易的買賣雙方，能夠有一個安全以及方便的平台來交易。  
ens.bid 會透過智能合約的輔助，協助雙方透過一個可信任的依據完成交易。  
網站的部分會提供競標形式與固定價格的方式來提供 `.eth` 網域的交易。

## How is ens.bid work?
- DApp
    - 競標
    - 固定價格
- Contract
    - 履約保證合約

## Reference
1. [Ethereum Name Service](http://ens.domains/)
2. [CoinDash Hack News](https://www.hackread.com/coindash-token-sale-ico-website-hacked-ethereum-stolen-2/)

----
## Authors

[Phyrex Tsai](https://github.com/PhyrexTsai)
