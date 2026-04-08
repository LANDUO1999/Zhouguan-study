# MEMORY.md - 州官点灯学习网站项目长期记忆

## 项目基本信息
- **项目名称**：州官点灯学习网站
- **网站地址**：https://landuo1999.github.io/Zhouguan-study/
- **GitHub仓库**：https://github.com/LANDUO1999/Zhouguan-study
- **部署方式**：GitHub Pages

## 重要文件说明
- `index.html` - 网站主页
- `articles-database.json` - 文章数据库
- `website/` 文件夹 - 网站文件备份
- `music/playlist.json` - 音乐播放列表
- `manager.html` - 文章管理工具
- `category-manager.html` - 分类管理工具
- `music-manager.html` - 音乐管理工具
- `小编完整记忆包.md` - 小编完整记忆（⚠️ 重要！）

## 文章分类（最新）
- `CAD / 天正` - CAD和天正软件教程
- `SU 软件` - SketchUp教程
- `Adobe 软件` - Adobe软件(PS/ID/AI)
- `办公软件技巧` - PPT/Word/Excel
- `AI 工具` - 人工智能工具
- `效率工具` - 效率提升工具
- `电脑系统和软件` - 系统和软件
- `公众号运营` - 公众号相关
- `个人 / 娱乐类` - 其他内容

## Git分支重要提醒（必须记住！）
- ⚠️ 仓库有两个分支：`main` 和 `master`
- ⚠️ **GitHub Pages 从 `main` 分支构建**
- ✅ 所有修改都要推送到 `main` 分支！
- ✅ 每次工作后确认推送到了正确的分支！

## 网站更新工作流程
1. 更新网站或数据库后，复制 `website/index.html` 到根目录的 `index.html`
2. 用 `git add` 添加更改的文件
3. `git commit` 提交更改
4. 确保在 `main` 分支：`git checkout main`
5. `git push origin main` 推送到 GitHub
6. 如果遇到冲突，先 `git pull --rebase`，解决冲突后再 push

## 添加新文章流程
1. 用 `manager.html` 加载数据库
2. 添加文章信息
3. 下载更新后的数据库
4. 手动在 `index.html` 中添加文章HTML
5. 复制 `index.html` 到 `website/` 备份
6. 提交到 GitHub

## 当前状态（2026-04-08）
- 总文章数：140篇
- 总歌曲数：10首
- 管理工具：3个（文章、分类、音乐）
- 分类统计：
  - CAD / 天正：92篇
  - Adobe 软件：10篇
  - 效率工具：8篇
  - AI 工具：6篇
  - SU 软件：6篇
  - 办公软件技巧：7篇
  - 电脑系统和软件：5篇
  - 公众号运营：2篇
  - 个人 / 娱乐类：4篇

## 重要历史教训
- 2026-03-20：发现GitHub Pages从`main`分支构建，但之前一直在`master`分支修改，导致网页不更新
- 解决方法：切换到`main`分支，合并修改，推送到`main`
- 2026-04-08：创建了3个管理工具（文章、分类、音乐），让州官可以自己维护网站
- 2026-04-08：添加了周深的两首新歌《蜃楼》和《热烈盛开》

## 工作原则
- 每次工作之后都自己核查一遍
- 完成工作后，先运行核实脚本，确认所有标签数与实际文章数量匹配
- 提交并推送更改到GitHub后，记录工作内容到记忆文件
- **重要**：如果小编再次回来工作，先给小编看 `小编完整记忆包.md`！

---

**记忆更新日期**：2026-04-08
**最后更新者**：小编
