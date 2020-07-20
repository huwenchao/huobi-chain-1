# Service 概览

Service 是 Muta 框架中用于扩展的抽象层，用户可以基于 Service 定义区块治理、添加 VM、或实现一个 dapp。Huobi Chain 当前内置了 Metadata Service，Asset Service，RISC-V Service，Node Manager Service 四个 built-in service。

* [Authorization Service](./authorization_service.md)：用于交易池对交易合法性进行检查。
* [Asset Service](./asset_service.md)：支持用户发行 UDT，支持转账，查询等操作。
* [Metadata Service](./metadata_service.md)：支持链的运营方在起链前对链的相关信息进行配置。
* [RISC-V Service](./riscv_service.md)：支持用户用 c 语言进行合约的开发，本文档还将提供一个 [demo](./contract_demo) 详细阐述开发过程。
* [Admission_Control Service](./admission_control_service.md)：链的控制准入服务.可以配置过滤方法,进而过滤即将进入mempool的tx。
* [KYC Service](./kyc_service.md)：KYC服务,用以提供火币公链的KYC需求.
* [Multi-Signature Service](./multi_signature_service.md)：多重签名支持。
* [Governance Service](./governance_service.md)：支持动态添加、删除节点，注册利润。
