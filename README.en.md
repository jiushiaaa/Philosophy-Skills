# Philosophy Skills

[中文](README.md) | [English](README.en.md)

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with Nuwa](https://img.shields.io/badge/Made_with-Nuwa-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**46 independent thinking and literary skills: 21 original modules + 25 attributed upstream modules.** Preserve disagreements; select the relevant thinker rather than blending them into a single worldview. Camus and Hegel use our independently rewritten versions.

The original modules were built with [nvwa-skill](https://github.com/alchaincyf/nuwa-skill). The other 25 retain their upstream authorship; they are not presented as our original work.

## Install the collection

This skill follows the open [Agent Skills](https://agentskills.io/) standard and can run in any skills-compatible AI agent runtime, including Claude Code, Codex, Cursor, OpenClaw, Hermes Agent, CodeBuddy, Workbuddy, Gemini CLI, OpenCode, and the broader ecosystem of 50+ runtimes.

```bash
npx skills add jiushiaaa/Philosophy-Skills
```

Select skills interactively. List available skills or install one directly:

```bash
npx skills add jiushiaaa/Philosophy-Skills --list
npx skills add jiushiaaa/Philosophy-Skills --skill descartes-perspective
```

Append `-a codex` / `-a claude-code` / `-a cursor` to select a runtime and `-g` for global installation. For manual installation, clone the repository and copy individual `skills/<name>/` folders to the runtime skill directory. Standard compatibility is not a claim of testing every runtime. See [Skills CLI](https://github.com/vercel-labs/skills).

## 21 original modules

|Thinker|Focus|Repository|Install|
|---|---|---|---|
|[Theodor W. Adorno](skills/adorno-perspective/README.en.md)|Non-identity, the culture industry, and negative critique|[adorno-skill](https://github.com/jiushiaaa/adorno-skill)|`npx skills add jiushiaaa/adorno-skill`|
|[J. L. Austin](skills/austin-perspective/README.en.md)|Speech acts, excuses, and situated distinctions|[austin-skill](https://github.com/jiushiaaa/austin-skill)|`npx skills add jiushiaaa/austin-skill`|
|[Albert Camus](skills/camus-perspective/README.en.md)|Absurdity, art, and concrete human situations|[camus-skill](https://github.com/jiushiaaa/camus-skill)|`npx skills add jiushiaaa/camus-skill`|
|[Auguste Comte](skills/comte-perspective/README.en.md)|Positive inquiry, classification of sciences, and historical limits|[comte-skill](https://github.com/jiushiaaa/comte-skill)|`npx skills add jiushiaaa/comte-skill`|
|[Jacques Derrida](skills/derrida-perspective/README.en.md)|Textual differences, iterability, and questions of justice|[derrida-skill](https://github.com/jiushiaaa/derrida-skill)|`npx skills add jiushiaaa/derrida-skill`|
|[René Descartes](skills/descartes-perspective/README.en.md)|Doubt, judgment, and grounds of knowledge|[descartes-skill](https://github.com/jiushiaaa/descartes-skill)|`npx skills add jiushiaaa/descartes-skill`|
|[Johann Gottlieb Fichte](skills/fichte-perspective/README.en.md)|Self-activity, judgment, and practice|[fichte-skill](https://github.com/jiushiaaa/fichte-skill)|`npx skills add jiushiaaa/fichte-skill`|
|[Hans-Georg Gadamer](skills/gadamer-perspective/README.en.md)|Understanding, tradition, and question-and-answer|[gadamer-skill](https://github.com/jiushiaaa/gadamer-skill)|`npx skills add jiushiaaa/gadamer-skill`|
|[Jürgen Habermas](skills/habermas-perspective/README.en.md)|Communication, validity claims, and public deliberation|[habermas-skill](https://github.com/jiushiaaa/habermas-skill)|`npx skills add jiushiaaa/habermas-skill`|
|[G. W. F. Hegel](skills/hegel-perspective/README.en.md)|Immanent critique, determinacy, and recognition|[hegel-skill](https://github.com/jiushiaaa/hegel-skill)|`npx skills add jiushiaaa/hegel-skill`|
|[Martin Heidegger](skills/heidegger-perspective/README.en.md)|Everydayness, being-in-the-world, and understanding|[heidegger-skill](https://github.com/jiushiaaa/heidegger-skill)|`npx skills add jiushiaaa/heidegger-skill`|
|[Max Horkheimer](skills/horkheimer-perspective/README.en.md)|Instrumental reason and critical theory|[horkheimer-skill](https://github.com/jiushiaaa/horkheimer-skill)|`npx skills add jiushiaaa/horkheimer-skill`|
|[Edmund Husserl](skills/husserl-perspective/README.en.md)|Intentionality, epoché, and descriptions of experience|[husserl-skill](https://github.com/jiushiaaa/husserl-skill)|`npx skills add jiushiaaa/husserl-skill`|
|[Søren Kierkegaard](skills/kierkegaard-perspective/README.en.md)|Existence, choice, and indirect communication|[kierkegaard-skill](https://github.com/jiushiaaa/kierkegaard-skill)|`npx skills add jiushiaaa/kierkegaard-skill`|
|[Claude Lévi-Strauss](skills/levi-strauss-perspective/README.en.md)|Structural relations, classification, and cultural evaluation|[levi-strauss-skill](https://github.com/jiushiaaa/levi-strauss-skill)|`npx skills add jiushiaaa/levi-strauss-skill`|
|[John Stuart Mill](skills/mill-perspective/README.en.md)|Liberty, utility, and representative government|[mill-skill](https://github.com/jiushiaaa/mill-skill)|`npx skills add jiushiaaa/mill-skill`|
|[Charles S. Peirce](skills/peirce-perspective/README.en.md)|Belief, doubt, and inquiry|[peirce-skill](https://github.com/jiushiaaa/peirce-skill)|`npx skills add jiushiaaa/peirce-skill`|
|[Bertrand Russell](skills/russell-perspective/README.en.md)|Logical analysis, knowledge, and social ideals|[russell-skill](https://github.com/jiushiaaa/russell-skill)|`npx skills add jiushiaaa/russell-skill`|
|[Jean-Paul Sartre](skills/sartre-perspective/README.en.md)|Freedom, bad faith, and common praxis|[sartre-skill](https://github.com/jiushiaaa/sartre-skill)|`npx skills add jiushiaaa/sartre-skill`|
|[F. W. J. Schelling](skills/schelling-perspective/README.en.md)|Subject-object relations, ground, and freedom|[schelling-skill](https://github.com/jiushiaaa/schelling-skill)|`npx skills add jiushiaaa/schelling-skill`|
|[William James](skills/william-james-perspective/README.en.md)|Experience, pragmatism, and belief|[william-james-skill](https://github.com/jiushiaaa/william-james-skill)|`npx skills add jiushiaaa/william-james-skill`|

## 25 upstream modules and credits

|Thinker|Original repository|Author / owner|License|
|---|---|---|---|
|[Hannah Arendt](skills/arendt-perspective/README.en.md)|[nuwa-skills/arendt-skill](https://github.com/nuwa-skills/arendt-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/arendt-perspective/LICENSE)|
|[Aristotle](skills/aristotle-perspective/README.en.md)|[nuwa-skills/aristotle-skill](https://github.com/nuwa-skills/aristotle-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/aristotle-perspective/LICENSE)|
|[Simone de Beauvoir](skills/beauvoir-perspective/README.en.md)|[nuwa-skills/beauvoir-skill](https://github.com/nuwa-skills/beauvoir-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/beauvoir-perspective/LICENSE)|
|[Jorge Luis Borges](skills/borges-perspective/README.en.md)|[nuwa-skills/borges-skill](https://github.com/nuwa-skills/borges-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/borges-perspective/LICENSE)|
|[John Dewey](skills/dewey-perspective/README.en.md)|[nuwa-skills/dewey-skill](https://github.com/nuwa-skills/dewey-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/dewey-perspective/LICENSE)|
|[Michel Foucault](skills/foucault-perspective/README.en.md)|[nuwa-skills/foucault-skill](https://github.com/nuwa-skills/foucault-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/foucault-perspective/LICENSE)|
|[Ernest Hemingway](skills/hemingway-perspective/README.en.md)|[nuwa-skills/hemingway-skill](https://github.com/nuwa-skills/hemingway-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/hemingway-perspective/LICENSE)|
|[Franz Kafka](skills/kafka-perspective/README.en.md)|[nuwa-skills/kafka-skill](https://github.com/nuwa-skills/kafka-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/kafka-perspective/LICENSE)|
|[Immanuel Kant](skills/kant-perspective/README.en.md)|[nuwa-skills/kant-skill](https://github.com/nuwa-skills/kant-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/kant-perspective/LICENSE)|
|[Karl Marx](skills/karl-marx/README.en.md)|[youaifuou/karl-marx-skill](https://github.com/youaifuou/karl-marx-skill/tree/main/karl-marx)|[youaifuou](https://github.com/youaifuou)|[MIT](skills/karl-marx/LICENSE)|
|[Lao She](skills/laoshe-perspective/README.en.md)|[momozi1996/awesome-ai-persona-skills](https://github.com/momozi1996/awesome-ai-persona-skills/tree/main/Novelists/laoshe-skill)|[momozi1996](https://github.com/momozi1996)|[MIT](skills/laoshe-perspective/LICENSE)|
|[Lu Xun](skills/luxun-perspective/README.en.md)|[youaifuou/luxun-skill](https://github.com/youaifuou/luxun-skill/tree/main/luxun-perspective)|[youaifuou](https://github.com/youaifuou)|[MIT](skills/luxun-perspective/LICENSE)|
|[Mao Zedong](skills/mao/README.en.md)|[wwwaapplleecu-source/mao-skill](https://github.com/wwwaapplleecu-source/mao-skill)|[wwwaapplleecu-source](https://github.com/wwwaapplleecu-source)|[MIT](skills/mao/LICENSE)|
|[Mozi](skills/mozi-perspective/README.en.md)|[nuwa-skills/mozi-skill](https://github.com/nuwa-skills/mozi-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/mozi-perspective/LICENSE)|
|[Friedrich Nietzsche](skills/nietzsche-perspective/README.en.md)|[nuwa-skills/nietzsche-skill](https://github.com/nuwa-skills/nietzsche-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/nietzsche-perspective/LICENSE)|
|[George Orwell](skills/orwell-perspective/README.en.md)|[nuwa-skills/orwell-skill](https://github.com/nuwa-skills/orwell-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/orwell-perspective/LICENSE)|
|[Plato](skills/plato-perspective/README.en.md)|[nuwa-skills/plato-skill](https://github.com/nuwa-skills/plato-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/plato-perspective/LICENSE)|
|[Arthur Schopenhauer](skills/schopenhauer-perspective/README.en.md)|[nuwa-skills/schopenhauer-skill](https://github.com/nuwa-skills/schopenhauer-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/schopenhauer-perspective/LICENSE)|
|[Shi Tiesheng](skills/shitiesheng-perspective/README.en.md)|[momozi1996/awesome-ai-persona-skills](https://github.com/momozi1996/awesome-ai-persona-skills/tree/main/Novelists/shitiesheng-skill)|[momozi1996](https://github.com/momozi1996)|[MIT](skills/shitiesheng-perspective/LICENSE)|
|[Socrates](skills/socrates-perspective/README.en.md)|[nuwa-skills/socrates-skill](https://github.com/nuwa-skills/socrates-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/socrates-perspective/LICENSE)|
|[Wang Xiaobo](skills/wangxiaobo-perspective/README.en.md)|[nuwa-skills/wangxiaobo-skill](https://github.com/nuwa-skills/wangxiaobo-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/wangxiaobo-perspective/LICENSE)|
|[Wang Yangming](skills/wangyangming-perspective/README.en.md)|[nuwa-skills/wangyangming-skill](https://github.com/nuwa-skills/wangyangming-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/wangyangming-perspective/LICENSE)|
|[Ludwig Wittgenstein](skills/wittgenstein-perspective/README.en.md)|[nuwa-skills/wittgenstein-skill](https://github.com/nuwa-skills/wittgenstein-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/wittgenstein-perspective/LICENSE)|
|[Eileen Chang](skills/zhangailing-perspective/README.en.md)|[momozi1996/awesome-ai-persona-skills](https://github.com/momozi1996/awesome-ai-persona-skills/tree/main/Novelists/zhangailing-skill)|[momozi1996](https://github.com/momozi1996)|[MIT](skills/zhangailing-perspective/LICENSE)|
|[Zhuangzi](skills/zhuangzi-perspective/README.en.md)|[nuwa-skills/zhuangzi-skill](https://github.com/nuwa-skills/zhuangzi-skill)|[nuwa-skills](https://github.com/nuwa-skills)|[MIT](skills/zhuangzi-perspective/LICENSE)|

## Using the collection

Our 21 modules default to neutral thought analysis. Persona expression requires an explicit request; fiction work returns to neutral analysis. The 25 upstream modules keep their own instructions and may have different defaults. Choose one module at a time, or ask for separately sourced comparisons. See [USAGE.md](USAGE.md).

## License and sources

Original work and integration documentation are [MIT licensed](LICENSE). Upstream modules retain their original copyright and license notices; their repositories are linked above. Source books and translations retain their separate rights. See [ATTRIBUTION.md](ATTRIBUTION.md).

README and usage guides are bilingual; skill bodies and research notes retain their source languages.
