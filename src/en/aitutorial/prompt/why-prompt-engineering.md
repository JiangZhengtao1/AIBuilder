---
date: 2024-10-22
title: 为什么是提示词工程（Prompt Engineering）而不是提示词技术？
shortTitle: 提示词工程而非技术
category:
  - Prompt
---

=="工程"比"技术"更适合描述针对LLM的提示创作过程== ，主要基于以下三个方面：
![提示词工程](/images/prompt/prompt-engineering.png)
## 1. 复杂性与不确定性
   - LLM输出的高度**不确定性和多样性**
   ::: tip 高度不确定性和多样性
     例如：同一个提示"写一个关于春天的短诗"可能产生完全不同风格和内容的诗歌。
   :::
   - 需要工程化方法来**控制和引导结果**
   ::: tip 需要工程化方法来控制和引导结果
     例如：使用详细的指令、示例和约束条件来引导AI生成特定风格或格式的内容。
   :::

## 2. 系统思维的必要性
   - 需要考虑多个维度（上下文、目标、模型特性等）
   ::: tip 
     例如：在设计客服聊天机器人时，需同时考虑用户查询的多样性、公司政策、以及AI模型的语言能力。
   :::
   - 涉及系统工程要素（问题分解、约束设计、结果验证）
     - 问题分解：将复杂任务拆解为可管理的子任务
     ::: tip 问题分解
       例如：开发一个AI文章生成器时，可以将任务分解为：1) 生成文章大纲 2) 扩展每个段落 3) 添加过渡句 4) 优化标题
     :::
     - 约束设计：设置明确的限制和规则以引导AI输出
     ::: tip 约束涉及
       例如：在设计AI对话系统时，可以设置字数限制、语气要求、禁用词列表等约束条件
     :::
     - 结果验证：评估和验证AI输出的质量和准确性
     ::: tip 结果验证
       例如：为AI生成的代码设计自动化测试，或使用人工审核来验证AI生成的内容是否符合要求
     :::
   - 要求整体规划和精确控制
   ::: tip 整体规划和精确控制
     例如：在开发AI写作助手时，需要设计一套完整的提示词系统，包括内容生成、修改、润色等多个环节。
   :::

## 3. 迭代优化的核心地位
   - 提示词效果需要多轮测试和改进
   ::: tip 提示词效果需要多轮测试和改进
     例如：开发AI翻译工具时，需要反复测试不同类型的文本，并根据结果调整提示词。
   :::
   - 每个应用场景可能需要独特策略
   ::: tip 每个应用场景可能需要独特策略
     例如：医疗诊断AI和创意写作AI的提示词策略会有很大差异。
   :::
   - 持续优化特性更接近工程领域
   ::: tip 持续优化特性更接近工程领域
     例如：随着用户反馈的积累，需要不断调整和优化提示词系统，类似软件工程中的版本迭代。
   :::

总之，"工程"强调了这是一个需要系统思维、专业知识、持续迭代和稳定可复现保障的创作过程。这种复杂性和系统性使得提示词工程更像是一门工程学科，而非单纯的技术应用。
