# 竹白 (Zhubai)

一款为中文阅读优化的 Typora 主题，基于 GitHub 默认主题修改。

## 特点

- 基础字号 14px，适合中文阅读
- 字体栈优先使用系统中文字体（苹方、微软雅黑等）
- 柔和的背景色 `#fafafa`，减少长时间阅读的视觉疲劳
- 正文颜色 `#363636`，对比度适中不刺眼
- 段落间距加大，结构更清晰
- 引用块颜色加深，提升可读性
- 打印/导出 PDF 时自动切换为白色背景

## 安装

1. 打开 Typora → 偏好设置 → 外观 → 打开主题文件夹
2. 将 `zhubai.css` 复制到主题目录中
3. 重启 Typora，在主题菜单中选择 **Zhubai**

## 手动安装

```bash
cp zhubai.css ~/Library/Application\ Support/abnerworks.Typora/themes/
```

## 字号调整

如果觉得字号偏大或偏小，修改 `zhubai.css` 中的：

```css
html {
    font-size: 14px;
}
```

推荐范围：13px ~ 15px。

## 许可

MIT
