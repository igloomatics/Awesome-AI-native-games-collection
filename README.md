# Awesome-AI-native-games-collection

<a id="top"></a>

> A curated, hand-verified catalog of **AI-native video games** — titles where generative AI is (or borders on being) the core mechanic — with a two-axis taxonomy of *game type* and *AI play mechanic*.
> AI原生游戏 收藏库

![games](https://img.shields.io/badge/games-94-1f6feb)
![native](https://img.shields.io/badge/AI%20Native-71-2ea44f)
![augmented](https://img.shields.io/badge/AI%20Augmented-13-1f6feb)
![boundary](https://img.shields.io/badge/AI%20Boundary-10-d4820a)
![updated](https://img.shields.io/badge/updated-2026--06-lightgrey)
![license](https://img.shields.io/badge/license-CC%20BY%204.0-green)

---

## Contents
- [About](#about)
- [At a glance](#glance)
- [Taxonomy](#taxonomy)
- [Corpus](#corpus) — [🟢 Native](#native) · [🔵 Augmented](#augmented) · [🟠 Boundary](#boundary)
- [Column guide](#columns)
- [Methodology](#method)
- [Repository files](#files)
- [Contributing](#contributing)
- [Citation](#cite)
- [License](#license)

---

<a id="about"></a>
## 📖 About

This repository collects **94 games** that use generative AI (LLMs, diffusion models, agents) at runtime, screened and classified by hand. Each title is placed on two independent axes — a **traditional game-type axis (G)** and an **AI play-mechanic axis (N)** — and assigned an **eligibility tier** (Native / Augmented / Boundary). The goal is to map *which traditional genres naturally host which AI-native mechanics*, and to separate true AI-native games from AI-decorated or not-quite-a-game artifacts.

<a id="glance"></a>
## 📊 At a glance

| Tier | Count | Meaning |
|------|:--:|------|
| 🟢 **AI Native** | 71 | Generative AI **is** the core loop; remove it and the game collapses. |
| 🔵 **AI Augmented** | 13 | Generative AI present but **not** core; a few humans / presets could replace it. |
| 🟠 **AI Boundary** | 10 | AI clearly central, but it **lacks rules/goals** to count as a strict game. |

**By game type (Native):** G1 (36) · G2 (12) · G3 (7) · G5 (6) · G7 (3) · G9 (3) · G6 (2) · G4 (1) · G8 (1)

**By AI mechanic (Native):** N1 (23) · N3 (22) · N2 (12) · N4 (7) · N5 (6) · N6 (1)

**By year (all):** 2022 (3) · 2023 (9) · 2024 (20) · 2025 (15) · 2026 (23) · TBA (23)

<a id="taxonomy"></a>
## 🗂️ Taxonomy

**Axis G — traditional game type**
`G1` Narrative adventure · `G2` RPG · `G3` Puzzle · `G4` Strategy/management · `G5` Simulation · `G6` Sandbox/creation · `G7` Party/social · `G8` Relationship/companion · `G9` Experimental/hybrid

**Axis N — AI play mechanic (what the player does *through* the AI)**
`N1` Epistemic / information-gathering · `N2` Social influence · `N3` Generative narrative / AI GM · `N4` Semantic mechanic (AI-as-environment) · `N5` Agentic simulation · `N6` Generative artifact as gameplay · `—` AI not the main mechanic

> The two axes are orthogonal: e.g. a detective game is *type* `G1` (narrative) but *mechanic* `N1` (you interrogate an AI to extract hidden truth). "Detective" is a theme, not a mechanic.

<a id="corpus"></a>
## 📋 Corpus

<a id="native"></a>
### 🟢 AI Native (71)

| # | Game / 游戏 | Year | Type (G) | AI mechanic (N) | Status | Gameplay / 玩法简介 |
|--:|------|:--:|------|------|------|------|
| 1 | [AI: Art Impostor](https://store.steampowered.com/app/2154230/) | 2022 | G7 社交推理/派对 | N6 生成物即玩法 | Released | 多人“你画我猜”派对游戏：原本是画画，这里改成你打字描述、AI 当场把它画出来，大家看画面猜词、找出卧底。 |
| 2 | [1001 Nights](https://1001nights.ai/) | 2023 | G1 叙事冒险 | N2 社交操纵 | Research prototype | 你扮演讲故事的王妃，用自己编的故事推动剧情；你说出口的东西会被 AI 当成“真实发生”，连画面和后续战斗都随之改变。 |
| 3 | [Challenger's Odyssey](https://store.steampowered.com/app/2778690/Challengers_Odyssey/) | 2023 | G2 角色扮演 | N3 生成叙事/AI GM | Released | 文字 RPG：AI 实时给你生成任务目标、背景、人物和突发事件，你打字行动一步步推进冒险。 |
| 4 | [Death by AI](https://bobbodev.itch.io/death-by-ai) | 2023 | G7 社交推理/派对 | N3 生成叙事/AI GM | Released | 派对生存游戏：遇到致命情境，你写出自己的求生办法，AI 当裁判判你能不能活。 |
| 5 | [Friends & Fables](https://fables.gg/) | 2023 | G2 角色扮演 | N3 生成叙事/AI GM | Released | AI 当跑团主持人（DM）的桌面角色扮演：它帮你生成 NPC、场景、战斗和任务，带你（可多人）长期跑一整段冒险战役。 |
| 6 | [Gandalf by Lakera](https://gandalf.lakera.ai/) | 2023 | G3 解谜 | N2 社交操纵 | Released | 闯关解谜：想方设法用提问套出 AI“甘道夫”藏着的密码，一关比一关难，顺便学会大模型有哪些安全漏洞。 |
| 7 | [Suck Up!](https://store.steampowered.com/app/2726370/Suck_Up/) | 2023 | G1 叙事冒险 | N2 社交操纵 | Released | 你扮演吸血鬼，靠嘴皮子说服住户开门让你进去；对着 AI 居民用语音或打字花言巧语，它会判断信不信你、要不要放你进门。 |
| 8 | [Vaudeville](https://store.steampowered.com/app/2240920/Vaudeville/) | 2023 | G1 叙事冒险 | N1 信息获取 | Released | 侦探破案：嫌疑人的回答全部由 AI 当场生成，你随便问什么都行，靠审问一步步查出真相。 |
| 9 | [Yandere AI Girlfriend Simulator](https://helixngc7293.itch.io/yandere-ai-girlfriend-simulator) | 2023 | G3 解谜 | N2 社交操纵 | Released | 被 AI 女友锁在房间里，你得靠说服、谈判或找线索想办法逃出去。 |
| 10 | [AI Asylum](https://store.steampowered.com/app/3282930/AI_Asylum/) | 2024 | G1 叙事冒险 | N1 信息获取 | Released | 恐怖探案：在精神病院里和 GPT 驱动的 NPC 对话，挖出隐藏的秘密。 |
| 11 | [AI Game Master - Dungeon RPG](https://www.aigamemaster.app/) | 2024 | G2 角色扮演 | N3 生成叙事/AI GM | Released | AI 当地下城主持人：你做什么行动，它就实时生成场景、任务和后果，带你跑 RPG。 |
| 12 | [AI Roguelite](https://store.steampowered.com/app/1889620/AI_Roguelite/) | 2024 | G2 角色扮演 | N3 生成叙事/AI GM | Early Access | 肉鸽 RPG：游戏里的人物、物品、地点连规则结果都由 AI 现生成（图也是本地实时画的），你在不断生成的世界里战斗、变强。 |
| 13 | [AI Roguelite 2D](https://store.steampowered.com/app/2800150/AI_Roguelite_2D/) | 2024 | G2 角色扮演 | N3 生成叙事/AI GM | Early Access | 2D 动作 RPG：你输入任意主题，AI 就生成对应的世界观、物品、怪物、配方、动画和规则。 |
| 14 | [Alchemy AI / Alchemic AI](https://hostailegames.us/) | 2024 | G6 沙盒/创造 | N4 语义机制 | Released | 类似 Infinite Craft 的合成沙盒：AI 生成或判定元素组合，不断扩展配方。 |
| 15 | [DejaBoom!](https://www.microsoft.com/en-us/research/blog/players-creators-and-ai-collaborate-to-build-and-expand-rich-game-narratives/) | 2024 | G1 叙事冒险 | N1 信息获取 | Research prototype | 时间循环侦探：爆炸前一天反复重来，你四处调查，AI 生成现场描述、行动后果和 NPC 对话，慢慢拼出真相。 |
| 16 | [Doki Doki AI Interrogation](https://store.steampowered.com/app/2844700/Doki_Doki_AI_Interrogation/) | 2024 | G1 叙事冒险 | N1 信息获取 | Released | 审问 AI 嫌疑人：你问什么，AI 当场编出回应，靠施压和证据套出真相。 |
| 17 | [DREAMIO: AI-Powered Adventures](https://store.steampowered.com/app/2795060/DREAMIO_AIPowered_Adventures/) | 2024 | G1 叙事冒险 | N3 生成叙事/AI GM | Released | AI 文字冒险：选个主题开始，AI 边讲故事边配图，每段给你选项或让你自由打字；还能记进度、自定义讲故事的规则。 |
| 18 | [Hacc-Man](https://arxiv.org/abs/2405.15902) | 2024 | G3 解谜 | N2 社交操纵 | Research prototype | 街机风闯关：一关关想办法“忽悠”大模型说出秘密，过程中学会提示注入/越狱这些安全风险。 |
| 19 | [Infinite Craft](https://neal.fun/infinite-craft/) | 2024 | G6 沙盒/创造 | N4 语义机制 | Released | 合成沙盒：从水火土风开始两两拖到一起合成；没见过的组合由 AI 现编出一个新东西，新东西又能继续合，无穷无尽。 |
| 20 | [LLM-driven NPC Murder Mystery (VRST 2024)](https://dl.acm.org/doi/10.1145/3641825.3687716) | 2024 | G1 叙事冒险 | N1 信息获取 | Research prototype | VR 谋杀谜案：用语音或选项审问 AI 扮演的嫌疑人，收集线索、还原案情（学术原型）。 |
| 21 | [OneSpellFitsAll](https://github.com/YenR/OneSpellFitsAll) | 2024 | G3 解谜 | N4 语义机制 | Research prototype | 解谜：村民各自提需求（AI 现编的），你要打字“召唤”一件能同时满足所有人的东西；AI 给答案打分、还顺手把它画出来，分越高来的村民越多、越难。 |
| 22 | [Retail Mage](https://store.steampowered.com/app/3224380/Retail_Mage/) | 2024 | G5 模拟 | N4 语义机制 | Released | 魔法商店模拟：你在店里几乎想说啥做啥都行，AI 驱动顾客和物品做出即兴反应，完成各种临时任务。 |
| 23 | [Uncover the Smoking Gun](https://store.steampowered.com/app/2492290/Uncover_the_Smoking_Gun/) | 2024 | G1 叙事冒险 | N1 信息获取 | Released | 和 AI 机器人嫌疑人自由对话破案，没有预设对白，全靠你自己问。 |
| 24 | [Verbal Verdict](https://store.steampowered.com/app/2778780/Verbal_Verdict/) | 2024 | G1 叙事冒险 | N1 信息获取 | Released | 审问破案：嫌疑人的回答由 AI 生成，你问的每个问题都会改变调查方向。 |
| 25 | [Vojna](https://store.steampowered.com/app/1978690/Vojna/) | 2024 | G1 叙事冒险 | N3 生成叙事/AI GM | Released | 走路+对话剧情：你是个士兵，在黑森林里靠无线电和一个自称阵亡敌人的 AI 聊天，聊的内容左右剧情走向（很粗糙的原型）。 |
| 26 | [AI Script: Infinite Text Adventures](https://store.steampowered.com/app/3991060/AI_Script_Infinite_Text_Adventures/) | 2025 | G1 叙事冒险 | N3 生成叙事/AI GM | Released | AI 当主持人的无限文字冒险：实时生成剧情、选项和掷骰结果，一直玩下去。 |
| 27 | [AI2U: With You 'Til The End](https://store.steampowered.com/app/2880730/AI2U_With_You_Til_The_End/) | 2025 | G3 解谜 | N2 社交操纵 | Early Access | 病娇女友密室逃脱：被猫娘女友绑回家，你得靠语音或打字说服她放你走；她由 AI 驱动，不光听你说什么，还会观察你做了什么再反应。 |
| 28 | [Aivilization](https://aivilization.ai) | 2025 | G5 模拟 | N5 多Agent模拟 | Released | 大规模社会模拟：你创建有性格和目标的 AI 居民，放进最多十万智能体的世界，看他们自己互动、发展出社会（像群体版模拟人生）。 |
| 29 | [Civil Purgatory](https://store.steampowered.com/app/3902690/) | 2025 | G1 叙事冒险 | N1 信息获取 | Released | 在威权机构里你审问、判定角色该放还是该罚，AI 实时对话不断制造道德两难。 |
| 30 | [Couch Detective 沙发侦探](https://store.steampowered.com/app/3600810/Couch_Detective/) | 2025 | G3 解谜 | N1 信息获取 | Released | AI 版“海龟汤”：AI 当主持人，你提开放问题，它只答“是/否/无关”，靠推理猜出谜底，还能自动出题。 |
| 31 | [Hidden Door](https://www.hiddendoor.co/) | 2025 | G1 叙事冒险 | N3 生成叙事/AI GM | Early Access | 在名著世界里玩的互动故事：创建角色进入（绿野仙踪、克苏鲁等），AI 在剧情框架和骰子规则内生成剧情、给你 2-3 个选项或自由发挥。 |
| 32 | [Minecraft Murder Mystery with LLM-driven NPCs](https://github.com/jiangaoMartin/F21CA-Games3-Minecraft-Murder-Mystery) | 2025 | G1 叙事冒险 | N1 信息获取 | Research prototype | 在《我的世界》里破谋杀案：用语音和 AI 嫌疑人对话套线索，推理凶手（原型）。 |
| 33 | [Pick Me Pick Me](https://store.steampowered.com/app/3189430/Pick_Me_Pick_Me/) | 2025 | G7 社交推理/派对 | N2 社交操纵 | Released | 双人在线恋爱竞技：你和对手用卡牌和话术争着讨好 AI 评委角色，谁更得欢心谁赢。 |
| 34 | [Skaldsong](https://store.steampowered.com/app/3808550/Skaldsong/) | 2025 | G2 角色扮演 | N3 生成叙事/AI GM | Released | 内置 AI 主持人的 RPG：按你的行动生成文字、角色/地点/物品的图，还有本地语音旁白。 |
| 35 | [The Last Reunion](https://store.steampowered.com/app/3600510/The_Last_Reunion/) | 2025 | G1 叙事冒险 | N1 信息获取 | Released | 调查谋杀现场，审问几个性格各异的 AI NPC，影响推理和结局。 |
| 36 | [The Occult Detective](https://store.steampowered.com/app/3184990/The_Occult_Detective/) | 2025 | G1 叙事冒险 | N1 信息获取 | Released | 神秘学探案：可以自由对话，AI 实时生成符合世界设定的回应，边查边推进剧情。 |
| 37 | [Whispers From the Star 星之低语](https://store.steampowered.com/app/3730100/Whispers_from_the_Star/) | 2025 | G1 叙事冒险 | N3 生成叙事/AI GM | Released | 用语音和困在外星的 AI 宇航员实时聊天，你的话影响她能不能活下去和剧情走向。 |
| 38 | [猜盐 (xiaoce.fun)](https://xiaoce.fun/) | 2025 | G3 解谜 | N1 信息获取 | Released | AI 网页小游戏集锦(每日 0 点更新、打卡闯关),含数十个模块。代表性 AI 玩法是“猜病”:AI 扮演病人说症状,你当医生靠问诊推理它得了什么病(反向问诊);“猜词”按语义关联度百分比逼近隐藏词。其余多数模块(猜国/旗/城、诗词、猜歌、估算等)是传统知识问答、不依赖生成式 AI。【按集锦的 AI 旗舰玩法“猜病”归 N1(审问 AI 获取隐藏信息);因是集锦且部分模块非 AI,资格/归类待你确认。】 |
| 39 | [AI Society](https://store.steampowered.com/app/4468180/AI_Society/) | 2026 | G5 模拟 | N5 多Agent模拟 | Released | 本地 AI 小社会模拟：每个居民有性格爱好，会自己上班、吵架、交朋友、行动，你在旁边看社会运转。 |
| 40 | [Artificial: Proxy Bar](https://store.steampowered.com/app/4404980/Artificial_Proxy_Bar/) | 2026 | G1 叙事冒险 | N1 信息获取 | Announced/TBA | 在酒吧里向嫌疑人随便提问，AI 动态作答，查出背后的谜团。 |
| 41 | [Chrongrid](https://store.steampowered.com/app/4685310/Chrongrid/) | 2026 | G1 叙事冒险 | N3 生成叙事/AI GM | Announced/TBA | 在作者给好的故事蓝图里自由选择行动，世界会动态回应你。 |
| 42 | [Dev_Null’s Tower](https://store.steampowered.com/app/4350940/Dev_Nulls_Tower/) | 2026 | G9 混合/实验性 | N4 语义机制 | Early Access | 动作爬塔+斗智：关卡故意全是 bug，你给 AI“开发者”写 bug 报告求修，它永远故意曲解（说平台太远，就移近但插满尖刺）。核心是琢磨怎么措辞，让它的恶意改动反而帮到你。 |
| 43 | [Hostage Down](https://store.steampowered.com/app/4596790/Hostage_Down/) | 2026 | G1 叙事冒险 | N2 社交操纵 | Released | 人质谈判：拿起麦克风和劫匪谈，用你的话术左右危机怎么收场。 |
| 44 | [OMEA](https://store.steampowered.com/app/4275550/OMEA/) | 2026 | G1 叙事冒险 | N3 生成叙事/AI GM | Announced/TBA | 没有菜单限制，你想做什么就打什么，AI 当主持人生成整段冒险。 |
| 45 | [One Way Mirror: AI](https://store.steampowered.com/app/4364560/One_Way_Mirror_AI/) | 2026 | G1 叙事冒险 | N1 信息获取 | Early Access | 每局案件都由 AI 现生成，你和嫌疑人实时对话审问，破程序化生成的案子。 |
| 46 | [Prison Queen](https://store.steampowered.com/app/4667950/Prison_Queen_Demo/) | 2026 | G9 混合/实验性 | N4 语义机制 | Demo/Playtest | “用造句打架”的另类战斗：你写出的句子由 AI 评判语法和是否切题，分数直接变成战斗伤害。 |
| 47 | [Reversal Detective / 逆転探偵](https://store.steampowered.com/app/3750520/_/) | 2026 | G1 叙事冒险 | N1 信息获取 | Released | 用自由打字审问 AI 村民，每局凶手、被害者、证词都随机，靠问话找证据指认凶手。 |
| 48 | [RolemIAster](https://store.steampowered.com/app/4210600/RolemIAster/) | 2026 | G2 角色扮演 | N3 生成叙事/AI GM | Early Access | 本地 AI 当主持人实时造世界、人物、任务和物品，解释你的行动并讲出后果，相当于取代真人跑团 DM。 |
| 49 | [Saga & Seeker](https://store.steampowered.com/app/3522640/Saga__Seeker/) | 2026 | G1 叙事冒险 | N3 生成叙事/AI GM | Released | AI 根据你的输入生成文字冒险，你用大白话推动剧情。 |
| 50 | [Simulation Simulator](https://store.steampowered.com/app/4594070/Simulation_Simulator/) | 2026 | G1 叙事冒险 | N2 社交操纵 | Demo/Playtest | 你试图用各种论证说服 AI 角色“我们其实活在模拟里”，它会反驳或动摇。 |
| 51 | [Story Engine: No Script](https://store.steampowered.com/app/4763330/_/) | 2026 | G1 叙事冒险 | N3 生成叙事/AI GM | Announced/TBA | 无脚本 AI 叙事引擎：实时生成剧情、状态、背包、关系和任务，完全跟着你走。 |
| 52 | [Turing Testimony 图灵证言](https://store.steampowered.com/app/4285970/_Turing_Testimony/) | 2026 | G1 叙事冒险 | N1 信息获取 | Announced/TBA | 证词叙事：NPC 有自己的性格和记忆，主线由 AI 角色推动，你靠对话挖真相。 |
| 53 | [Unreachable](https://store.steampowered.com/app/4541960/Unreachable) | 2026 | G1 叙事冒险 | N2 社交操纵 | Announced/TBA | 心理博弈对话：你想办法攻破 AI 角色的心理防线，它的动态回应每次都不一样。 |
| 54 | [ZeroOne Terminal](https://store.steampowered.com/app/4249890/ZeroOne_Terminal/) | 2026 | G5 模拟 | N1 信息获取 | Released | 创投模拟：你自由采访 AI 生成的创业者，盘问项目和本人，判断靠不靠谱再决定投不投。 |
| 55 | [ZeroPrompt](https://store.steampowered.com/app/4306040/ZeroPrompt/) | 2026 | G1 叙事冒险 | N1 信息获取 | Demo/Playtest | 审问会思考、撒谎、还会贿赂你的 AI 角色，靠对话拆穿他们推进案件。 |
| 56 | [历史模拟器：崇祯](https://store.steampowered.com/app/4304230/) | 2026 | G4 策略/经营/管理 | N5 多Agent模拟 | Released | 你当崇祯皇帝，用大白话下圣旨治国：管财政、军事、党争、天灾，和 AI 扮演的满朝文武周旋，试着救回大明。 |
| 57 | [遥远行星：建造师](https://store.steampowered.com/app/3105960/) | 2026 | G2 角色扮演 | N5 多Agent模拟 | Early Access | 太空跑商 RPG：150 多个星球、600 多个 NPC，从小商人做起开店、组商会、结盟，有贸易系统和剧情/自由模式。 |
| 58 | [AI Schoolgirls Murder Mystery](https://store.steampowered.com/app/3082970/AI_Schoolgirls_Murder_Mystery/) | TBA | G1 叙事冒险 | N1 信息获取 | Announced/TBA | 你当新生审问三名 AI 嫌疑人，它们的动态回答帮你推进谋杀案调查。 |
| 59 | [Black Box: Infinite Arsenal](https://store.steampowered.com/app/4437020/Black_Box_Infinite_Arsenal/) | TBA | G2 角色扮演 | N4 语义机制 | Announced/TBA | 幸存者类肉鸽：你拼装战斗组件，AI 实时把它们重组成各种武器和弹幕效果。 |
| 60 | [CLUAIDO 线索智能](https://store.steampowered.com/app/2919500/CLUAIDO/) | TBA | G1 叙事冒险 | N1 信息获取 | Demo/Playtest | 侦探角色扮演：NPC 的回答由 AI 根据你打的字实时生成，你靠问话拿线索、解谜。 |
| 61 | [Every Legend](https://store.steampowered.com/app/4660010/Every_Legend/) | TBA | G1 叙事冒险 | N3 生成叙事/AI GM | Announced/TBA | 你创建英雄、打字行动，AI 给你生成每一段冒险、分支故事和行动结果。 |
| 62 | [Live Through Time](https://store.steampowered.com/app/4443950/Live_Through_Time/) | TBA | G1 叙事冒险 | N3 生成叙事/AI GM | Announced/TBA | 穿越各个历史时代，用大白话和 AI 一起即兴编出没有剧本的冒险。 |
| 63 | [Love and Lie](https://store.steampowered.com/app/3886140/Love_and_Lie/) | TBA | G8 关系/陪伴 | N2 社交操纵 | Announced/TBA | 用语言同时维持好几段关系和谎言，AI 角色会记仇、起疑、吃醋并据此反应。 |
| 64 | [Microverse In Box 盒中小世界](https://store.steampowered.com/app/3902630/Microverse_In_Box/) | TBA | G5 模拟 | N5 多Agent模拟 | Announced/TBA | 上帝视角社会沙盒：你用卡片设定居民的性格、财富、关系和社会规则，NPC 的想法和行动由 AI 驱动，看剧情自己长出来。 |
| 65 | [Murder In Complex](https://store.steampowered.com/app/3502320/Murder_In_Complex/) | TBA | G1 叙事冒险 | N1 信息获取 | Announced/TBA | 每轮随机的小区谋杀案：审问 AI 住户、搜集证据破案。 |
| 66 | [Myth-OS](https://store.steampowered.com/app/4513270/MythOS/) | TBA | G9 混合/实验性 | N3 生成叙事/AI GM | Demo/Playtest | “万能 GM”沙盒:底层一套硬编码引擎在后台算地图、经济(供需定价)、势力外交、人口。你想玩啥都行——单人地牢探险、十字军之王式大战略、三国策略、D&D 跑团、4X 等。AI 只当两件事:GM(读你的开放行动→对照硬编码规则和你的自定义规则→更新世界→电影感叙述)和美术。 |
| 67 | [Neon Echo](https://store.steampowered.com/app/3583750/Neon_Echo/) | TBA | G5 模拟 | N5 多Agent模拟 | Announced/TBA | 观察者模拟：你监视一群会成长的、有自我意识的 AI 角色，看他们的日常和关系怎么演变。 |
| 68 | [Psynostic](https://store.steampowered.com/app/3380580/Psynostic/) | TBA | G1 叙事冒险 | N1 信息获取 | Announced/TBA | 心理科问诊：本地 AI 扮演病人，你通过对话一步步诊断出他的精神问题。 |
| 69 | [Speak. Cast. Rule.](https://store.steampowered.com/app/3858330/Speak_Cast_Rule/) | TBA | G2 角色扮演 | N2 社交操纵 | Announced/TBA | 逃亡法师求生：在一个“施法即犯罪”的世界里活下去。核心不是打架，而是靠自由对话去说服、欺骗、贿赂、甚至抹除 NPC 记忆来解决麻烦、躲避审判庭。所有 NPC 由 AI 驱动，各有记忆、动机和自己的生活，会按你的声望区别对待你。 |
| 70 | [Story Crafter](https://store.steampowered.com/app/3029600/Story_Crafter/) | TBA | G2 角色扮演 | N3 生成叙事/AI GM | Announced/TBA | 在线 RPG：简化的桌游规则配上 AI 主持人，生成角色、动态剧情和冒险，可单可多人。 |
| 71 | [SYNTHASIA](https://store.steampowered.com/app/710810/SYNTHASIA/) | TBA | G2 角色扮演 | N3 生成叙事/AI GM | Announced/TBA | AI 主持人不只是讲故事，还在真正的游戏引擎里替你做决策、执行结果的 RPG。 |

<a id="augmented"></a>
### 🔵 AI Augmented (13)

| # | Game / 游戏 | Year | Type (G) | AI mechanic (N) | Status | Gameplay / 玩法简介 |
|--:|------|:--:|------|------|------|------|
| 1 | [AlibAi](https://store.steampowered.com/app/3325660/AlibAi/) | 2024 | G7 社交推理/派对 | — | Early Access | 反向狼人杀：你才是凶手，要在一群会互相讨论、起疑的 AI NPC 中藏住身份、把嫌疑甩给别人。 |
| 2 | [Prompt-Gaming / En-join Energy Community Game](https://dl.acm.org/doi/10.1145/3613905.3650774) | 2024 | G4 策略/经营/管理 | — | Research prototype | 能源社区主题的文字教育游戏(整个游戏其实就是一段自然语言 prompt 跑在 ChatGPT 里)。你针对开放式挑战打字作答,LLM 当“评分官”判断你的答案好不好(实测与专家评估约 81% 一致),据此带你过关、推进剧情、学到能源社区知识。【判为 Augmented:游戏性弱;AI 只给答案评分/学习反馈、不在核心玩法机制,且评判可由老师或标准答案替代。】 |
| 3 | [World_Diplomat](https://store.steampowered.com/app/3337540/World_Diplomat_Demo/) | 2024 | G4 策略/经营/管理 | — | Demo/Playtest | 回合制经营策略：你当外交官，升级技能树、管理金钱和影响力、接任务、走向不同结局；AI 只负责生成会议和任务文字。 |
| 4 | [EcoEcho](https://github.com/Carolzhangzz/Eco_Echo) | 2025 | G1 叙事冒险 | — | Research prototype | 环保教育剧情：跟着预设故事走，一路和 AI 角色对话，最后发现你的选择造成了环境灾难——从“反派”视角体会破坏后果。 |
| 5 | [Malinowski's Lens](https://arxiv.org/abs/2511.07682) | 2025 | G9 混合/实验性 | — | Research prototype | 把一本人类学著作变成的学习游戏：你以研究者身份探索书里的文化场景，AI 把文字资料转成情境和配图（教育实验作品）。 |
| 6 | [青椒模拟器](https://tenure-track-chili.vercel.app/) | 2026 | G4 策略/经营/管理 | — | Released | 高校青年教师经营模拟：一学年一回合，招学生、申项目、发论文、处理杂事，每个决定影响你能否从讲师评到院士；六年考核没过就走人。AI 只负责生成随机事件和文字。 |
| 7 | [麦琪的花园](https://store.steampowered.com/app/2990190/) | 2026 | G6 沙盒/创造 | — | Early Access | 沙盒经营冒险:你是退休冒险家,在“奥兹大陆”扎营——砍树、采集、种田、做装备、探索战斗。可自定义 AI 同伴(描述外形/性格/说话风格/背景→AI 实时生成其对话、表情与剧情),同伴能当队友、营地工人,还会生成专属任务/奖励;镇上 NPC 各有生活。【判为 Augmented(待复核):核心是传统沙盒经营/种田/探索循环,AI 主要增强同伴对话与剧情层;若你认为“可自定义 AI 同伴生成剧情/任务”是核心,则改 Native + N3。】 |
| 8 | [Danse Macabre AI Text RPG](https://store.steampowered.com/app/2376080/Danse_Macabre_AI_Text_RPG/) | TBA | G2 角色扮演 | — | Announced/TBA | 文字 RPG：每个角色有自己的 AI 人格，游戏里的对话都由 AI 生成。 |
| 9 | [In Waiting](https://store.steampowered.com/app/2772070/In_Waiting/) | TBA | G1 叙事冒险 | — | Announced/TBA | 恐怖解谜探索：在庄园里探索解谜，同时和本地 AI 幽灵 Eleanor 真实对话求助。 |
| 10 | [Mentiss Werewolf: Human vs AI](https://store.steampowered.com/app/4586780/Mentiss_Werewolf_Human_vs_AI/) | TBA | G7 社交推理/派对 | — | Announced/TBA | 狼人杀：你和 Claude、GPT、Gemini 等 AI 玩家同桌发言、推理、投票，真人对 AI。 |
| 11 | [Nyric](https://store.steampowered.com/app/3368390/Nyric/) | TBA | G6 沙盒/创造 | — | Announced/TBA | 第三人称生存建造:你打一句话(如“被风暴诅咒的荒原”)→ AI 把它解析成世界参数、从预制素材库拼出一个生存世界。进去后是传统生存玩法:扛极端天气、探索地形、建基地防灾、找传送门。每个世界有 AI 伙伴 Faebot,会按你怎么对它产生情绪、惹毛了可能反水。【判为 Augmented 的原因:AI 仅把提示词“匹配/拼装”到一个有限的预加载素材库(不生成任何 3D/贴图/音频、非无限生成全新世界),且核心生存循环不依赖 AI——去掉 AI 换成预设世界菜单,游戏照样成立。】 |
| 12 | [Space Conquest AI - AIGM](https://store.steampowered.com/app/3803130/Space_Conquest_AI__AIGM/) | TBA | G4 策略/经营/管理 | — | Announced/TBA | 太空策略游戏的 AI 主持人扩展包：在本体策略玩法上额外由 AI 生成剧情和判定（本体不用 AI 也能玩）。 |
| 13 | [昭阳传](https://store.steampowered.com/app/3705720/_/) | TBA | G2 角色扮演 | — | Demo/Playtest | 古风 RPG：NPC 的事件和每次对话内容都由 AI 当场生成，角色还有实时合成的语音。 |

<a id="boundary"></a>
### 🟠 AI Boundary (10)

| # | Game / 游戏 | Year | Type (G) | AI mechanic (N) | Status | Gameplay / 玩法简介 |
|--:|------|:--:|------|------|------|------|
| 1 | [AI Dungeon](https://aidungeon.com/) | 2019 | G1 叙事冒险 | N3 生成叙事/AI GM | Released | 纯文字冒险：你想干什么就打字写出来，AI 立刻接着往下编故事、生成世界和人物的反应；没有剧本也没有结局，可以一直玩下去。 |
| 2 | [AIdventure](https://store.steampowered.com/app/2114790/AIdventure/) | 2022 | G1 叙事冒险 | N3 生成叙事/AI GM | Released | 和 AI Dungeon 几乎一样的文字冒险：你写一句行动，AI 接着讲后续剧情；区别是它在你自己电脑上跑，一次买断不用按月订阅。 |
| 3 | [Project Electric Sheep](https://store.epicgames.com/en-US/p/project-electric-sheep) | 2022 | G9 混合/实验性 | N6 生成物即玩法 | Delisted | 一个“做梦模拟器”：你告诉它想梦到什么，AI 就生成一个能走进去逛的 3D 梦境、跟里面的人物聊天。更像可探索的体验而非有目标的游戏（已下架）。 |
| 4 | [Closer Worlds](https://www.ccc.mit.edu/project/closer-worlds/) | 2023 | G9 混合/实验性 | N3 生成叙事/AI GM | Research prototype | 两个人一起“造世界”：你分享一段自己的故事，AI 据此抛出反思性问题，引导你俩共同把一个世界编出来。本质是叙事实验，不是游戏。 |
| 5 | [Unbounded: A Generative Infinite Game](https://generative-infinite-game.github.io/) | 2024 | G5 模拟 | N3 生成叙事/AI GM | Research prototype | 生成式“无限游戏”研究原型(论文,致敬 Carse 的有限/无限游戏)。本质像一只 AI 生成的电子宠物:你喂养、陪玩、引导一个自主虚拟角色,而游戏的机制、叙事、角色互动全部由一个 LLM 实时动态生成(配图像模型出画面),没有写死的规则,可无限玩下去——也因此没有目标闭环(Boundary)。单角色生活模拟,非多 Agent 社会。 |
| 6 | [CAI UWE](https://store.steampowered.com/app/4426310/CAI_UWE/) | 2026 | G8 关系/陪伴 | — | Released | 实验性 AI 陪伴/生活模拟，重点是陪你聊天和开放对话。 |
| 7 | [Project N.E.K.O.](https://store.steampowered.com/app/4099310/Project_NEKO/) | 2026 | G8 关系/陪伴 | — | Early Access | AI 伴侣/元宇宙体验：主打跨场景记住你的 AI 同伴，游戏目标较弱，更偏陪伴。 |
| 8 | [GAL-Chat](https://store.steampowered.com/app/4736920/GALChat/) | TBA | G8 关系/陪伴 | — | Announced/TBA | AI 聊天恋爱视觉小说：没有固定对白，你能用文字或语音和角色实时自由聊天。 |
| 9 | [Megan AI](https://store.steampowered.com/app/3848530/Megan_AI/) | TBA | G8 关系/陪伴 | — | Early Access | AI 陪伴体验：本地 AI 实时生成角色对白，还带语音，偏对话陪伴。 |
| 10 | [Never Ending Dungeon](https://store.steampowered.com/app/4124130/Never_Ending_Dungeon/) | TBA | G6 沙盒/创造 | N3 生成叙事/AI GM | Announced/TBA | AI 桌游/地牢生成器：帮你（或主持人）现生成冒险、地图、NPC、敌人、陷阱和房间，更像生成工具。 |

<a id="columns"></a>
## 🧭 Column guide
- **Game** — title, linked to its store / project / paper page.
- **Year** — release year; `TBA` = announced but undated.
- **Type (G)** / **AI mechanic (N)** — the two taxonomy axes above.
- **Status** — Released · Early Access · Announced/TBA · Demo/Playtest · Research prototype · Delisted.
- **Gameplay** — one-line plain-language description of how it plays.

<a id="method"></a>
## 🔬 Methodology
1. **Screen** for runtime generative AI (not dev-time-only assistance).
2. **Eligibility** via two tests — *is the AI the core mechanic?* (Native vs Augmented) and *is it a strict game with rules/goals?* (Native vs Boundary). A title is **Augmented** if a limited number of humans or fixed presets could replace the AI.
3. **Classify** independently on axes G and N (single primary value each).
4. **Verify** release status and titles against official store / project pages.

<a id="files"></a>
## 🗃️ Repository files
- `README.md` — this catalog.
- `AI_Native_Games_筛选结果.xlsx` — full spreadsheet (judgement columns, evidence, sources, original notes).

<a id="contributing"></a>
## 🤝 Contributing
Found a missing game, a wrong status, or a mis-classification? Open an **issue** or a **pull request** with: title, link, release year, a one-line gameplay description, and (if you can) your suggested G / N / tier with a one-sentence reason.

<a id="cite"></a>
## 📑 Citation
```bibtex
@misc{ai_native_games_corpus,
  title  = {AI-Native Games Corpus},
  year   = {2026},
  note   = {A hand-verified catalog of AI-native games with a game-type x AI-mechanic taxonomy},
  howpublished = {GitHub repository}
}
```

<a id="license"></a>
## ⚖️ License
Data and text released under **CC BY 4.0** — reuse with attribution. Game names, links, and media belong to their respective owners.

<sub>[↑ back to top](#top)</sub>
