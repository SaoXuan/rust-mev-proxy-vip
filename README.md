# rust-mev-proxy-vip
本软件非免费试用，需要购买授权，请勿用于非法用途。
[官方网站 ：https://www.solboxs.com/proxy](https://www.solboxs.com/proxy)

[使用教程：https://rust-mev-bot.solboxs.com/basics/proxy-fu-wu](https://rust-mev-bot.solboxs.com/basics/proxy-fu-wu)

## 使用说明

1. 下载本软件，解压后，修改config.yaml文件，配置jito_engine和rpc_type
2. 运行本软件，启动后，会自动扫描网卡，获取ip地址，并启动多个线程，每个线程会启动一个http服务，监听8081端口
3. 需要配置你的套利钱包和支付费用的签名tx，否则程序鉴权会失败，只能使用支付费用的钱包进行套利，否则程序会自动停止
4. 支付钱包地址：G53haKTkFHUjex3tsAsdukkZTgirU74rJg5UkRmsTBZL  需要支付USDC，否则无法使用，只支持USDC
5. 需要你手动设置修改系统的ulimit 否则ip太多，系统的描述符会不够用，导致程序无法正常运行

### 授权方案

| 支付金额 | 使用期限 |
|---------|---------|
| 200 USDC | 30 天 |
| 500 USDC | 100 天 |
| 1000 USDC | 240 天 |

## 免责声明

- 本软件为付费授权使用
- 严禁用于非法用途
- 使用前请确保符合当地法律法规

