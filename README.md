# AI 破局拆解

> 杭州 AI 破局大会 19 场分享 · 道法术器 + 7 字段精华拆解

## 这是什么

把杭州 AI 破局大会 19 场（去重后）现场分享，按统一框架"**道法术器 + 7 字段**"拆解成可直接抄作业的结构化笔记，配 1 个静态站浏览。

## 7 字段

1. **嘉宾身份** —— 他是谁，凭什么讲
2. **真实结果** —— 跑出过什么
3. **关键数据** —— 可验证的数字
4. **核心故事** —— 最戳的那段
5. **方法框架** —— 道法术器
6. **工具清单** —— 能立刻用上的
7. **金句** —— 能复用的金句

## 在线访问

部署在 GitHub Pages：开启后访问 `https://siuserxiaowei.github.io/<repo>/`

## 本地预览

```bash
cd 这个目录
python3 -m http.server 8000
# 浏览器打开 http://localhost:8000
```

> 注意：直接双击 `index.html` 打开会因 CORS 限制无法 fetch markdown 文件，需要用 http server。

## 文件结构

```
.
├── index.html          # 首页（Hero + 19 张卡片 + 狗哥极致拆解）
├── detail.html         # 详情页（fetch markdown + 渲染）
├── posts/              # 19 篇 markdown 拆解
└── assets/             # 公众号二维码等图片
```

## 联系

- 微信：`siuserxiaowei`（备注「破局拆解」优先通过）
- 作者微信二维码：`assets/wechat-personal.jpg`
- 公众号二维码：`assets/qrcode.jpg`

---

由 **小伟** 制作 · 源稿来自 AI 破局俱乐部杭州大会现场录音整理
