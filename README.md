# 南通针织供应商考察地图

🧶 上海闵行 → 南通如东/海安 供应商实地考察互动地图

**在线查看：** https://waynejapan.github.io/supplier-field-scout-map/

## 覆盖供应商

### Day 1 — 如东集群（周六）
1. 🔴 **南通妍阳工艺品** — 如东掘港（A级，最大优先）
2. 🔴 **南通晨派针织** — 如东丰利（B级，小单灵活）
3. 🟡 **南通健辉工艺服饰** — 如东（A级，Alibaba金品）
4. ⚪ **南通晶漫服饰** — 如东马塘（C级，备选）

### Day 2 — 海安+返程（周日）
5. 🔴 **南通七巧手编结** — 海安南莫镇（B级，产能清晰）

## 地图功能

- **彩色标记** — A级红色🔴 / B级黄色🟡 / C级蓝色🔵 / 起点绿色🟢
- **虚线路线** — 两日考察路线
- **编号标记** — 建议考察顺序
- **点击标记** — 弹出详情面板（含电话、邮箱、网站、高德导航链接）
- **PWA支持** — 可添加到手机主屏幕离线查看

## 技术栈

- Leaflet + OpenStreetMap（免费，无需API密钥）
- 自包含HTML，单文件部署
- GitHub Pages托管

## 文件说明

| 文件 | 说明 |
|------|------|
| `index.html` | 新Nantong地图（默认页） |
| `nantong-map.html` | Nantong地图（备份） |
| `field-scout-map.html` | 旧版OpenClaw地图（AMap版，需API Key） |
| `manifest.json` | PWA配置 |
| `sw.js` | Service Worker |
| `icons/` | PWA图标 |

## 本地开发

```bash
# 更新地图数据
# 1. 编辑 Data 部分
# 2. 重新生成 GeoJSON
# 3. 重新生成 HTML
```
