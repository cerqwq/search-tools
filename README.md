# 🔍 Search Tools

AI搜索工具，支持搜索引擎配置、查询优化、索引设计。

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenAI-API-green?logo=openai" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

## ✨ 特性

- 📐 搜索索引设计
- ⚙️ Elasticsearch配置
- ⚡ 查询优化
- 🖥️ 搜索UI生成
- 📊 搜索日志分析

## 🚀 快速开始

```bash
pip install openai

python tools.py
```

## 📖 使用

```python
from search_tools import create_tools

tools = create_tools()

# 设计索引
design = tools.design_search_index("商品数据", "全文搜索")

# Elasticsearch配置
es_config = tools.generate_elasticsearch_config("电商搜索")

# 优化查询
optimized = tools.optimize_search_query(query, mapping)

# 生成搜索UI
ui = tools.generate_search_ui(["全文搜索", "筛选", "排序"])

# 分析日志
analysis = tools.analyze_search_logs(search_logs)
```

## 📁 项目结构

```
search-tools/
├── tools.py       # 搜索工具核心
└── README.md
```

## 📄 许可证

MIT License
