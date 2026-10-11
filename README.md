# gh-pages — 隐私政策托管源

这个目录里的文件**整体推到 GitHub 公开仓库的根目录**，用来拿到商店要求的隐私政策 URL。

```
gh-pages/
├─ index.html    ← 隐私政策页面（GitHub Pages 的入口文件，必须叫这个名字）
└─ .nojekyll     ← 告诉 GitHub 别跑 Jekyll 构建，直接原样发布
```

发布后地址形如：`https://<你的用户名>.github.io/<仓库名>/`

详细步骤见上一级 `README.md` 的「第 1 步」。

> ⚠️ 上传前记得把 `index.html` 里的 `[待填写你的联系邮箱]` 换成真实邮箱。
