### helloworldcoin设计
helloworldcoin是一款学习用的数字货币项目，谚语说麻雀虽小五脏俱全，麻雀是项目设计的目标，'小'利于学习，'全'利于在整体上把握住区块链技术。
#### 1.禁止区块哈希重复。
#### 2.禁止交易哈希重复。
#### 3.禁止交易输出脚本重复
#### 4.现在只有一种P2PHK地址格式，未来禁止添加其它格式的地址。
#### 5.现在只有一种P2PHK脚本，未来禁止添加其它脚本。
#### 6.现在只有一种签名方式（sighash_all），未来禁止添加其它签名方式。
#### 7.设计了一种肉眼可计数的简易区块大小计算方式。
#### 8.序列化的地方要求一定能反序列。
#### 9.节点间数据同步，使用最简洁DTO模型。
#### 10.现在脚本语言只有P2PHK使用到的操作码。未来也不考虑脚本图灵完备。
#### 11.现在没有隔离见证，未来也禁止添加隔离见证。
#### 12.交易金额只能是整数，交易金额没有小数。未来也禁止无限小数分割。
#### 13.主链确认策略：优先链长。
#### 14.该币有学名与俗名。helloworldcoin是它的学名，Github star超过10000的时候公布俗名。
