# 比特币开发者手册中文版
> [英文原版](https://bitcoin.org/en/developer-reference)来自 bitcoin.org

> 翻译 庞四 @ 芜湖滂湃科技
| email: <pangsitao@hotmail.com>
| wechat: pstpstpst

## Preface
 1. [介绍](preface/introduction1.md)  **[Done here!]**

## A. 区块链
 1. 区块头
 2. 区块版本
 3. Merkle 树
 4. 目标 nBits
 5. 序列化区块

 ## B. 交易
 1. 操作代码 Opcodes
 2. 地址转化
 3. 原始交易格式
 4. CompactSize 无标记整形

 ## C. 钱包
 1. 确定式钱包格式
 2. 类型1：单链钱包
 3. 类型2：分层的确定式钱包（HD钱包）
 ## D. P2P网络
 1. 一些常量与初始值
 2. 协议版本
 3. 消息头
 4. 区块
 5. GetBlocks 获取区块
 6. GetData 获取数据
 7. GetHeaders 获取区块头
 8. Headers 区块头
 9. inv
 10. MemPool 内存池
 11. MerkleBlock Merkle块
 12. CmpctBlock 请求合约块
 13. SendCmpct 发送合约块
 14. GetBlockTxn
 15. BlockTxn
 16. NotFound
 17. Tx
 18. 控制消息 Control Messages
 19. 地址 Addr
 20. 警报 Alert
 21. 费用过滤器 FeeFilter
 22. 过滤器增加 FilterAdd
 23. 过滤器清理 FilterClear
 24. 过滤器载入 FilterLoad
 25. 获得地址 GetAddr
 26. Ping
 27. Pong
 28. 拒绝 Reject
 29. 头发送 SendHeaders
 30. VerAck
 31. 版本 Version


 ## E. 比特币核心 APIs

