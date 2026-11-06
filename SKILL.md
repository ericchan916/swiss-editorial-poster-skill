---
name: swiss-editorial-poster
description: 瑞士编辑海报：以严格网格、不对称与现代编辑克制，做一张字体主导的精炼海报。根据【主标题】【短句】【场景】【版式】【主色强调】【画幅】生成一张简体中文海报。当用户提到「瑞士编辑 / Swiss Editorial / 网格编辑海报」时使用。 Use when the user asks for a Swiss editorial, grid typography poster, International Typographic Style poster — produces one poster with only three visible Chinese lines: headline, supporting line, and footer「一张有戏 · 视觉习作」.
license: MIT
---

# 瑞士编辑 · Swiss Editorial Poster

以严格网格、不对称与现代编辑克制，做一张字体主导的精炼海报。
A refined typography-led poster with strict grid discipline, asymmetry, clarity, and modern editorial restraint.

## 输入 · Inputs

```
【主标题】：
【短句】：
【场景】：
【版式】：（big-type-only / editorial-column，缺省 editorial-column）
【主色强调】：（红 / cobalt / acid green / orange（选一））
【画幅】：9:16（默认）
```

**缺失字段不要追问**：只给了主标题（或部分字段）时，由你根据主标题自行补全其余字段，并保证场景、版式、主色强调彼此协调、指向同一概念。画幅缺省为 9:16。
If any field is missing, fill it yourself coherently from the headline — never ask. Default aspect ratio 9:16.

## 使用方法 · How to use
1. 读取输入，补全缺失字段（内部完成，不输出分析）。
2. 按下方核心规则 + [prompt.md](prompt.md) 组合提示词，交给图像生成工具，**只输出一张**海报。
3. 若当前环境不能生图，输出下方「可直接粘贴的最终提示词」，已填好字段，供用户粘贴到 ChatGPT / 其他图像模型。

示例输入见 [examples/themes.md](examples/themes.md)。

## 核心规则 · Core rules

### 目标 · Intent
以严格网格、不对称与现代编辑克制，做一张字体主导的精炼海报。
Create a refined, typography-led poster with strict grid discipline, asymmetry, clarity, and modern editorial restraint.

### 字体 · Typography
- Use clean neo-grotesk or grotesk sans-serif direction.
- Favor strong scale contrast: oversized headline, compact metadata.
- Use left alignment, asymmetric placement, and disciplined baseline rhythm.
- Avoid decorative fonts and excessive type effects.

### 配色 · Palette
- Neutral base: white, warm white, black, charcoal, gray. Add one precise accent such as red, cobalt, acid green, or orange.
- 【主色强调】只取一个精确强调色，不要彩虹堆砌。

### 意象 · Imagery
- Use one restrained image, abstract crop, simple object, or no image. Imagery should support the typographic grid, not dominate it.
- 【场景】描述应支撑字体与版式，不要喧宾夺主（除非风格本身以主体物件为第一阅读）。

### 质感 · Texture / Material
- Mostly clean matte paper or subtle print grain. Keep surface treatment minimal.

### 构图 · Composition
- Use visible or implied grid columns.
- Keep text blocks aligned and intentional.
- Use rules, numbers, or small labels sparingly.
- 版式从该风格允许的布局中选择：`big-type-only / editorial-column`；缺省 `editorial-column`。
- 单一焦点、清晰阅读顺序：主标题 → 焦点画面 → 短句 → 页脚。

### 文字锁定 · Text lock（一张有戏）
- 画面可见文字**只有三行**：【主标题】、【短句】、页脚「一张有戏 · 视觉习作」。
- 简体中文；每个字正确成形；不要英文乱码、假活动、假日期、假地址、假奖项、假价格、假 CTA、假品牌。
- 不要按钮/圆角胶囊/UI 容器；页脚就是普通小字排印。

### 避免 · Avoid
- Centered generic flyer layouts, random decoration, too many colors, fake Swiss clichés, illegible tiny type, and cluttered backgrounds.
- 额外假字、随机 logo、二维码、装饰堆砌、畸形字体、通用 AI 海报噪声、水印、UI。

### 执行 · Execution
不提问、不展示分析、不出多版本，直接输出一张海报。

## 可直接粘贴的最终提示词 · Ready-to-paste prompt template

```
【主标题】：{{主标题}}
【短句】：{{短句}}
【场景】：{{场景}}
【版式】：{{版式，缺省 editorial-column；可选 big-type-only / editorial-column}}
【主色强调】：{{主色强调}}
【画幅】：{{画幅，默认 9:16}}

Create exactly ONE polished professional {{画幅，默认 9:16}} portrait poster, static flat artwork, Chinese-mainland cultural/creative studio portfolio concept.
Language: Simplified Chinese. Headline: {{主标题}}. Supporting phrase: {{短句}}. Tiny plain footer: 一张有戏 · 视觉习作. Exact visible text ONLY these three phrases, every character correctly formed. No English clutter, random numbers, fake events, dates, addresses, awards, offers, prices, affiliations, calls to action or status labels. All content is fictional/conceptual creative brief, no real client claim.
If any field above is empty, fill it coherently from 【主标题】 so scene, accent and layout support one clear idea — do not ask questions.

SELECTED STYLE — STRICTLY THIS VISUAL SYSTEM, DO NOT MIX OTHER STYLES:
# Swiss Editorial
Intent: Create a refined, typography-led poster with strict grid discipline, asymmetry, clarity, and modern editorial restraint.
Typography: Use clean neo-grotesk or grotesk sans-serif direction. Favor strong scale contrast: oversized headline, compact metadata. Use left alignment, asymmetric placement, and disciplined baseline rhythm. Avoid decorative fonts and excessive type effects.
Palette: Neutral base: white, warm white, black, charcoal, gray. Add one precise accent such as red, cobalt, acid green, or orange. Use exactly one precise accent from 【主色强调】.
Imagery: Use one restrained image, abstract crop, simple object, or no image. Imagery should support the typographic grid, not dominate it. Scene direction: {{场景}}.
Texture / Material: Mostly clean matte paper or subtle print grain. Keep surface treatment minimal.
Composition: Use visible or implied grid columns. Keep text blocks aligned and intentional. Use rules, numbers, or small labels sparingly. Use layout {{版式，缺省 editorial-column}} from allowed set (big-type-only / editorial-column). One dominant message, one focal point; reading order headline -> focal image -> supporting copy -> footer. Confident spacing; no overstuffed layout; no UI buttons/pills for the footer.

Avoid: Centered generic flyer layouts, random decoration, too many colors, fake Swiss clichés, illegible tiny type, and cluttered backgrounds. Also avoid fake extra text, logos, QR codes, decorative clutter, malformed typography, generic AI-poster noise, watermarks, UI chrome.

Do not ask questions. Do not show analysis or alternatives. Output the single finished poster only.
```
