# Codyhome · 免费可商用素材导航

一个单文件即可使用的素材收集导航页,收录 **33 大类、390+ 站点**:

本次新增 **工业 AI / 工业前端设计参考** 分类,用于云湃智算等工业智能、算力基础设施、可信决策和企业级 B2B 网站的视觉研究。收录 Palantir、Cognite、NVIDIA Enterprise、Siemens、Schneider Electric、Rockwell Automation、CoreWeave、LandingAI、Augury、Anthropic、OpenAI、Google Cloud AI、Microsoft Azure AI 等参考网站,并为每个站点补充了风格特征和适用场景。

另有 **闹钟 / 时间 / 睡眠** 分类,收录计时器、倒计时、睡眠追踪和世界时区等设计参考,以及 FlipClock.js、ClockPicker、Luxon、dayjs 等可直接使用的 CSS/HTML 时钟组件与日期时间库。

图片 · 壁纸 / 背景 · 手机壁纸 · 视频 · BGM · 游戏 · 贴图纹理 · 动态素材 · 游戏角色 · 动漫立绘 · 动漫头像 · UI 参考 · 开屏 / 交互动效 · HTML / CSS 源码 · UI 组件代码 · 图标 · 字体 · 设计工具 · 剪辑 / 转场动效 · 电子书 · 教育备课 · 在线接单 / 远程工作 · Skill 技能 · MCP 合集 · 提示词库 · AI 工具站 · 语音配音 · 白噪音 · 音乐直链 · 像素素材 · 海洋专题

## 使用方式

- 直接双击 `index.html` 用浏览器打开即可,无需安装、无需联网依赖。
- 支持:搜索、分类筛选、收藏、备注、导出 / 导入备份。

## 数据说明

- 收藏与备注保存在**浏览器的 localStorage**(本机、本浏览器),各人各存各的,互不影响。
- 换设备或换打开方式时,用右上角「导出」备份,再到新位置「导入」。

## 如何添加新站点

用任意文本编辑器打开 `index.html`,找到 `SITES` 数组,照着格式加一行即可:

```js
{ cat:'image', name:'站点名', url:'https://...', hot:true,
  desc:'简介', license:'免费商用' },
```

字段说明:

- `cat`: 分类,取值 `image` / `wallpaper` / `mwall` / `video` / `audio` / `game` / `texture` / `motion` / `character` / `anime` / `avatar` / `ui` / `industrial` / `uimotion` / `htmlcss` / `component` / `clock` / `icon` / `font` / `tool` / `edit` / `book` / `edu` / `freelance` / `skill` / `mcp` / `prompt` / `aitool` / `voice` / `noise` / `direct` / `pixel` / `ocean`
- `name` 名称、`url` 网址、`desc` 简介
- `license` 授权(标注「需署名」的记得注明作者)
- `hot`: 可选,设为 `true` 显示「推荐」徽标

## 部署到 GitHub Pages(可选,让朋友直接点链接访问)

1. 仓库 `Settings → Pages → Branch: main / root → Save`
2. 稍等约 1 分钟,访问 `https://<你的用户名>.github.io/sucai-nav/`
