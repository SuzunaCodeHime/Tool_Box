# Tool Box 🐧

浏览器端工具集，纯前端实现，无需后端，开箱即用。

## 特点

- 纯前端，所有工具在浏览器本地运行
- 无需服务器，可直接用浏览器打开
- 深色主题，响应式设计
- 大部分工具无外部依赖

## 工具列表

| 工具 | 说明 | 依赖 |
|------|------|------|
| 二维码生成 | 文本 / URL 转二维码 | qrcode.js |
| 文本统计 | 字数 / 字符 / 行数 / 阅读时间实时统计 | 无 |
| 条形码生成 | Code128 / EAN-13 / EAN-8 / UPC-A，支持下载 PNG | 无 |
| 照片信息查看 | EXIF / IPTC / XMP 元数据解析，GPS 定位，导出 JSON | exifr |
| 简繁转换 | 简体 ↔ 繁体实时转换 | OpenCC |
| 时钟 | 模拟时钟与数字时钟显示 | 无 |

## 使用

直接用浏览器打开 `index.html`，或部署到任意静态服务器：

- **GitHub Pages**：Settings → Pages → 选择分支
- **Vercel**：导入仓库，自动检测
- **Netlify**：拖拽文件夹上传

## 项目结构

```
Linux/
├── index.html          # 主页
├── QRCode/             # 二维码生成
├── text-stats/         # 文本统计
├── barcode/            # 条形码生成
├── exif-viewer/        # 照片信息查看
├── zh-convert/         # 简繁转换
└── clock/              # 时钟
```

## License

MIT
