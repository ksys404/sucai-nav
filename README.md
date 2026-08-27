# Codyhome · 免费可商用素材导航

一个单文件即可使用的素材收集导航页,收录 **18 大类、220+ 免费可商用站点**:

图片 · 视频 · BGM · 游戏 · 贴图纹理 · 动态素材 · 游戏角色 · UI 参考 · 图标 · 字体 · 设计工具 · 电子书 · 教育备课 · Skill 技能 · 语音配音 · 白噪音 · 音乐直链 · 像素素材

## 使用方式

- 直接双击 `index.html` 用浏览器打开即可,无需安装、无需联网依赖。
- 支持:搜索、分类筛选、⭐ 收藏、📝 备注、💾 导出 / 📥 导入备份。

## 数据说明

- 收藏与备注保存在**浏览器的 localStorage**(本机、本浏览器),各人各存各的,互不影响。
- 换设备或换打开方式时,用右上角「💾 导出」备份,再到新位置「📥 导入」。

## 如何添加新站点

用任意文本编辑器打开 `index.html`,找到 `SITES` 数组,照着格式加一行即可:

```js
{ cat:'image', name:'站点名', url:'https://...', hot:true,
  desc:'简介', license:'免费商用' },
```

字段说明:

- `cat`: 分类,取值 `image` / `video` / `audio` / `game` / `texture` / `motion` / `character` / `ui` / `icon` / `font` / `tool` / `book` / `edu` / `skill` / `voice` / `noise` / `direct` / `pixel`
- `name` 名称、`url` 网址、`desc` 简介
- `license` 授权(标注「需署名」的记得注明作者)
- `hot`: 可选,设为 `true` 显示「推荐」徽标

## 部署到 GitHub Pages(可选,让朋友直接点链接访问)

1. 仓库 `Settings → Pages → Branch: main / root → Save`
2. 稍等约 1 分钟,访问 `https://<你的用户名>.github.io/sucai-nav/`
