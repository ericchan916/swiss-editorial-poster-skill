# 瑞士编辑 · 完整提示词

## 填写模板 · Fill-in template

```
【主标题】：
【短句】：
【场景】：
【版式】：（big-type-only / editorial-column，缺省 editorial-column）
【主色强调】：（红 / cobalt / acid green / orange（选一））
【画幅】：9:16（默认）
```

> 只填主标题也可以：其余字段由模型根据主标题协调补全。

## 完整提示词 · Full prompt（复制以下全部）

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

## English summary
A refined typography-led poster with strict grid discipline, asymmetry, clarity, and modern editorial restraint. One Simplified-Chinese 9:16 poster; visible text only: headline, supporting line, footer「一张有戏 · 视觉习作」. Style lock: Swiss Editorial. Layouts: big-type-only, editorial-column.
