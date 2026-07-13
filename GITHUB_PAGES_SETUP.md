# GitHub 仓库与 Pages 配置说明

本目录已经整理为可直接上传的静态作品集仓库。建议仓库名称使用：

```text
ternary-community-qingdao
```

发布后的默认地址为：

```text
https://patrick-loylee.github.io/ternary-community-qingdao/
```

## 1. 创建仓库

1. 登录 GitHub，选择 **New repository**。
2. Repository name 填写 `ternary-community-qingdao`。
3. Description 可填写：

   ```text
   Ternary Community - Xiliuzhuang Residential Planning Design, Qingdao
   ```

4. 选择 **Public**。
5. 不勾选自动生成 README、.gitignore 或 License，因为本目录已经包含这些文件。
6. 创建仓库。

## 2. 上传内容

将 `github-showcase` 目录中的全部内容上传到仓库根目录。上传完成后，仓库首页应直接显示本项目的 `README.md`。

需要保留的关键路径：

```text
index.html
README.md
assets/
docs/a3-residential-planning-portfolio.pdf
```

不要上传原始 PSD、DWG、SKP、AI、TIF、DOCX 或 PPTX 文件。它们体积较大，也不适合公开仓库；`.gitignore` 已经配置为自动排除这些类型。

## 3. 启用 GitHub Pages

1. 打开仓库的 **Settings**。
2. 在左侧选择 **Pages**。
3. 在 **Build and deployment** 中，将 Source 选择为 **Deploy from a branch**。
4. Branch 选择 `main`，文件夹选择 `/ (root)`。
5. 点击 **Save**。
6. 等待 GitHub 完成发布，通常几分钟后页面地址会显示在同一设置页。

## 4. 发布后检查

- 首页能否正常打开并显示社区鸟瞰。
- 导航能否跳转到总图、公共空间、住宅和展板部分。
- 四张 A1 高清图能否在新窗口打开。
- A3 成果册链接能否打开 16 页 PDF。
- 手机浏览时是否保持单列排版且文字可读。

## 5. 后续更新

如果只是替换图片或 PDF，并且文件名保持不变，通常无需修改 `index.html` 或 `README.md`。如果更改文件名或目录位置，必须同步修改网页和 README 中的相对链接。

建议每次更新后检查仓库中的 **Actions** 或 **Deployments** 状态，确认 Pages 已完成重新发布。
