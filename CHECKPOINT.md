# 2026-11-02 Wind 通用查询与年报证据（开发候选，未发布）

基线 `d7af6017f16f2ea2ac2d8ba71876a4be64c7f11d`。本轮本人要求第二轨作为主演示、巨潮保底，财务与年报都纳入、不限制为财务专线。

日份数上限允许 0，并明确显示每日不限总量；每分钟速率和并发照旧。属于用户取消 Wind 调用次数上限的通用渠道配置，不改变已有正数上限。新独立分支 feat/wind-query-supply（从本工位 luna HEAD 起）。
验证 pnpm 测试 67 passed / 15 files（/tmp/luna-wind-admin-tests.log），typecheck、i18n 和变更格式检查通过。未发布。

发布由 qwen/Jenkins；不代点用户采单、不修改线上任务。以下为此前历史：
