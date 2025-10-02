# 斗罗小说项目

## 项目结构

```
douluo/
├── README.md                 # 项目说明
├── todo.md                   # 待办事项
├── AI-INSTRUCTIONS.md        # AI协作指南
├── chapters/                 # 章节目录
│   ├── ch1.xxx.md           # 第一章（按格式命名）
│   ├── ch2.xxx.md           # 第二章
│   └── ...
├── settings/                 # 设定文档
│   ├── world.md             # 世界观设定
│   ├── characters.md        # 人物设定
│   ├── plot-outline.md      # 情节大纲
│   └── timeline.md          # 时间线
└── docs/                     # 索引文档
    ├── index.md             # 总目录
    ├── character-index.md   # 人物索引
    └── world-index.md       # 世界观索引
```

## 文件命名规范

### 章节文件
- 格式：`ch{章节号}.{章节名}.md`
- 示例：`ch1.重生斗罗.md`、`ch2.武魂觉醒.md`

## 使用指南

### 开始新章节
1. 查看 `settings/plot-outline.md` 确认情节规划
2. 查看 `docs/index.md` 了解已完成章节
3. 在 `chapters/` 目录创建新章节文件
4. 更新 `docs/index.md` 添加章节记录
5. 更新 `todo.md` 标记进度

### 修改设定
1. 修改对应设定文件（`settings/` 目录）
2. 更新相关索引文件（`docs/` 目录）
3. 检查已有章节是否需要调整

### 查找信息
- **人物信息**：`settings/characters.md` 或 `docs/character-index.md`
- **世界观**：`settings/world.md` 或 `docs/world-index.md`
- **情节规划**：`settings/plot-outline.md`
- **时间线**：`settings/timeline.md`

## 版本控制建议

建议使用 Git 进行版本控制：
```bash
cd douluo
git init
git add .
git commit -m "初始化项目结构"
```

## 备份策略

- 定期备份整个项目文件夹
- 重要节点（完成章节、重大修改）及时提交 Git
- 可使用云同步（如 iCloud、Dropbox）自动备份

---
*创建日期：2025-10-03*
