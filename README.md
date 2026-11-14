# IELTS Speaking · 表达训练室

浏览器版个人雅思口语训练系统。68 个核心表达、144 道 Part 1 示例、39 道 Part 2 提纲、163 道 Part 3 关联。

## 如何开始

打开仓库 About 中的网站链接，点击「第一次使用？查看训练指南」。先设定开始日期，进入今日学习，主动回忆后自评，再到口语练习中回答真实题目。

学习进度存于浏览器 localStorage，录音存于 IndexedDB，不上传 GitHub。建议每天下载一次完整 JSON 备份。换设备需手动恢复；不要用无痕模式长期学习。

示例为教学内容，不代表使用者真实经历，不提供自动 IELTS 评分。来源只保留必要短片段及页码，不含讲义全文。

## 部署

GitHub Pages 使用 .github/workflows/pages.yml 自动发布 web/。直接编辑 web 文件并推送 main 即可更新。

本地预览：python3 -m http.server 8503 --directory web
