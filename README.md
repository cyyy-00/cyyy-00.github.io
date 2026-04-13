# 机器人项目补充材料网站

这是一个可直接上传到 GitHub Pages 的静态网站版本。

## 文件说明
- `index.html`：主页
- `style.css`：样式文件
- `assets/`：建议存放图片、视频封面、简历 PDF 等资源

## 如何上传到 GitHub Pages
1. 新建一个 GitHub 仓库，例如：`yourname.github.io`
2. 上传 `index.html`、`style.css` 和 `assets/` 文件夹
3. 在仓库 Settings -> Pages 中启用 GitHub Pages
4. 稍等几分钟即可访问网站

## 你下一步需要替换的内容
1. 页面中的姓名、GitHub 链接、简历 PDF 链接
2. 三个项目右侧的媒体占位区域
3. 你自己的项目视频、图片、流程图

## 视频嵌入方法
### 方案 1：直接放 mp4
可以把视频放到 `assets/` 目录，然后在 HTML 中把占位区替换为：

```html
<video controls poster="assets/cover.jpg">
  <source src="assets/demo.mp4" type="video/mp4">
</video>
```

### 方案 2：跳转到 Bilibili / YouTube
把占位区替换成封面图 + 链接按钮即可。
