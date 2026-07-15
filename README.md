# 石子彧的个人网站

这是我的个人主页，用于记录本科阶段的学习经历、竞赛荣誉与科研实践。

[访问网站](https://yukiko-shi.github.io/) · [GitHub 主页](https://github.com/yukiko-shi)

## 网站内容

- 个人简介与专业背景
- 学年成绩、绩点排名和综合测评情况
- 竞赛、奖学金及其他荣誉记录
- 部分获奖证书与证明材料
- 生物信息学开源项目 [MutCleaner](https://github.com/xulab-research/MutCleaner)
- 联系方式

## 技术实现

网站采用原生前端技术构建，并通过 GitHub Pages 部署：

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts
- GitHub Pages

页面支持响应式布局，并对 `prefers-reduced-motion` 做了适配，以改善不同设备和使用偏好下的浏览体验。

## 仓库结构

```text
.
├── index.html          # 网站页面、样式与交互逻辑
├── portrait.jpg        # 个人照片
├── proofs/             # 获奖证书与证明材料
└── README.md
```

## 本地预览

克隆仓库后，在项目根目录启动一个本地静态文件服务器：

```bash
python -m http.server 8000
```

随后在浏览器中访问 <http://localhost:8000>。

## 更新说明

- 页面内容、样式与交互逻辑集中在 `index.html` 中。
- 替换个人照片时，请保持文件名为 `portrait.jpg`，或同步修改页面中的图片路径。
- 新增证明材料时，将文件放入 `proofs/`，并在对应荣誉条目中更新链接。
- 新增或删除荣誉条目后，需要同步调整 `data-count`，确保页面中的荣誉总数正确。
- 推送到 `main` 分支后，GitHub Pages 会自动更新网站。

## 联系方式

- 邮箱：202421090428@stu.zuel.edu.cn
- GitHub：[@yukiko-shi](https://github.com/yukiko-shi)
