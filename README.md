# Kairos Web

Kairos World Model 团队展示网站，纯前端静态实现。

## 在线预览

https://zhangjingyi301.github.io/kairos-web/

当前使用 GitHub Pages 默认地址。

## 本地运行

```bash
python3 -m http.server 8000
```

访问 <http://localhost:8000>。项目无需安装依赖或构建，也可以直接打开 `index.html`。

## 主要功能

- 响应式 mobile-first 布局
- `< 60rem` 移动端 hamburger 菜单，`≥ 60rem` 桌面横向导航
- Latest 轮播、Demo 分类、视频展示与详情弹层
- 基础无障碍、键盘交互与无 JavaScript 降级
- GitHub、arXiv、Hugging Face、ModelScope 外链

## 项目结构

```text
index.html    网站主体、样式与交互
media/        图片、图标和 Demo 视频
README.md     项目说明
```

## 响应式检查

页面使用流式 gutter、响应式容器和卡片布局，建议检查：

```text
320px · 390px · 768px · 1024px · 1440px · 1920px
```

移动菜单支持打开、关闭、遮罩、Escape 和点击导航项后自动关闭。

## 内容与媒体

- 页面文案和结构：`index.html`
- Demo 视频：`media/demos/`
- 替换视频时可保持原文件名，避免修改 HTML 路径
- 上传前请压缩视频；GitHub 普通 Git push 不支持单个超过 100 MB 的文件

## 发布检查

- [ ] 手机、平板和桌面布局正常
- [ ] 无非预期横向滚动
- [ ] Hamburger 菜单和锚点跳转正常
- [ ] 视频、图片、favicon 和外链正常
- [ ] 联系方式与公开数据已确认
- [ ] GitHub Pages 部署成功

网站通过 GitHub Pages 从 `main` 分支部署。

## 当前限制

纯前端静态站点，不包含后台、账号、数据库、评论、支付或在线推理。

## 版本

V1.0 · 2026-08-26
