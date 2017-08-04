# ens.bid progress

## Web design
透過material design設計一個風格漂亮好操作的網站，設計概念需要比ens.domains好操作

## Landing page
- ICO 介紹
- ENS 介紹
- ENS Register

## DApp
- 串接 INFURA，提供購買ENS的服務
- 建構 Escrow 的平台
    - 鏈外搓合、鏈上透過履約保證交易ENS
- 建構 Load 的平台
    - 鏈上質借ENS，並且計算利息

## Whitepaper
- 介紹ENS如何改善Ethereum網路架構，並且描述其必要性與願景
- 簡介現實世界中domain name的交易量與成長速度
- 敘述ENS跟domain name擁有的價值，並且大型企業都出高價購買domain name，Ethereum未來勢必有重要的DApp或者服務會出現
    - ENS的唯一性
    - ENS的好處，方便記憶，也不容易被駭客竄改
    - 結合 IPFS 後的去中心化域名形式
- Token分配的模式
    - 50%的股權會被販售出去，並且剩下的50%將會鎖定一年以上
- ENS Escrow 的流程，與獲利模式
    - 提供履約保證合約協助交易，並且從中抽取手續費
- ENS Loan 的流程，與獲利模式
    - 提供抵押ETH域名，獲得ETH，可以在一定期間內贖回，從中收取利息，概念類似資產擔保借款的概念

## Marketing
- Google AdWord
- ICO website
    - Smith & Crown
    - TokenMarket
    - ICOTracker

## Smart Contract
This project defined 4 contract to handle all process.

### Wallet
保存ICO期間所發售的Token換來的ETH，這邊可以照個人參與比例領取等值的EHT

### ERC20
ICO販售的主要合約，Token是用來作為領取 Escrow & Loan 的憑證，每當一筆 Escrow 或 Loan 交易完成，系統都會記錄所有代幣得領取權利

### Escrow
ENS交易履約保證合約，合約會跟賣方抽取1％的手續費

### Loan
ENS借款的合約，借款成立將會從wallet支付款項，並且取得ENS的所有權，並且記錄贖回的時間點，超過期限則該網域歸為ens.bid所有，並且期滿後可以兌現

## Road Map
預計整個項目完成一至兩個月  

### 短期項目

1. Website/Landing page
2. Whitepaper
3. Contract(ERC20, Wallet)
4. Website/DApp
5. Marketing

### 中期項目

1. Escrow
2. Loan

# Members

- Phyrex
- Yan
- Park
- Johnny
- Wesley
