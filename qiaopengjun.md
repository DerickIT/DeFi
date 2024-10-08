---
timezone: Asia/Shanghai
---

> 请在上边的 timezone 添加你的当地时区，这会有助于你的打卡状态的自动化更新，如果没有添加，默认为北京时间 UTC+8 时区
> 时区请参考以下列表，请移除 # 以后的内容

timezone: Pacific/Honolulu # 夏威夷-阿留申标准时间 (UTC-10)

timezone: America/Anchorage # 阿拉斯加标准时间 (UTC-9)

timezone: America/Los_Angeles # 太平洋标准时间 (UTC-8)

timezone: America/Denver # 山地标准时间 (UTC-7)

timezone: America/Chicago # 中部标准时间 (UTC-6)

timezone: America/New_York # 东部标准时间 (UTC-5)

timezone: America/Halifax # 大西洋标准时间 (UTC-4)

timezone: America/St_Johns # 纽芬兰标准时间 (UTC-3:30)

timezone: America/Sao_Paulo # 巴西利亚时间 (UTC-3)

timezone: Atlantic/Azores # 亚速尔群岛时间 (UTC-1)

timezone: Europe/London # 格林威治标准时间 (UTC+0)

timezone: Europe/Berlin # 中欧标准时间 (UTC+1)

timezone: Europe/Helsinki # 东欧标准时间 (UTC+2)

timezone: Europe/Moscow # 莫斯科标准时间 (UTC+3)

timezone: Asia/Dubai # 海湾标准时间 (UTC+4)

timezone: Asia/Kolkata # 印度标准时间 (UTC+5:30)

timezone: Asia/Dhaka # 孟加拉国标准时间 (UTC+6)

timezone: Asia/Bangkok # 中南半岛时间 (UTC+7)

timezone: Asia/Shanghai # 中国标准时间 (UTC+8)

timezone: Asia/Tokyo # 日本标准时间 (UTC+9)

timezone: Australia/Sydney # 澳大利亚东部标准时间 (UTC+10)

timezone: Pacific/Auckland # 新西兰标准时间 (UTC+12)

---

# {你的名字}

1. 自我介绍
   Qiao Pengjun 乔鹏军。三年左右Python开发。有Python、Go、Rust、solidity的开发经验。大约是去年开始了解Web3，最近在学习solidity。对区块链技术很感兴趣。了解了一点Solana、Sui、Starknet... 正在继续学习。希望本次学习能让我更深入的了解Web3。拥抱Web3，拥抱未来。
2. 你认为你会完成本次残酷学习吗？
   我认为我会完成本次残酷学习，因为我有信心，并且我相信我能够克服任何困难。

## Notes

<!-- Content_START -->

### 2024.08.19

#### 稳定币

稳定币是DeFi 三大支柱之一，稳定币是去中心化金融（DeFi）的核心组成部分，它为用户提供了一种安全、稳定的货币，可以用于交易、借贷、投资等各种金融活动。稳定币的发行和交易过程通常不需要中心化机构的介入，而是通过智能合约在区块链上进行。这使得稳定币具有很高的透明度和安全性，同时也为用户提供了更多的金融选择和灵活性。

稳定币的发行通常需要一种锚定资产，如美元、欧元等，以确保其价值稳定。稳定币的发行方需要定期对锚定资产进行评估，并根据评估结果调整稳定币的供应量，以保持其价值稳定。稳定币的发行方通常需要持有一定数量的锚定资产作为储备，以确保其价值稳定。

稳定币的安全性主要依赖于其发行方的信誉和透明度。稳定币的发行方需要定期公布其储备情况，以确保用户对其信任。同时，稳定币的发行方还需要遵守相关的法律法规，以确保其合法性和安全性。

区块链提供比传统银行系统更高级别的安全性，交易通过加密保护并直接发送到用户的钱包。要通过区块链完成交易，您只需正确输入您的钱包地址，即可保证转账不会有被盗风险。唯一的风险是用户错误，因为您没有中介机构（银行）来纠正任何错误。这种个人责任制是一种安全福利，也是一种人为错误风险；加密转账的新世界需要个人责任制。

#### 稳定币分类

#### Off-Chain Collateralized Stablecoins

We have different classes of the off-chained collateralized stablecoins which are;

1.      Fiat Collateralized stablecoins

2.      Commodity Collateralized stablecoins

稳定币的风险

- 稳定币受其所挂钩资产的健康状况影响。
- 监管始终会给这些中心化的链下抵押稳定币带来风险。
- 当涉及链下抵押资产时，总是存在交易对手风险。如果公司没有现金储备，稳定币的价值就会螺旋式下降。用户应该注意透明度报告。
- 价格攻击（价格操纵攻击）也是稳定币面临的一个风险，通常被称为二级市场操纵。

#### Crypto-collateralized Stablecoins

由于加密资产通常波动较大，因此加密抵押稳定币需要超额抵押，以确保其与美元保持挂钩。

优势

- 无需信任
- 无需许可、不受审查和监管
弱点
- 维持挂钩的困难以及克服它的权衡
- 资本效率低下。在此背景下，资本效率是指必须锁定以支持稳定币的抵押品数量。加密抵押稳定币是资本效率最低的稳定币类型，因为它们需要超额抵押。

#### Algorithmic Stablecoins

算法稳定币通过使用算法来维持其价值，而不是使用抵押品。算法稳定币的价值取决于其算法，该算法根据市场情况调整稳定币的供应量。算法稳定币的价值通常与美元挂钩，但也可以与其他资产挂钩。

算法稳定币的优势

- 无需抵押品：算法稳定币的核心特征是它们不依赖传统的抵押品，而是通过编程算法来动态调节稳定币的供应，以维持其目标价值。这与抵押型稳定币（如USDT或DAI）不同，后者依赖于储备资产来支撑其价值。
- 无需信任：：这种说法在某些情况下是正确的，尤其是在算法完全去中心化和公开的情况下。然而，如果算法是由中心化实体控制或存在缺乏透明度的问题，则这一点可能不成立。
- 无需许可、不受审查和监管：理论上，去中心化的算法稳定币是无需许可的，即任何人都可以在没有中介或审查的情况下使用它们。然而，实际上，许多算法稳定币仍可能面临监管挑战，尤其是在某些国家或地区。
- 由于无需锁定任何抵押品，算法稳定币是三种类型中资本效率最高的稳定币。然而，这种资本效率的代价是潜在的稳定性风险。
算法稳定币的弱点

- 算法风险：算法本身的设计和实施存在风险，尤其是在极端市场条件下，算法可能无法按预期工作，导致稳定币价格大幅波动。
- 挂钩资产的风险：如果稳定币的价值挂钩于某一特定资产（如美元），那么挂钩资产的波动性或信用风险也会影响稳定币的稳定性。
- 交易对手风险：虽然算法稳定币理论上应减少交易对手风险，但在某些情况下（如依赖于第三方运营的系统或智能合约漏洞），仍可能存在交易对手风险。
- 中心化风险：如果算法由少数实体控制，或者治理机制不透明，算法稳定币可能存在中心化的风险，这会影响其去中心化的声誉和安全性。
- 未经测试且高风险：许多算法稳定币尚未经过长期市场测试，一旦遭遇市场剧烈波动或黑天鹅事件，其算法可能无法如预期般维持稳定。

目前，稳定币可以被视为处于早期采用阶段，其中信任正在建立在最低限度可行的解决方案之上，以推动其进入主流。

#### 参考

- <https://banklessdao.substack.com/p/the-stablecoin-edition-defi-download>

### 2024.08.20

中心化稳定币
Tether (USDT)
去中心化稳定币
DAI
算法稳定币利用算法来控制稳定币的市场结构和经济基础。
对各种去中心化的算法稳定币有两种分类方法：

a) 没有抵押品（ESD、AMPL和BAC）

b) 部分/全部由他们自己的原生代币抵押（FRAX、sUSD和UST）

算法稳定币可以进一步细分为不同的类别--主要的子类别是：rebase（弹性）和seigniorage（铸币税）模式。
弹性模式（rebase）
弹性模式通过改变稳定币的全部供应量来控制价格。根据稳定币的价格是高于还是低于预定的挂钩价格，协议将在一个固定的时期内自动增加或减少每个持有人钱包中代币的供应量。
每隔24小时，Ampleforth（AMPL）的全部流通供应量都会按比例增加或减少，以确保价格保持在1美元。
铸币税模式（Seigniorage Model）
铸币税模式通过引入一个动态影响市场的奖励系统来控制价格。如果价格高于挂钩，新的代币就会被铸造出来，并分配给提供流动性或有代币抵押的参与者。

如果价格低于挂钩，代币将停止铸造，并引入机制以减少供应。用户可以购买燃烧相关代币的优惠券，将其从供应中销毁。这些优惠券在未来可以被兑换成更多的代币，但只有当价格回到或超过预定的挂钩时才可以。
Empty Set Dollar
Basis Cash是一种双代币征税模式。
Frax Finance
算法稳定币实际上是DeFi对取代“中央银行”的一种尝试，而算法稳定资产是DeFi模仿黄金标准和创造可靠的数字抵押品的方式。

#### 学习参考

- <https://nigdaemon.gitbook.io/how-to-defi-advanced-zhogn-wen-b/di-6-zhang-qu-zhong-xin-hua-de-wen-ding-bi-he-wen-ding-zi-chan>

### 2024.08.21

起底 MakerDAO RWA，看 DeFi 捕获链下资产的治理体系与交易架构

MakerDAO  或者 DeFi  迫切需要一种更为稳定的基础层抵押品（a Baselayer Level of Collateral），以支持稳定币 DAI  在加密世界大规模采用，构筑一条可持续、可规模化的通路。

RWA  的益处包括：
（1）提高市场风险和资产使用的透明度；
（2）提供 DeFi  的可组合性；
（3）改善银行服务不足和资金不足人群的可触达性；
（4）从更大更稳定传统金融市场中捕获价值。

对于资金体量不大的项目，且在风险可控/可承担的前提下，可以直接采购第三方提供的代币化美债，没有问题。但是我们依然需要思考几个问题：（1）如何保障提供底层资产的交易对手（Red Cedar Digital. Ltd.）不会破产跑路？想想当初如日中天的 FTX；（2）更进一步，交易对手破产之后，这种没有法律实体的链上协议，如何作为债权人去法院参与资产清算/重整？

 DeFi  法律包装的必要性作为几十亿美元 RWA  资金体量的 MakerDAO，无论是在资金的安全角度，还是在法人主体资格层面，都考虑到了目前可识别的风险，这些风险来自：

交易对手风险。试想交易对手破产/跑路的案例，MakerDAO  需要保障的是任何第三方（包括基金经理/投资顾问）都没有能力直接控制、支配、转移其巨额资金；
主体资格认证。链上协议或 DAO  组织无法完成合法持有资产需要的客户识别认证（KYC/AML），导致无法合法购买、持有链下资产。同理，也无法持有自身的 IP  资产；
破产清算资格。一旦出现链下资产的违约、破产、清算情形，由于链上协议或 DAO  并不是一个法律主体，无法立即与现实世界的法院、清算机构做交互。那么就需要保障 MakerDAO  有能力通过治理体系以及法律架构，及时行使处置链下资产的权利。
<https://web3caff.com/zh/archives/80903>

### 2024.08.22

闪电贷直接导致了 DeFi 的成熟，因为一个安全漏洞的暴露会让其他项目在自己的系统中发现并修补相同的漏洞。
AMM 有三种类型：Uniswap、Curve 和 Balancer。Uniswap 的模型是最常见的，它允许用户使用任何一对代币以 50/50 的比例创建流动性池。Curve 创建类似资产的流动性池，而 Balancer 允许最多八种不同代币的资产池。虽然模型不同，但效果是一样的：系统使用户能够以订单簿模型的所有便利性交换代币，同时具有去中心化和无需许可的区块链的 24/7 特性。
在 DeFi 中，如果你有抵押品，你就有能力获得贷款。如果你有资产可以借贷，但对当地信用合作社支付的低于 1% 的利率不感兴趣，DeFi 也有适合你的地方。这就是金融的民主化。
金钱买不到自由，但 DeFi 的自由可以让你用钱做更多的事情。

DeFi 的魅力在于，它使获取复杂的金融服务变得像访问互联网一样简单，而且 DeFi 借贷在多个方面优于传统金融借贷：

可信的中立性：用户无需通过中心化的第三方机构来抵押资产进行贷款。智能合约可处理包括利率、抵押和清算在内的所有事宜。

无需许可：每个人都有相同的贷款渠道，任何人都可以成为贷款人。只要你有资金，你的利率将与地球另一端的人相同。种族、宗教、性别和外貌对你的信誉没有任何影响。

速度：用户不再需要等待贷款审批。这加快了贷款发放流程，因为只要用户拥有必要的抵押品，他们就可以借贷。用户借贷所需的唯一东西就是资金和互联网连接。

透明度：由于所有交易、资金、合约和活动都在链上，因此每个人都可以看到系统的变化和市场条件的变化。

可用性：每天 24 小时都可以通过任何一台连接互联网的计算机访问应用程序。没有银行假期，也无需员工执行交易。

税收影响：借贷协议允许用户利用其加密资产的杠杆敞口，而无需在其抵押品上产生应税事件。
<https://banklessdao.substack.com/p/the-lending-edition-defi-download>

### 2024.08.23

AMM
用户需要一种方式来交换价值（不会因滑点而造成损失）、保管自己的资产并降低交易对手风险。
<http://bafybeidynfkz2mipcr7pv26jlt3i5hqvydzcrr362bbdrc7gkcojwrqouy.ipfs.localhost:8080/general/2017/06/22/marketmakers.html>
AMM 是一组智能合约，可创建资产池，为交易者提供流动性——无需订单簿。

Slippage is the difference between the expected price and what the final price is when the exchange is executed. While slippage occurs in many marketplaces, including stock markets and crypto order book markets, it can be significant in AMMs and DEXs — particularly with large trades and small liquidity pools. Large pools with deep liquidity are better at handling swaps with less slippage.

大多数 AMM 和 DEX 都会显示预计滑点，并允许您设置可接受的滑点限额。但是，设置较低的滑点容忍限额可能会导致您的订单需要很长时间才能完成。

无常损失

虽然流动性提供者从其存入的代币中赚取费用和奖励，但他们也面临着最终可能导致他们亏损的风险：无常损失。当存入资产的市场价格与存入时相比发生变化时，就会发生无常损失。

AMM 流动性池使用算法来维持池中代币价值的稳定比率。例如，50/50 ETH/DAI 池旨在使池中 ETH 代币的价值等于 DAI 代币的价值。如果 ETH 的价格在公开市场上上涨，套利交易者（或机器人）将通过存入 DAI 购买流动性池中低于市场价格的 ETH，直到两种代币的价值比率恢复到 50/50。

因此，当流动性提供者赎回其 LP 代币时，他们可能会发现收到的代币价值低于他们只是将其放在钱包中时的价值。这种损失被称为无常损失，因为在赎回 LP 代币之前，损失是不确定的。如果代币的价格回到存入时的水平，预计的损失将消失。

套利

套利是指交易者利用价格之间或市场内的价差来获利。一个简单的例子是，当交易者发现两个不同的 DEX 上的资产价格存在差异时。如果他们行动迅速，他们可以在一个交易所买入大量低价代币，然后在另一个交易所以更高的价格卖出，赚取差价。

当订单簿交易所的买卖价差较大，或者如上所述，当流动性池中发生无常损失时，也存在其他套利机会。不幸的是，对于人类交易者来说，很难超越被编程为寻找并快速抢占套利机会的机器人的速度。

<https://banklessdao.substack.com/p/the-amm-edition-part-i-defi-download>

### 2024.08.24

集中流动性的引入使 Uniswap 成为有史以来最灵活、最高效的 AMM，同时也解决了创建资本高效的去中心化市场的一些主要挑战。
与其他使用 50/50 资产分割来创建流动性池的 AMM 不同，Balancer 允许用户创建最多包含八种不同代币的池。这些池会根据智能合约自动平衡，从而大大降低无常损失的风险。
DEX 聚合器监控 DeFi 中的多个流动性来源，并使用复杂的算法来检测滑点最小的最优惠利率。
MEV 代表最大可提取价值，是加密生态系统的重要组成部分。它不仅是利润来源，而且是维持系统平衡的无形之手。让我们深入了解它是什么、谁使用它、它的不同类型以及它的优点和缺点。

在一个区块内，经济能量通过所有传入交易流入区块链。MEV Extraction 通过重新排序、包含和排除交易来收获这种能量以获取货币收益。

MEV 搜索者会从大量数据中寻找有利可图的交易（因此得名），并运行自动执行这些交易的机器人。这对矿工也有好处，因为他们可以通过搜索者通常支付的更高 gas 费获得利润分成，以确保他们被纳入下一个区块。要成为一名搜索者，你需要精通技术，懂得如何编码，并愿意应对激烈的竞争。

但是搜索者在哪里可以找到 MEV 机会呢？答案是通过链上数据和内存池。

内存池是所有传入交易的驻留地，等待矿工拾取并包含在下一个区块中。由于此池是公开的，搜索者会对其进行监控以检测可能带来利润的交易。

链上数据也是公开的，也可以进行分析以寻找机会。例如，搜索者可以监控去中心化交易所 (DEX) 上的 ETH 价格。

There is a vast range of different MEV types. We will have an overview on

Arbitrage

Liquidations

Front and Back Running

Sandwich Trading

<https://banklessdao.substack.com/p/the-amm-edition-part-ii-defi-download>

### 2024.08.25

Dex聚合器
DEX聚合器通过汇集不同DEX的流动性来寻找最具成本效益的交易路线。通过在多个流动性池子中路由单一交易，进行大额交易的交易者可以节约gas成本，并尽量减少因流动性低而影响价格的成本。
<https://1inch.io/>

与其他DEX聚合器不同，1inch有两个原生代币。一个是gas代币（CHI），另一个是治理代币（1INCH）。

Matcha
与其他DEX聚合器不同，Matcha在整个交易体验中利用了链上和链下组件的组合。0x API找到最具成本效益的交易路径（包括gas成本），如果发现对交易者更有益，Matcha甚至可以在多个流动性来源之间自动分割单个订单。
除了原生链或流动性来源所需的必要网络费用外，Matcha在技术上不收取交易费用。
与1inch不同的是，Matcha将所有的正向滑点分享给用户。其他值得注意的功能包括限价订单和Matcha最近对Binance智能链网络和Polygon网络的支持。
<https://matcha.xyz/>

ParaSwap
协议收入主要通过两个途径产生。第一个是通过第三方集成商，如果他们对促成的交换收取费用，ParaSwap将收取15%的费用。第二种是通过正向滑点，其中50%直接用于协议，另外50%则与用户分享。 ParaSwap目前有48个流动资金来源。这是由私人做市商提供的本地池（ParaSwapPools）所补充的。ParaSwap最近还在与Binance智能链网络和Polygon网络整合。
<https://www.paraswap.io/>

DEX聚合器的性能因素
路由算法

流动性来源

当前的市场状态

交易的规模
DEX聚合器所产生的成本节约对于较大的交易来说是成比例的，因为它们更容易出现较高的价格滑点。较小的交易可能不需要依赖不同的流动性池，因为单一的流动性池是最理想的途径。
<https://nigdaemon.gitbook.io/how-to-defi-advanced-zhogn-wen-b/di-4-zhang-dex-ju-he-qi>

### 2024.08.26

相关的风险
最好不要将DEX聚合器的报价视为“福音”。虽然DEX聚合器旨在确保执行的交易符合报价，但有时结果与预期会存在偏差。

另一点是交易的规模。尽管DEX聚合商为大型交易提供了更好的成本节约，但对于小型交易者来说，有时直接与DEX互动可能会更好。

DEX聚合器通常是可靠的，但也有交易通过小型和非流动性池的情况。作为一个用户，你应该在批准交易之前始终检查你的滑点是否过高。

DEX聚合器是DeFi可组合性的一个典型例子。DEX聚合器是建立在DEX之上的，以服务于不同的用户。

Ren是一个允许用户在区块链之间匿名交互和转移代币的无需许可协议。Ren协议通过Ren虚拟机（RenVM）提供的RenBridge产品来实现无许可的跨链转移代币。
<https://bridge.renproject.io/>

### 2024.08.27

DeFi 漏洞的原因

- 资本操纵/闪电贷（Flash Loans）
- 在生产环境中测试代码（test in prod）
- 马虎的编码和不充分的审计
- 卷款跑路（Rug Pull）
- 预言机攻击
- Metamask攻击
Metamask的钓鱼网站攻击也是主要风险，它们通过模仿Metamask，让用户输入私钥，盗取用户资产。切记认清Metamask网址
闪电贷（Flash Loans）
闪电贷是一种用户可以在没有任何抵押品的情况下借到资金的贷款模式，只要用户在同一笔交易中偿还了贷款就行。如果用户没有在同一笔交易中偿还贷款，交易将自动失败，同时会产生交易费损失，此时闪电贷不会发生。闪电贷由各种DeFi协议提供，如Aave和dYdX。

与普通贷款相比，闪电贷款有三个主要特点：

没有违约风险。闪电贷在同一笔交易中得到偿还。因此，不存在违约风险。

无抵押品。借款人只要能在一次交易中偿还贷款，就可以在不提供任何抵押品或信用检查的情况下获得贷款。

无限贷款规模。用户可以从DeFi协议中借到任何金额，但不超过可利用的总流动资金。

闪电贷主要被用于套利目的。套利是利用市场之间的价格差异来赚取利润的行为。
闪电贷的第二个用途是贷款清算。如果借款人让协议清算他们的头寸，通常会有惩罚。当市场有较大的价格波动时，借款人可以选择使用闪电贷自行清算他们的头寸，避免罚款。
抵押品互换。
Furucombo是一个能让普通用户使用闪电贷的第三方应用程序。

### 2024.08.28

去中心化的稳定币和稳定资产
稳定币是加密货币生态系统的一个重要组成部分
中心化稳定币
Tether (USDT)
Tether通过1:1的抵押品系统维持其1美元的挂钩。通过持有现金作为储备抵押品，然后发行等量的USDT。从理论上讲，这是一个可靠和直接的方法，以确保USDT保持其挂钩。毕竟，这是对黄金标准的复刻，在上个世纪，美元曾经由黄金支持。
Tether的非透明发行过程
去中心化稳定币
DAI
超额抵押
过度抵押限制了资本效率
稳定币问题的核心是平衡DeFi的去中心化精神与创造一种能够可靠地维持其挂钩的货币。
算法稳定币利用算法来控制稳定币的市场结构和经济基础。
Perpetual是一个去中心化的协议，提供永续合约交易，允许用户在各种加密资产上建立高达10倍的杠杆多头或空头头寸。
dYdX是一个去中心化的交易所协议，提供借贷，现货交易，保证金交易和永续合约交易。作为首批专门从事去中心化衍生品交易的项目之一，dYdX支持三种资产的现货和保证金交易--ETH、USDC和DAI。对于永续合约交易，有11种不同的合约可供交易，包括BTC、ETH、AAVE和LINK。

### 2024.08.29

传统的期货合约也称为交割合约，有固定的合约日，通常为月度或季度交割。合约价格与标的资产价格一致，所有未平仓头寸均已结算。
与传统合约不同，永续合约没有兑现，则交易者可以永久持仓。如果没有合适的价格确定机制，合约价格和现货价格将无法保持一致。使永续合约中的合约价格和指数价格保持平衡的机制是资金费率。
资金费率决定了注资期永续合约持多头寸或空头寸的交易者之间的情况付款。
注资期是指资金费用在持多头寸和空头寸的交易者之间进行支付的定期事件。通常8小时支付一次。用户支付或收到的金额金额被称为资金费用。
请注意，币安合约的资金费用不是支付给币安平台的费用，而是交易者之间相互支付的。该机制是维持合约市场与现货市场中加密货币价格的平衡。
资金费=资金费率x头寸名义价值

资金费率是由期货价格和现货价格之间的差额确定的周期性利率（可以是正数或负数）。
头寸名义价值是期货合约中未平仓头寸的大小。
资金费用通常每8小时一次加息。默认资金利率为0.01%（预设定利率），年化约为10%。

在极端情况下，频率会每小时至4个小时，甚至2个小时来抑制过度投机，以确保永续合约与现货价格挂钩。

怎样套利
简单来说

（常见）当某永续合约的资金费用为正数时，做空该永续合约，同时买入对应数量的现货
当某个永续合约的资金费用为负数时，做多该永续合约，同时在杠杆交易卖出对应数量的现货（此处杠杆借币利率必须低于资金利率，交易盈利）
资金费套利的典型方式是用USDT本金，用USDT买入现货，并在USDT永续上做空。

### 2024.08.30

锁定总价值（TVL）是衡量锁定在DeFi协议内的资本数额，它一直在以惊人的速度增长。
流动性挖矿是一种奖励计划，将协议的原生代币发放给在DeFi协议上提供流动性的用户，在DeFi中并不是一个陌生的概念。早在2019年7月，Synthetix就首次提出了这一概念，后来在2020年6月被Compound普及。
TVL是DeFi中最广泛使用的指标之一，因为它代表了每个协议所持有的资产总量。作为一个经验法则，锁定在协议中的价值越多，对协议来说就越好。
随着时间的推移，查看TVL以衡量资本的保留和用户粘性是至关重要的。
空投本质上是免费分发的代币。项目通常将空投作为其营销策略的一部分，以引起人们对其代币发行的关注和炒作，尽管这样做的代价是稀释了代币所有权。

初始粘合曲线发行，或称IBCO，是一个相当新的概念，旨在防止抢跑。从本质上讲，随着越来越多的投资者向粘合曲线提供资金，代币价格将不断上涨。

然而，你选择什么时候出资并不重要，因为所有投资者将根据相同的最终结算价格支付。基于IBCO结束时的价格，每个投资者将根据他们在总投资资本中的份额获得一部分代币。Hegic和Aavegotchi等项目在其最初的代币发行中使用了这种分配方法，取得了巨大的成功。

Fei是另一个使用这个方法的例子

### 2024.08.31

流动资金引导池（LBP，Liquidity Bootstrapping Pool）

使用Balancer的智能池托管，流动性引导池（LBP）是项目使用可配置的自动做市商出售代币的一种方式。通常，这些池子会包含项目代币和一个抵押代币，通常以稳定币计价。智能池的控制者可以改变其参数，并为销售引入各种功能，如随着时间的推移，价格不断下降，以及由于高需求或外部漏洞，暂停任何进一步的交换。

初始农场发行(IFO，Initial Farm Offering)

初始农场发行（IFO）是由PancakeSwap首次推出的，它允许用户将他们的流动性提供者（LP）代币作为赌注来交换项目的代币。通过使用溢出机制，用户可以按自己的意愿入股，或多或少。在超额认购的情况下，任何多余的代币都会返还给投标人。PancakeSwap上的IFO使用CAKE-BNB LP代币，项目收到BNB代币以换取其新铸的协议代币，而剩余的CAKE代币则被烧毁。

还有一些其他有趣的IXO，比如Mask的ITO（Initial Twitter Offering），各种发行方式都有潜在的获利方法。
<https://zapper.xyz/dashboard>
DEX是一个平台，可以实现代币的交易和直接交换，而不需要中介机构（即中心化交易所）。你不需要经历 "了解你的客户"（KYC）流程的麻烦，也不会受到管辖范围的限制。
DEX的类型

1. 基于订单簿的DEXs
2. 基于流动性池的DEXs

自动做市商（AMM，Automated Market Makers）
流动性池本质上是持有两个或更多的代币的储备，这些代币存在于DEX的智能合约中，可供用户随时交易。
你可以认为基于订单簿的交易所遵循点对点的模式，而AMMs则遵循点对合约的模式。
一些比较流行的AMM公式如下：

恒定乘积做市商公式：x * y = k
恒定和做市商公式：x + y = k
恒定平均值做市商公式
稳定交换公式

### 2024.09.01

Uniswap
SushiSwap
Balancer
Curve Finance
Bancor
AMM之间的主要区别是什么？
I.资金池费用
II.流动性挖矿
III.资金池权重
使用AMM的相关风险
I.价格滑点（Price Slippage）
II.抢跑（Front-running）三明治攻击
III.无常损失（Impermanent Loss）
其他值得一提的协议
PancakeSwap
TerraSwap
0x协议

### 2024.09.02

去中心化固定利率协议
固定利率的协议（Fixed-Interest Rate Protocols - FIRPs）。
Yield是一个去中心化的借贷系统，使用"fyTokens"作为中间权益代币的方式，提供固定利率借贷和利率市场。目前的v1版本提供DAI稳定币的fyTokens。这种新的代币被称为"fyDai"，可以在DAI中实现完全抵押的固定利率借款和贷款。
Saffron Finance是流动性提供者的去中心化收益聚合器，也是最早的风险分级协议之一。风险分级是按风险、到期时间或其他特征划分后，创建不同的流动池，并销售给不同风险偏好的投资者。
与传统的收益聚合器不同，Horizon允许用户根据博弈论原则创建自己的市场。博弈论设想了一个只有理性行为者的环境。在这种假设的情况下，买方和卖方将根据现有的信息做出最佳决定。
如何选择固定利率协议？
I. 他们做出了什么样的承诺？
II. 他们打算如何维持该承诺？
III. 他们对外部代理人维持该承诺的依赖程度如何？
最重要的风险之一是FIRP提供固定利率的能力。
Notional
BarnBridge
88mph
Pendle

### 2024.09.03

加密货币催生了收益耕作（yield farming）的活动，用户只需在DeFi协议中分配资本就可以获得收益。
收益聚合器的诞生是为了满足用户投资策略自动化的需要，使他们不必为监测市场上的最佳收益农场而烦恼。
收益聚合器协议
Yearn Finance始于Andre Cronje的创意想法，目的是实现借贷平台之间资金的自动转换，以获得不同DeFi借贷平台的最佳收益。
金库（vault）
策略
Alpha Finance通过他们的第一个产品Alpha Homora引入了杠杆式产量耕作的概念。它允许用户借入资产，以增加他们在流动性挖矿活动中的头寸。从本质上讲，它既是一个借贷协议，也是一个收益聚合器协议。
Badger DAO的目标是创建一个将比特币引入以太坊的DeFi产品生态系统。它是第一个选择专注于将比特币作为主要储备资产的DeFi项目，而不是使用以太坊。
Sett是一个专注于代币化BTC的收益聚合器。
Harvest Finance
在决定使用哪个收益聚合器时，需要考虑的一个重要因素是收取的费用
收益聚合器由于其从风险较高的协议中寻求高收益的性质，面临着被黑的高风险。
Pancake Bunny是BSC生态系统中最大的收益聚合器。它只提供基于PancakeSwap的农场。
AutoFarm是一个跨链的收益聚合器，支持BSC和HECO链。
收益聚合器的作用与主动管理基金或对冲基金类似。他们的工作是寻找最佳投资机会，并从中赚取收益。
收益聚合器是DeFi协议，旨在通过将资金分配到多个收益农场来最大化收益。
但是，它的可持续性是一个重要的问题。由于收益聚合器协议的利润来自于其他协议的收益，如果这些协议的收益减少，收益聚合器协议的收益也会减少。
收益聚合器协议的另一个重要方面是它们如何管理风险。由于收益聚合器协议依赖于其他协议的收益，如果这些协议面临风险，收益聚合器协议也可能面临风险。

### 2024.09.04

MEV
最大可提取价值 Maximal Extractable Value
在区块链网络中，具有排序权的参与者通过重新排序、包含或排除区块中的交易，能
够提取的最大利润，包括抢先交易、套利和三明治攻击等行为。MEV 反映了这些参与
者利用交易顺序控制权力所能获得的额外价值。
MEV 策略
• 抢跑交易(Front-running)：利用未确认交易的信息，提前进行相同交易以获取利润。
• 套利(Arbitrage)：利用不同交易所或市场之间的价格差异，进行快速买卖以获取差价利润。
• 三明治攻击(Sandwich Attack)：在目标交易前后插入自己的交易，以操纵市场价格获取利润。
• 清算(Liquidations)：通过触发借贷平台上的清算机制，从清算中获利。
• 矿池提取：在去中心化交易所（DEX）中，通过操控流动性池中的交易顺序，获取最大收益。
监控发现机会 -> 攻击者抢先买入资产 -> 受害者买入（Swap时得到的更少） -> 攻击者后置交易卖出资产

什么是Flashbots
Flashbots 成立于 2020 年，是一家研发组织，旨在减轻最大可提取值
(MEV) 带来的负面外部性和生存风险。推出了 mev-geth、Flashbots
Protect、MEV-Boost、MEV-Share、开放研究。
为 MEV建立一个无需许可、透明且可持续的生态系统：
• 照亮： 为 MEV 活动带来透明度。
• 民主化： 使获取 MEV 收入的途径民主化。
• 分配：实现 MEV 收入的可持续分配。

### 2024.09.05

Perpetual Protocol（永续协议）
• vAmm： 虚拟流动性提供极高流动性，免于做市商的依赖
• 没有真实的资金池：借的是虚拟币，获取的虚拟头寸
• 多空双方互为对手
• 通过 Chainlink 喂价，结算资金费来保持价格不偏离

相关术语
• 杠杆倍数（leverge）
• 保证金（Margin）
• 持仓仓位、头寸（Postion）：
• 仓位（名义）价值：头寸 *价格， 正数表示多头，负数表示空头。
• PNL：盈亏（profit and loss），做多时：仓位价值-开仓价值，做空时：开仓价值 - 仓位价值
• 保证金率（Margin Ratio） = （保证金 + PNL）/ 仓位价值 , 当低于6.25％触发清算。
• 资金费 = 头寸* 资金费率， 资金费率 = （TWAP - Oracle价格)/24， 资金费率为正时，多方向空方支付资金费。
• 保障基金（InsuranceFund）：（清算获利），弥补行情剧烈波动带来的穿仓的损失。

抵押型稳定币，稳定币作为债务形式存在。
• 链下以美元抵押（中心化），如：USDC
• 以链上资产做抵押，通过利息调节供应，如：DAI
• 算法稳定币：
• 通过算法调节供需关系：AMPL BAS FRAX FEI UST OHM 等

### 2024.09.06

为什么需要DEX
DEX通过使用智能合约和链上交易来减少或消灭对中介的需要。
中心化交易所（CEX）允许在流动性充裕的情况下进行大宗交易，但是由于用户在交易所中并
不拥有其资产的所有权，因此中心化交易所仍具有很大的风险。
去中心化
用户掌握资产 隐私保护 减少交易费用
抗审查
开放金融 透明

DEX 类型
基于订单簿
基于流动性

AMM DEX 使用算法管理流动性池，用户可以直接与流动性池交易，而无需撮合买卖订单。
主要特点: 消除订单簿，实现持续和自动化的交易。
DEX的流动性可以在跨DEX共享

恒定乘积
使用 dY 兑换 X，假设兑换到 dX 个 X
要求兑换后 K 不变（面积不变）即：
(X - dX ) *(Y + dY) = X* Y
dX = X - X *Y / (Y+dY)
dX = ( X* dY ) / (Y+dY)

价格预言机: TWAP
时间加权平均价格（英语：time-weighted average price，TWAP）
当前价格累计值 = 上一次价格累计值 + 当前最新价 * 当前时间

### 2024.09.07

DeFi（去中心化金融）指的是一种基于区块链技术的金融系统，运行时不依赖于传统的金融中介，如银行或金融机构。相反，DeFi 使用智能合约——这些合约是自执行的代码，包含在区块链上运行的条款，主要是以太坊网络上的智能合约，来实现点对点的金融服务。

### DeFi 的主要特点

1. **去中心化**：系统没有中央机构控制。交易和操作通过智能合约执行，这些合约透明且不可篡改。
2. **无需许可**：任何人只要有互联网连接，都可以访问 DeFi 服务，而不需要获得批准或满足特定要求。
3. **透明性**：所有交易和智能合约都记录在公共区块链上，使整个过程透明且可审计。
4. **互操作性**：DeFi 协议通常可以协同工作，允许不同的服务和平台之间进行集成和互动。
5. **可编程性**：DeFi 平台是基于智能合约构建的，开发者可以创建各种金融产品和服务，例如借贷平台、稳定币等。

DeFi 提供了传统金融系统之外的新型金融服务，特别是在全球金融包容性和金融创新方面具有很大的潜力。

DeFi 聚合器是一类平台，它们通过整合多个去中心化金融（DeFi）协议和服务，提供统一的界面和优化的用户体验。DeFi 聚合器的主要目标是简化用户与各种 DeFi 协议的交互，同时帮助用户在不同平台之间获得最佳收益和效率。

### DeFi 聚合器的主要功能

1. **跨平台整合**：DeFi 聚合器能够接入多个 DeFi 协议，如去中心化交易所（DEX）、借贷协议、收益农场等，让用户可以通过一个平台访问多种服务。
2. **最佳价格路径**：在进行交易时，聚合器会自动选择多个 DEX 中的最佳价格路径，帮助用户在不同流动性池之间进行最具性价比的交易。
3. **收益优化**：通过整合多个收益农场或流动性挖矿项目，DeFi 聚合器帮助用户自动找到最有利可图的投资策略，最大化收益率。
4. **降低交易成本**：通过将多个交易打包执行，聚合器可以帮助用户减少链上的交易费用（Gas 费）。
5. **流动性整合**：用户无需手动在不同平台上进行资产管理，聚合器可以汇总多个协议的流动性，简化管理。

### 常见的 DeFi 聚合器

1. **1inch**：1inch 是一个著名的去中心化交易所聚合器，通过访问多个 DEX 提供最佳的交易价格和最低的滑点。
2. **Yearn Finance**：Yearn Finance 是一个收益优化聚合器，它会自动将用户的资产分配到不同的 DeFi 协议中，以获得最高的收益率。
3. **Matcha**：一个跨 DEX 的聚合交易平台，提供用户友好的界面和最佳交易路由。

### DeFi 聚合器的优势

- **便捷性**：通过一个界面即可使用多个 DeFi 平台的服务，简化了用户的操作流程。
- **优化收益**：聚合器帮助用户在多协议之间选择最佳投资路径，提升资金效率。
- **降低风险**：通过分散资金在多个平台上，用户能够降低由于单一平台故障或安全问题带来的风险。

DeFi 聚合器的出现为用户提供了更高效和便捷的方式来参与 DeFi 生态系统，同时通过优化投资路径和降低成本，进一步提升了资金利用率。

DeFi 聚合器并不能完全取代 DeFi 本身，而是作为对 DeFi 生态系统的一种补充和优化工具。它们通过整合和简化用户与多个 DeFi 协议的交互，提供更好的用户体验，但并不直接替代各个 DeFi 协议的核心功能。

### 以下是 DeFi 聚合器与 DeFi 协议的关系和区别

1. **功能层次不同**：
   - **DeFi 协议**：DeFi 协议（如 Uniswap、Aave、Compound 等）是构建在区块链上的基础层金融工具，提供核心的金融功能，如去中心化交易、借贷、质押、收益农场等。
   - **DeFi 聚合器**：聚合器是整合这些协议的工具，通过优化策略、提供统一的界面来帮助用户更高效地使用这些协议，但其核心功能仍然依赖于各个 DeFi 协议。

2. **依赖关系**：
   - DeFi 聚合器本质上依赖于现有的 DeFi 协议来运作。它们通过调用多个 DeFi 协议的功能来实现交易路由、收益优化等服务。因此，聚合器无法脱离 DeFi 协议独立存在。
   - 如果没有底层的 DeFi 协议，聚合器将无法提供任何金融服务。

3. **目标不同**：
   - DeFi 协议的目标是提供去中心化的金融服务，它们专注于某一领域的金融功能（例如交易、借贷、流动性提供）。
   - DeFi 聚合器的目标是简化用户的操作，帮助他们在多个协议间选择最优方案，如最佳交易路径、最高的收益率等。

4. **风险管理与分散性**：
   - DeFi 聚合器可以通过分散用户资金在多个协议上，帮助用户减少因单一协议出现问题而带来的风险。
   - 然而，DeFi 协议本身是提供金融服务的基础，如果协议出现漏洞或问题，聚合器也可能无法避免相应的损失。因此，聚合器能减少风险，但并不完全消除它。

### 总结

DeFi 聚合器无法取代 DeFi，因为它们是依赖 DeFi 协议的辅助工具。聚合器的作用在于提升用户体验、优化交易和收益路径，但 DeFi 协议仍是提供金融功能的基础。两者是相辅相成的关系，聚合器的出现进一步增强了 DeFi 生态系统的灵活性和可访问性，但无法取代 DeFi 协议的核心角色。

### 2024.09.08

什么是三明治攻击（Sandwich Attack）？

三明治攻击是一种在DeFi中使用的常见交易操纵技术，通常发生在自动做市商（AMM）或去中心化交易所（DEX）中。它利用了前置交易和后置交易的策略。

操作步骤：

 • 前置交易（Front-running）: 攻击者监测到一笔大额交易即将发生时，会通过提交一笔相似的交易，先一步在链上执行。通常通过支付较高的手续费，优先将交易放在受害者的交易之前。
 • 目标交易（Victim Transaction）: 受害者的交易按预期执行（例如买入或卖出某种代币）。
 • 后置交易（Back-running）: 在受害者的交易执行后，攻击者会立即发起一笔反向交易，利用受害者交易造成的价格波动，获得利润。

举例：

 1. 攻击者看到用户要在某个去中心化交易所买入一大笔代币X。
 2. 攻击者提前买入代币X，推高价格。
 3. 用户的交易以较高的价格成交。
 4. 攻击者在用户交易后立即卖出代币X，获取差价利润。

什么是套利？

套利是通过利用市场之间价格差异来获利的行为。在DeFi中，套利通常涉及在不同的交易所之间买卖同一资产，以从价格差中获利。

操作步骤：

 1. 寻找价格差异: 监控多个去中心化交易所（如 Uniswap、SushiSwap、Curve 等）之间同一代币的价格差异。
 2. 低买高卖: 在价格较低的交易所买入代币，然后在价格较高的交易所卖出，从而获得利润。
 3. 重复操作: 不断寻找新的套利机会。

举例：

 1. 在交易所A上，某代币的价格是10 USDT；而在交易所B上，价格是12 USDT。
 2. 你可以在交易所A上以10 USDT买入代币，然后在交易所B上以12 USDT卖出，赚取2 USDT的差价。

三明治攻击 是通过操纵交易顺序获利的方式。
套利 是通过利用不同市场的价格差异进行交易获利。

<!-- Content_END -->
