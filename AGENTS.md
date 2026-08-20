# AGENTS.md

量潮科技工作意图档案库（intention），记录「我们要什么、为什么」。意图是元工程体系的关键资产，是下游一切工程活动的输入。

## 文档定位

意图文档回答「我们要什么、为什么」，不回答「怎么做」：

- 纲领式：定位、核心目标、演化方向
- 机制细节归洞察库（data/insight），怎么走归路线图（data/roadmap），原始思考归日志（data/journal）
- 不引用文件路径

## 目录结构

按治理主题组织，每个主题一个文件夹，`index.md` 为入口：

- 主题：asset、delib、execute、strategy
- 业务线：qtacademics、qtadmin、qtbusiness、qtclass、qtcloud、qtconsult、qtcrowd、qtdata、qtopen、qtproduct、qtrecurit
- 总述：intro

## 工作流程

1. 进入仓库先读 README.md 与 CONTRIBUTING.md，浏览主题目录
2. 从日志沉淀意图：把 data/journal 中的思考收敛为意图表述
3. 新增或修改意图时，确认与洞察、路线图的分工：机制细节进 insight，演进进 roadmap
4. 用户精简后的版本是权威：不恢复被删内容，不添加用户删除的细节
5. 提交遵循 Conventional Commits（`docs: 描述`），原子提交

## 工作原则

- 纲领式优先：能一句话说清的不写一段
- 主题高于产品线：治理主题与业务线平级
- 用户意图优先：用户明确指示时以用户为准，不自作主张扩展
