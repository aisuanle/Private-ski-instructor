# Private-ski-instructor 私人滑雪教练

一个可移植的 Trae skill：以温柔、平和的私人教练角色，陪用户从第一次上雪，一步步走到究极大神；如果用户愿意，再走向职业选手、教练或向导。

## 作用

- **长期陪伴**：先安定情绪，再教动作；一次只改一件事，不评判、不催促。
- **成长路径**：初遇雪 → 会停 → 会转 → 独立 → 全山 → 究极大神 → 职业选手。
- **技术诊断**：单板、双板、小众雪上项目；支持文字、图片、视频、语音输入。
- **分级教学**：按初级、中级、高级、业余大神、职业竞技给练习与验收标准。
- **方向专项**：自由式、公园、跳台、大山野雪、登山滑雪、竞速、旗门。
- **装备建议**：板、固定器、雪鞋、护具的选型、调试、保养、租买判断。
- **雪场与行程**：雪道选择、缆车、雪况、目的地对比、套餐类型。
- **安全边界**：急救、雪崩、头盔与规则；不替代现场教练、雪场巡逻队和医生。
- **讲人话**：先结论，再打比方，术语紧跟括号解释。

不适用于非雪上运动。

## 目录

```text
Private-ski-instructor/
├─ SKILL.md                  # 入口：人格设定、工作流、路由表、多模态协议、输出模板
├─ README.md                 # 本文件
├─ LICENSE                   # MIT
├─ references/
│  ├─ persona.md                     # 教练人格、语气、陪伴机制、成长七阶
│  ├─ discipline-alpine.md           # 双板技术
│  ├─ discipline-snowboard.md        # 单板技术
│  ├─ discipline-niche.md            # 坐式、Telemark、越野等
│  ├─ discipline-freestyle-park.md   # 自由式与公园
│  ├─ discipline-jumping.md          # 跳台与 Big Air
│  ├─ discipline-big-mountain.md     # 大山野雪与登山滑雪
│  ├─ discipline-racing.md           # 竞速与旗门
│  ├─ knowledge-gear.md              # 装备
│  ├─ knowledge-resort.md            # 雪场、目的地、套餐
│  ├─ knowledge-safety.md            # 安全、急救、雪崩
│  ├─ levels.md                      # 等级标准与晋升验收
│  ├─ taxonomy.md                    # 分类矩阵与术语
│  ├─ faq-quick-answers.md           # 新手 100 问总表
│  ├─ faq-snowboard.md               # 单板 100 问
│  ├─ faq-alpine.md                  # 双板 100 问
│  ├─ faq-gear.md                    # 装备 100 问
│  ├─ plain-language.md              # 术语翻译与话术
│  ├─ media-index.md                 # 文本、图片、视频索引
│  └─ sources.md                     # 引用编号、链接、可信度分级
└─ assets/
   ├─ README.md              # 每张示意图的来源、用途、引用限制
   └─ images/                # 28 张 AI 生成讲解示意图
```

## 资源来源

| 类别 | 主要来源 | 用途 |
|---|---|---|
| 国际规则与标准 | FIS、ISO 11088 / 11087 | 行为准则、竞赛规则、固定器装配 |
| 教学体系 | PSIA-AASI、CASI、CSIA | 双板/单板技术框架与教练认证 |
| 行业安全 | NSAA、Avalanche Canada | 责任守则、头盔、雪崩三件套 |
| 中国官方 | 国家体育总局、冬运中心 | 大众滑雪 1–9 级、指导员标准 |
| 雪场与票务 | 万龙官网、中国旅游报、吉林发布、北京日报、Epic / Ikon | 雪场特点、开板信息、套餐与通票 |
| 图片素材 | AI 生成示意图（Trae GenerateImage） | 动作与概念讲解，不冒充真实照片 |

- 所有引用编号与完整链接见 `references/sources.md`，按 A/B/C/D 分级。
- 价格、开板、雪道开放属于动态信息，回答时必须提示以官方当日公告为准。
- 图片均为示意图，不含第三方版权素材；使用规范见 `assets/README.md`。

## 安装

把整个目录放到项目的 `.trae/skills/` 下，或放到用户级 `~/.trae-cn/skills/` 下即可。问到滑雪技术、装备、雪场或训练计划时会自动触发。

## 声明

- 本 skill 不替代现场教练、雪场巡逻队和医生。
- 伤情、脑震荡、雪崩等场景只给保守流程，具体以专业人员判断为准。
- 采用 MIT License。
