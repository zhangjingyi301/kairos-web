# Kairos Mobile Web · V1.0

移动端 Kairos World Model 展示原型交付包。

## 预览

直接双击 `index.html`，或在目录内启动静态服务器：

```bash
python3 -m http.server 8000
```

然后打开 `http://localhost:8000`。

推荐使用最新版 Chrome、Safari 或 Edge，并以手机宽度预览（设计基准：390 × 844）。

## 已包含

- 明亮极简、紫色强调的移动优先页面
- 中英文切换与语言偏好记忆
- Latest 自动轮播、暂停、滑动和减少动态效果支持
- Demo 分类、详情弹层、分享/复制入口
- 菜单抽屉、页脚折叠、回到顶部
- GitHub、论文、Hugging Face、ModelScope 外链
- 无 JavaScript 时的静态内容降级

## 当前占位与发布前事项

- Demo 视频、封面和字幕尚未提供，页面使用 `Coming soon / 即将上线` 占位。
- `contact@kairos.ai` 是原型占位邮箱，发布前必须替换为团队确认的公开邮箱。
- 当前 Logo 为文字版；正式发布建议替换为官方透明 KAIROS Logo。
- 评测数字来源于 Kairos GitHub 公开信息（截至 2026-08），发布前请复核口径。
- 本交付是纯前端静态原型，不包含后台、统计、账号、表单或在线推理。

## 目录

- `index.html`：可直接打开的完整原型
- `design-spec.md`：视觉、内容、交互和验收规格
- `preview/homepage-mobile.png`：手机端首页预览
- `preview/RECORDING-TODO.md`：交互录屏脚本和输出要求；正式录屏完成后补充 `interaction-demo.mp4`
- `DELIVERY-CHECKLIST.md`：已完成项与正式发布前待办

## 版本

V1.0 · 2026-08-21
