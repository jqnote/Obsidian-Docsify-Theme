# Docsify Theme for Obsidian

一个受 Docsify 启发的 Obsidian 主题，采用清新的绿色配色方案，提供优雅的阅读和写作体验。

## 主题特色

### 🎨 配色方案
- **主题色**: `#42b983` - 清新的绿色，带来舒适的视觉体验
- **协调配色**: 基于主题色构建的完整配色体系，包括深色、浅色变体
- **高对比度**: 优化的文本颜色，确保良好的可读性

### ✨ 主要特性
- **嵌入字体**: 内置 Source Sans Pro 和 Roboto Mono 字体，无需外部加载
- **优化的 Metadata**: 美观的元数据属性显示，标签样式优化
- **代码高亮**: 协调的代码块配色，支持语法高亮
- **响应式设计**: 适配不同屏幕尺寸
- **平滑过渡**: 丰富的动画效果，提升交互体验

### 📝 样式优化
- 清晰的标题层级
- 优雅的引用块样式
- 优化的表格显示
- 美观的链接样式
- 协调的滚动条样式

## 安装

### 从 Obsidian 主题商店安装
1. 打开 Obsidian 设置
2. 进入「外观」→「主题」
3. 点击「浏览」按钮
4. 搜索 "Docsify"
5. 点击「安装」并「启用」

### 手动安装
1. 下载 `theme.css` 和 `manifest.json` 文件
2. 将文件放入你的 Obsidian 库的 `.obsidian/themes/Docsify/` 目录
3. 在 Obsidian 设置中启用主题

## 配色变量

主题使用 CSS 变量，方便自定义：

```css
/* 主题色 */
--theme-color: #42b983;
--theme-color-dark: #359a6f;
--theme-color-light: #5fc99a;
--theme-color-lighter: #e8f5ef;

/* 文本颜色 */
--text-color: #2c3e50;
--text-color-muted: #7a8a9a;

/* 背景颜色 */
--bg-color: #ffffff;
--bg-color-secondary: #f8faf9;
--bg-color-accent: #e8f5ef;
```

## 截图

> 提示：添加主题截图到仓库根目录，命名为 `screenshot.png`（推荐尺寸：512x288，16:9 比例）

## 版本历史

### 1.0.0
- 初始版本
- 基于 #42b983 的配色方案
- 嵌入字体支持
- 优化的 metadata 样式
- 完整的主题变量系统

## 开发

### 本地开发
1. 克隆仓库
2. 修改 `theme.css` 文件
3. 在 Obsidian 中重新加载主题查看效果

### 贡献
欢迎提交 Issue 和 Pull Request！

## 许可证

MIT License

## 作者

**jqnote**
- Website: [https://jqnote.com](https://jqnote.com)

---

## 发布说明

### 添加主题截图

在仓库根目录添加主题截图，命名为 `screenshot.png`。截图应为 16:9 比例，推荐尺寸为 512x288。

### 提交到主题商店

要将主题添加到 Obsidian 主题商店，需要向 [`obsidianmd/obsidian-releases`](https://github.com/obsidianmd/obsidian-releases#community-theme) 提交 Pull Request。

## 版本发布

### 首次发布 (1.0.0)

1. 在仓库中点击 "Releases"
2. 点击 "Draft a new Release"
3. 填写发布信息：
   - **Tag**: 输入版本号（如 `1.0.0`）
   - **Release Title**: 版本号
   - **Description**: 更新说明
   - **Files**: 上传 `manifest.json` 和 `theme.css` 文件
4. 点击 "Publish Release"
5. 确保 `versions.json` 配置正确：
   ```json
   {
     "1.0.0": "1.0.0"
   }
   ```

### 发布新版本

发布新版本的步骤与首次发布相同。发布后，更新 `versions.json` 文件：

```json
{
  "1.0.0": "1.0.0",
  "1.0.1": "1.0.0"
}
```

版本号作为键，值为该主题版本兼容的最低 Obsidian 版本。
