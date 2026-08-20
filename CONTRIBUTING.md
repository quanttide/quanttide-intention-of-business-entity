# CONTRIBUTING

本仓库是量潮科技工作意图档案库（intention），记录「我们要什么、为什么」——意图是下游一切工程活动的输入。

## 项目结构

按治理主题组织，每个主题一个文件夹，`index.md` 为入口：

```
data/intention/
├── asset/          # 资产主题
├── delib/          # 议事主题
├── execute/        # 执行环节主题
├── strategy/       # 战略主题
├── qtadmin/        # 量潮管理后台
├── qtclass/        # 量潮课堂
├── qtcloud/        # 量潮云
├── qtconsult/      # 量潮咨询
├── qtcrowd/        # 量潮众包
├── qtdata/         # 量潮数据
├── qtrecurit/      # 量潮招聘
└── intro/          # 总述
```

## 文档规范

### 意图文档回答「我们要什么、为什么」

- 纲领式：定位、核心目标、演化方向
- 不写工程细节：机制细节归洞察库，怎么走归路线图，实现归工程层
- 不引用文件路径

### 按主题组织

- 主题文件夹是可持续生长的容器：`index.md` 为入口，主题内部可继续展开子文档
- 主题高于产品线：治理主题（asset、delib、execute、strategy）与业务线（qtcloud、qtdata 等）平级
- 跨主题的内容归位洞察库的 org 与 knowl，意图层不重复承载

## 维护流程

- 从日志沉淀意图：data/journal 中的思考收敛为意图表述
- 意图与洞察、路线图对齐：机制细节进 insight，演进进 roadmap
- 用户精简后以用户版本为准：纲领式优先，删除状态与工程细节

## 提交规范

遵循 Conventional Commits：`docs: 描述`。
