# BSC全能分红代币合约

支持分红SHIB/ETH/USDT/DOGE等BSC所有代币。

# 源码：
https://github.com/tmimehi/dividendcontract/blob/main/dividendcontract.sol


# 如果遇到问题可联系TG：

https://t.me/zvx_Staff


# 编译/开源参数

COMPILER: v0.8.7+commit.e28d00a7.js

Enable optimization: 开启并使用默认值200

Other Settings: default evmVersion, MIT license

# 部署参数

Value填写：200000000000000000 （0.2BNB）

CONTRACT 选择 dividendcontract，

name_: BTC COIN (代币名称)

symbol_: BTC (代币简称)

totalSupply_: 21000000 (发行量 发多少就写多少)

rewardAddr_: 要分红的代币合约，BSC常用代币地址在下方

marketingWalletAddr_:      你自己的营销钱包地址

buyFeeSetting_: [4,3,2,1] (分红、流动性、营销钱包、燃烧)

sellFeeSetting_: [5,4,3,2] (分红、流动性、营销钱包、燃烧)

tokenBalanceForReward_: 10000000000000000000000 (持有多少代币参与分红。数量后要加18个0)

# BSC常用代币合约地址

SHIB: 0x2859e4544C4bB03966803b044A93563Bd2D0DD4D

USDT: 0x55d398326f99059fF775485246999027B3197955

ETH: 0x2170Ed0880ac9A755fd29B2688956BD959F933F8

DOGE: 0xbA2aE424d960c26247Dd6c32edC70B295c744C43

BUSD: 0xe9e7CEA3DedcA5984780Bafc599bD69ADd087D56

CAKE: 0x0E09FaBB73Bd3Ade0a17ECC321fD13a19e81cE82

# Remix

https://remix.ethereum.org/

# TG电报群交流群

https://t.me/ZVX_Official
