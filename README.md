# Super arXiv

Super arXiv 是一个面向 `arxiv.org` 的效率插件，帮助你更快完成论文检索、筛选、下载和收藏管理。

Chrome Edge

## 安装

Chrome 版本已上线：

- [Chrome Web Store - Super arXiv](https://chromewebstore.google.com/detail/super-arxiv/emjofeihemfkkooiabkgnfocghkmeabk)

Edge 版本正在审核中，即将上线。

## 核心能力

- 在 arXiv 摘要页显示增强工具栏
- 一键跳转 `Google Scholar`、`Hugging Face Papers`、`GitHub`
- 显示投稿版本时间线（`Submission timeline`）
- 可选显示引用数（`Citations`）
- 显示作者单位信息（`Affiliations`，尽力而为）
- 一键下载 PDF，并自动整理文件名
- 内置收藏夹（`Bookmarks`）用于论文归档与批量管理

## 快速使用

1. 打开任意 arXiv 摘要页（例如 `https://arxiv.org/abs/2401.01234`）
2. 页面标题区域会出现 `Super arXiv` 工具栏
3. 建议先打开 `Settings` 调整你需要显示的组件
4. 日常使用中最常见的三个动作：
  - 点击 `Download PDF` 下载论文
  - 点击星标收藏论文
  - 点击文件夹图标进入收藏夹管理

## 工具栏功能说明

### Google Scholar

- 打开该论文在 Scholar 的检索结果页，便于快速查看相关工作和被引情况。

### Citations（可选）

- 显示引用数信息，默认关闭。
- 开启后如果出现 `-` 或暂未显示，通常是网络环境或上游限制导致，可稍后重试。

### Hugging Face

- 跳转到对应的 Hugging Face Papers 页面（如果该论文有收录）。

### GitHub

- 自动聚合论文相关的代码链接。
- 当没有可用链接时，按钮会保持不可点击状态。

### Download PDF

- 下载当前论文 PDF。
- 文件名会自动整理为更易管理的形式（通常是论文标题）。

### Refresh

- 刷新当前论文的扩展信息（如引用数、单位等），适合在信息未更新时使用。

## 收藏夹（Bookmarks）

收藏夹支持“从记录到导出”的完整管理流程：

- 收藏/取消收藏当前论文
- 文件夹管理：新建、重命名、删除、移动
- 批量勾选后下载 PDF（ZIP）
- 批量移除收藏
- 记录个人笔记（Note）
- 导出 Excel，便于后续整理和复盘

## 设置说明

在 `Settings` 中你可以：

- 控制工具栏中各功能是否显示
- 开启/关闭 `Citations`
- 选择界面语言（中文/英文）

## 隐私说明

- 插件以本地使用为主，收藏和设置等信息保存在你的浏览器本地。
- 不会要求你提供账号，也不需要额外配置。

## 常见问题

### 为什么 Citations 没有数值？

- 该功能受网络环境和上游页面状态影响，偶尔会出现暂时不可用。

### 为什么 GitHub 按钮不能点？

- 当前论文未检测到可用的代码仓库链接。

### 为什么有时作者单位信息为空？

- 单位信息依赖论文内容本身，部分论文无法稳定识别。