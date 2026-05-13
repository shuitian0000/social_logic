# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

社会运行底层逻辑分析系统 — an interactive HTML-based knowledge system that visualizes and explains the underlying logic of social operation for young adults (刚成年的年轻人).

## Architecture

Single-page application: `index.html` contains all HTML, CSS, and JavaScript. No build system, no dependencies, no server required. Open directly in a browser.

## Five Interactive Sections

1. **关系图谱** — SVG-based interactive relationship graph (3-layer: macro/micro/evolution)
2. **规则清单** — 10 iron rules with expandable details
3. **实践映射** — Scenario-to-action guides (job/career/social/wealth/life choices)
4. **认知纠偏** — Misconception vs reality comparison table
5. **演化动画** — Canvas particle animation showing 6 stages of social evolution

## Theoretical Foundation

- Wu Si (吴思): 潜规则, 血酬定律, 元规则, 官家主义, 法酬公式
- Bourdieu: Four capitals (economic/cultural/social/symbolic), habitus, field
- Granovetter: Weak ties; Burt: Structural holes; Bian Yanjie: Strong ties in China
- Information asymmetry (Akerlof), Resource dependence theory
- 四差理论: 信息差→认知差→资源差→执行差
