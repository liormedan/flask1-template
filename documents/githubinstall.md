## חיבור ויצירת הרחבת גיטהאב לפרויקט

**הקדמה:**

הרחבת גיטהאב מאפשרת לך לשתף פעולה עם אחרים ולנהל את קוד המקור של הפרויקט שלך ב-GitHub.

**דרישות:**

* חשבון GitHub
* Git מותקן במחשב שלך
* פרויקט קיים

**הוראות:**

1. **פתח חלון טרמינל:**
    - **Windows:** לחץ לחיצה ימנית על תפריט התחל ובחר "Windows PowerShell".
    - **Mac:** פתח את "Terminal" מ-Applications/Utilities.

2. **עבור לתיקיית הפרויקט:**

```
cd /path/to/your/project
```

3. **הוסף remote:**

```
git remote add origin https://github.com/your-username/your-project-name.git
```

4. **דחוף את השינויים:**

```
git push origin master
```

**הערה:**

* החלף את `your-username` בשם המשתמש שלך ב-GitHub.
* החלף את `your-project-name` בשם הפרויקט שלך.
* ודא שאתה נמצא בענף `master` לפני שתדחוף את השינויים.

**יצירת הרחבה:**

1. **באתר GitHub:**
    - עבור לפרויקט שלך ב-GitHub.
    - לחץ על "Settings".
    - לחץ על "Extensions".
    - לחץ על "New Extension".
    - הזן שם ותיאור עבור ההרחבה.
    - לחץ על "Create Extension".

2. **בקובץ manifest.json:**

    - הוסף את שם המשתמש שלך ב-GitHub תחת `author`.
    - הוסף את שם הפרויקט שלך תחת `name`.
    - הוסף תיאור עבור ההרחבה תחת `description`.
    - הוסף את גרסת ההרחבה תחת `version`.
    - הוסף את נתיב קובץ JavaScript עבור ההרחבה תחת `main`.

3. **בקובץ JavaScript:**

    - כתוב קוד JavaScript עבור ההרחבה.
    - השתמש ב-API של GitHub כדי לגשת למידע ולנהל את הפרויקט.

4. **פרסום ההרחבה:**

    - לחץ על "Publish Extension".

**טיפים:**

* השתמש ב-GitHub Pages כדי לארח את אתר ההרחבה שלך.
* השתמש ב-GitHub Actions כדי לבנות ולבדוק את ההרחבה שלך.
* השתמש ב-GitHub Marketplace כדי לקדם את ההרחבה שלך.

**משאבים:**

* GitHub documentation for extensions: [https://docs.github.com/en/developers/apps/building-github-apps/creating-a-github-app](https://docs.github.com/en/developers/apps/building-github-apps/creating-a-github-app)
* GitHub API documentation: [https://docs.github.com/en/rest](https://docs.github.com/en/rest)

**הערה:**

ההסבר למעלה הוא סקירה כללית בסיסית. ייתכנו צעדים נוספים בהתאם לפונקציונליות הרצויה של ההרחבה שלך.
