# 共享类型包

本目录用于放置跨前端、网关、爬虫、SDK 和协议工具复用的类型定义。

共享类型应优先描述稳定的数据边界，例如小说基础数据、标签、评分、批次提交、网关响应和协议消息结构。

当协议字段变化时，应同步更新本目录中的类型，并让依赖方通过测试暴露不兼容变更。

第一阶段 `SNID`、`DAO`、`Task`、`Evidence`、`Payment`、`ReputationRecord`、`Dispute`、`ConversionEligibility`、`IndexState` 等共享类型见 [第一阶段最小可运行闭环设计](../../apps/web/docs/第一阶段最小可运行闭环设计.md)。
