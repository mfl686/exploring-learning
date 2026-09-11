# 探索学习日志

> 个人知识积累库 · 记录学习、思考与发现

---

## 目录结构

```
exploring-learning-1_1/
├── README.md                 # 本文件
├── _config/                  # 配置
│   └── tags.md               # 标签体系
├── categories/               # 按主题分类
│   ├── programming/          # 编程开发
│   ├── finance/              # 金融投资
│   ├── tools/                # 工具使用
│   ├── ai/                   # AI/大模型
│   └── notes/                # 其他笔记
├── daily/                    # 每日记录
│   └── YYYY-MM-DD.md
├── projects/                 # 项目备忘
└── resources/                # 参考资料链接
    └── bookmarks.md
```

---

## 快速开始

### 新建笔记

```bash
# 每日记录
./scripts/new-note.sh daily/2026-09-11

# 主题分类
./scripts/new-note.sh categories/finance/缠论分析.md
```

### 常用命令

| 操作 | 命令 |
|------|------|
| 查看笔记列表 | `find . -name "*.md" ! -path "./.git/*" | sort` |
| 搜索关键词 | `grep -r "关键词" . --include="*.md"` |
| 按标签筛选 | 见 `_config/tags.md` |

---

## 标签体系

参考 `_config/tags.md` 统一管理标签。

常用标签：
- `#todo` — 待办
- `#learn` — 学习笔记
- `#reference` — 参考资料
- `#project` — 项目相关
- `#review` — 定期复习

---

## 最近更新

| 日期 | 文件 | 说明 |
|------|------|------|
| 2026-09-11 | `README.md` | 初始化仓库结构 |

---

## 统计

- 总笔记数：0
- 今日新增：1
- 活跃标签：无
