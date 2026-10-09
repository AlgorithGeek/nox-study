# Nox Study

面向中文学习笔记的 Typora 主题，采用适中的阅读宽度、暖色表格、中性炭灰代码块和清晰的标题层级。

打开示例笔记 [从请求到响应](examples/从请求到响应.md)，可查看正文、标题、表格、代码、引用和任务列表的效果。

## 文件结构

```text
nox-study/
├── nox-study.css          # 主题样式与配置
├── nox-study/             # 字体资源，安装时与 CSS 保持同级
│   ├── font.css
│   ├── JetBrainsMono-*.woff2
│   ├── OFL.txt           # 字体版权与许可证
│   └── FONT-SOURCES.md   # 字体版本、官方来源与校验值
├── LICENSE
└── README.md
```

## 安装

1. 在 Typora 的外观设置中打开主题文件夹。
2. 将本项目根目录的 `nox-study.css` 和 `nox-study/` 文件夹一起复制进去。
3. 重启 Typora，在主题菜单中选择 **Nox Study**。

长代码横向滚动需要关闭 Typora 的代码块自动换行设置；该设置由 Typora 管理，不会随 CSS 自动切换。短代码不显示横向滚动条。PDF 打印样式仍会对长代码换行。

## 本地维护

以这个目录中的文件作为源码。修改并验证后，再复制到 Typora 主题文件夹应用。项目不需要构建工具或安装依赖。

主要字体、字号、行距和颜色集中在 `nox-study.css` 开头的 `:root` 中；正文宽度位于 `#write` 规则中。保留 `nox-study.css` 与字体目录的相对位置，避免资源加载失败。

当前版本从正在使用的主题复制，未包含历史备份、临时测试文件和导出产物。

## 验证范围

已在 macOS 的 Typora 1.14.10 中使用和检查。其他操作系统、完整 PDF 分页和独立 HTML 离线字体仍需发布前验证。

## 许可

CSS 中保留了原有版权与 MIT 许可声明，完整文本见 `LICENSE`。

附带的四个 JetBrains Mono 字体为官方 2.242 版本，适用 SIL Open Font License 1.1，不由本项目的 MIT 许可证重新授权。完整字体版权与许可见 [nox-study/OFL.txt](nox-study/OFL.txt)，版本、官方来源和逐文件核验结果见 [字体来源记录](nox-study/FONT-SOURCES.md)。分发时请保留字体目录中的许可证。
