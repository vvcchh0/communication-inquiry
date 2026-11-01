# Agent 通信研究线索

本支线源于用户关于 agent 是否形成自己的语言，以及防御性表达会怎样影响协作的疑问。当前会话已决定优先推进人的表达研究。

## 已查阅的原始材料

### OpenAI 的通信学习实验

[Learning to communicate，2017](https://openai.com/index/learning-to-communicate/)：代理在合作环境中通过共享奖励和训练形成通信符号及组合；发言成本、小词表偏好等实验条件参与塑造表达。研究关注带奖励及参数更新的训练过程。

### FAIR 的谈判实验

[Deal or no deal，2017](https://engineering.fb.com/2017/06/14/ml-applications/deal-or-no-deal-training-ai-bots-to-negotiate/)：同时训练谈判双方时观察到语言偏离人类语言；后续方案通过固定一方并保留人类语言训练维持与人的交流。语言漂移是否提升精度或效率，需按具体指标另行考察。

### Anthropic 的研究系统经验

[How we built our multi-agent research system](https://www.anthropic.com/research/multi-agent-research-system)：目标、输出要求、来源和任务边界的具体程度影响分工；过于笼统的任务描述会带来范围误解和重复搜索。这是系统工程经验，当前记录依据检索返回的相关正文节选。

### Anthropic 的协作实验

[Patterns and problems in multiagent systems](https://www.anthropic.com/research/multiagent-systems)：隐藏信息任务把事实分给不同代理，共有信息倾向于错误选项，个别代理掌握正确判断所需的关键事实。实验研究信息如何被提出和采纳，以及讨论中的共识与个体信息之间的关系。

## 后续可检验的问题

保持交接事实内容一致，比较直接陈述、相关否定和额外无关否定的表达，观察任务理解、工作范围扩张及完成质量。此为会话中提出的实验方向，尚未执行。

当前材料提供通信机制、任务交接和信息采纳的研究线索；针对本会话所定义“无来由的反驳”的影响，仍需专门寻找或设计实验。
