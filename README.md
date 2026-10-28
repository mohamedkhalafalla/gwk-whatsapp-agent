<p align="center">
  <img src="docs/assets/og.png" alt="Claude يرد على WhatsApp بتاعك: شرح من Grow With Khalaf" width="100%">
</p>

<div dir="rtl">

# خلّي Claude يرد على WhatsApp بتاعك

ده شرح بالعربي من **Grow With Khalaf** إزاي تربط Claude Code بـ [Kapso](https://kapso.com)، وتبني agent على واتساب يرد على الـ leads ويحجزلهم ديمو مع السيلز.

**الدليل الكامل خطوة بخطوة: [mohamedkhalafalla.github.io/gwk-whatsapp-agent](https://mohamedkhalafalla.github.io/gwk-whatsapp-agent/)**

> **الكريديت:** Kapso والـ [agent skills](https://github.com/gokapso/agent-skills) بتوعها من عمل فريق Kapso. الريبو ده فيه الشرح بس، ومفيهوش أي ملفات من Kapso.

## الخطوات باختصار

</div>

```bash
export KAPSO_API_KEY="your_api_key"
npm install -g @kapso/cli
npx skills add gokapso/agent-skills
kapso login
kapso setup
```

<div dir="rtl">

بعدها افتح Claude Code، وقوله انت عايز الـ agent يعمل إيه. البرومبت جاهز في [الدليل](https://mohamedkhalafalla.github.io/gwk-whatsapp-agent/#prompt).

## جوه الريبو

| المسار | فيه إيه |
|---|---|
| `docs/index.html` | صفحة الدليل (GitHub Pages) |
| `docs/assets/` | اللوجوهات، وسكرينات من Kapso، وصورة المعاينة |

المعلومات من [docs.kapso.ai](https://docs.kapso.ai) ومن docs بتاعة Meta، واتراجعت في 28 أكتوبر 2026. مش تابعين لـ Kapso ولا Anthropic ولا Meta.

</div>

---

**English:** An Arabic step-by-step guide by Grow With Khalaf for connecting Claude Code to WhatsApp through [Kapso](https://kapso.com) and its [agent skills](https://github.com/gokapso/agent-skills). Kapso and its skills are Kapso's work; this repo only holds the guide page. Not affiliated with Kapso, Anthropic or Meta.
