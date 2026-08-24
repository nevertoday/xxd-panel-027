<p align="center">
  <img src="./assets/banner.svg" alt="XXD Panel 027 项目横幅" width="1200">
</p>

<div align="center">

# 🦁 XXD Panel 027

### 把照片压印成乳白纸面上的东方博物馆浅浮雕

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Four Modes](https://img.shields.io/badge/Modes-4-d75d32?style=flat-square)](#四种输出共享同一种压印浮雕逻辑)
[![Raster Output](https://img.shields.io/badge/Output-PNG-3c6f67?style=flat-square)](#边界与信任)

<strong>简体中文</strong> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> 乳白厚纸 · 浅凸浅凹 · 极简线刻 · 哑金焦点 · 博物馆展陈

XXD Panel 027 是一个面向 Codex 与兼容 Agent 的图像生成 Skill。它保留主体身份、轮廓、姿态与叙事关系，再把源图重构为压印在厚重乳白纸上的东方浅浮雕：凸起、凹陷、细线刻、阶差与边缘软影共同保住识别，不机械复制照片细节。

视角从主体结构中选择俯瞰、正视、微俯视或轴线延展，不给所有题材套同一模板。画面以乳白、暖白或浅纸色和大面积留白为主，只在源图最关键的识别点加入极少量哑金。柔和暖光让纸纤维、压印高度与细腻阴影成立；文字以深灰或克制金色沿轴线、主体下方、留白边缘或结构轮廓对齐。

## 为什么需要 027

普通“浮雕风”很容易退化成一键 3D 倒角、白色石膏像、豪华包装压纹或大面积镀金，源照片只剩一个通用图标。

027 的顺序完全相反：

```text
锁定身份／轮廓／姿态／关系 → 选择源图有依据的观察视角与轴线 → 建立专属浮雕高度图谱 → 用浅凸、浅凹、线刻、阶差概括主体 → 让乳白纸面和大留白承担宁静 → 只在关键点使用哑金 → 让文字与浮雕轴线共同形成展览秩序
```

如果换成一张无关照片，浮雕轮廓、高度图谱、视角轴线、环境线索、金色焦点和文字关系仍然成立，这张图就不属于 027。

## 027 的视觉契约

- **源图身份：** 至少三个专属线索保住轮廓、姿态、动作、结构、尺度、负形与关系。
- **源图视角：** 根据主体选择俯瞰、正视、微俯视或轴线延展；视角必须强化身份和空间关系。
- **真实浅浮雕：** 浅凸、浅凹、极简线刻、纸面阶差与边缘软影符合厚纸的物理尺度，不是深雕或通用位移贴图。
- **展陈秩序：** 宁静中央轴线或源图有依据的偏轴、清晰主次和大面积留白共同支撑一个主浮雕；环境轮廓不变成微缩布景。
- **同色纸面：** 乳白、暖白、奶油白或浅纸色统领画面，层次来自高度、软影和微小明暗，而不是多彩装饰。
- **哑金焦点：** 最多一个源图有依据的关键局部可用极少量哑金或暖白光强化，绝不大面积铺金。
- **真实材质：** 柔和暖光清楚表现纸纤维、压印边缘、凹槽、阶差与细腻自然影。
- **展览文字：** 一个极短标题和少量微字沿轴线、浮雕底部、留白边缘或结构轮廓对齐。

## 样张 · 来自 X

> [小小东（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2090444626285261046) · 2026-08-20<br>
> GPT2 x 浮雕 x 金 x 高级 x 美学提示词 x VOL.027

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090444626285261046"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 027 样张 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090444626285261046"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 027 样张 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090444626285261046"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 027 样张 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090444626285261046"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 027 样张 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2090444626285261046">查看原推文与完整提示词 →</a></p>

这些样张用于展示 027 的美学动机，不会把样张中的主体、构图、配色、文案或旧画幅变成生成参考或当前默认值。

## 原始提示词优先，而不是二次导演

`references/027-source.md` 是本项目唯一的创作与审美权威。Skill 不再额外总结或扩写它，也不会统一规划颜色、色板、美学动机、标题或微文案。原始提示词要求怎样处理颜色、材料、构图、留白与文字，GPT Image 2 就按那套逻辑执行。

模式与尺寸会完整替换原始提示词旧有的 3:4 上下交付容器，但不改写它的转译美学。每张成品只向 GPT Image 2 发送一个已选模式的最终契约，不再把四种模式放进同一个通用模板让模型自行猜测。

## 四种可组合输出模式

模式可以单选或多选：`top-bottom`、`left-right`、`design-only`、`wallpaper-pack`；多选时，每个模式分别生成、分别拥有自己的提示词。

- `top-bottom`：整张画面由上方现实画面与下方设计转译两个主要部分组成。
- `left-right`：整张画面从顶部到底部保持完整左右结构，原图在左、设计在右；文字融入这两个区域，不再生成横跨全宽的第三块底栏。左右宽度可以不对称，由模型自主构图。
- `design-only`：原图只作为不可见的身份、结构、颜色与事实依据；整张成品的每个可见元素都必须属于该 Skill 自己的设计转译语言。
- `wallpaper-pack`：每台设备分别生成完整画布的设计转译壁纸，原图不作为照片区域出现。

上下或左右都不做分界线、中线百分比或像素坐标检测。只有用户明确要求像素级分区或原片逐像素不变时，才使用确定性拼合。

普通成品尺寸同样可以多选：自动适配、跟随原图、1:1、3:4、4:3、4:5、5:4、2:3、3:2、9:16、16:9、21:9、5:7、7:5，或自定义比例／准确像素。没有静默默认尺寸；每个不同比例都会基于同一份原始提示词独立重构。

壁纸套装可选“连贯”或“四张独立”。连贯模式先生成一张定调图，其余设备同时参考原图与定调图重新构图；不会把一张图机械裁成四种尺寸。

## 文字方式

正式生图前只确认三种选择：

1. **模型根据原始提示词生成文字**：用户只指定语言或地区，文字内容、数量、气质与排版由 GPT Image 2 按原始提示词生成；所有文字都从当前图片的内容、气质或隐喻中自然生长，任何事实或资料式信息都必须有用户输入、图片可见内容或已核实信息作为依据。
2. **使用我的准确文字**：逐字传给图像模型，不改写、不翻译、不补标题；排版仍遵循原始提示词。
3. **不要文字**：严格禁止文字与伪文字。

外层 Skill 不再预编标题、微文案或文案包。文字语言与操作语言分开确认，不根据人物、场景或文件名猜测国家与受众。

## 完整画布优先与位图边界

图像模型负责整张成品的审美重构，双联也默认一次直出完整画布。`scripts/compose_panel.py` 只保留为条件明确的兜底、无创尺寸校准和只读审计工具，不再预先规划每次任务，也不评价审美是否成功。

全部交付为 PNG 位图。每次调用都在 `~/Desktop/xxd/` 下创建新任务；已配置图像通道只返回脱敏状态，不公开供应商、端点、凭据、请求头、提示词、响应或账户信息。SVG、HTML、Canvas、图表和程序绘图不能替代最终作品。

## 能力自适应问询与快捷参数

同一个 Skill 会根据宿主真正提供的交互能力选择界面，不会把文本符号伪装成可点击控件：

- **Claude Code 提供 `AskUserQuestion + multiSelect: true` 时**：模式和尺寸使用真正的 checkbox；文字方式与壁纸关系使用单选。常用尺寸会按方形、竖版、横版分组展示，并累计多组选项；自定义尺寸进入自由输入。
- **Codex 只提供 `request_user_input` 时**：它只用于文字方式、壁纸关系等互斥单选，不拿来伪装模式或尺寸多选。模式与尺寸改用清楚的组合输入。
- **没有交互工具时**：使用两轮文字问询。第一轮选择一个或多个模式；第二轮填写尺寸与文字方式。Skill 不显示假的 `- [ ]`，也不会为了获得表单要求用户切换 Plan mode。

默认第二轮只展示“智能推荐／跟随原图／常用比例／自定义”四个入口；只有选择常用比例时，才展开完整比例库：方形 `1:1`，竖版 `3:4、4:5、2:3、9:16、5:7`，横版 `4:3、5:4、3:2、16:9、21:9、7:5`。所有比例都可组合，也可直接输入准确像素。

全部设置都可以直接作为参数传入：

```text
/xxd-panel-027 photo.jpg --mode top-bottom,design-only --size auto,3:4,9:16 --text prompt --locale ja-JP
```

支持 `--mode`、可重复或逗号分隔的 `--size`、`--text prompt|exact|none`、`--locale`、`--copy`、`--wallpaper linked|independent`、`--wallpaper-size` 和 `--out`。参数齐全时跳过全部问询；参数不完整时只询问缺失项。

## 生图模型优先级

GPT Image 2 是默认首选，并继续执行本项目现有的高保真垫图、生成前确认整张画幅、双联一次生成完整画布、脚本仅作条件式兜底等逻辑。

当当前工具或已配置兼容通道确实可用，并能满足原图保真、整张成品比例、目标语言文字和连贯壁纸多图参考等要求时，也支持 Seedance 5.0 Pro、Nano Banana Pro（Gemini Image Pro）、Nano Banana 2（Gemini Image Flash）或其他兼容位图模型。备用模型只替换生成通道，不得改变模式、画幅、文案、语言、壁纸关系和完整画布优先策略。

如果没有合适的生图通道，Skill 会请用户启用生图工具或提供 API Key。用户主动提供的凭据可以用于当前任务，但不得在回复或日志中回显、展示或泄露；未经用户明确要求，不会长期保存凭据或修改供应商、账户、计费及全局路由配置。

## 开始使用

```bash
git clone https://github.com/nevertoday/xxd-panel-027.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-027" ~/.codex/skills/xxd-panel-027
```

Claude Code 用户可以把同一目录链接到 `~/.claude/skills/xxd-panel-027`。安装后重新启动 Agent 会话。

```text
$xxd-panel-027
把这张照片做成左右双联，文案由你根据照片内涵创作，使用自然韩语。
```

只上传照片也可以调用。Skill 会先用分行编号菜单询问一个或多个模式，再询问文字设置；选择壁纸时还会确认连贯或独立以及设备尺寸。

完整规范：

- [Skill 工作流](SKILL.md)
- [中文运行适配器](references/xxd-panel-027-prompt.zh-CN.md)
- [英文运行适配器](references/xxd-panel-027-prompt.en.md)
- [原始风格提示词](references/027-source.md)

## 边界与信任

- 每张照片只在自己的任务中使用，不借用其他输入、旧成品或样张里的主体、颜色、文案和构图。
- 每次调用都创建新的任务子文件夹；相同原图和参数也要重新生成，旧成品不能冒充当前任务。
- 最终交付为 PNG 位图，不是 SVG、HTML、Canvas 或程序绘图替代品。
- 已配置位图桥接只返回脱敏状态，不显示供应商、端点、请求头、凭据、提示词或服务器响应正文。
- 每个所选普通模式各返回一张；若选择 `wallpaper-pack`，再返回四张独立壁纸。选择 `全部` 时每张原图共返回 7 个 PNG，分处四个同级模式文件夹，绝不生成拼贴总览。

本地拼版需要 Python 3 和 Pillow。安全位图桥接使用 Python 3.11+ 的 `tomllib`。图像生成仍需要主机 Agent 的内置位图能力或已经配置好的兼容位图路径。

## 项目结构

```text
xxd-panel-027/
├── SKILL.md
├── README.md / README.en.md / README.ja.md / README.ko.md / README.ar.md
├── agents/openai.yaml
├── assets/
│   ├── banner.svg
│   └── examples/（未来本地样张占位）
├── scripts/
│   ├── compose_panel.py
│   └── configured_imagegen.py
└── references/
    ├── xxd-panel-027-prompt.zh-CN.md
    ├── xxd-panel-027-prompt.en.md
    └── 027-source.md
```

## 关于 XXD

XXD 是小小东的品牌名称缩写。项目由 [@xiaoxiaodong01](https://x.com/xiaoxiaodong01) 创建并维护。

## 服务与会员

### 深度咨询 · 299 元/小时

Skills 使用的一对一深度咨询按 299 元/小时收费。请通过下方微信二维码联系小小东预约。

### 小小东 Skills 用户交流群 · 入群 99 元

一次支付 99 元加入用户交流群，用于交流工作流、作品与互助；不包含按小时的一对一深度咨询。扫码后请备注“Skills 用户交流群”。

### 知识星球＋成员提示词库 · 699 元/年

[知识星球](https://wx.zsxq.com/group/15554814142882)与[小小东成员提示词库](https://vip.xiaoxiaodong.ai/)是同一份会员权益：**一次年费同时开通两边，无需重复付费。**

1. 在[知识星球](https://wx.zsxq.com/group/15554814142882)开通后，微信联系小小东领取成员提示词库兑换码。
2. 在[成员提示词库](https://vip.xiaoxiaodong.ai/)自助开通后，微信联系小小东邀请进入知识星球。

<p align="center">
  <a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="小小东付费服务微信二维码" width="320"></a>
</p>

<div align="center">

**不是给照片加一道浮雕滤镜，而是让纸张压出它真正的身份与秩序。**

</div>

---

<div align="center">
  <h2>☕ 为开源项目赞助算力</h2>
  <p>如果这个项目为你节省了时间，可以通过微信或支付宝赞助后续测试与生成算力。</p>
  <table>
    <tr>
      <td align="center" width="240">
        <a href="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png" alt="小小东微信算力赞助二维码" width="180"></a><br>
        <strong>微信算力赞助</strong>
      </td>
      <td align="center" width="240">
        <a href="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png" alt="小小东支付宝算力赞助二维码" width="180"></a><br>
        <strong>支付宝算力赞助</strong>
      </td>
    </tr>
  </table>
  <p><sub>赞助完全自愿，不会改变这个开源项目的使用权限。</sub></p>
</div>
