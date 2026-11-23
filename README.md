# 空间设计师 × AI 工作流：GitHub 精选收藏

> 收集者为一位**空间设计师兼项目经理**整理的 GitHub 精选清单。原则是少而精：正式收录 12 个（外加 1 个备选），每个都是我打开仓库看过、核对过星标数（Star）和最近更新时间的。
>
> 清单不局限于设计软件：也包括日常传文件、处理 PDF 这类马上能用的工具。你电脑上已经装了 **Codex** 和 **WorkBuddy**，和 AI 相关的条目会写怎么配合这两个工具用。
>
> 📅 数据核对时间：**2026 年 11 月 23 日**（每周一更新；星标数和“最近更新”以核对当天为准，之后会变化）
> 🧭 第一次用 GitHub？先看 [GITHUB_GUIDE.md](./GITHUB_GUIDE.md)
>
> 难度说明：**入门** = 会看网页、会复制粘贴就能用；**进阶** = 需要装软件插件或在终端里粘贴几行命令（可以让 Codex 带着你装）。

---

## ⭐ 我最推荐先试这 3 个

1. **[LocalSend](https://github.com/localsend/localsend)**：像跨系统的 AirDrop。你的 iPhone、Windows 电脑和同事的 Mac 连同一个局域网，就能互传照片和文件，不用账号、不经网盘。**半天都不用，装上就能用。**
2. **[Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF)**：装在自己电脑上的 PDF 工具箱，合并、拆分、加水印、加密都可以离线做，图纸和报价单不用上传到陌生网站。
3. **[AI-Coding-Guide-Zh](https://github.com/KimYx0207/AI-Coding-Guide-Zh)**：一套中文教程，Codex 和 WorkBuddy 都讲，正好对应你装的两个工具。先跟着 Codex 和 WorkBuddy 两条线各做一个小练习，**半天就能上手**。

---

## 一、先学会用 AI 助手（Codex / WorkBuddy 入门）

### 1. [KimYx0207/AI-Coding-Guide-Zh](https://github.com/KimYx0207/AI-Coding-Guide-Zh)
- ⭐ 约 6.5k｜最近更新：2026-11｜MIT 开源
- **是什么**：“老金”维护的中文零基础教程，分 Claude Code、Codex、OpenClaw、WorkBuddy 四条学习线，每条入门路线都配了练习材料，还有结果对照可以自己检查。
- **对你的价值**：Codex 这条线讲了桌面 App 的安装、项目指令、MCP、Skills、自动化（Automations）；WorkBuddy 这条线专门讲办公场景，比如周报、表格、待办和定时任务。你两个工具都装了，跟着它学，路线最顺。
- **难度**：入门
- **怎么开始**：打开仓库首页，找到“今天先完成哪件事”表格，先做 **CX-01 Codex App 安装与认证**、**CX-02 桌面工作流**，再看 WorkBuddy 的定时任务那篇（WB-07），把每周要交的进度汇报设成自动生成。

### 2. [AlephAITech/WorkBuddyGuide](https://github.com/AlephAITech/WorkBuddyGuide)
- ⭐ 约 3.9k｜最近更新：2026-11｜MIT 开源
- **是什么**：社区写的《WorkBuddy 实战蓝皮书》，按真实任务来组织：使用手册、办公/文件/会议/知识管理案例、怎么打造 Skill、多 Agent，还有“岗位与行业”工作流。
- **对你的价值**：WorkBuddy 是腾讯出的办公 AI，用它整理会议纪要、管理项目资料和日常文件，比 Codex 更顺手。书里还有“常用指令模板与场景速查表”，能直接抄来用。
- **难度**：入门
- **怎么开始**：直接在浏览器打开在线版 **workbuddy.homes**（比在 GitHub 上看排版好），从第一篇第 1 章读起。先跑通“会议纪要”和“文件整理”两个案例，再套到你的项目例会上。

---

## 二、给 AI 装“技能包”（文件、项目管理、室内设计专业流程）

> “技能（Skill）”就是一个文件夹，里面放着一份 `SKILL.md` 说明书，有的还附带脚本，AI 读了就会按固定流程干活。Codex 支持装这类技能。

### 3. [anthropics/skills](https://github.com/anthropics/skills)
- ⭐ 约 19.9 万｜最近更新：2026-11｜官方示例仓库（文件处理类技能是“源码公开”，不是完全开源）
- **是什么**：Anthropic 官方发布的 Agent Skills 示例库，其中 `docx`（Word）、`xlsx`（Excel）、`pptx`（PPT）、`pdf` 四个文件技能是生产环境里真在用的；另外还有 `skill-creator`（帮你自己写技能）和 `template`（技能模板）。
- **对你的价值**：报价单/工程量清单（BOQ）、材料表、施工进度表、设计说明、汇报 PPT，这些都是 Word/Excel/PPT 文件。让 AI 按这些技能来生成和修改，排版、公式、格式都更可靠。用 `skill-creator` 还能把你们公司的报价模板和交付规范做成**自己的技能**。
- **难度**：入门～进阶（看懂、套用是入门；改成自己公司的版本算进阶）
- **怎么开始**：在 Codex 里直接说：“请参考 https://github.com/anthropics/skills 里的 xlsx 技能，把我这份报价单整理成带公式的 Excel，并按空间分组小计。”想长期用，就让 Codex 帮你把需要的技能文件夹装到它的技能目录里（常见是 `~/.codex/skills`，以 Codex 官方说明为准）。

### 4. [jnMetaCode/agency-agents-zh](https://github.com/jnMetaCode/agency-agents-zh)
- ⭐ 约 2.2 万｜最近更新：2026-11｜MIT 开源
- **是什么**：328 个现成的中文“AI 专家角色”，每个角色都写好了人设、工作流程和要交付的成果，分 22 个部门，支持 Codex 等 20 种 AI 工具。其中 67 个是面向中国市场的原创角色。
- **对你的价值**：它的**项目管理部**有“高级项目经理”（需求拆解、范围管控）、“项目牧羊人”（跨团队协调、进度跟踪）、“工作室制片人”（创意项目管理、资源调度）、“会议纪要专家”（提取决议和待办），正好对应你的 PM 日常。
- **难度**：入门（复制角色文本就能用）；进阶（用安装脚本 `./scripts/install.sh --tool codex` 一键装进 Codex）
- **怎么开始**：打开仓库里 `project-management/` 文件夹下的“会议纪要专家”，把全文复制给 Codex 或 WorkBuddy，再贴上你的项目例会录音转写稿，让它输出“决议 / 待办 / 责任人 / 截止日期”表。
- ⚠️ 提醒：仓库首页有第三方 API 中转服务的赞助广告，和技能本身无关，不必理会。

### 5. [liuqing0224/interior-design-skills](https://github.com/liuqing0224/interior-design-skills)
- ⭐ 19（新项目，星标还少）｜最近更新：2026-10
- **是什么**：中文“室内设计全流程 15 个 Skills”，包括总控、需求任务书、现场测量、平面布置、概念、空间表现、材料、灯光、定制柜、机电、图纸、软装、预算、校审、交付。附带两个完整示范项目（96㎡ 住宅、84㎡ L 形户型），产出有 PDF 图集、DXF 图纸和 Excel 预算。
- **对你的价值**：这是唯一一个**按室内设计师真实工作阶段**拆好、而且**明确支持 Codex** 的技能套件。预算会跟着模型变更联动（作者演示过：改一处衣柜，图纸、清单、预算一起更新），对兼做 PM 的你很实用。作者也写明了：没有内置未核实的规范数值，示范项目也不能当成真实施工成果。
- **难度**：进阶（需要 Python；出图部分还要 Blender）
- **怎么开始**：先在浏览器里看 `projects/DEMO-APT-096` 示范项目的 PDF 和预算表，判断值不值得用。觉得有用，就把仓库地址给 Codex，说：“请按这个仓库 README 的‘快速使用’把技能安装到我的 Codex，然后用 `$interior-orchestrator` 帮我整理 XX 项目的需求和未知项。”
- ⚠️ 新项目，用于真实项目前请人工复核所有尺寸和金额。

---

## 三、让 AI 直接操作你的设计软件（MCP 插件）

> **MCP** 可以理解成“AI 和软件之间的转接头”。装好之后，你在 Codex 里用中文下指令，AI 就能在 SketchUp / Blender / Rhino 里建模、读取场景、改材质。三个都需要先装插件、再连 Codex，统一算**进阶**，但都可以让 Codex 带你一步步装。

### 6. [mhyrr/sketchup-mcp](https://github.com/mhyrr/sketchup-mcp)
- ⭐ 约 560｜最近更新：2026-04｜MIT（README 中声明）
- **是什么**：把 SketchUp 和 AI 连起来的 MCP 插件。AI 可以创建、移动、删除组件，赋材质，读取场景信息，导出模型，还能执行 Ruby 脚本。
- **对你的价值**：SketchUp 是国内室内设计最常用的建模软件。拉体块、排家具、批量改材质这类重复操作，可以改成一句话交给 AI，你把时间留给方案判断。
- **难度**：进阶
- **怎么开始**：在 SketchUp 的“扩展程序管理器”里安装它的 `.rbz` 扩展，再到“扩展程序 > SketchupMCP > Start Server”启动服务；然后把仓库地址给 Codex：“请把 https://github.com/mhyrr/sketchup-mcp 配置成我的 MCP 服务器。”
- 💡 备选：[laowang-wy/adai-sketchup-skill-mcp](https://github.com/laowang-wy/adai-sketchup-skill-mcp)（⭐ 116，2026-11 更新）是中文作者为 **Codex** 做的 SketchUp 建模 Skill 加 MCP，不过目前写明的适配基线是 Windows 和 SketchUp 2018/2019，用其他版本要自己验证。
- ⚠️ 正式条目上次代码更新仍是 2026 年 4 月（约 7 个月），尚未超过 12 个月，先保留；若长期停更再考虑是否改推备选。

### 7. [ahujasid/mcp-for-blender](https://github.com/ahujasid/mcp-for-blender)（原名 blender-mcp）
- ⭐ 约 3.5 万｜最近更新：2026-11｜MIT 开源
- **是什么**：最有名的“AI 控制 Blender”插件，可以用自然语言建模、布置场景、改材质，支持 Codex。
- **对你的价值**：Blender 免费，渲染效果好。可以用它快速搭空间白模、调灯光和相机、出概念氛围图，再和后面的 ComfyUI 配合出效果图。
- **难度**：进阶（这三个里安装最省事）
- **怎么开始**：Windows 上按 README 用 `winget install --id=astral-sh.uv -e` 装好 uv，再运行 `uvx mcp-for-blender setup`，安装程序会自动找到 Codex 并完成配置。也可以手动在终端运行 `codex mcp add blender -- uvx mcp-for-blender`。打开 Blender 后，在 Codex 里说“搭一个 4m×5m、层高 2.8m 的客厅白模”试试。

### 8. [jingcheng-chen/rhinomcp](https://github.com/jingcheng-chen/rhinomcp)
- ⭐ 约 1.2k｜最近更新：2026-11｜MIT 开源，有简体中文 README
- **是什么**：把 Rhino 8 和 Grasshopper 接到 AI 上的 MCP 插件。AI 能建模、读文档、截取视口，还能自动连 Grasshopper 电池。
- **对你的价值**：做异形吊顶、曲面墙、参数化格栅这类造型时，可以直接用中文描述，让 AI 生成 Grasshopper 定义，不用自己从头连线。
- **难度**：进阶（需要 Rhino 8）
- **怎么开始**：在 Rhino 的“工具 → Package Manager”里搜索 `rhinomcp` 安装，然后把这句话发给 Codex（README 推荐的做法）：“Please install https://github.com/jingcheng-chen/rhinomcp as a local MCP server named `rhino`.”

---

## 四、AI 出效果图

### 9. [Comfy-Org/ComfyUI](https://github.com/Comfy-Org/ComfyUI)
- ⭐ 约 14.8 万｜最近更新：2026-11｜GPL-3.0 开源
- **是什么**：最主流的开源 AI 生图/生视频工具，用“节点连线”的方式搭工作流，可以在本地电脑上运行。
- **对你的价值**：毛坯房照片或白模截图转效果图、换风格、换材质、局部重绘，几乎所有设计 AI 出图流程都建立在它上面。在本地运行，客户资料也不用上传到别人的网站。
- **难度**：进阶（最好有 NVIDIA 显卡；没有显卡也能用官方云服务）
- **怎么开始**：按 README 的建议，新手直接下载官方**桌面版**（comfy.org/download），比手动安装简单得多。装好后先跑通内置模板里的一张文生图，再装下面的室内设计插件。

### 10. [amir84ferdos/ComfyUI-ArchAi3d-Qwen](https://github.com/amir84ferdos/ComfyUI-ArchAi3d-Qwen)
- ⭐ 72｜最近更新：2026-04
- **是什么**：专门做室内设计的 ComfyUI 插件，基于通义千问 Qwen 的图像编辑模型，有 4 种模式：文字生成设计、情绪板（Mood Board）参考设计、透视参考设计、清理现场杂物。还带材质替换（48 种材质）、相机视角控制等节点。
- **对你的价值**：可以把毛坯房或施工中的现场照片“清理”干净再出方案图，也可以用情绪板快速给客户出几种风格对比，前期提案时特别省时间。
- **难度**：进阶
- **怎么开始**：在 ComfyUI 里打开 ComfyUI Manager，搜索“ArchAi3d Qwen”，点击安装，然后重启。先用“Room Cleaning（清理房间）”模式处理一张现场照片试试效果。
- ⚠️ 星标不多，是个人开发者的项目，大约 7 个月没更新了。尚未超过 12 个月，先保留。

---

## 五、日常效率（跨设备传文件、处理 PDF）

### 11. [localsend/localsend](https://github.com/localsend/localsend)
- ⭐ 约 10.0 万｜最近更新：2026-11｜Apache-2.0 开源
- **是什么**：免费开源的跨平台传文件应用，官方定位是 AirDrop 的替代方案。Windows、macOS、Linux、iPhone、Android 都能用，设备之间走本地局域网，用 HTTPS 加密，不经过第三方服务器，也不需要账号。官方网站：[localsend.org](https://localsend.org)。有简体中文说明。
- **对你的价值**：你用 iPhone 和 Windows，同事很多用 Mac，互相传方案图、照片和文件时常常受阻。双方都装上 LocalSend、连同一个 Wi-Fi，就能直接互传，不用优盘、也不必先传到网盘。
- **难度**：入门
- **怎么开始**：Windows 可在仓库 [Releases](https://github.com/localsend/localsend/releases) 下载 `LocalSend-1.18.2-windows-x86-64.exe`（也可用 winget 等包管理器，商店或包管理器安装以后更新更省事，因为应用本身没有自动更新）。iPhone 请到 App Store 认准官方页面：[LocalSend（ID 1661733229）](https://apps.apple.com/cn/app/localsend/id1661733229)，不要下载同名收费软件。Mac 同事同样装官方版。
- ⚠️ 双方必须在同一个局域网。公司网络如果开了访客隔离（AP isolation）或设备互相看不见，可能搜不到对方；必要时要在防火墙放行 TCP/UDP 端口 53317。它只管传文件，**不能**解决 Keynote `.key` 无法编辑、或 PPT 在 Mac / Windows 之间排版错乱的问题。

### 12. [Stirling-Tools/Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF)
- ⭐ 约 9.7 万｜最近更新：2026-11｜开源核心是 MIT，部分目录另有许可（官方称 open-core）
- **是什么**：在自己电脑或自己服务器上处理 PDF 的工具箱，也可以当桌面应用来用。合并、拆分、旋转、裁切、加水印、加密、签章、图片转 PDF 等常用操作，桌面版可以离线完成，文件不用上传。界面支持 40 多种语言，可改成中文。官方文档：[docs.stirlingpdf.com](https://docs.stirlingpdf.com/)。个人使用桌面版免费，无需账号。
- **对你的价值**：设计日常经常要合并图纸、拆分页、给 PDF 加水印或加密再发给客户。用它在自己电脑上处理，比把文件传到在线转换网站更稳妥。
- **难度**：入门（装 Windows 安装包即可；若要压缩、OCR、PDF 转 Word/PPT，则要另接服务，算进阶）
- **怎么开始**：Windows 10/11（x64）到仓库 [Releases](https://github.com/Stirling-Tools/Stirling-PDF/releases) 下载 `Stirling-PDF-windows-x86_64.msi` 安装，也可以看 [官网下载页](https://www.stirling.com/download)。装好后先试合并和加水印。
- ⚠️ 桌面版默认只带核心功能。按官方文档，压缩、修复、OCR、以及 PDF 转 Word / PowerPoint / HTML 等，需要连接他们的 Cloud 或自建服务器（文件会离开你的电脑，**客户资料请谨慎**）。不要为了这几项高级功能随手把项目文件传到 Cloud。

---

## 附：一个马上能用的小技巧（AGENTS.md）

Codex 打开一个文件夹时，会读取里面的 `AGENTS.md` 文件，把它当作“这个项目的工作说明”。你可以在每个项目文件夹里放一份，比如：

```markdown
# 项目说明（给 AI 看）
- 项目：XX 办公室室内设计，面积约 800㎡，城市：上海
- 我的身份：主案设计师兼项目经理
- 文件约定：报价单在 /报价，进度表在 /进度，会议纪要在 /会议
- 输出要求：一律用简体中文；金额保留两位小数；尺寸单位 mm
- 不确定的尺寸和价格不要编造，列成“待确认清单”
```

这样每次打开这个项目，Codex 都会自动按你的规矩干活，不用每次重复交代。

---

### 关于取舍
- 只收录 2026 年 11 月 23 日核对时**仍在更新**（近 12 个月内有更新）的仓库。本周没有删除已有条目。
- 按你后来补充的偏好，本周新增的是日常就能用的成品工具，而不是新的 3D 软件转接头。上周未合并的更新里曾拟加入 `cl0nazepamm/3dsmax-mcp`，这次没有并入，避免再往清单里堆 MCP 插件。
- 有些常见推荐没有收，比如英文的“AI 建筑 awesome 清单”：我核对时发现，大多数要么星标很低，要么已经停更，对你帮助不大。也没有把“能在 Windows 上可靠编辑现代 Keynote `.key` 文件”的开源工具写进来——核对时没有找到值得推荐的成熟方案。
- 星标少的项目（第 5、10 项）是因为和你的本行特别贴才收进来的，已经单独标了提醒。第 6、10 项已有约 7 个月没有代码更新，尚未超过 12 个月，先保留并标明。
