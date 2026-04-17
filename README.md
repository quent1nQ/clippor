# Clippor

Clippor 的官网静态页面项目，用于展示产品定位与主视觉。

## 文件结构

- `index.html`：首页内容
- `styles.css`：页面样式
- `assets/`：图片与图标资源

## 本地预览

这是一个纯静态站点，不需要构建。

可以直接打开 `index.html`，或者在项目目录启动一个静态文件服务，例如：

```bash
python3 -m http.server 8000
```

然后访问 `http://localhost:8000`。

## 部署

将仓库根目录作为静态站点目录发布即可，当前线上域名为：

- `http://clippor.quentinqi.cn`
