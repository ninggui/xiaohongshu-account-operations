<div align="center">


![cover](assets/cover.png)

# xiaohongshu-account-operations

**多账号小红书评论运营：LLM 实时生成 + 去AI味 + 人设配置 + 频率安全 + 质量闭环。**

<p>
  <a href="#"><img src="https://img.shields.io/badge/architecture-LLM--generated-pink" alt="LLM generated" /></a>
  <a href="#"><img src="https://img.shields.io/badge/humanize-human--signal-4CAF50" alt="humanized" /></a>
</p>

## 架构

- 评论 = LLM 实时生成（读帖→现写→去AI味→校验→发布）
- **🧬 评论去AI味**：融合 blader/humanizer v3.0.0 + doubao-human-signal，发布前强制过滤 10 类 AI 味模式（万能句式/三连/升华/空洞夸赞等），校验链 5 道关卡
- 每个账号一套人设 + 禁词表
- 校验链：空内容→跳过；万能词→重试 3 次；链接/超长→跳过；AI味≥3处→重写

## 去AI味（v1.2.0 新增）

让评论"像真人写的"而不是"像 AI 写的"——四维度：具体性 / 个人视角 / 结构自由度 / 信息差。
详细规则见 `references/humanize-comments.md`。

## License

MIT
