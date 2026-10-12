# 导演

> 想拍出电影感但不会导？这个库收集 X 上实战验证过的导演级视频 prompt skills，每条都写清楚能帮你解决什么、怎么用它搞钱。
>
> A curated collection of directing prompts & skills for viral short videos, gathered from practitioners sharing on X.
> 
> Each entry answers two questions: what problem it solves (and who it's for), and how to make money with it.
> 
> Star counts verified via GitHub API on 2026-10-12. Continuously updated.

## 条目

### beshuaxian/higgsfield-seedance2-jineng

**核心提炼**
- 解决什么问题：有想法但不会"导"——AI 视频缺电影感、缺钩子。15 个 Claude 技能把 Claude 变成各风格的提示词工程师，每个技能自带 2 秒钩子框架、摄像机运动百科、5+ 条制作级示例提示词。
- 核心用法（4 步）：1) 选风格：电影 / 3D CGI / 动漫 / 电商广告 / 音乐视频等 15 个；2) 安装：把对应 SKILL.md 复制到 Claude 技能目录；3) 描述：用中文或英文描述想要的视频；4) 输出：Claude 生成 15–25 行制作级提示词（含时间线、镜头、灯光、声音、2 秒钩子），粘贴到 Higgsfield 的 Seedance 2.0 生成（4–15 秒、720p、带声音）。
- 什么时候用 / 常见坑：用 Seedance 2.0 / Higgsfield 出片时用。注意单条上限 15 秒、720p，长片要分段做。素材引用用 `@image1` `@video1` `@audio1`，输入文件合计不超过 12 个。

**适用场景**：想接 AI 短片 / 广告单、但缺导演经验的人。

**怎么用它搞钱**：AI 短片导演接单——电商广告、品牌故事类短视频按条收费，"电影感 + 钩子"是报价的底气。

**来源**：[beshuaxian/higgsfield-seedance2-jineng](https://github.com/beshuaxian/higgsfield-seedance2-jineng) · ⭐961 · 更新于 2026-04-09

### jnMetaCode/ai-shortfilm-prompts

**核心提炼**
- 解决什么问题：普通人写的提示词全是"电影感、高级感"这种空话，生成出来像游戏 CG。它的方法论来自被好莱坞导演点赞的 AI 短片《Zombie Scavenger》：用真实机位 + 镜头语言（模拟 IMAX 机身、Panavision 镜头、呼吸感手持）把 AI 锚定到真实电影美学。
- 核心用法（4 步）：1) 输入：任意想法或一句话剧情；2) 选路径：免安装的网页 prompt builder（21 种类型选填空）或 Claude Code skill；3) 输出：完整多镜头提示词 + negative prompt（5 阶段结构：主题 / 氛围 / 机位 / 时间线 / 结尾）；4) 生成：粘贴到 Sora / Kling / Veo / Seedance 出片。
- 什么时候用 / 常见坑：想拍"不像 AI 拍的"短片时用。README 里那句单行魔法提示词（Anamorphic widescreen + breath-like float）今晚就能试；翻车了对照 cases.md 的 failure→fix 图鉴修。

**适用场景**：想做电影质感 AI 短片 / 广告片的创作者。

**怎么用它搞钱**：广告片 / 宣传片定制——品牌方要"电影感"短视频时，这套"真实机位语言"方法论就是差异化报价的理由。

**来源**：[jnMetaCode/ai-shortfilm-prompts](https://github.com/jnMetaCode/ai-shortfilm-prompts) · ⭐462 · 更新于 2026-10-12

### Rylaispirit/cinematic-video-prompt-skill

**核心提炼**
- 解决什么问题：提示词里写 "a nice cinematic scene" 这种空话，模型只能瞎猜。它是一份 700+ 电影术语词典（机位 70+、运镜 60+、灯光 80+、构图 80+……），教你把模糊描述换成精确指令。
- 核心用法（4 步）：1) 安装：`git clone` 到 `~/.claude/skills/cinematic-video-prompt`，或把 SKILL.md 粘给任何 AI 当 system prompt；2) 套公式：[景别+角度]、[主体]、[动作]、[场景]、[灯光]、[运镜]、[风格+色彩]、[情绪]、[技术参数]；3) 查词典：运镜 / 灯光 / 构图按"什么时候用"选词，不整库照抄；4) 输出：一条各模型通用的精确提示词，粘贴到 Veo 3 / Kling / Sora / Runway 生成。
- 什么时候用 / 常见坑：任何模型出片前想提升"电影感"时用。内置规则：一条片子只用一种运镜、一个主动作，灯光要和天气时间对上。bonus 附带东方仙侠场景 skill 和角色一致性 skill。

**适用场景**：各模型通吃、不想被单一平台绑定的 AI 视频创作者。

**怎么用它搞钱**：AI 视频提示词代写 / 教学——700+ 术语词典是现成的课程素材；给电商、品牌做产品短视频时，"精确运镜 + 灯光"就是比同行贵的理由。

**来源**：[Rylaispirit/cinematic-video-prompt-skill](https://github.com/Rylaispirit/cinematic-video-prompt-skill) · ⭐149 · 更新于 2026-09-27

### CyberJ0605/cinematic-video-prompt-engineer-skill

**核心提炼**
- 解决什么问题：有剧情但不会分镜。它先诊断剧情里真正"看得见"的事件、冲突和情绪转折，再分配时长、镜头、表演、声音，最后输出可直接生成的提示词——不是形容词堆砌。
- 核心用法（5 步）：1) 安装 skill；2) 输入剧情 / 小说片段 / 一句场景想法，说"请用 $cinematic-video-prompt-engineer 处理这个剧情"；3) 诊断：skill 输出剧情诊断 + 电影化策略（6–30 秒自适应时长）；4) 选路径：直接视频路径（单人单场景）或参考图优先路径（古装 / 多人 / 产品：先出角色场景参考图，再编译视频提示词）；5) 迭代：生成翻车只改失败变量，不推倒重来。
- 什么时候用 / 常见坑：剧情类短片、反转叙事、多人打戏、一镜到底时用。46 种运镜模块按剧情功能选；选竖屏 9:16 时会重新构图，不是简单裁横屏。

**适用场景**：做剧情号、AI 微短剧、产品故事片的人。

**怎么用它搞钱**：AI 剧情短片 / 微短剧代制——"参考图优先"路径能保人物一致性，这是连载类订单的关键卖点，按集收费。

**来源**：[CyberJ0605/cinematic-video-prompt-engineer-skill](https://github.com/CyberJ0605/cinematic-video-prompt-engineer-skill) · ⭐128 · 更新于 2026-10-11

## 收录标准

- 来源：X 博主实战分享（原帖 / 评论区 / 引用链）及 GitHub 高星项目
- 每条格式：核心提炼（解决什么问题 / 核心用法 / 什么时候用与常见坑）+ 适用场景 + 一条「怎么用它搞钱」+ 来源（链接只作来源，star 数与更新时间以 GitHub API 为准）
- 用户视角写作：不写满，禁用"全网最全／唯一／第一／没人做"等断言；没读到的不写
- 去重：同一项目只收录一次，不堆 raw 链接

## 相关分类

- 总索引：[x-viral-video-skills](https://github.com/kkone1238899/x-viral-video-skills) —— 13 个分类导航
- [x-viral-video-scripts](https://github.com/kkone1238899/x-viral-video-scripts) —— 编剧 / 脚本
- [x-viral-video-hooks](https://github.com/kkone1238899/x-viral-video-hooks) —— 标题 / 5 秒钩子
- [x-viral-video-creative-direction](https://github.com/kkone1238899/x-viral-video-creative-direction) —— 创意总监
- [x-viral-video-replication](https://github.com/kkone1238899/x-viral-video-replication) —— 复制爆款
- [x-viral-video-breakdown](https://github.com/kkone1238899/x-viral-video-breakdown) —— 拉片
- [x-viral-video-pipeline](https://github.com/kkone1238899/x-viral-video-pipeline) —— 流水线 / 生产管线
- [x-viral-video-de-ai](https://github.com/kkone1238899/x-viral-video-de-ai) —— 去 AI 味
- [x-viral-video-characters](https://github.com/kkone1238899/x-viral-video-characters) —— 人物构建
- [x-viral-video-editing](https://github.com/kkone1238899/x-viral-video-editing) —— 视听剪辑技巧
- [x-viral-video-prompt-opt](https://github.com/kkone1238899/x-viral-video-prompt-opt) —— 提示词优化
- [x-viral-video-copywriting](https://github.com/kkone1238899/x-viral-video-copywriting) —— 文案
- [x-viral-video-showcase](https://github.com/kkone1238899/x-viral-video-showcase) —— X 病毒视频合集

## 投稿

发现好的导演 prompt / skill，欢迎提 Issue 或 PR（格式见 CONTRIBUTING.md）。

## 更新日志

- 2026-10-12：条目升级为小节格式（核心提炼 / 适用场景 / 怎么用它搞钱 / 来源）；新增 2 个项目（Rylaispirit/cinematic-video-prompt-skill、CyberJ0605/cinematic-video-prompt-engineer-skill）
- 2026-10-11：首版，2 个项目，持续收录中
