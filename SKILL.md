---
name: swiss-editorial-poster-skill
description: Generate a Simplified-Chinese 9:16 poster in the 「瑞士编辑」(swiss-editorial) style by 一张有戏. Use when the user wants a 瑞士编辑 / swiss editorial poster.
---

# 瑞士编辑 · swiss-editorial poster skill

一张有戏「瑞士编辑」风格海报技能。输出一张 9:16 竖版、简体中文的独立海报。

## 用法
1. 确定一个主标题（2–4 字）和一句短句。
2. 画面只出现三段文字：主标题、短句、页脚「一张有戏 · 视觉习作」。
3. 版式可选：big-type-only, editorial-column。
4. 参照下方完整提示词模板，替换 Headline / Supporting phrase / 场景描述。

## 示例主题
- 字间：几何字形的节奏与间距（editorial-column）— Large precisely spaced Chinese glyphs with one cobalt rectangle, hairline baseline guides, white ground, optical scale contrast.
- 声场：让声音拥有清晰的形状（big-type-only）— One cropped monochrome loudspeaker cone with a single red line tracing acoustic rhythm, rigid asymmetric grid.
- 城市切面：在楼影之间看见秩序（editorial-column）— One high contrast black-and-white architectural facade crop, narrow orange vertical type column, austere grid.
- 时间刻度：把流动分成可见的片段（big-type-only）— A large cropped clean black clock dial segment without digits or branding, precise cobalt circular rule and quiet white space.
- 纸上秩序：留白也是结构的一部分（editorial-column）— One folded white paper plane under crisp side shadow, asymmetrical black Chinese large type, one red thin rule.
- 留白练习：让目光有一处停留（big-type-only）— Almost no imagery, outsized black Chinese type in lower-left and a small cobalt square upper-right, meaningful optical tension.
- 节奏：让重复产生新的方向（editorial-column）— Unequal repeated black parallel bars disrupted once by a red bar, disciplined alignment and huge headline.
- 看见结构：从一根线开始建立关系（big-type-only）— Minimal axonometric black line architectural stair fragment over white, small cobalt crop and strict title column.

## 完整提示词模板（第 1 张原文）
```
Use case: ads-marketing. Create exactly ONE polished professional 9:16 portrait poster, static flat artwork, Chinese-mainland cultural/creative studio portfolio concept.
Language: Simplified Chinese. Headline: 字间. Supporting phrase: 几何字形的节奏与间距. Tiny plain footer: 一张有戏 · 视觉习作. Exact visible text ONLY these three phrases, every character correctly formed. No English, random numbers, fake events, dates, addresses, awards, offers, prices, affiliations, calls to action or status labels. All content is fictional/conceptual creative brief, no real client claim.

SOURCE UNIVERSAL RULES:


These rules apply to every poster. Do not repeat them in layout or style notes.

- Build around one dominant message, one clear focal point, and one communication goal.
- Establish a simple reading order: headline -> focal image -> supporting copy -> supplied details.
- Preserve required copy exactly unless the user explicitly asks for rewriting.
- Keep important text readable, high-contrast, and inside safe margins.
- Use confident spacing and avoid overstuffed layouts.
- Avoid fake extra text, random logos, QR codes, decorative clutter, malformed typography, and generic AI-poster noise.
- Treat the poster canvas as static print/editorial artwork rather than a clickable interface. If the source explicitly requests a product UI, browser window, dashboard, or device mockup, preserve that depicted content inside the poster.
- CTA copy is extractive-only: include it only when the source explicitly supplies the wording. When output language differs, verify the translated CTA against a recorded exact source quote. Never invent action or status labels.
- If no CTA is sourced, leave the action area empty. If one is sourced, render it as ordinary poster typography in a footer or text lockup. Do not place poster-level action copy inside a button, rounded rectangle, pill, chip, capsule, tab, input field, or any other clickable-looking UI container; do not decorate it with a shadow, arrow, chevron, or cursor icon.



SELECTED STYLE — STRICTLY THIS VISUAL SYSTEM, DO NOT MIX OTHER STYLES:
# Swiss Editorial

## Intent

Create a refined, typography-led poster with strict grid discipline, asymmetry, clarity, and modern editorial restraint.

## Typography

- Use clean neo-grotesk or grotesk sans-serif direction.
- Favor strong scale contrast: oversized headline, compact metadata.
- Use left alignment, asymmetric placement, and disciplined baseline rhythm.
- Avoid decorative fonts and excessive type effects.

## Palette

Neutral base: white, warm white, black, charcoal, gray. Add one precise accent such as red, cobalt, acid green, or orange.

## Imagery

Use one restrained image, abstract crop, simple object, or no image. Imagery should support the typographic grid, not dominate it.

## Texture / Material

Mostly clean matte paper or subtle print grain. Keep surface treatment minimal.

## Composition Rules

- Use visible or implied grid columns.
- Keep text blocks aligned and intentional.
- Use rules, numbers, or small labels sparingly.

## Avoid

Centered generic flyer layouts, random decoration, too many colors, fake Swiss clichés, illegible tiny type, and cluttered backgrounds.


INTERNAL COMPOSITION:
# Editorial Column

## Composition Structure

- Use one large typographic area and one narrower supporting column.
- Create asymmetric balance with image, negative space, or rule lines.
- Place metadata in a disciplined column or margin note.
- Let the layout feel like a high-end magazine page converted into a poster.

## Hierarchy Rules

1. Large headline or image creates first read.
2. Column copy provides context.
3. Source-supplied metadata sits in a small typographic lockup. Source-supplied action copy may appear only as plain text.

## Text Placement

- Use strong alignment and column widths.
- Keep body copy brief and readable.
- Use margins intentionally, including large empty zones.

## Image Treatment

Use editorial photography, cropped object, art detail, or abstract field.

## Spacing Rules

Whitespace is an active design element. Avoid filling the entire page.

## Aspect-Ratio Behavior

Best in `2:3`, `3:4`, `4:5`, and `16:9`. In square, use one dominant column and one compact side note.

## Avoid

Centered brochure layouts, generic event flyer structure, too many font styles, and long body copy.


SPECIFIC SUBJECT AND ART DIRECTION:
Large precisely spaced Chinese glyphs with one cobalt rectangle, hairline baseline guides, white ground, optical scale contrast.

Quality: exquisite thoughtful art direction, one immediate focal point, sophisticated typographic spacing and clear reading order, original expressive composition with wide enough safe margins. Headline large and readable at phone thumbnail; secondary text restrained, not generic template. Typography adapted sensitively to real Chinese glyphs, with the visual weight demanded by style. Material/light/print treatment consistent with selected style. If any person appears, fictional mainland Chinese adult, natural anatomy and authentic face; otherwise no people. All props physically coherent unless the SPECIFIC surreal idea deliberately changes physics. No trademarks or label text on products, no fake logos/watermarks/QR. No poster mockup, wall frame, multiple-poster collage, UI buttons or decorative website components. The creative theme must determine composition; vary crop, hierarchy and negative space across the series. Output one finished poster only.
```

全部 8 条提示词见 `PROMPTS.json`，来源见 `SOURCES.md`。
