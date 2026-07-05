# ל.א.ה דיגיטל - אתר נחיתה סטטי

אתר תדמית מינימלי ל-ל.א.ה דיגיטל, מותאם לפריסה מהירה דרך GitHub ו-Vercel.

## מה יש כאן

- `index.html` - עמוד נחיתה בעברית, RTL, עם SEO בסיסי.
- `styles.css` - עיצוב מלא ללא ספריות חיצוניות.
- `assets/logo.svg` - לוגו טקסטואלי תואם שפה מותגית.
- `assets/favicon.svg` - אייקון בסיסי לדפדפן.
- `assets/og-image.svg` - תמונת שיתוף לרשתות.
- `vercel.json` - כותרות אבטחה בסיסיות.

## לפני העלאה לאוויר

ב-`index.html`, החלף:

- `REPLACE_WITH_REAL_EMAIL` במייל אמיתי.
- `REPLACE_WITH_PHONE` במספר WhatsApp בפורמט בינלאומי, לדוגמה: `972501234567`.
- אם יש דומיין סופי, הוסף אותו להגדרות ה-Open Graph ולסייטמאפ בעתיד.

## העלאה ל-GitHub

```bash
git init
git add .
git commit -m "Initial LEA Digital landing page"
git branch -M main
git remote add origin https://github.com/YOUR_USER/lea-digital.git
git push -u origin main
```

## פריסה ב-Vercel

1. פתח Vercel.
2. לחץ Add New Project.
3. בחר את הריפו `lea-digital` מתוך GitHub.
4. Framework Preset: `Other`.
5. Build Command: להשאיר ריק.
6. Output Directory: להשאיר ריק.
7. Deploy.

זה אתר סטטי, לכן אין צורך ב-env vars, דטהבייס או Build מורכב.
