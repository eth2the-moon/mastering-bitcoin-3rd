# 基于构建块的应用程序

\
基于比特币提供的构建块，可以用来构建应用程序的信任平台元素。以下是一些现有应用程序及其使用的构建块的示例：

_存在证明（数字公证）_&#x20;

&#x20;        不变性 + 时间戳 + 持久性。区块链上的交易可以承诺一个数值，证明某个数据在记录时存在（时间戳）。该承诺无法事后修改（不变性），并且证据将被永久存储（持久性）。

_众筹（Lighthouse）_&#x20;

&#x20;         一致性 + 原子性 + 完整性。如果您签署了一个筹款交易的一个输入和输出（完整性），其他人可以为筹款做出贡献，但在达到目标（输出金额）之前无法支出（原子性）（一致性）。

_支付通道_&#x20;

&#x20;         控制多重签名 + 时间锁定 + 无双花 + 不过期 + 抗审查 + 授权。一个多重签名的2-of-2（控制多重签名），带有时间锁定的（时间锁定）作为支付通道的“结算”交易可以在任何时间由任一方（授权）持有（不过期）和支出（抗审查）。然后，两个当事人可以创建超过（无双花）较短时间锁定的结算的承诺交易（时间锁定）。