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

### @TraceJie《AI 视频"情绪套利"操盘 SOP：7 天 2500 万播放》

**核心提炼**
- 解决什么问题：情绪短剧账号起号难——不造新故事，做"情绪套利"：把成熟霸总/狗血剧模板翻拍成"亲情+反派+逆袭"情绪短片，核心论点是"爆款=旧情绪刺激的组合创新"。
- 核心用法（7 步）：1) 只找 7 天内爆火的对标视频，用 Gemini/ChatGPT-4o 做像素级逆向拆解；2) 用 ChatGPT/Claude 先钉死人物关系与情节曲线；3) 参考总表：Midjourney/Niji 固定 Seed，--cref --sref 保人物一致性；4) 分镜：Seedance 2.0 单条≤15 秒，用"视听导演"式分镜 Prompt 指导；5) 锁死首帧图：Midjourney V6/Niji 6、--ar 16:9、--cref --cw 100，加光影指令；6) 图生视频运动幅度 30%–50%（情绪短剧要克制）；7) 工业化 QC：近 200 条素材，SSR 标准=脸部稳定、运镜平滑、动作逻辑、情绪准确。
- 什么时候用 / 常见坑：做情绪短剧/矩阵账号批量起号时用。情绪爆发和动作段要留 3–5 秒无台词空间，别把台词塞满。

**适用场景**：想系统做 AI 情绪短剧账号、复制爆款模板批量起号的创作者。

**怎么用它搞钱**：跑通后做短剧矩阵账号接商单/卖课程，或把 SOP 打包成智能体卖给企业。

**来源**：[@TraceJie](https://x.com/TraceJie/status/2110175256111694001)（2026-10-14）

### @qinghaiwu9527《MiniMax H3 提示词保姆级教程》

**核心提炼**
- 解决什么问题：MiniMax H3 出片人物漂移、镜头混乱、声音失控——"5 步解决"，附万能生成模板。
- 核心用法：先选任务模式再写提示词；把提示词拆成三个"剧组部门"——画面与表演（风格/景别/构图/人物身份/动作/运镜/对白/镜头切换）、环境音（风声雨声/脚步呼吸/底噪等非语言人声）、背景配乐（写清乐器+情绪+变化）。
- 每个镜头写清六件事：景别/构图/动作/运镜/光影/对白；人物一致性用约束写法；同一角色跨镜头用稳定说话人编号（S1），首次交代年龄/性别/音高/音色/语速。
- 什么时候用 / 常见坑：用 MiniMax H3 做短片时用；附实战案例"雨夜客栈女主登场"完整提示词和六个高频翻车点。

**适用场景**：用 MiniMax H3 做 AI 短片、总被人物漂移/镜头混乱困扰的创作者。

**怎么用它搞钱**：接 MiniMax/H3 风格短片代制单，或做成付费教程/提示词库售卖。

**来源**：[@qinghaiwu9527](https://x.com/qinghaiwu9527/status/2110014506713874760)（2026-10-13）

### @dog_not_ai《纯 AI 土味综艺：月入 50 万+ 拆解》

**核心提炼**
- 解决什么问题：AI 内容没人设没 IP、做不大——老徐的四层技术逻辑：1) 三句话定位（节目名/slogan/第一句）；2) 世界观设定（虚构小地方+本地梗土话老照片口音）；3) 人物设定（主持人+3–5 固定嘉宾，不同年龄层/口音/性格，固定长相）；4) 情节设定（反差冲突+剧情反转）；文化复兴+AI 结合是关键（旧录像带/方言/老照片/街拍）。
- 变现五条路：广告植入（酒桌/麻将镜头植酒品牌、本地小店上桌）、带货（山货土特产"县长同款"）、文旅（政府/景区邀约、地方 IP 综艺）、开课收徒（线上"AI 综艺实操课"+线下小班）、加盟制（城市合伙人卖 SOP）。
- 什么时候用 / 常见坑：想做系列化 AI 内容 IP 而不是单条爆款时用；先把世界观钉死，再做单集。

**适用场景**：想做 AI 虚拟综艺/IP 系列内容、把地方文化元素做成连续节目的团队。

**怎么用它搞钱**：按这套世界观+人物设定方法论起 AI 综艺号，变现路径照抄（广告植入/文旅邀约/卖课/加盟）。

**来源**：[@dog_not_ai](https://x.com/dog_not_ai/status/2110258128814215347)（2026-10-14）

### @Soranlan《古风仙侠硬派动作电影》导演级 prompt

**核心提炼**
- 解决什么问题：AI 动作戏软绵绵像舞蹈、空间看不懂——七拍动作戏结构公式：铺垫→压迫→第一次破解→敌人适应→真实死局→第二层反制→骤然收尾（按 30 秒完整动作戏设计，不做 15 秒拉长）。
- 导演逻辑：空间始终看得懂、动作爆发极快、爆发之间保留判断停顿、镜头变化必须承担叙事功能；动作六阶段：启动/加速/撞击/失衡/恢复/急停。
- 资产锁定：主角、核心武器、本轮环境 DNA 强锁定，配角只做功能连续；"活背景原则"：环境自然运动但叙事中立，背景绝不能帮任何一方。
- 三层协同围杀：前排藤牌腰刀手（撞线/压缩空间/遮挡视野）、中排长枪手（抓空隙杀招）、远层弓手（只在关键时刻放箭造时间压力）。
- 13 个镜头每个标注"导演功能"（如 24mm 大全景建战场几何、兵器遮挡天然换轴、85mm 极近特写骤停收尾）；剪辑节奏：0–4 秒克制慢→4–14 秒加速→14–18 秒最密集→18–20 秒主动降低切镜让死局成立→20–29 秒再加速→最后 1 秒完全静止；声音：配乐不能盖住武器/脚步/呼吸，最后一击后所有大声音撤掉只留呼吸。
- 什么时候用 / 常见坑：Seedance 2.5 做古风/武侠/动作类短片时直接套用。

**适用场景**：用 Seedance 2.5 做古风/武侠/动作类 AI 短片、想直接套完整 prompt 框架的创作者。

**怎么用它搞钱**：接武侠/仙侠风 AI 短片定制单，或把这套 prompt 做成付费模板包/课程。

**来源**：[@Soranlan](https://x.com/Soranlan/status/2110222256018493828)（2026-10-14）

### @wangfenganc《Next Scene LoRA（V2）》推荐

**核心提炼**
- 解决什么问题：多镜头短片人物/光线/构图不一致——"像导演一样思考"的图生分镜 LoRA：输入当前画面，生成连贯的"下一个镜头"，可链式做完整分镜序列。
- 核心用法：基础模型 Qwen-Image-Edit-2509，LoRA 强度 0.7–0.8，提示词开头固定为"下一个场景："。
- 什么时候用 / 常见坑：用本地/开源方案做 AI 短片分镜、被一致性问题卡住时用；HF 有公开权重。

**适用场景**：做 AI 短片分镜、想用开源方案解决人物/场景一致性的人。

**怎么用它搞钱**：把这套工具链整合进 AI 短片代制工作流降本提效，或做教程带货。

**来源**：[@wangfenganc](https://x.com/wangfenganc/status/2110263474282709170)（2026-10-14）

### @TraceJie《AI 短剧出海 TK：4000 万播放工作流内幕》

**核心提炼**
- 解决什么问题：AI 短剧出海不知道赚什么、成本多少——商业本质：TK 漫剧（Drama Center）核心收益来自平台播放量分成和独家买断补贴（B 级万播 3–5 美金、A 级 6–10、S 级 15–30、S+ 级 40+ 美金）。
- 选题：海外用户吃"社交死亡+超自然觉醒/复仇逆袭"（霸凌、复仇、吸血鬼狼人），不要低水平直接翻译国内短剧。
- 入场：首选 TK Drama Center（流量深、无缝同步 YouTube 赚第二份）、干净住宅 IP、跨境收款。
- 成本核算：Seedance 2.0/2.5 主力；35 分钟剧账号费约 1700 元含 66000 积分（1 秒≈0.33 元×2 次抽卡≈1386 元）；省钱做法：先用 480P 低分辨率跑基础视频，总成本可控在 1600–3500 元。
- 工作流：原子级操作拆解；步骤 0 机器读剧本→步骤 1 人工介入定资产（人物脸/发色/场景）→脚本自动跑几百个 API 请求。
- 反风控：提示词不出现真实明星名（反向提示词隔离墙）、AI 音乐避 DMCA、避 COPPA/暴力审核；二次方裂变：ElevenLabs 一键翻译配音西语/葡语做多语言套利。
- 什么时候用 / 常见坑：做 TK/YouTube 出海漫剧时用；成本先算清再开干。

**适用场景**：想做 AI 短剧出海（TK/YouTube）赚美金分成的团队。

**怎么用它搞钱**：按这套成本核算和工作流做漫剧吃播放量分成，或卖自动化脚本+提示词库。

**来源**：[@TraceJie](https://x.com/TraceJie/status/2110209680710787330)（2026-10-14）

### @shengtang135754《导演级拉片拆解 prompt》

**核心提炼**
- 解决什么问题：爆款视频看不懂、学不会——让 AI 扮演"专业导演+短视频编导"，对上传的视频做逐镜头（Shot-by-Shot）深度拆解。
- 核心用法：每切换画面或关键动作变化=一个新分镜；强制 Markdown 表格输出：镜号与时间轴（秒级）、景别与运镜（特写/中景/全景，推/拉/摇/移/固定/转场）、画面视觉描述（主体/动作表情/场景布置/光影色调）、画面文字/贴纸、音频与台词（逐字提取+BGM 情绪变化及关键音效）、导演意图分析（黄金前 3 秒视觉钩子/制造痛点/推进节奏/引导转化）。
- 表格输出完后加 3 句话总结该视频的爆款脚本结构和节奏特点。
- 什么时候用 / 常见坑：配合多模态模型（如 Gemini）用；做"爆款逆向"前先用这套拆出分镜表。

**适用场景**：想逆向拆解爆款视频分镜、学习导演运镜逻辑的创作者。

**怎么用它搞钱**：批量拆解爆款做成自己的分镜库，接短剧/广告分镜策划单。

**来源**：[@shengtang135754](https://x.com/shengtang135754/status/2110257048927838462)（2026-10-14）

### @Xaroon_x《CRIMSON FLASHPOINT》（Seedance 2.5 导演级 prompt 模板）

**核心提炼**
- 解决什么问题：动作类短片 prompt 写散、资产漂移——完整"总-分"式模板：48 秒/16:9/12 镜头×4 秒/ARRI ALEXA 65/变形宽银幕/胶片颗粒格式头。
- LOCATION 段锁定场景（雨夜霓虹十字路口，crimson 为主色调）；HERO 资产锁定：每镜头保持相同面部/发型/胡须/肤色/年龄/体型，变身前后服装分别描述；反派三人组各有体型+武器+职能。
- 12 个分镜逐个带景别运镜：overhead tracking、360° orbit、85mm close-up、low side-tracking、over-the-shoulder、wide low-angle pull-back 等。
- AUDIO 设计：管弦+合成器配乐、雨声/电流/撞击/水花，第 10 镜达音乐高峰，无对白；CONTINUITY 规则：人物身份/盔甲/敌人数量/场景布局/光照/屏幕方向全片一致，真实物理、自然运动模糊、稳定运镜；NEGATIVE 清单：卡通感、换脸、盔甲不一致、随机运镜、抖动闪烁等。
- 什么时候用 / 常见坑：做超级英雄/动作类 AI 短片、想直接套模板时用；改模板先改资产锁定段。

**适用场景**：做超级英雄/动作类 AI 短片、想直接套用 prompt 模板的人。

**怎么用它搞钱**：照此模板接动作类 AI 短片定制，或改造成自己的 prompt 模板库售卖。

**来源**：[@Xaroon_x](https://x.com/Xaroon_x/status/2110248837432439129)（2026-10-14）

### @umesh_ai《I SAVED YOU ONE》（20 秒电影微短片导演 prompt）

**核心提炼**
- 解决什么问题：情感类短片缺"导演思维"——20 秒/10 镜头/24fps/2.39:1 变形宽银幕，四张参考图强制锁定构图/氛围/美术/调色/光照。
- 故事：父亲在雾气弥漫的医院走廊等待→奶奶给熟睡的孙子剥橘子→医院电话打断→母子赶到医院→发现父亲已死，他是 lingering presence 等着见儿子最后一面，孩子给他留了一瓣橘子。
- 10 个分镜精确到秒级时间码（00:00–00:02.0 等），每镜头带景别运镜（dolly inward、85mm close-up、macro close-up、smash cut）；剪辑语言：每个剪辑点都做情绪/节奏连接（医院 beep→剥橘子声→手机振动→汽笛/玻璃→监护仪→电梯马达→开门→病房揭示→flatline→男孩声音→静默）。
- 配乐架构：84 BPM 心跳脉冲，大提琴/钢琴/低音提琴/模拟合成器，19.5 秒音乐骤停、20.0 秒绝对静默；表演指导：父亲是疲惫的等待与释然，母亲强撑，男孩天真自然，拒绝戏剧化哭泣。
- 绝对视觉限制：无 VFX、无鬼魂光效、无慢动作、无字幕，"超自然只通过构图、行为和最终视觉证据揭示"。
- 什么时候用 / 常见坑：做情感类/剧情类 AI 微短片、学"声音-剪辑-情绪"一体化导演思维时用。

**适用场景**：做情感类/剧情类 AI 微短片、想学习声音-剪辑-情绪一体化导演思维的人。

**怎么用它搞钱**：接情感类 AI 广告/微电影定制单（品牌故事片需求大），或做成导演课案例。

**来源**：[@umesh_ai](https://x.com/umesh_ai/status/2110262181162033558)（2026-10-14）

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

- 2026-10-14：新增 9 个 X 来源条目（@TraceJie 情绪套利 SOP、@qinghaiwu9527 MiniMax H3 教程、@dog_not_ai AI 土味综艺拆解、@Soranlan 仙侠动作导演 prompt、@wangfenganc Next Scene LoRA、@TraceJie TK 出海漫剧工作流、@shengtang135754 导演级拉片 prompt、@Xaroon_x CRIMSON FLASHPOINT、@umesh_ai I SAVED YOU ONE），条目总数 13
- 2026-10-12：条目升级为小节格式（核心提炼 / 适用场景 / 怎么用它搞钱 / 来源）；新增 2 个项目（Rylaispirit/cinematic-video-prompt-skill、CyberJ0605/cinematic-video-prompt-engineer-skill）
- 2026-10-11：首版，2 个项目，持续收录中
