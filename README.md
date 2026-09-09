# AI 智批产品演示稿

打开 index.html 即可运行，无需本地服务。可将此目录内容发布到 GitHub Pages。

复核页直接复用 homework-correction/assets/review-template.html、review-layout.js、review-export.js 和内置批改符号；不是简化替代界面。

本版本经用户明确授权，包含本地任务 job-e0e4497ed91e 的真实学生姓名、作业图片及批改结果，未脱敏：1 套作业、2 位学生、8 页。资源全部内嵌，不调用批改接口，不包含接口凭据。公开本目录会公开这些作业内容。

支持原复核页的按题查看、按学生查看、改判和整批 ZIP 下载。静态版改判仅在浏览器中保存，不代表 Agent 或本地文件同步已实现。结果概要为导出时的结果快照。

重新生成：保持本地 demo 服务运行，在父项目执行 node scripts/build-real-product.cjs。不要运行虚构数据构建脚本覆盖本版本。
