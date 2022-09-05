> Link: https://github.com/paritytech/substrate <br/>

重点目录注释：

```bash
substrate-master/
├── bin  // 包含节点的可执行程序
│   ├── node  // 功能完备的node
│   ├── node-template  // node模板
│   └── utils  // 包含常用的工具
│       ├── chain-spec-builder
│       └── subkey  // 用来管理密钥
├── client  // 包含节点所必须的组件，比如网路P2P的消息机制，数据库读写，共识的底层组件等
├── frame  // runtime开发所支持的各种模块、和业务模块
│   ├── system  // https://crates.parity.io/frame_system/index.html
│   ├── timestamp  // 记录链上时间戳
│   ├── transaction-payment  // 用来计算交易的费用，并对费用做实际的扣除
│   ├── utility  // 工具模块
├── primitives  // 包含常用的runtime、客户端需要的公用类型方法接口等
```

已将frame模块的部分代码做了注释，待持续更新。
- system
- timestamp
- transaction-payment
- utility