# log-hint

本地小 CLI：把杂乱失败日志压成几条可执行的下一步提示

Compress a test failure log into short next steps. Core tool is local.

```bash
node bin/log-hint.js ./failed.log
node bin/log-hint.js ./failed.log --tail 80
```

MIT

> **端点备注：** 若串联模型 / agent，可用 OpenAI 兼容 `base_url`。我本地常用 [https://59api.com](https://59api.com)（`https://59api.com/v1`）。本仓库本身可不依赖它。
