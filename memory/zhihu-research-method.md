---
name: zhihu-research-method
description: 知乎内容获取的替代方案和经验教训
type: feedback
originSessionId: 4d6493e6-b9b3-47b0-bb22-7659098b3f1d
---
知乎直接URL提取会被反爬机制阻断，Tavily extract 全部失败。替代方案：用 Tavily deep research (pro model) 可以成功生成综合报告，tavily_search 搜索片段也能提供部分内容。

**Why:** 知乎有严格的反爬措施，直接抓取页面内容不可行。

**How to apply:** 需要知乎内容时，优先用 Tavily research/search，不要尝试直接 extract 知乎URL。如需用户个人收藏数据，需先让用户启动Chrome远程调试端口后再用Chrome DevTools MCP。