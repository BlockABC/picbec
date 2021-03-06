# EOSpark.com推出EOS合约源代码验证功能

## 背景
最近[FOMO3D](http://exitscam.me/play)非常火爆，有团队就把这个以太坊上的游戏移植到了EOS上，然而最近[该游戏](https://eosfo.io/)暴出漏洞，被个别玩家利用溢出攻击获取了6w多个EOS，详情见[这里](https://baijiahao.baidu.com/s?id=1607137899969271059&wfr=spider&for=pc)

我们之所以去参与区块链游戏，是因为在区块链的世界里，代码就是规则、法律和约束。而规划、法律和约束应该是人人可见，人人可以知晓。即，智能合约的源代码应该做到公开。前面的EOS游戏中，用户损失6w多个EOS，其中重要的原因就在于，玩家不能查看游戏的源代码，无法检查游戏中是否存在恶意漏洞。

因此，EOSPark第一时间推出了EOS合约源代码验证功能。该功能包括：
1. 用户可以查看一个合约的源代码
2. 项目方可以自行上传源代码进行在线验证
3. 合约异常告知

## 用户查看合约源代码
目前已有不少项目方公开其智能合约的源代码。

#### 合约：eosiomeetone
合约地址：<https://eospark.com/MainNet/contract/eosiomeetone>

![eosiomeetone](https://github.com/BlockABC/picbec/raw/master/contract_valid/eosiomeetone.png)

#### 合约：gameworldcom
合约地址：<https://eospark.com/MainNet/contract/gameworldcom>

![gameworldcom](https://github.com/BlockABC/picbec/raw/master/contract_valid/gameworldcom.png)

## 上传源代码
如果一个智能合约没有公开其源代码，用户可要求项目方到EOSpark上传源代码。如果项目方拒绝上传，则应该谨慎使用该合约。如果项目方上传错误的源代码，将不会得到EOSpark的验证。

![Upload_Source_Code](https://github.com/BlockABC/picbec/raw/master/contract_valid/Upload_Source_Code.png)

![Upload_Source_Code_Form](https://github.com/BlockABC/picbec/raw/master/contract_valid/Upload_Source_Code_Form.png)

## 合约异常告知

由于EOS的智能合约可以重新部署，若项目方上传源代码并通过验证之后又重新部署了合约，这意味着使用该合约可能存在的风险。对于此类情况，EOSpark会给出异常提醒，且项目方可以重新上传对应的源代码。

![Source_Code_Error](https://github.com/BlockABC/picbec/raw/master/contract_valid/Source_Code_Error.png)

区块链世界的信任建立在公开透明的基础之上，合约的安全关乎的用户的资产安全。因此，合约源代码公开是项目方应尽的职责，也是对用户负责的表现。EOSpark推出合约代码验证功能，旨在协助项目方为用户提供一个安全可信的区块链应用世界，为保护用户资产安全尽一份力量。
