# 台湾2024年大选选情分析

这是一个基于Web的台湾2024年大选数据可视化分析平台，使用D3.js和TopoJSON展示选举结果和选情分析。

## 功能特点

- 📊 台湾全岛选举地图可视化
- 🗺️ 各县市选情详细分析
- 📈 选区胜选排名统计
- 🔄 罢免数据对比分析
- 📱 响应式设计，支持移动端访问

## 技术栈

- HTML5 / CSS3
- JavaScript (ES6+)
- D3.js v7 - 数据可视化库
- TopoJSON - 地理数据格式

## 文件结构

```
taiwan-election-2024/
├── index.html              # 主页面
├── styles.css              # 样式文件
├── taiwan-map.js           # 台湾地图渲染
├── district-map.js         # 选区地图
├── election-data.js        # 选举数据
├── winner-ranking.js       # 胜选排名
├── district-winner-ranking.js  # 选区胜选排名
├── recall-framework.js     # 罢免数据分析框架
├── district-config.js      # 选区配置
├── counties.json           # 县市地理数据
└── *-real-data.js          # 各县市真实选举数据
└── *-recall-data.js        # 各县市罢免数据
```

## 使用方法

1. 直接在浏览器中打开 `index.html` 文件
2. 或使用本地服务器（推荐）：
   ```bash
   # 使用Python
   python -m http.server 8000
   
   # 使用Node.js
   npx http-server
   ```
3. 访问 `http://localhost:8000`

## 数据来源

选举数据来源于台湾中选会官方数据。

## 浏览器支持

- Chrome (推荐)
- Firefox
- Safari
- Edge

## 许可证

本项目仅供学习和研究使用。

