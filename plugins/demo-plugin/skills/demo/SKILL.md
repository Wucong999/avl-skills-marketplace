---
description: Clean up rough text into clearer Markdown while preserving meaning and avoiding invented facts.
disable-model-invocation: true
---
# Text Cleaner Demo Skill

一个开源的 AVL Skills 测试包示例，用于测试平台的 ZIP 上传、解析和审核流程。  
它不依赖外部服务，也不包含敏感权限，仅演示一个“文本整理/润色”的简单 Skill 描述。

## 基本信息

- Slug: `text-cleaner-demo`
- Display Name: `文本整理助手 Demo`
- Version: `1.0.0`
- Category: `中国应用`
- License: `MIT`

## 能力说明

这个 Skill 可以帮助用户把零散、口语化、格式混乱的文本整理成更清晰的版本。

适合场景：

- 简历项目描述整理
- 产品介绍文案整理
- 更新日志整理
- 客服回复话术整理
- Markdown 文档排版

## 使用方式

用户输入一段原始文本后，Skill 按以下步骤处理：

1. 保留原意，不虚构事实。
2. 删除重复、口水化表达。
3. 按主题拆分段落。
4. 优化语气，使其更清楚、更自然。
5. 输出 Markdown 格式结果。

## 输入示例

```text
我这个工具可以翻译游戏 然后有些引擎支持回显 也能改道具数量 目前主要是mv mz 后续支持unity
```

## 输出示例

```markdown
这个工具主要用于游戏文本翻译与运行时回显，目前重点支持 RPG Maker MV/MZ 引擎。

核心能力包括：

- 提取游戏内原文并批量翻译
- 将译文注回游戏资源或运行时回显
- 提供基础金手指能力，例如修改道具数量
- 后续计划扩展 Unity 等更多引擎支持
```

## 注意事项

- 不改变用户原本表达的核心意思。
- 不主动添加未经确认的数据、成绩、收益或公司信息。
- 如果原文信息不足，应明确提示“信息不完整”，不要强行编造。
- 适合作为上传测试包，不建议直接用于生产环境。

## 开源协议

本示例使用 MIT License。

