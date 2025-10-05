# Michelle Chen - 个人作品集网站（README）

这是 **陈美晖（Michelle Chen）** 的现代化、响应式个人作品集网站，面向校招与初入职场的 **售前 / 云解决方案 / 产品-运营** 岗位。网站聚焦「真实项目复盘 + 可落地方案表达」，强调把技术转成业务语言与可量化指标。

**在线访问（Live Demo）**：[https://CheMiui.github.io/](https://CheMiui.github.io/)
（建议在此处放一张首页截图与一张 Projects 区截图）

---

## 核心理念

**将技术转化为可衡量的商业价值。** 这不是简历的网页化，而是一份可被快速阅读与验证的“迷你产品”：

* **复合型定位**：懂业务、会拆解、能落地；对话对象既包括技术团队也包括业务方。
* **数据驱动**：过程尽量留痕，结果尽量量化（TCO、SLA、转化、复购等指标）。
* **解决方案思维**：不堆技术名词，专注“为什么选它”“怎么权衡”“值不值得”。

---

## 主要功能（Features）

* **中英双语切换**：按钮一键切换，中英文本同时维护，适合招聘方与海外合作方浏览。
* **明亮/暗黑主题**：视觉一致性 + 对比度优化，夜间可读性良好。
* **响应式设计**：桌面 / 平板 / 手机全覆盖；断点与字号随场景自适应。
* **玻璃拟态（Glassmorphism）**：半透明磨砂卡片 + 阴影层级 + 轻微上浮，干净耐看。
* **动态交互**

  * 平滑滚动、进入视口淡入；卡片悬停上浮与阴影加深；
  * Projects 支持轻量筛选；Experience 时间轴支持折叠/展开；
  * Contact：**多邮箱选择弹窗**（一键复制）、**WeChat 二维码弹窗**、小红书/GitHub/LinkedIn 外链。
* **AI 数字人视频（Hero）**：使用AI agent制作数字人形象,用短视频定位自身；提供 mp4/webm + poster，移动端静音自动播放，保证首屏观感。

---

## 技术栈（Tech Stack）

* **前端**：原生 **HTML5 + CSS3 + JavaScript（ES6）**，不依赖框架，方便 GitHub Pages 托管与后续维护。
* **图标**：本地 **SVG**（品牌官方或开源）
* **字体**：Google Fonts（Inter / Space Grotesk 等）
* **设计语言**：极简排版、玻璃拟态卡片、可访问性（ARIA / 键盘可达）

---

## About Me（简要）

**陈美晖（Michelle Chen）**
定位：**售前与云解决方案工程师**。在旅游管理本科的业务视角基础上，完成信息技术硕士的技术补全，愿意做“业务 ↔ 技术”的桥梁，把复杂问题讲清楚、把方案落成指标。

* **教育**：

  * 信息技术硕士 · 西澳大学（The University of Western Australia，QS 100）
  * 旅游管理学士
* **特质**：结果导向，自驱力强；多线程推进与时间管理；跨文化沟通与关系经营。
* **方向**：2026 届 **Pre-Sales / Solution Engineering / Product-Ops** 相关岗位。

---

## 精选项目（Featured Projects）

### 1）HPE dHCI 金融行业解决方案（售前实训/复盘）

* **定位**：围绕金融客户的混合负载与现代化运维诉求，做架构选型、容量规划、价值量化的一次完整练习。
* **方案**：对比传统 HCI / SimpliVity / Nutanix 后，基于“**存储增长快于计算**”与“**少量裸机**”的需求，选择 **HPE Alletra dHCI + GreenLake**（计算/存储解耦，订阅式交付）。
* **方法**：

  * 参考 **CloudPhysics** 负载画像 + **NinjaSTARS** 容量规划做 **Sizing**，解释 **6 台 n+1** 的取舍（为何不是 5/7 台）；
  * 用 **TCO** 把 CAPEX→OPEX 的财务差异讲清楚；
  * 提前说明极端故障场景的降级策略与 **4h SLA**（风险透明）。
* **结果（模拟测算口径）**：TCO 与运维投入显著下降，性能明显提升；细节见报告页面。
* **链接**：[https://chemiui.github.io/dHCI-Financial-Solution-Project/](https://chemiui.github.io/dHCI-Financial-Solution-Project/)

---

### 2）Northridge Digital｜内容驱动的智能零售（个人项目复盘）

* **定位**：围绕“信任-效率-复购”的小型电商闭环，覆盖选品、转化与私域沉淀。
* **动作**：

  * A/B 找到“**室外场景化**”的内容表达更易转化；
  * 公域（闲鱼）→ 私域（社群/朋友圈）沉淀，构建**轻量 KPI 看板**（曝光-询盘-转化-复购）；
  * 尝试 **KOC 分销** 与供应链议价，改善客单与毛利。
* **结果（阶段峰值/区间）**：

  * 总 GMV **15w+**；私域沉淀 **200+**；**复购 ~35%**；
  * 单月利润峰值 **过万元**；内容 A/B 后转化显著抬升。
* **链接**：[https://chemiui.github.io/Northridge_Digital/](https://chemiui.github.io/Northridge_Digital/)

---

### 3）API × 云存储自动化交付（个人电商自动化）

* **定位**：虚拟/数字内容的“**下单即交付**”，减少人工、提升体验。
* **方案**：电商订单 → 校验 → 凭证生成/取回 → 云端分发（网盘/API）→ 回执写回，形成轻量流水线。
* **观测**：人均处理效率 **≈ +300%**，响应 **秒级**；转化与复购小幅提升；贴吧/社群为主要获客渠道（累计 **1000+** 用户）。
* **注**：因平台规则调整，已主动下线；给自己留下了**合规与风控**方面的经验。

---

## 目录结构（建议）

```text
/
├─ index.html              # 单页应用（结构/样式/交互）
└─ images/                 # 本地资源
   ├─ hero_avatar_720.mp4
   ├─ hero_avatar_720.webm
   ├─ hero_poster.jpg
   ├─ github_logo.svg
   ├─ linkedin_logo.svg
   ├─ email_logo.svg
   ├─ wechat_logo.svg
   ├─ wechat_QR.jpg
   ├─ Xiaohongshu_logo.svg
   └─ ... 其它截图/缩略图
```

> 需替换素材时，保持同名覆盖即可；或在 HTML 中更新路径。

---

## 本地运行

1. 克隆或下载本仓库到本地。
2. 将图片 / SVG / 视频放入 `images/` 目录（已在 HTML 中引用）。
3. 直接用浏览器打开 `index.html` 即可预览；推荐用轻量服务器：

   ```bash
   # 三选一
   npx serve .
   npx http-server -p 8080
   python3 -m http.server 8080
   ```
4. 访问 `http://localhost:8080`

---

## 部署（GitHub Pages）

1. 将代码推送到 GitHub 仓库的 `main` 分支（根目录有 `index.html`）；
2. 进入 **Settings → Pages**，选择 **Deploy from a branch**（`main / root`）；
3. 等待数十秒，GitHub 会生成站点 URL。

---

## 可自定义项

* **主题色**：在 `<style>` 的 `:root` 里调整 `--primary / --primary-light` 等变量。
* **中英文本**：页面中 `.zh / .en` 两套文本并存，按钮 `toggleLanguage()` 切换。
* **邮件弹窗**：在 Email 弹窗列表区增加或删除邮箱；复制按钮走 Clipboard API。
* **微信弹窗**：替换 `images/wechat_QR.jpg` 与账号文案（`data-id="..."`）。
* **小红书/GitHub/LinkedIn**：在 Contact 区更新外链与图标。

---

## 可访问性与性能

* **可访问性**：模态使用 `aria-modal / aria-labelledby`，支持遮罩点击与 `ESC` 关闭；图像 `alt` 与可聚焦控件完备。
* **性能**：

  * Hero 视频使用 `mp4/webm + poster`，建议 720p/24fps；
  * 图片支持 `loading="lazy"`（适用于 Projects/Insights 区）；
  * 无第三方运行时，静态资源易缓存。
* **移动端**：按钮由并排改纵排；字号与行距增大；卡片单列显示。

---

## 我在这个作品集中展现的能力

* **解决方案落地**：将 dHCI/GreenLake/VMware 等技术方案转换为 TCO、SLA 等可决策语言；
* **产品与运营**：A/B 验证、KPI 看板、公私域联动与轻量 CRM；
* **数据表达**：用流程图/架构图/指标把“为什么值得做”讲清楚；
* **前端呈现**：用简单可维护的方式把信息组织清楚（无框架、可读性强）；
* **内容制作**：AI 数字人视频 + 项目复盘文字，让信息更直观。

---

## 后续计划（Roadmap）

* 抽离样式与脚本为 `styles.css / main.js`，减少 `index.html` 体积；
* 将项目卡文案抽成 JSON，提供轻量渲染逻辑；
* 接入表单服务（Formspree / Netlify Forms）实现真实留言；
* 增加 Project Detail 页面（Markdown 转静态渲染）；
* 简单埋点（PV / 点击量），不采集个人隐私。

---

## 联系方式（Contact）

* **邮箱**：`cmh001116@163.com` / `cmh001116@outlook.com`（站内弹窗支持复制）
* **GitHub**：[https://github.com/CheMiui](https://github.com/CheMiui)
* **LinkedIn**：站内按钮
* **小红书**：站内按钮（直达主页）

> 如需 PDF 版作品集或项目讲述稿，请邮件联系。
