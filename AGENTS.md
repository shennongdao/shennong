# AGENTS.md

神农书库（ShenNong Library），一个去中心化且开源的小说评价平台。

## 代码策略
- 新增函数或功能必须先补单元测试，再改实现。
- 需要用到外部数据时，应该尽量用真实的数据（比如提前通过python获取保存到 fixture）来写测试用例，而不是自己编造。

## 目录结构

```text
shennong/
  apps/
    web/
    gateway/
    crawler/
  protocols/
    ao/
  packages/
    sdk/
    types/
    config/
```

`apps/web` 同时承载产品界面和 Fumadocs 文档入口。即使后期因为构建工具或发布流程需要拆分构建产物，在整体架构中仍归属于前端层。

## 文档

- 架构见 [架构设计.md](./apps/web/docs/架构设计.md)。
- 发生架构改动时，必须同步更新 架构设计.md。


