# 日历工坊 · Calendar Studio

日历工坊是一个在浏览器里生成可打印日历的双语工具。可以为全年规划、月度安排、工作周和每日撕页制作自己的日历。简体中文版默认生成中文日历，也可以在生成器里选择其他日历语言。

**在线使用** · [简体中文](https://calendars.wangruofeng007.com/) · [English](https://calendars.wangruofeng007.com/en/)

| 版式 | 用法 |
| --- | --- |
| 单页年历 | 在一张纸上查看全年 12 个月。 |
| 月历 | 每页一个月，最多一次生成 24 个月，可调整起始月、每周起始日和周数标记。 |
| 工作日历 | 每页一个月，只显示周一到周五。 |
| 每日撕页日历 | 选择全年或自定义日期范围，排版后打印、裁切和叠放。可自定义日期文字与每日短语。 |

## 导出和打印

先选择版式，再调整日期、日历语言和版式参数。页面会即时更新预览；下载 PDF 可获得完整页数，SVG 和 PNG 导出预览中的第一页。打印时选择「实际大小」或 100%。「复制链接」可分享日期和版式设置，每日短语不会写入链接。

## 离线使用

点击首页的「下载应用」，或直接用浏览器打开 `index.html`（简体中文）或 `en/index.html`（英文）。两版均为独立 HTML 文件，无需安装依赖。要在本地同时浏览两版，可在仓库根目录运行 `python3 -m http.server 8000`，然后访问 [简体中文](http://localhost:8000/) 或 [English](http://localhost:8000/en/)。

## 部署与来源

Cloudflare Pages 从 `main` 分支自动部署，静态输出目录为仓库根目录，无需构建命令。

项目基于 Kevin MacLeod 的 [Incompetech Calendars 2.1](https://incompetech.com/calendars/) 改编。本应用及生成的日历采用 [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)。

---

Calendar Studio makes yearly, monthly, weekday, and cut-and-stack calendars in your browser. Customize dates, paper size, and calendar language, then export PDF, SVG, or PNG. Try the [English edition](https://calendars.wangruofeng007.com/en/) online or download a standalone copy for offline use.
