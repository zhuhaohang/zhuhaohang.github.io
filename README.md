# Haohang Zhu's Homepage

这是我的个人学术主页，用于通过 GitHub Pages 展示个人简介、研究方向、项目经历、奖项与访问统计。

主页地址在部署后通常为：

```text
https://<your-github-username>.github.io/
```

## 页面内容

- 个人简介：Haohang Zhu / 朱浩航
- 教育经历：Shanghai Jiao Tong University、Beijing Institute of Technology
- 研究兴趣：AI4Ocean
- 项目经历：道路损伤评估、多传感器小目标检测
- 代表性奖项：北京市优秀毕业生、MathorCup 全国一等奖、挑战杯专项赛全国三等奖
- 访问统计：ClustrMaps

## 文件结构

```text
.
├── index.html    # 个人主页主体文件
├── 1.jpg         # 个人照片
└── README.md     # 项目说明
```

## 本地预览

这是一个纯静态网页，不需要安装依赖。可以直接在浏览器中打开：

```text
index.html
```

如果需要修改头像，请替换根目录下的 `1.jpg`，或在 `index.html` 中修改图片路径。

## 部署到 GitHub Pages

1. 创建或使用名为 `<your-github-username>.github.io` 的 GitHub 仓库。
2. 将 `index.html`、`1.jpg` 和 `README.md` 推送到仓库根目录。
3. 进入仓库的 `Settings` -> `Pages`。
4. Source 选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/root`。
6. 保存后等待 GitHub Pages 自动部署。

常用命令示例：

```bash
git add index.html 1.jpg README.md
git commit -m "Update personal homepage"
git push
```

## 关于源码可见性

GitHub Pages 发布的是静态网页。只要网页可以被访问，浏览器就必须下载 HTML、CSS 和图片资源，因此访问者可以通过浏览器查看页面源码。

如果希望仓库本身不可见，可以将仓库设置为 private；但最终公开展示的网页内容仍然无法完全隐藏。更稳妥的方式是只在公开仓库中放最终展示文件，不放草稿、私人材料、未公开论文、证件信息或敏感数据。

## License

This homepage is for personal academic use. Please do not reuse personal photos or biographical content without permission.
