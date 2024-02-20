הנחיות כלליות 
1.	HTML

בתיקיית VIEWS נמצא קוד HTML לכל עמוד שיצרנו לאתר שלנו שמהווה את המבנה שלו , שם העמוד מתבטא בשם הקובץ ואפשר להבין למה הוא העמוד.  
בכל עמוד נמצא כפתורים מצד ימין למעלה שמבטאים navigation bar .

2.	CSS
לכל מבנה עמוד שנכתב ב-HTML עיצבנו את המסך שלו לפי קובץ הסטייל באותו שם של העמוד, לכל עמוד קיים קובץ CSS משלו וכולם נמצאים בתיקיית STYLES.
שלבנו אנימציה בעמוד הביית, בנוסף אנימציות לכפתורים מסוג "submit" 
במהלך העיצוב מורגש שקיימים עיצובים מאוד דומים בין העמודים השונים, אנו עשינו זאת  על מנת לשמור על אחדות מראה מסכים ובגלל הדרישה לצור קובץ CSS בנפרד לכל מסך.

3.	JAVA SCRIPT
יצרנו 4 קבצים של java script 
1.	SwichPages : המטרה הייתה לעבור בצורה חלקה בין העמודים דרך ה-navigation bar
2.	CustomerRegister : מטרתו לצור לקוח חדש שנרשם כעת
3.	Booking : זהו השירות המרכזי שהאתר שלנו נותן ללקוח, המטרה היא לקבוע שיעור חדש בסטודיו שלנו.
4.	CustomerSignIn : זהו המקום ללקוח שרשום כבר להתחבר ושיוכל לעבור לפרופילו האישי.

שני האיווינטים המרכזיים שלנו הן הרשמת לקוח חדש, והזמנת שיעור ספורט. אשר בלחיצה דיי קלה הלקוח יכול לעשות זאת. איווינט נוסף הוא. sign in  

4.	פונקציונאליות
-	באמצעות register form  אנו קולטים את הנתונים שהלקוח הזין ואז מוודאים כל מני validation functions  שנמצאים בתוך CustomerRegister.js
-	באמצעות עמוד book lesson  הלקוח מזין את הנתונים לשיעור שברצונו להזמין, אנחנו קולטים אותם ובודקים גם וולידציה, במידה וכן הצליח התהליך להזמין שיעור אנחנו מעדכנים את הלקוח בהודעה. תהליך זה מטופל בקובץ Bookin.js
-	קיימת אפשרות ללקוח לבטל שיעור שכבר הזמין וגם לצפות בשיעורים גם עתידים וגם שעברו באמצעות הלחיצה על כפתור update במסך view my bookings .
-	בגלל שעוד לא יצרנו בסיס נתונים ו-server לקוח מצליח לעשות signIn רק אם הוספנו אותו לרשימת הלקוחות הזמנית שיצרנו בקוד פשוט.

