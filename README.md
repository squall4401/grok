# Grok3 地球上最聪明的AI

1. 算力碾压：
    - 20万块H100 GPU训练，算力是DeepSeek R1的50倍（DeepSeek R1仅用2048块H800 GPU）。
    - 训练耗时2亿GPU小时，是Grok 2的10倍，硬件规模全球第一。
2. 性能屠榜：
    - 数学能力：AIME'24测试96分（DeepSeek V3仅39分）。
    - 编程效率：LCB测试57分，15分钟生成《星际俄罗斯方块》完整代码。
    - 推理能力：Chatbot Arena ELO评分1400+，全球首个突破此分数的模型。
3. 独家功能碾压：
    - DeepSearch：实时联网搜索+多源验证（对比DeepSeek R1依赖中文自媒体，Grok 3抓取GitHub、arXiv等权威数据）。
    - Think模式：思维链长度是DeepSeek R1的10倍，推理速度反而更快。
    - 多模态处理：同步解析文本+图像（例：分析医学CT报告


## Deno 调试

Windows 安装 Deno:
> irm https://deno.land/install.ps1 | iex

Mac/Linux 安装 Deno:
> curl -fsSL https://deno.land/install.sh | sh

启动项目：

> cd grok

> deno run --allow-net --allow-read src/deno_index.ts