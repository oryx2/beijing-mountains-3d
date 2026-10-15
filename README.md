# 北京山川地形 · 3D 网页

## 打开方式

在本目录启动静态服务后用浏览器访问：

```bash
cd /workspace/beijing-terrain/web
python3 -m http.server 8080
# 浏览器打开 http://127.0.0.1:8080/
```

不要直接双击 `index.html`（浏览器会拦截本地 GLB 加载）。

## 文件

| 文件 | 说明 |
|------|------|
| `index.html` | Three.js 浏览页（标题「北京山川地形」、轨道相机、重置视角） |
| `beijing_mountains.glb` | 地形 + 部分河网（约 12.6 MB） |

## 操作

- 左键拖动：旋转
- 右键拖动：平移
- 滚轮：缩放
- 「重置视角」：回到初始机位
