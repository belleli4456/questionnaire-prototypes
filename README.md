# GitHub Pages 发布说明

这个目录已经整理好，可直接用于 GitHub Pages 发布。

## 文件说明

- `index.html`：统一入口页
- `ops-admin.html`：问卷调查-运营后台
- `miniapp.html`：问卷调查-小程序端

## 最快发布方式

1. 在 GitHub 上新建一个仓库，例如 `questionnaire-prototypes`
2. 把这个目录下的 3 个文件上传到仓库根目录
3. 打开仓库 `Settings`
4. 进入 `Pages`
5. 在 `Build and deployment` 中选择：
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - `Folder`: `/ (root)`
6. 保存后等待 1 到 3 分钟

## 发布后链接格式

假设你的 GitHub 用户名是 `yourname`，仓库名是 `questionnaire-prototypes`，则链接通常是：

- 入口页：`https://yourname.github.io/questionnaire-prototypes/`
- 运营后台：`https://yourname.github.io/questionnaire-prototypes/ops-admin.html`
- 小程序端：`https://yourname.github.io/questionnaire-prototypes/miniapp.html`

## 放到文档里的推荐写法

```md
- [问卷调查原型入口](https://yourname.github.io/questionnaire-prototypes/)
- [运营后台原型](https://yourname.github.io/questionnaire-prototypes/ops-admin.html)
- [小程序端原型](https://yourname.github.io/questionnaire-prototypes/miniapp.html)
```
