<div dir="rtl">

# להבין ECMAScript 6

מאת ניקולאס סי. זאקאס

[![Creative Commons License](http://i.creativecommons.org/l/by-nc-nd/3.0/88x31.png)](https://creativecommons.org/licenses/by-nc-nd/3.0/)

ECMAScript 6
מהווה את השינוי הגדול ביותר שעבר על מה שידוע לנו כ
JavaScript
מאז שנוצרה השפה. המהדורה השישית
הוסיפה לא רק משתנים חדשים אלא גם תחביר חדשני ויכולות חדשות.
המהדורה השישית הושלמה בשנת 2014
לאחר שנים של דיון
ועבודת הכנה מעמיקה.
למרות שיקח זמן מה עד שכל סביבות הג׳אווהסקריפט הקיימות יתמכו בה תמיכה מלאה,
רצוי וחשוב לדעת מה קיים כעת ומה עתיד לבוא.

הספר נועד לשמש כמדריך עבור המעבר בין מהדורה 5 ל-6 של השפה. הוא איננו מיועד לשמש עבור סביבת ריצה ספציפית, כך שהוא שימושי באותה המידה עבור מפתחים שעובדים בסביבת דפדפן
(מפתחי ווב)
או מפתחי 
Node.js

מה מכיל הספר:
* כל השינויים שחלו בשפה מאז מהדורה 5
* כיצד תחביר המחלקה החדש מתקשר למושגים מוכרים בשפה
* התועלת שבגנרטורים ואיטרטורים
* ההבדל בין פונקציות חץ לפונקציות רגילות
* אפשרויות חדשות לאחסון מידע בעזרת סטים, מפות ועוד.
* הכוח הטמון בירושה ממשתנים בסיסיים
* מדוע אנשים כה מתרגשים ממשתנה הפרומיס בנוגע לתכנות אסינכרוני
* כיצד מודולים ישפיעו על כתיבת הקוד שלך

## היכן לקרוא

[גרסת המוציא לאור](https://leanpub.com/understandinges6/read/)
זמינה בחינם ומכילה את הגרסה העדכנית ביותר.
התוכן לא בהכרח סופי אבל אמור להיות נכון. 
גרסאות חדשות מפורסמות מספר פעמים בחודש.

תוכן שאינו מופיע בגרסת המו״ל נחשב לתוכן לא מושלם וייתכן שיכיל חסרים או שגיאות.

המו״ל הינו חברת לינפאב
(Leanpub)

## רכישת עותק דיגיטלי

ניתן לרכוש עותק דיגיטלי של הספר דרך חברת
[Leanpub](https://leanpub.com/understandinges6). 
במידה ותרכוש עותק לפני שהספר יושלם, תקבל את כל העדכונים לספר בזמן העדכון כולל הגרסה הסופית.

## רכישת עותק מודפס

הספר מודפס על ידי חברת 
No Starch Press
וניתן
[לרכוש עותק באמזון](http://amzn.to/22YQOer).
גרסת הדפוס מופצת לאחר עריכה מקצועית

## תמיכה במחבר

אם נהנית מהספר ותרצה לתמוך במאמציי ליצירת תוכן חדש, קיימות מספר דרכים:

* [השאר טיפ](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=EFQLNGT3QEL6J) בפייפאל
* [הפוך לפטרון](https://patreon.com/nzakas) ב Patreon

תרומה קטנה תעזור מאוד להמשיך בעבודתי.

## השתתפות בתוכן

למרות שהספר נכתב בדרך של שיתוף תוכן, הפרויקט פועל תחת תנאים שונים מפרויקט קוד פתוח
נא לקרוא את ההמשך לפני הוספת תוכן משלך.

### תחביר של Leanpub

Leanpub
עובד בסגנון מיוחד עבור קבצי המקור. יש לעיין 
[בדוקומנטציה](https://leanpub.com/help/manual#leanpub-auto-styling-text)
לגבי המותר והאסור.

**שים לב:** 
Leanpub
לא נותנים תמיכה לכל האפשרויות הקיימות בסגנון כתיבה רגיל המצוי בגיטהאב

### בקשות שינוי
בקשות שינוי
PR (Pull Requests)
יתקבלו רק עבור *תיקונים*
ולא עבור *יצירת תוכן*

בקשות שינוי שיתקבלו:

* שגיאות כתיב
* שגיאות תחביר
* תיאורים אלטרנטיביים
* הבהרות

עקרונית, ניתן להגיש בקשות שינוי כדי לתקן את מה שקיים בקוד אבל לא להוסיף אליו

**הערה:** בקשת שינוי שהתקבלה משמעותה ששמך יתווסף לרשימת התורמים
תורמים עדיין כפופים לתנאי הרשיון, כלומר אינך נחשב ליוצר או בעלים של התוכן לאחר שהוכנס לקוד. הדבר נחשב לתרומה של מאמץ ליצירת הספר.

### סוגיות (Issues)
באמצעות סוגיות ניתן להצביע על שגיאות כמו גם להציע שינויים.
ניתן להשתמש בסוגיות בשביל:

* שאלות בנוגע לתוכן
* הערה על שגיאה או בעיה בתוכן
* בקשה ליותר אינפורמציה על חלק מהתוכן

כל סוגיה פתוחה תקבל מענה. סוגיות ייסגרו לאחר שקיבלו מענה או במידה והסוגיה לא תקבל מענה.

אין לפתוח סוגיות עבור:

* שאלות מתי תוכן מסויים יושלם
* כל דבר שמסומן בקבצים בתור ״ TODO״

## זכויות יוצרים ורשיון
זכויות יוצרים שייכות לניקולאס סי. זאקאס 2014-2016

יצירה זו מופיעה תחת רשיון מסוג 
[Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Unported License](http://creativecommons.org/licenses/by-nc-nd/3.0/).

## שאלות 

### מתי יושלם הספר?

הספר הושלם מבחינת תוכן מתאריך 10 ביוני 2016.

### אם ארכוש את הספר עכשיו, האם אקבל את הגרסא הסופית?

כן. כאשר תרכוש עותק אלקטרוני של Leanpub , תקבל גם את כל העדכונים לספר. עדכונים יתקבלו באמצעות דואר אלקטרוני לאחר הרכישה.

### באיזו תדירות מפורסם הספר?

בערך כל שבוע עד שבועיים השינויים ב Github מפורסמים תחת Leanpub

### כיצד להתייחס לתוכן בגיטהאב?

כל מה שמופיע בגיטהאב נחשב לתוכן בתהליך יצירה.
החלקים שנחשבים לנכונים ומסודרים מפורסמים תחת
Leanpub. 
זו הסיבה שקיים יותר תוכן בגיטהאב מאשר בלינפאב, 
מאחר וגיטהאב מכיל את התוכן כולו, כולל תוכן שעוד לא פורסם.

### מה ההבדל בין הגרסא המודפסת לבין גרסת לינפאב?

הנושאים והסדר שבו הם מופיעים בספר זהים בין הגרסאות. ההבדל הוא במספר מילים וביטויים ששונו על ידי עורכים למען בהירות או על מנת לשמור על סגנון הכתיבה של חברת 
No Starch. 
השינויים האלו לא מועברים ללינפאב מכיוון שהם מתרחשים בתוך קבצים בפורמט 
PDF 
ולפעמים בצורה לא ברורה, כך שקשה לשמור על שתי הגרסאות מסונכרנות זו עם זו.

### האם ניתן לרכוש זכויות תרגום

כן. יש ליצור קשר עם חברת
[No Starch Press](https://www.nostarch.com/) 
למען רכישת זכויות תרגום

</div>