# Ocean Spa — CLAUDE.md

ملف الإعداد الرئيسي لـ Claude في مشروع **Ocean Spa**.
يسجّل هذا الملف مهارات الوكيل (Agent Skills) المتاحة ومتى تُستخدم.

## طريقة استخدام المهارات

- استدعِ المهارة بأداة `Skill` باسمها الكامل كما هو مسجّل أدناه (مثال: `social-media-skills:caption-writer`).
- يمكن للمستخدم تشغيل أي مهارة مباشرة بكتابة `/<اسم-المهارة>`.
- إذا كانت المهمة تطابق مهارة مسجّلة، حمّل المهارة أولاً ثم نفّذ حسب تعليماتها.
- اللغة الافتراضية للمحتوى الموجّه للعملاء: العربية، مع الإنجليزية عند الطلب.

---

## مهارات التسويق والسوشيال ميديا (الأهم للسبا)

| المهارة | الاستخدام |
|---|---|
| `social-media-skills:brand-profile` | بناء هوية العلامة وصوتها |
| `social-media-skills:social-strategy` | الاستراتيجية العامة لمنصات التواصل |
| `social-media-skills:content-pillars` | محاور المحتوى |
| `social-media-skills:content-calendar` | تقويم النشر |
| `social-media-skills:batch-content-plan` | تخطيط دفعات المحتوى |
| `social-media-skills:caption-writer` | كتابة الكابشن |
| `social-media-skills:hook-writer` | كتابة الافتتاحيات الجاذبة |
| `social-media-skills:hashtag-strategy` | الهاشتاقات |
| `social-media-skills:instagram-growth` | نمو حساب إنستغرام |
| `social-media-skills:reels-script` | سكربتات الريلز |
| `social-media-skills:story-writer` | الستوريز |
| `social-media-skills:carousel-writer` | منشورات الكاروسيل |
| `social-media-skills:tiktok-script` / `tiktok-growth` | تيك توك |
| `social-media-skills:before-after-and-transformation` | محتوى قبل/بعد |
| `social-media-skills:social-proof-and-testimonials` | آراء العملاء |
| `social-media-skills:seasonal-and-moment-marketing` | المواسم والمناسبات (رمضان، العيد، الصيف) |
| `social-media-skills:ugc-and-influencer` | المؤثرون ومحتوى العملاء |
| `social-media-skills:community-management` / `reply-and-comment-writer` | الردود وإدارة المجتمع |
| `social-media-skills:analytics-and-reporting` | تقارير الأداء |
| `social-media-skills:image-prompt` / `nano-banana` / `canva` | التصاميم والصور |
| `marketing:campaign-plan` | خطة حملة تسويقية |
| `marketing:content-creation` / `marketing:draft-content` | إنشاء المحتوى |
| `marketing:email-sequence` | سلاسل البريد الإلكتروني |
| `marketing:seo-audit` | تدقيق SEO للموقع |
| `marketing:brand-review` | مراجعة الالتزام بالهوية |
| `marketing:competitive-brief` | تحليل المنافسين |

## مهارات التصميم

| المهارة | الاستخدام |
|---|---|
| `codesign:create` | إنشاء تصميم جديد (بوستر، فلاير، بوست، فيديو) |
| `codesign:brand` | تطبيق هوية العلامة على التصميم |
| `codesign:resize` / `codesign:formats` | تغيير المقاسات لكل منصة |
| `codesign:animate` | تحريك تصميم ثابت |
| `codesign:judge` | مراجعة جودة التصميم |
| `design:design-critique` / `design:ux-copy` / `design:accessibility-review` | مراجعة واجهات ونصوص الموقع |
| `image-generation:image-generation` | توليد الصور |

## مهارات المبيعات والعملاء

| المهارة | الاستخدام |
|---|---|
| `sales:draft-outreach` | رسائل التواصل مع العملاء/الشركات |
| `sales:customer-voice` | تحليل آراء العملاء |
| `sales:handle-objection` | الرد على اعتراضات العملاء |
| `sales:schedule-meeting` | جدولة المواعيد |
| `b2b-sales-enablement:sales-proposal-builder` | عروض الشراكات والشركات |
| `b2b-sales-enablement:meeting-prep-debrief` | التحضير للاجتماعات |

## مهارات الإدارة والمالية والإنتاجية

| المهارة | الاستخدام |
|---|---|
| `productivity:task-management` | إدارة المهام عبر `TASKS.md` |
| `productivity:memory-management` | حفظ السياق والملاحظات |
| `finance:variance-analysis` / `finance:financial-statements` | التحليل المالي |
| `management-consulting:financial-modeling` | دراسات الجدوى ونماذج الأرباح |
| `management-consulting:strategic-analysis` | قرارات التوسع والاستراتيجية |
| `management-consulting:process-excellence` | تحسين العمليات التشغيلية |

## مهارات المستندات

| المهارة | الاستخدام |
|---|---|
| `anthropic-skills:docx` | ملفات Word |
| `anthropic-skills:pdf` | ملفات PDF (قوائم الأسعار، الكتيبات) |
| `anthropic-skills:pptx` | العروض التقديمية |
| `anthropic-skills:xlsx` | جداول Excel |
| `anthropic-skills:skill-creator` | إنشاء مهارات مخصصة جديدة للمشروع |

## مهارات التطوير (للموقع/التطبيق)

| المهارة | الاستخدام |
|---|---|
| `run` | تشغيل التطبيق ومعاينة التغييرات |
| `code-review` | مراجعة الكود |
| `simplify` | تبسيط الكود |
| `security-review` | المراجعة الأمنية |
| `update-config` | إعدادات Claude Code والـ hooks |

---

## مهارات مخصصة للمشروع

ضع أي مهارة خاصة بـ Ocean Spa داخل `.claude/skills/<اسم-المهارة>/SKILL.md`
وأضفها إلى هذا القسم مع وصف مختصر لاستخدامها.
