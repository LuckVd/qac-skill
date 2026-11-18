---
name: clean-coding
description: >
  Use automatically for coding tasks, including feature
  implementation, bug fixes, refactoring, and code changes.
  Apply clean, minimal-impact engineering practices throughout
  the task. Avoid unnecessary comments, files, complexity,
  and unrelated changes. Work silently without extra reports
  or user invocation. Do not use for discussion-only tasks.
---

# Clean Coding

在编码任务中，以克制、整洁、低侵入性的方式完成工作。

## 1. 变更范围

- 理解需求和现有实现，只修改完成任务所必要的内容。
- 优先选择影响范围较小且符合现有设计的方案。
- 不主动重构无关代码或改变无关行为。
- 修改公共模块或核心逻辑时，考虑对其他调用方的影响。
- 不为追求最小改动而牺牲正确性或可维护性。

## 2. 实现洁净

- 遵循项目现有约定，优先复用已有实现。
- 避免不必要的抽象、兼容逻辑、配置和依赖。
- 注释只解释有长期价值且不直观的信息。
- 不在注释中记录提示词、对话、修改过程或历史。
- 不创建无必要的文档、备份、调研记录及其他过程性文件。
- 合理的测试、配置和辅助文件不受限制。

## 3. 交付检查

- 根据变更风险进行必要验证。
- 检查改动是否包含无关修改、冗余注释或调试代码。
- 清理本次产生且不再需要的临时产物。
- 保留用户已有修改，不擅自删除或覆盖已有工作。

## 执行原则

- 本 Skill 是工程实践指导，不替代用户要求和项目已有规范。
- 根据实际情况灵活判断，不机械执行上述原则。
- 在整个编码过程中自然应用，无需单独启动审查流程。
- 静默执行，不主动宣告 Skill 启动、执行步骤或检查结果。
- 不额外生成计划、报告或总结文件。
- 正常完成任务所需的沟通不受限制；重要风险仍应告知用户。
- 不因本 Skill 增加不必要的交互、流程或工作量。
