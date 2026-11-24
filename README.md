# DocuClean Pro (`文档表格秒转引擎`) — Zero-Cloud PDF/HTML/CSV Mojibake to `.xlsx` & `.docx` Converter

[![Zero Cloud](https://img.shields.io/badge/privacy-100%25%20offline-10b981)](https://2848823170.github.io/docuclean-pro/)
[![Live Web Converter](https://img.shields.io/badge/demo-live%20browser%20studio-f59e0b)](https://2848823170.github.io/docuclean-pro/demo.html)

**DocuClean Pro (`文档表格秒转引擎`)** converts messy CSVs (`GB18030` / `GBK` / `Big5` / double-encoded UTF-8 mojibake), `rowspan`/`colspan` HTML tables, JSON/XML dumps, and multi-page PDF tables into **clean, auto-column-sized, formula-ready OpenXML `.xlsx` workbooks** and **structured `.docx` documents** with `0` bytes uploaded to any server.

## Live Links

- **Official Storefront & Embedded Sandbox**: **[https://2848823170.github.io/docuclean-pro/](https://2848823170.github.io/docuclean-pro/)**
- **Full-Screen Offline Web Converter**: **[https://2848823170.github.io/docuclean-pro/demo.html](https://2848823170.github.io/docuclean-pro/demo.html)**
- **Done-For-You PDF-to-Word/Excel, Multi-Sheet Merge & Formula Service (`¥4.90` on Goofish / 闲鱼)**:
  - **[PDF转Word排版Excel表格提取合并公式代做乱码修复批量处理](https://www.goofish.com/item?id=1101539642643)**
- **Custom AI Agent Skill / MCP Server / Python Automation (`¥5.00` diagnostic entry)**:
  - **[AI智能体Skill定制MCP插件配置Python自动化脚本远程部署](https://www.goofish.com/item?id=1102654549394)**

## Key Capabilities

- **Automatic CJK Mojibake Recovery**: Detects `GB18030` / `GBK` / `Big5` / `UTF-16` and repairs UTF-8-decoded-as-Latin1 text automatically.
- **Exact Long-ID & Formula-Injection Protection**: Preserves 16–28 digit order/ID numbers as text (never `E+17`) and sanitizes untrusted leading `=`, `+`, `-`, `@` DDE/formula strings + control characters (`\x00–\x1F`) so Excel and Word open every file cleanly without repair dialogs.
- **Styled OpenXML `.xlsx` & `.docx` Generation**: Produces native `.xlsx` (frozen header row, auto-fitted column widths, currency/number formatting, summary formulas) and `.docx` files directly in the browser (`connect-src 'none'`).

## Sister Projects

- **[LedgerClean Pro (`账清`)](https://2848823170.github.io/ledgerclean-pro/)** — Offline multi-platform statement & electronic voucher reconciler
- **[ledgerclean-cli](https://github.com/2848823170/ledgerclean-cli)** — Zero-dependency Node.js CLI for Beancount, QuickBooks & Excel CSV reconciliation
