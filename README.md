# דישראלי 14 חיפה - אתר מכירת דירות

אתר סטטי (בלי שרת ובלי בנייה). הקבצים:

- `index.html` - הדף עצמו (עיצוב ותצוגה)
- `data.js` - כל התוכן: מחירים, קומות, סטטוס "נמכרה", תיאור ומפרט. כאן עורכים.
- `images/` - הדמיית הבניין ותוכניות הדירות

## עדכון
- מחיר או קומה: לשנות את הערך בשורה של הדירה ב-`data.js`.
- דירה שנמכרה: לשנות `"sold": false` ל-`"sold": true`.
- להחזרת באנר "דירות פנויות": `pills: true`.
- תמונה חדשה: להחליף את הקובץ בתיקיית `images/` באותו שם.

## העלאה
1. GitHub: ליצור repository חדש ולהעלות את כל הקבצים (Add file > Upload files).
2. Netlify: Add new site > Import an existing project > GitHub, לבחור את ה-repository.
   Build command - להשאיר ריק. Publish directory - להשאיר ריק (או `.`).
3. כל שינוי שנשמר ב-GitHub יתפרסם אוטומטית ב-Netlify.
