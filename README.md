<div align="center">

# xiaohongshu-account-operations

**多账号小红书评论运营：LLM 实时生成 + 人设配置 + 频率安全 + 质量闭环。**

<p>
  <a href="#"><img src="https://img.shields.io/badge/architecture-LLM--generated-pink" alt="LLM generated" /></a>
</p>

## 架构

- 评论 = LLM 实时生成（读帖→现写→校验→发布）
- 每个账号一套人设 + 禁词表
- 校验链：空内容→跳过；万能词→重试 3 次；链接/超长→跳过

## License

MIT
