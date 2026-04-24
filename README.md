<p align="center">
  <img src="pic/super%20arxiv.png" alt="Super arXiv logo" width="108" />
</p>

<h1 align="center">Super arXiv</h1>

<p align="center">
  <b>中文</b> | <a href="README_EN.md">English</a>
</p>

<p align="center">
  面向 <code>arxiv.org</code> 的效率插件，帮你更快完成论文检索、筛选、下载与收藏管理。
</p>

<p align="center">
  <a href="https://chromewebstore.google.com/detail/super-arxiv/emjofeihemfkkooiabkgnfocghkmeabk">
    <img src="https://img.shields.io/badge/Chrome-Available-4285F4?logo=googlechrome&logoColor=white" alt="Chrome Available" />
  </a>
  <img src="https://img.shields.io/badge/Edge-In%20Review-0078D4?logo=microsoftedge&logoColor=white" alt="Edge In Review" />
  <img src="https://img.shields.io/badge/arXiv-Productivity-b31b1b?logo=arxiv&logoColor=white" alt="arXiv Productivity" />
  <img src="https://img.shields.io/badge/Language-ZH%20%2F%20EN-orange" alt="ZH / EN" />
  <a href="https://awesome.re">
    <img src="https://awesome.re/badge.svg" alt="Awesome" />
  </a>
</p>

<p align="center">
  <a href="https://chromewebstore.google.com/detail/super-arxiv/emjofeihemfkkooiabkgnfocghkmeabk">
    <img src="pic/chrome.png" alt="Chrome Logo" width="48" />
  </a>
  <img src="pic/edge.png" alt="Edge Logo" width="48" />
</p>

<p align="center">
  <sub>Edge 版本正在审核中，敬请期待。</sub>
</p>

![Super arXiv 整体预览](pic/overview.png)

## ✨ 为什么选择 Super arXiv？

- 📌 在 arXiv 摘要页直接显示增强工具栏，减少来回切换页面的成本。
- 🔎 一键跳转 `Google Scholar`、`Hugging Face Papers`、`GitHub`，快速补齐论文上下文。
- 🕒 展示投稿版本时间线，帮助你迅速了解论文迭代历史。
- 📚 内置收藏夹、子文件夹、批量下载和笔记能力，便于持续整理文献。
- 💾 下载 PDF 时自动整理文件名，更适合本地归档。
- 🔐 收藏与设置保存在浏览器本地，开箱即用。

## 🚀 快速开始

1. 前往 [Chrome Web Store 安装 Super arXiv](https://chromewebstore.google.com/detail/super-arxiv/emjofeihemfkkooiabkgnfocghkmeabk)
2. 打开任意 arXiv 摘要页，例如 `https://arxiv.org/abs/2401.01234`
3. 在页面标题区域使用 `Super arXiv` 工具栏
4. 首次使用建议先打开 `Settings`，按你的习惯调整显示组件

## 🧩 核心能力

### 论文页增强

- `Google Scholar`：快速查看相关工作与被引情况
- `Citations`：显示引用数，需在设置页手动开启
- `Hugging Face Papers`：如果论文已被收录，可一键跳转
- `GitHub`：自动聚合论文相关代码链接
- `Download PDF`：一键下载并自动整理文件名
- `Submission timeline`：查看论文版本变化历史
- `Affiliations`：识别作者单位信息
- `Refresh`：手动刷新引用数、单位等扩展信息

### 收藏与管理

- 收藏/取消收藏当前论文
- 新建、重命名、删除、移动文件夹与子文件夹
- 批量下载 PDF（ZIP）
- 批量移除收藏
- 记录个人笔记（Note）
- 导出 Excel，方便整理、复盘和分享

## 🖼️ 功能预览

### 🔎 Google Scholar

打开当前论文在 Scholar 的检索结果页，方便快速查看相关工作和被引情况。

![Google Scholar 功能截图](pic/scholar.png)

### 📈 Citations（可选）

显示引用数信息，首次使用需前往设置页面开启。若出现 `-` 或暂未显示，通常与网络环境或上游限制有关，可稍后重试。

![Citations 功能截图](pic/cite.png)

### 🤗 Hugging Face

跳转到对应的 Hugging Face Papers 页面；若该论文暂未被收录，则不会显示有效跳转结果。

![Hugging Face 功能截图](pic/hf.png)

### 🧑‍💻 GitHub

自动聚合论文相关代码链接；如果没有可用仓库，按钮会保持不可点击状态。

![工具栏整体截图（含 GitHub 入口）](pic/overview.png)

### ⬇️ Download PDF

下载当前论文 PDF，并自动整理为更易管理的文件名（通常是论文标题）。

![Download PDF 功能截图](pic/download.png)

### 🕒 Submission timeline

展示论文投稿版本时间线，帮助你快速了解版本变更历史。

![Submission timeline 功能截图](pic/timeline.png)

### 🏫 Affiliations

显示作者单位信息，帮助快速判断研究背景与机构来源。

![Affiliations 功能截图](pic/affiliation.png)

## 📚 收藏夹（Bookmarks）

收藏夹支持从「记录」到「导出」的一整套管理流程，适合长期积累和系统化整理文献。

### 🗂️ 子文件夹管理

支持新建、重命名、删除和移动子文件夹，方便按主题、项目或研究方向组织收藏。

![子文件夹管理截图](pic/subfolder.png)

### 📦 批量操作

支持批量下载、批量移除等操作，显著提升整理效率。

![批量操作截图](pic/batch.png)

### 📝 笔记功能

可为论文添加个人备注，方便后续回顾、复盘与二次筛选。

![笔记功能截图](pic/note.png)

## ⚙️ 设置说明

在 `Settings` 中你可以：

- 控制工具栏中各功能是否显示
- 开启或关闭 `Citations`
- 选择界面语言（中文 / 英文）

## 🔐 隐私说明

- 插件以本地使用为主，收藏和设置等信息均保存在浏览器本地。
- 所有信息处理尽可能在你的本地完成，不要求账号登录，也不需要额外配置。

## ❓ 常见问题

<details>
<summary><strong>为什么 Citations 没有数值？</strong></summary>

该功能受网络环境和上游页面状态影响，偶尔会出现暂时不可用的情况，稍后重试通常即可恢复。

</details>

<details>
<summary><strong>为什么 GitHub 按钮不能点？</strong></summary>

当前论文未检测到可用的代码仓库链接，因此按钮会保持不可点击状态。

</details>

<details>
<summary><strong>为什么有时作者单位信息为空？</strong></summary>

单位信息依赖论文正文内容本身。部分论文的格式或写法会影响识别效果；如果你发现无法识别的论文，欢迎反馈，我们会持续改进支持范围。

</details>

## 💌 支持与反馈

如果你有建议、需求或发现了 bug，欢迎通过以下方式联系我们：

- 邮件：`dnarso@163.com`
- 问卷反馈：[点击填写反馈问卷](https://v.wjx.cn/vm/e3s3Bs9.aspx#)

如果这款插件对你有帮助，也欢迎分享给更多小伙伴，并在 GitHub 仓库点亮 `Watching` 和 `Star`，第一时间获取更新动态。你的每一份支持，都是我们持续迭代与维护的最大动力！

如果它确实帮你节省了不少查论文的时间，也欢迎请开发者喝一杯咖啡，或者让开发者买得起更多 token。谢谢支持 ❤️

<table>
  <tr>
    <td align="center">
      <strong>Ko-fi</strong><br />
      <img src="pic/kofi.png" alt="Ko-fi payment QR code" width="260" height="260" />
    </td>
    <td align="center">
      <strong>Alipay</strong><br />
      <img src="pic/alipay.jpg" alt="Alipay payment QR code" width="260" height="260" />
    </td>
  </tr>
</table>