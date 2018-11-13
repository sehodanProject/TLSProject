קובץ README

להלן רשימת שמות הקבצים המצויים בתקיה זו:
1.	Project_book.docx
2.	Final_Presentation.pptx
3.	Proxy.py
4.	t1_enc.c

מיקום הקובץ t1_enc.c הוא במדריך הבא:
openssl-1.0.2n/ssl/t1_enc.c

המקור לקוד שרת הפרוקסי:
http://voorloopnul.com/blog/a-python-proxy-in-less-than-100-lines-of-code/

הסבר קצר אודות הקבצים המצורפים בהתאמה:
1.	מסמך המתאר את הפרויקט
2.	מצגת המסבירה על תהליך הכנת הפרויקט.
3.	קוד המכיל בין היתר את המימוש לשרת הפרוקסי. כל החבילות עוברות דרך שרת זה מפוענחות ע"י מחלקה בשם Descriptor ומנוטרות ע"י פונקציה בשם parse_data, שנוספו לקוד המקורי שמטרתן לפענח ולוודא את לגיטימיות חבילות המידע העוברות דרך הפרוקסי בדרכן אל היעד.
בנוסף, פונקציה בשם get_keys_from_client אחראית להעברת המפתחות מהלקוח ל-middlebox.
4.	זהו קובץ בקוד המקור של OpenSSL, בו מפתחות ה-session נוצרים.
בקובץ נוספה פונקציה בשם hexdump על מנת לחלץ את המפתחות לקובץ שיצרנו בתחילת הקוד ולהציגם בייצוג הקסהדצימלי, לשם נוחות קריאתם.

קישור ל-Repository באתר GitHub המכיל את קבצים:
גש
