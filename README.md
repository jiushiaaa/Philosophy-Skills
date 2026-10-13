# Philosophy Skills

[中文](README.md) | [English](README.en.md)

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with Nuwa](https://img.shields.io/badge/Made_with-Nuwa-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**46个独立思想与文学 Skill：21个自制模块 + 25个注明来源的上游模块。** 各人物保持独立，按问题选择，不把不同思想混成一种立场。加缪、黑格尔仅收录本项目独立重写版。

21个自制模块使用 [nvwa-skill](https://github.com/alchaincyf/nuwa-skill) 构建，其余25个保留上游归属，不作为本项目原创成果。

## 安装合集

本 skill 基于开放的 [Agent Skills](https://agentskills.io/) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

```bash
npx skills add jiushiaaa/Philosophy-Skills
```

运行后选择需要的 Skill；也可先列出清单或只安装一个：

```bash
npx skills add jiushiaaa/Philosophy-Skills --list
npx skills add jiushiaaa/Philosophy-Skills --skill descartes-perspective
```

指定 runtime 添加 `-a codex` / `-a claude-code` / `-a cursor`，全局安装添加 `-g`。手动安装可克隆仓库，再复制 `skills/<name>/` 完整目录到对应 runtime。协议兼容不代表逐一实测全部 runtime。安装器见 [Skills CLI](https://github.com/vercel-labs/skills)。

## 21个自制模块

|人物|方向|独立仓库|安装|
|---|---|---|---|
|[阿多诺](skills/adorno-perspective/README.md)|非同一性、文化工业与否定批判|[adorno-skill](https://github.com/jiushiaaa/adorno-skill)|`npx skills add jiushiaaa/adorno-skill`|
|[奥斯汀](skills/austin-perspective/README.md)|言语行为、借口与具体情境|[austin-skill](https://github.com/jiushiaaa/austin-skill)|`npx skills add jiushiaaa/austin-skill`|
|[加缪](skills/camus-perspective/README.md)|荒诞、艺术与具体人的处境|[camus-skill](https://github.com/jiushiaaa/camus-skill)|`npx skills add jiushiaaa/camus-skill`|
|[孔德](skills/comte-perspective/README.md)|实证方法、科学分类与历史限制|[comte-skill](https://github.com/jiushiaaa/comte-skill)|`npx skills add jiushiaaa/comte-skill`|
|[德里达](skills/derrida-perspective/README.md)|文本差异、可重复性与正义问题|[derrida-skill](https://github.com/jiushiaaa/derrida-skill)|`npx skills add jiushiaaa/derrida-skill`|
|[笛卡尔](skills/descartes-perspective/README.md)|怀疑、判断与认识根据|[descartes-skill](https://github.com/jiushiaaa/descartes-skill)|`npx skills add jiushiaaa/descartes-skill`|
|[费希特](skills/fichte-perspective/README.md)|自我活动、判断与实践|[fichte-skill](https://github.com/jiushiaaa/fichte-skill)|`npx skills add jiushiaaa/fichte-skill`|
|[伽达默尔](skills/gadamer-perspective/README.md)|理解、传统与问答|[gadamer-skill](https://github.com/jiushiaaa/gadamer-skill)|`npx skills add jiushiaaa/gadamer-skill`|
|[哈贝马斯](skills/habermas-perspective/README.md)|交往、有效性要求与公共讨论|[habermas-skill](https://github.com/jiushiaaa/habermas-skill)|`npx skills add jiushiaaa/habermas-skill`|
|[黑格尔](skills/hegel-perspective/README.md)|内在批判、规定性与承认|[hegel-skill](https://github.com/jiushiaaa/hegel-skill)|`npx skills add jiushiaaa/hegel-skill`|
|[海德格尔](skills/heidegger-perspective/README.md)|日常性、在世存在与理解|[heidegger-skill](https://github.com/jiushiaaa/heidegger-skill)|`npx skills add jiushiaaa/heidegger-skill`|
|[霍克海默](skills/horkheimer-perspective/README.md)|工具理性与批判理论|[horkheimer-skill](https://github.com/jiushiaaa/horkheimer-skill)|`npx skills add jiushiaaa/horkheimer-skill`|
|[胡塞尔](skills/husserl-perspective/README.md)|意向性、悬置与经验描述|[husserl-skill](https://github.com/jiushiaaa/husserl-skill)|`npx skills add jiushiaaa/husserl-skill`|
|[克尔凯郭尔](skills/kierkegaard-perspective/README.md)|生存、选择与间接传达|[kierkegaard-skill](https://github.com/jiushiaaa/kierkegaard-skill)|`npx skills add jiushiaaa/kierkegaard-skill`|
|[列维-斯特劳斯](skills/levi-strauss-perspective/README.md)|结构关系、分类与文化评价|[levi-strauss-skill](https://github.com/jiushiaaa/levi-strauss-skill)|`npx skills add jiushiaaa/levi-strauss-skill`|
|[穆勒](skills/mill-perspective/README.md)|自由、功利与代议制度|[mill-skill](https://github.com/jiushiaaa/mill-skill)|`npx skills add jiushiaaa/mill-skill`|
|[皮尔士](skills/peirce-perspective/README.md)|信念、怀疑与探究|[peirce-skill](https://github.com/jiushiaaa/peirce-skill)|`npx skills add jiushiaaa/peirce-skill`|
|[罗素](skills/russell-perspective/README.md)|逻辑分析、知识与社会理想|[russell-skill](https://github.com/jiushiaaa/russell-skill)|`npx skills add jiushiaaa/russell-skill`|
|[萨特](skills/sartre-perspective/README.md)|自由、自欺与共同实践|[sartre-skill](https://github.com/jiushiaaa/sartre-skill)|`npx skills add jiushiaaa/sartre-skill`|
|[谢林](skills/schelling-perspective/README.md)|主客关系、根据与自由|[schelling-skill](https://github.com/jiushiaaa/schelling-skill)|`npx skills add jiushiaaa/schelling-skill`|
|[威廉·詹姆斯](skills/william-james-perspective/README.md)|经验、实用主义与信念|[william-james-skill](https://github.com/jiushiaaa/william-james-skill)|`npx skills add jiushiaaa/william-james-skill`|

## 25个上游模块与来源

|人物|原始仓库|作者 / 维护者|许可|
|---|---|---|---|
|[阿伦特](skills/arendt-perspective/README.md)|[nuwa-skills/arendt-skill](https://github.com/nuwa-skills/arendt-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/arendt-perspective/LICENSE)|
|[亚里士多德](skills/aristotle-perspective/README.md)|[nuwa-skills/aristotle-skill](https://github.com/nuwa-skills/aristotle-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/aristotle-perspective/LICENSE)|
|[波伏娃](skills/beauvoir-perspective/README.md)|[nuwa-skills/beauvoir-skill](https://github.com/nuwa-skills/beauvoir-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/beauvoir-perspective/LICENSE)|
|[博尔赫斯](skills/borges-perspective/README.md)|[nuwa-skills/borges-skill](https://github.com/nuwa-skills/borges-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/borges-perspective/LICENSE)|
|[杜威](skills/dewey-perspective/README.md)|[nuwa-skills/dewey-skill](https://github.com/nuwa-skills/dewey-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/dewey-perspective/LICENSE)|
|[福柯](skills/foucault-perspective/README.md)|[nuwa-skills/foucault-skill](https://github.com/nuwa-skills/foucault-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/foucault-perspective/LICENSE)|
|[海明威](skills/hemingway-perspective/README.md)|[nuwa-skills/hemingway-skill](https://github.com/nuwa-skills/hemingway-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/hemingway-perspective/LICENSE)|
|[卡夫卡](skills/kafka-perspective/README.md)|[nuwa-skills/kafka-skill](https://github.com/nuwa-skills/kafka-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/kafka-perspective/LICENSE)|
|[康德](skills/kant-perspective/README.md)|[nuwa-skills/kant-skill](https://github.com/nuwa-skills/kant-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/kant-perspective/LICENSE)|
|[马克思](skills/karl-marx/README.md)|[youaifuou/karl-marx-skill](https://github.com/youaifuou/karl-marx-skill/tree/main/karl-marx)|[youaifuou](https://github.com/youaifuou)|[MIT](skills/karl-marx/LICENSE)|
|[老舍](skills/laoshe-perspective/README.md)|[momozi1996/awesome-ai-persona-skills](https://github.com/momozi1996/awesome-ai-persona-skills/tree/main/Novelists/laoshe-skill)|[momozi1996](https://github.com/momozi1996)|[MIT](skills/laoshe-perspective/LICENSE)|
|[鲁迅](skills/luxun-perspective/README.md)|[youaifuou/luxun-skill](https://github.com/youaifuou/luxun-skill/tree/main/luxun-perspective)|[youaifuou](https://github.com/youaifuou)|[MIT](skills/luxun-perspective/LICENSE)|
|[毛泽东](skills/mao/README.md)|[wwwaapplleecu-source/mao-skill](https://github.com/wwwaapplleecu-source/mao-skill)|[wwwaapplleecu-source](https://github.com/wwwaapplleecu-source)|[MIT](skills/mao/LICENSE)|
|[墨子](skills/mozi-perspective/README.md)|[nuwa-skills/mozi-skill](https://github.com/nuwa-skills/mozi-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/mozi-perspective/LICENSE)|
|[尼采](skills/nietzsche-perspective/README.md)|[nuwa-skills/nietzsche-skill](https://github.com/nuwa-skills/nietzsche-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/nietzsche-perspective/LICENSE)|
|[奥威尔](skills/orwell-perspective/README.md)|[nuwa-skills/orwell-skill](https://github.com/nuwa-skills/orwell-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/orwell-perspective/LICENSE)|
|[柏拉图](skills/plato-perspective/README.md)|[nuwa-skills/plato-skill](https://github.com/nuwa-skills/plato-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/plato-perspective/LICENSE)|
|[叔本华](skills/schopenhauer-perspective/README.md)|[nuwa-skills/schopenhauer-skill](https://github.com/nuwa-skills/schopenhauer-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/schopenhauer-perspective/LICENSE)|
|[史铁生](skills/shitiesheng-perspective/README.md)|[momozi1996/awesome-ai-persona-skills](https://github.com/momozi1996/awesome-ai-persona-skills/tree/main/Novelists/shitiesheng-skill)|[momozi1996](https://github.com/momozi1996)|[MIT](skills/shitiesheng-perspective/LICENSE)|
|[苏格拉底](skills/socrates-perspective/README.md)|[nuwa-skills/socrates-skill](https://github.com/nuwa-skills/socrates-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/socrates-perspective/LICENSE)|
|[王小波](skills/wangxiaobo-perspective/README.md)|[nuwa-skills/wangxiaobo-skill](https://github.com/nuwa-skills/wangxiaobo-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/wangxiaobo-perspective/LICENSE)|
|[王阳明](skills/wangyangming-perspective/README.md)|[nuwa-skills/wangyangming-skill](https://github.com/nuwa-skills/wangyangming-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/wangyangming-perspective/LICENSE)|
|[维特根斯坦](skills/wittgenstein-perspective/README.md)|[nuwa-skills/wittgenstein-skill](https://github.com/nuwa-skills/wittgenstein-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/wittgenstein-perspective/LICENSE)|
|[张爱玲](skills/zhangailing-perspective/README.md)|[momozi1996/awesome-ai-persona-skills](https://github.com/momozi1996/awesome-ai-persona-skills/tree/main/Novelists/zhangailing-skill)|[momozi1996](https://github.com/momozi1996)|[MIT](skills/zhangailing-perspective/LICENSE)|
|[庄子](skills/zhuangzi-perspective/README.md)|[nuwa-skills/zhuangzi-skill](https://github.com/nuwa-skills/zhuangzi-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/zhuangzi-perspective/LICENSE)|

## 怎样使用

21个自制模块默认中性思想分析，明确请求后才开启人物表达，进入文游恢复中性。25个上游模块保留自己的规则，默认行为可能不同。按需选择单个人物，比较时分别给出依据并保留分歧。详见 [USAGE.md](USAGE.md)。

## 许可与来源

原创内容与整合文档采用 [MIT](LICENSE)。上游模块保留原作者署名与许可，原始仓库见上方列表；引用的原著与译本保留各自权利。详见 [来源说明](ATTRIBUTION.md)。

README 与使用文档提供中英双语，Skill 正文与研究底稿保留原文。
