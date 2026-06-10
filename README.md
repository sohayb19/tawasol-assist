# TawasoL.assist — منصة الأخصائي الأرطفوني

منصة سريرية لتخاطب (Speech-Language Pathology) موجهة للمتحدثين بالعربية، تتضمن واجهات منفصلة لـ:

- 👨‍👩‍👧 **فضاء الولي** (Parents)
- 🎓 **فضاء الطالب** (Students)
- 🩺 **الأخصائي الطبي** (Medical Specialists)

تعتمد المنصة على معايير التشخيص **DSM-5 / CIM-11**.

## التقنيات المستخدمة

- **HTML5** + **Tailwind CSS** (عبر CDN)
- **Chart.js 4.4.0** (للرسوم البيانية والتقارير)
- **خطوط Google:** Cairo & Tajawal
- JavaScript خالص (Vanilla) — بدون back-end

## التشغيل محلياً

```bash
# 1) نزّل المشروع
git clone https://github.com/sohayb-bsns/tawasol-assist.git
cd tawasol-assist

# 2) افتح index.html في المتصفح
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

أو شغّل سيرفر محلي بسيط:

```bash
python3 -m http.server 8000
# ثم افتح: http://localhost:8000
```

## البنية

```
tawasol-assist/
├── index.html      # التطبيق كاملاً (HTML + CSS + JS)
└── README.md
```

## الترخيص

© TawasoL.assist — جميع الحقوق محفوظة.
