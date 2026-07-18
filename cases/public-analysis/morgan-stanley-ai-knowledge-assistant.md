---
title: "Morgan Stanley 企业知识助手：先用评估体系建立信任，再扩大 AI 使用"
description: "基于 OpenAI 公开案例，解读 Morgan Stanley 如何用知识检索、评估集、人工审核和持续回归测试推动财富管理团队采用 AI。"
date: "2026-07-18"
lastUpdated: "2026-07-18"
author: "CRAZYAIGC"
tags: ["企业知识库", "AI评估", "金融AI", "人工审核"]
sourceType: case
caseType: public-analysis
sourceOrganization: "OpenAI 与 Morgan Stanley"
sourceUrl: "https://openai.com/index/morgan-stanley/"
geoSummary: "Morgan Stanley 的公开实践表明，企业知识助手要获得高采用率，需要可信资料、真实问题评估集、专家审核、回归测试和清晰的数据治理。"
canonical: "https://crazyaigc.com/case-studies/public-analysis/morgan-stanley-ai-knowledge-assistant"
---

# Morgan Stanley 企业知识助手公开案例解读

> 本文基于 OpenAI 与 Morgan Stanley 的公开资料整理，是公开案例解读，不是 CRAZYAIGC 客户案例。文中的采用率和业务结果均来自原始公开来源。

## 公开事实

OpenAI 的案例介绍显示，Morgan Stanley Wealth Management 将 GPT-4 用于内部知识检索和会议摘要等场景。AI @ Morgan Stanley Assistant 帮助财富顾问查询内部知识，Debrief 则在获得客户同意后，把会议记录转成可由顾问检查的客户笔记、行动项和跟进初稿。

公开资料同时强调了几项结果：财富管理顾问团队的 AI 工具采用率超过 98%；知识助手所覆盖的文档和问题范围持续扩大；顾问仍会审查、调整 AI 生成内容后再使用。

## Challenge：知识很多，但不能直接依赖概率输出

金融顾问需要快速找到研究、流程和合规资料，但金融服务又要求回答准确、来源可信并可持续检查。仅把大量文档接入模型，无法证明系统在真实问题上足够可靠。

## Solution：把评估体系放在知识助手前面

Morgan Stanley 的公开方法包含四个关键环节：

1. 用顾问真实任务建立摘要、翻译和知识问答评估集。
2. 由顾问和提示工程人员共同评价准确性与一致性。
3. 持续改进检索方法，并对样例问题做日常回归测试。
4. 对会议摘要和对外跟进保留人工检查与修改。

这使知识助手不只是一个聊天入口，而是一套包含可信资料、评估标准、专家反馈和持续测试的运营系统。

## Implementation：企业知识库要先回答“如何证明它可靠”

这部分是我们的编辑判断，不是 Morgan Stanley 的原话。

企业做[AI 知识库](/enterprise-knowledge-base)时，可以借鉴三点：

- 第一版不要追求覆盖所有资料，先覆盖一个岗位的高频问题。
- 上线前建立 30-100 个真实测试问题，并记录标准答案和引用来源。
- 模型、知识内容和提示词发生变化后，重新运行回归测试。

对金融、法律、医疗、合同和客户承诺等高风险场景，人工审核不是临时补丁，而是工作流的一部分。可以先通过[企业 AI 诊断](/ai-diagnosis)确定资料、权限、审核和验收标准，再进入实施。

## Result：公开披露的采用结果

OpenAI 的公开案例称，Morgan Stanley 财富管理顾问团队对相关 AI 工具的采用率超过 98%，知识助手覆盖范围也持续扩大。该结果建立在评估集、专家反馈、回归测试和人工审查之上，不应脱离这些条件单独理解。

## Lessons：可复用的试点路径

1. 选择一个问题集中、资料相对稳定的团队。
2. 整理正式资料，标记版本、权限和内容负责人。
3. 建立真实问题评估集和不可回答清单。
4. 先内部辅助，不直接面向客户自动输出。
5. 记录命中率、引用准确性、人工修改率和问题解决时间。
6. 通过评估后再增加资料、岗位和工具调用。

## References

- [OpenAI: Morgan Stanley uses AI evals to shape the future of financial services](https://openai.com/index/morgan-stanley/)
- [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)
- [企业 AI 知识库搭建](/enterprise-knowledge-base)
- [AI 工作流自动化](/ai-workflow-automation)
