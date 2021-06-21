
# Election - 一个投票 DAPP Demo



## 依赖
安装依赖
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/


## Step 1. 克隆代码
`git clone https://github.com/tyroyang/election.git`

## Step 2. 安装依赖
```
$ cd election
$ npm install
```
## Step 3. 启动Ganache 


## Step 4. 编译部署合约

`$ truffle migrate --reset`
You must migrate the election smart contract each time your restart ganache.

## Step 5. 配置MetaMask

See free video tutorial for full explanation of these steps:
- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

## Step 6. 启动
`$ npm run dev`
Visit this URL in your browser: http://localhost:3000

