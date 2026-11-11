## Hi there 👋

软件工程在读，关注 Agent 应用与工具开发：怎么用 Agent 做出有用、好玩的东西。

## 开源贡献

### 已合并

- **particle-agent**(开源 AI 个人助理)— 发现 SQLite 查询层未校验 `limit` 参数的缺陷(`LIMIT -1` 会返回全表),实现统一校验函数并编写 16 个回归测试;通过“未修复代码 13 失败 → 修复后全过”的对照验证证明修复有效性。([PR #13](https://github.com/codewithzubair07/particle-agent/pull/13))
- **awesome-dsh-plugin**(DSH 插件市场)— 将个人开发的背景主题插件 [awesome-dsh-background-plugin](https://github.com/leavestring/awesome-dsh-background-plugin) 按贡献规范收录进官方插件列表。([PR #1071](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin/pull/1071))

### 进行中

- **hermes-agent**(开源 AI 个人助理)— 改善桌面版 API Key 删除入口,让已保存的提供商及工具密钥无需进入编辑模式即可删除;保留二次确认和配置档隔离,补充 2 个真实界面交互回归测试,覆盖取消、确认与目标配置档。基于已有 PR 保留原作者署名并完善实现,设置模块 615 项测试通过。([PR #152606](https://github.com/NousResearch/hermes-agent/pull/152606),open · 待 review)

### 提案与讨论

- **mcp-use**(10.8k★,MCP 全栈框架)— 针对宿主按资源 URI 缓存视图、导致重新部署后仍返回旧文档的问题,提出 `views.resourceUri` 公开 API:覆盖 `tools/list`、成功 `tools/call` 结果、`resources/list`、`resources/read` 与 OAuth 资源门控,并在挂载期校验 `ui://` 前缀与跨视图唯一性,未配置时保持原 URI 逐字节不变;附 5 个新测试、文档与 changeset。维护者最终选择“自动 build-ID 版本化”方案并合并 [#3069](https://github.com/mcp-use/mcp-use/pull/3069),本 PR 作为设计提案关闭。([PR #3062](https://github.com/mcp-use/mcp-use/pull/3062),closed · superseded)

<!--
**leavestring/leavestring** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
