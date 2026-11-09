# Ocean Spa

مشروع سبا. المحتوى الموجّه للعملاء بالعربية افتراضياً.

## قواعد استخدام المهارات (توفير التوكن)

- قائمة المهارات الكاملة تصل تلقائياً، لا تعِد سردها ولا تقرأها كلها.
- حمّل مهارة واحدة فقط عندما تطابق المهمة بوضوح، ولا تحمّل مهارات احتياطاً.
- المهام القصيرة (كابشن واحد، رد، تعديل بسيط): نفّذها مباشرة بلا مهارة.
- استخدم الوكلاء الفرعيين (subagents) فقط عند طلب المستخدم.
- ردود مختصرة، بلا تكرار لما قيل سابقاً.

## المهارات المفضّلة للمشروع

- المحتوى: `social-media-skills:caption-writer`، `reels-script`، `content-calendar`، `seasonal-and-moment-marketing`
- الحملات: `marketing:campaign-plan`
- التصميم: `codesign:create`، `codesign:brand`
- العملاء: `social-media-skills:reply-and-comment-writer`، `sales:handle-objection`
- المستندات: `anthropic-skills:pdf`، `anthropic-skills:pptx`

## Context7 (توثيق المكتبات)

خادم MCP مسجّل في `.mcp.json`. استخدمه فقط عند كتابة كود يعتمد على مكتبة أو إطار عمل (مثل Next.js وTailwind) للحصول على توثيق محدّث، وليس للمحتوى التسويقي.

## 21st.dev Magic (مكوّنات واجهات)

خادم MCP `21st-magic` في `.mcp.json`. استخدمه فقط عند بناء واجهات الموقع (أزرار، بطاقات، صفحات هبوط). المفتاح من متغيّر `API_KEY_21ST`، ولا يُكتب في أي ملف.

## Strix (اختبار الأمان)

مهارات Strix في `.claude/skills/`. استخدمها فقط على أصول Ocean Spa (الموقع، الـ API، هذا المستودع). اطلب موافقة المستخدم قبل تشغيل أي فحص أو أي عملية تستهلك رصيداً في app.strix.ai.

## أدوات إضافية

- `agent-reach`: قراءة محتوى المنصات (X، Reddit، YouTube، Instagram) عند فشل البحث العادي فقط. قراءة فقط، ولا تسجّل دخولاً نيابة عن المستخدم.
- `awesome-free-llm-apis`: مرجع لمزوّدي النماذج المجانية، عند السؤال عنها فقط.
- `claude-automation-recommender`: اقتراح أتمتة لإعداد Claude Code عند الطلب.
- البلجنز `claude-code-setup` و`claude-mem` مسجّلة في `.claude/settings.json` وتُثبَّت تلقائياً على جهاز المستخدم.

## مهارات خاصة بالمشروع

تُوضع في `.claude/skills/<الاسم>/SKILL.md`.

## graphify

This project has a knowledge graph at graphify-out/ with god nodes, community structure, and cross-file relationships.

Rules:
- When graphify-out/graph.json exists, run `graphify query "<question>"` before your first grep, search or source-file read for a codebase question, and put this rule in every subagent prompt that explores code. Read raw files only for lines the graph or an earlier read already located. Use `graphify path "<A>" "<B>"` for relationships and `graphify explain "<concept>"` for focused concepts. These return a scoped subgraph, usually much smaller than GRAPH_REPORT.md or raw grep output.
- If graphify-out/wiki/index.md exists, use it for broad navigation instead of raw source browsing.
- Read graphify-out/GRAPH_REPORT.md only for broad architecture review or when query/path/explain do not surface enough context.
- After modifying code, run `graphify update .` to keep the graph current (AST-only, no API cost).
- A committed graphify-out/graph.json is rewritten whole on every build, so a large diff to it in a pull request is expected. Do not flag it as churn or suggest skipping the graph rebuild or its hooks.
