# 智能记事本

一个现代化的在线记事本应用，具有直观的用户界面和丰富的功能。

## 🌐 在线体验

**✅ 已部署到GitHub Pages！**  
访问地址：[https://ajkdfe2e2e.github.io/smart-notepad](https://ajkdfe2e2e.github.io/smart-notepad)

> 注意：如果页面还未能访问，请手动启用GitHub Pages：
> 1. 进入仓库 Settings → Pages
> 2. 在 "Source" 下选择 "Deploy from a branch"
> 3. 选择 "main" 分支和 "/ (root)" 文件夹
> 4. 点击 Save

## ✨ 特性

### 📝 核心功能
- **富文本编辑器** - 支持粗体、斜体、下划线、列表等格式
- **智能搜索** - 快速搜索笔记标题和内容
- **自动保存** - 每30秒自动保存，防止数据丢失
- **本地存储** - 数据存储在浏览器本地，无需登录

### 🎨 界面体验
- **现代化设计** - 简洁美观的用户界面
- **深色/浅色主题** - 支持主题切换，保护眼睛
- **响应式布局** - 完美适配桌面和移动设备
- **流畅动画** - 优雅的交互动画效果

### ⚡ 便捷操作
- **快捷键支持**
  - `Ctrl + S` - 保存当前笔记
  - `Ctrl + N` - 新建笔记
  - `Ctrl + F` - 打开搜索
  - `Esc` - 关闭搜索
- **一键导出** - 导出笔记为Markdown格式
- **字数统计** - 实时显示字数统计
- **删除确认** - 防止误删重要笔记

## 🚀 快速开始

### 方式一：在线使用（推荐）
直接访问GitHub Pages链接即可使用：
[https://ajkdfe2e2e.github.io/smart-notepad](https://ajkdfe2e2e.github.io/smart-notepad)

### 方式二：本地运行
1. 克隆仓库
```bash
git clone https://github.com/ajkdfe2e2e/smart-notepad.git
cd smart-notepad
```

2. 在浏览器中打开`index.html`文件

## 📱 使用说明

### 基本操作
1. **创建笔记** - 点击左侧"新建笔记"按钮
2. **编辑笔记** - 点击标题栏输入标题，在编辑区域输入内容
3. **保存笔记** - 自动保存或按`Ctrl+S`手动保存
4. **删除笔记** - 点击删除按钮并确认删除

### 高级功能
- **搜索笔记** - 点击搜索图标或按`Ctrl+F`
- **切换主题** - 点击右上角月亮/太阳图标
- **导出笔记** - 点击导出按钮下载Markdown文件
- **格式化文本** - 使用工具栏进行文本格式化

## 📸 预览截图

### 浅色主题
应用采用现代化的浅色主题设计，界面简洁清爽。

### 深色主题
支持深色主题，保护夜间使用者的眼睛。

### 移动端适配
完美适配移动设备，随时随地记录想法。

## 🛠️ 技术栈

- **HTML5** - 语义化标记
- **CSS3** - 现代样式和动画（CSS变量、Flexbox、Grid）
- **JavaScript (ES6+)** - 原生JavaScript，无框架依赖
- **Web APIs** - LocalStorage、Blob、URL、execCommand等

## 📋 功能特点

### 数据管理
- 所有数据存储在浏览器本地存储中
- 支持多篇笔记同时管理
- 自动保存和手动保存
- 数据导出功能（Markdown格式）

### 用户体验
- 直观的三栏布局设计
- 实时的字数统计
- 智能的日期显示（今天、昨天、几天前）
- 流畅的动画过渡

### 安全性
- 纯前端应用，数据不上传服务器
- 本地数据存储，保护隐私
- 删除操作二次确认

## 🔧 自定义配置

### 主题颜色
可在`styles.css`中的`:root`部分修改主题颜色：
```css
:root {
    --primary-color: #6366f1;    /* 主色调 */
    --success-color: #10b981;    /* 成功色 */
    --danger-color: #ef4444;     /* 危险色 */
}
```

### 自动保存间隔
在`script.js`中修改自动保存间隔：
```javascript
// 修改这个值来调整自动保存间隔（毫秒）
this.autoSaveInterval = setInterval(() => {
    if (this.isEditing) {
        this.saveCurrentNote();
    }
}, 30000); // 30秒
```

## 📊 浏览器兼容性

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ 移动浏览器（iOS Safari、Chrome Mobile等）

## 🤝 贡献

欢迎提交Issue和Pull Request！

### 开发流程
1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开Pull Request

### 贡献指南
- 保持代码风格一致
- 添加适当的注释
- 确保功能测试通过
- 更新相关文档

## 📄 许可证

本项目采用MIT许可证 - 查看[LICENSE](LICENSE)文件了解详情

## 🔮 未来规划

- [ ] 🌟 云端同步功能
- [ ] 🏷️ 笔记分类和标签系统
- [ ] 📷 图片上传和粘贴功能
- [ ] 👥 协作编辑功能
- [ ] 📋 笔记模板系统
- [ ] 🔍 全文搜索优化
- [ ] 📱 PWA支持（离线使用）
- [ ] 📤 数据导出更多格式（PDF、DOCX等）
- [ ] 🔔 提醒和日程功能
- [ ] 📊 数据统计和分析

## 📞 联系方式

如有问题或建议，请通过以下方式联系：
- 💬 提交Issue：[GitHub Issues](https://github.com/ajkdfe2e2e/smart-notepad/issues)
- 📧 发送邮件：2035325567@qq.com
- 🐦 社交媒体 倾覆

## 🙏 致谢

感谢以下开源项目和资源：
- [Font Awesome](https://fontawesome.com/) - 图标库
- [Inter Font](https://rsms.me/inter/) - 字体
- [GitHub Pages](https://pages.github.com/) - 托管服务

---

**⚡ 享受写作的乐趣！让思绪自由流淌** ✍️

<div align="center">
  <img src="https://img.shields.io/github/stars/ajkdfe2e2e/smart-notepad?style=social" alt="GitHub stars">
  <img src="https://img.shields.io/github/forks/ajkdfe2e2e/smart-notepad?style=social" alt="GitHub forks">
  <img src="https://img.shields.io/github/issues/ajkdfe2e2e/smart-notepad" alt="GitHub issues">
  <img src="https://img.shields.io/github/license/ajkdfe2e2e/smart-notepad" alt="License">
</div>
