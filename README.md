# AI 智批产品演示稿

打开 index.html 即可运行，无需本地服务。可将此目录内容发布到 GitHub Pages。

复核页直接复用 homework-correction/assets/review-template.html、review-layout.js、review-export.js 和内置批改符号；不是简化替代界面。

作业图片和学生信息均为虚构示例，全部内嵌，不上传文件、不调用批改接口。支持原模板的按题查看、按学生查看、改判和整批 ZIP 下载。静态版改判仅在浏览器中保存，不代表 Agent 或本地文件同步已实现。

重新生成：在父项目执行 node scripts/build-static-product.cjs。
