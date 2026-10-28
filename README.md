# ميزان — تنزيل التطبيق

ميزان تطبيق لتسجيل الديون بين الناس والحسابات الشخصية، من قروب التقنية
الإلكترونية (ETG) في ليبيا. بياناتك المالية على هاتفك، والديون المرسلة بين
الأشخاص مشفّرة من طرف إلى طرف.

هذا المستودع لنسخ أندرويد فقط. لا يحتوي أي كود.

**آخر نسخة:** [Releases → Latest](../../releases/latest)

> النسخ الحالية تجريبية: الواجهة الحالية ليست النهائية، وواجهة جديدة قادمة.

## أي ملف أحمّل؟

| الملف | لمن |
|---|---|
| `…-arm64-v8a.apk` | أغلب الهواتف الحديثة |
| `…-armeabi-v7a.apk` | الهواتف القديمة |
| `…-universal.apk` | إذا لم تعرف نوع هاتفك (حجمه أكبر) |

إذا ثبّتَّ نسخة `arm64-v8a` أو `armeabi-v7a` فاستمر عليها في كل تحديث:
النسخة الشاملة (`universal`) لا تُثبَّت فوقها.

## التأكد من الملف

بجانب كل نسخة ملف `SHA256SUMS.txt`. قارن بصمة الملف الذي نزّلته بما فيه:

- Windows: `certutil -hashfile mizan.apk SHA256`
- macOS أو Linux: `sha256sum mizan.apk`

كل النسخ موقّعة بمفتاح ميزان نفسه، وهذه بصمة شهادته (SHA-256):

```
6F:86:DC:BB:17:34:69:AA:E8:34:0F:4E:C9:B3:1D:B2:10:16:A2:87:60:83:A4:A3:82:8D:22:16:80:7B:78:73
```

## الرخصة

جميع الحقوق محفوظة لقروب التقنية الإلكترونية (ETG). المسموح فقط تنزيل
الملفات وتثبيت ميزان على جهازك للاستعمال الشخصي. يُمنع نسخ الملفات أو
إعادة نشرها أو تعديلها أو الهندسة العكسية لها أو أي استعمال تجاري. النص
الكامل في [LICENSE](LICENSE).

## روابط

- الموقع: https://www.mizan-etg.com
- سياسة الخصوصية: https://www.mizan-etg.com/privacy
- قناة التحديثات على تيليقرام: https://t.me/mizan_updates

---

**Mizan** — Android downloads only; this repository holds no source code.
Current versions are test versions; the interface is not final. Pick
`arm64-v8a` for most phones, `armeabi-v7a` for older ones. Check each file
against `SHA256SUMS.txt`; every APK is signed with the certificate whose
SHA-256 is shown above.

All rights reserved by ETG. You may only download the files and install
Mizan on your own device for personal use; no copying, redistribution,
modification, reverse engineering or commercial use. See
[LICENSE](LICENSE).
