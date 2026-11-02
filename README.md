# 拾径导航 (Shi Jing Nav)

> 简洁 · 极速 · 纯净的现代化网址导航与实用工具站。

在线访问地址：
- 🌐 **GitHub Pages 主站**：[https://zhangwei89.github.io/nav/](https://zhangwei89.github.io/nav/)
- ⚡ **国内极速镜像通道**：详见下方国内访问加速指南

---

## 🌟 核心特色与功能

1. **87+ 优质精选站点**：
   - 🌟 **综合推荐**：热榜、文摘、科技头条、精选资讯、理财等
   - ⚡ **常用服务**：Cloudflare、Vultr、NameSilo、周刊、网盘等
   - 🎓 **学术研究**：Sci-Hub、思谋学术、Z-Library、LibGen、谷歌学术等
   - 🛠️ **AI 与实用工具**：ChatGPT、Claude/Gemini/Grok、DeepSeek、秘塔搜索、Kimi等
   - 🎬 **影音娱乐**：豆瓣电影、IMDb、流媒体资源等
   - 📰 **全球资讯与新闻**：经济学人、FT中文网、路透、华尔街日报、BBC、卫报等

2. **多引擎聚合与站内秒级筛选**：
   - 支持 **站内秒搜**（输入关键词即时模糊高亮筛选全部卡片）
   - 一键切换至 **百度、Google、Bing、秘塔 AI、GitHub、开发者搜索、豆瓣、谷歌学术**
   - 快捷键支持：按 `/` 或 `Ctrl + K` 快速定位搜索框，按 `Esc` 一键清空

3. **专为国内网络环境深度优化**：
   - 杜绝外网阻塞加载：纯原生高品质单文件实现，零外部臃肿依赖
   - 智能 Favicon 优雅降级：当外部图标服务不可达时，毫秒级无缝自动切换为高颜值渐变首字徽标，绝无破图与白块

4. **个性化书签管理与本地备份**：
   - 支持直接在网页中点击「＋ 添加」自定义常用网站并分类，持久化保存在浏览器本地（LocalStorage）
   - 提供「备份与还原」功能，可一键导出完整 JSON 备份文件，在不同电脑或浏览器随时导入恢复

5. **现代审美与响应式体验**：
   - 支持一键切换 **浅色模式 / 暗黑夜间模式**（自动跟随系统偏好并记忆）
   - 桌面端左侧悬浮分类导航与智能滚动监听（ScrollSpy）
   - 移动端自适应横向滑条，全设备完美适配
   - 一键快捷复制网址，附带友好轻提示

---

## 🚀 国内访问与部署加速方案

### 方式一：直接访问 GitHub Pages
- 链接：[https://zhangwei89.github.io/nav/](https://zhangwei89.github.io/nav/)

### 方式二：Cloudflare 自定义域名加速（最推荐，国内访问极速稳定）
由于您在常用服务中已配置有 Cloudflare 和 NameSilo：
1. 登录 [Cloudflare 控制台](https://dash.cloudflare.com/)，进入 **Workers & Pages** -> **Create application** -> **Pages**。
2. 连接 GitHub 仓库 `zhangwei89/nav`，点击部署（无需任何构建命令，输出目录选根目录 `/`）。
3. 分配的 `*.pages.dev` 或绑定您在 NameSilo 的自有二级域名（例如 `nav.yourdomain.com`），国内无需任何梯子，全国全运营商高速直达！

### 方式三：本地离线单文件秒开
直接双击桌面上的 `导航.html`，无需网络连接即可本地极速秒开。
