# تجربتي مع اختبار Ejpt-v2 

![ejpt_page-0001](https://github.com/Amalalsuhaimi/ejptv2-experience/assets/56334190/f7778cb0-c96d-49e4-be95-a0c96741ce92)

#	نبذة مختصرة عن Ejptv2 
اختبار اختراق (عملي) مصمم للمبتدئين في عالم الاختراق. مقدم من INE بالتعاون مع elearnsecurity.
تحتوي النسخة الثانية من الاختبار علي ٣٥ سؤالاً و مدة الاختبار يومين ( ٤٨ ساعة ) .

نوع الاختبار Open-book (أي تستطيع العودة للمنهج او ملاحظاتك واستخدام قوقل أيضاً (لن تجد إجابة مباشرة لأسئلة الامتحان ولكن قد تجد بعض الأدوات والاجراءات المساعدة في ذلك).

نمط الأسئلة: هناك نوعين من الأسئلة، اختياري والبحث عن العلم وتقديمة كإجابة (الإجابات تعتمد على المعلومات التي تم جمعها عند تطبيق مراحل الاختراق على الأجهزة المتاحة)

هيكلة الامتحان: عبارة عن مجموعة أجهزة داخل  DMZ يتم اختراقها و أحد هذه الأجهزة مرتبط بشبكة آخرى يوجد بها جهاز قابل للاختراق و تسمى هذه العملية pivoting . كل ما عليك اختراق هذه الأجهزة من خلال الأدوات والاستراتيجيات التي تم دراستها وثم الإجابة على الأسئلة بشكل صحيح. لتفاصيل أكثر عن هيكلة الامتحان ابحث عن letter of engagement ejptv2 .

لا يوجد متطلبات معينه لأخذ الشهادة، ولكن يفضل ان يكون هناك معرفة سابقة بأساسيات الشبكات، أنظمة التشغيل وأحد لغات البرمجة.


# سعر الإختبار
سعر الاختبار بدون برنامج التدريب الخاص بالشهادة ≈ ٢٠٠ دولار.

او يكمن الحصول على العرض المقدم من INE  ٣ أشهر البرنامج التدريبي مع ٦ أشهر صلاحية الاختبار = ٢٤٩ دولار 



# درجة النجاح في الإختبار 
درجة النجاح في الاختبار ٧٠٪ فأعلى أي حل ٢٥/٣٥ سؤال بشكل صحيح. يرتكز الاختبار على ٤ محاور أساسية وهي:
![image](https://github.com/Amalalsuhaimi/ejptv2-experience/assets/56334190/737b14b6-3e18-4c6e-b79c-be0337e57948)  
１-	Assessment Methodologies  
２-	Host & Network Pentesting  
３-	Web Application Pentesting  
４-	Host & Network Auditing  

كما موضح في الصورة [1]، كل قسم يحتوي على عدة مهام أساسية يتم التقييم عليها من خلال الإجابة على أسئلة الاختبار.  

![photo_1445-07-12 11 59 40](https://github.com/Amalalsuhaimi/ejptv2-experience/assets/56334190/334ae4f1-67d1-4e21-bd08-8608d63e0803)    


# التحضير للاختبار  

هناك عدة وسائل مساعدة للاستعداد لهذا الاختبار. سأبدأ بسرد طريقتي في الاستعداد له ومن ثم بعض المصادر المجانية المساعدة للاستزادة.  

__１-	البرنامج التدريبي من (PTS) INE :__      


توفر منصة ine برنامج تدريبي مخصص لهذة الشهادة وهو ما بدأت الاستعداد به. 
يحتوي هذا البرنامج على ٤ أقسام، ١٢ درس، ٢٣٩ فيديو، ١٦٤ كويز، ١٢١ لاب  أهمها لاب الصندوق الأسود.
سعر البرنامج التدريبي ٣٩ دولار/ شهر 
صفحة البرنامج التدريبي ( https://shorturl.at/eDGI4 )


فكرة البرنامج التدربي قائمة على التكرار بحيث يسترجع معلومة سابقة بإضافة لمعلومة جديدة لتسهيل ربط وترسيخ مراحل الاختراق.. الصورة [2]  ملخص للمراحل الاختراق الثلاث بشكل مبسط ومساعد لفهم ماهيتها:  

1- جمع المعلومات Enumeration  
2- استغلال الثغرة Exploitation  
3- مابعد استغلال الثغرة Post Exploitation  


<img width="1214" alt="Screenshot 1445-07-12 at 5 58 40 PM" src="https://github.com/Amalalsuhaimi/ejptv2-experience/assets/56334190/046bf47d-a67f-40e2-9248-c6ffedb43cac">   


<img width="1035" alt="Screenshot 1445-07-12 at 7 05 19 PM" src="https://github.com/Amalalsuhaimi/ejptv2-experience/assets/56334190/34f38db8-760c-43b5-88b4-ade27e4807a3">




__2-	منصة Tryhackme :__  


توفر هذه المنصة شروحات و لابز مجانية لممارسة بعض الموضوعات المتعلقة بإختبار الاختراق. الصورة [4] توضح جميع اللابزالمطلوب معرفتها و التعلم منها بالإضافة  إلى لابز اخرى CTF لممارسة و تطبيق ما تم تعلمه في شروحات المنصة. 

صفحة منصة tryhackme  ( https://tryhackme.com/ ) 

<img width="1029" alt="Screenshot 1445-07-12 at 7 22 54 PM" src="https://github.com/Amalalsuhaimi/ejptv2-experience/assets/56334190/a6d91a3b-1e70-4f37-addb-713756a1ec93">



__3-	ملاحظات Helpful notes :__

هنا بعض الملاحظات الجاهزة Online  لكل الأدوات المستخدمة في كل مرحلة من مراحل الاختراق موثقة بعضها من قبل مختبرين سابقين. 
مسردة حسب الأهم فالاهم:


HackTricks  (https://book.hacktricks.xyz/) 

INE Training Notes (https://blog.syselement.com/ine/)

eJPTv2-CheatSheet (https://sezioss-gitbook.gitbook.io/ejptv2cheatsheet/) 

ejptv2-Notes (https://github.com/PakCyberbot/eJPTv2-Notes) 

AllThingsPayloads (https://github.com/swisskyrepo/PayloadsAllTheThings)  




# ما أنصح به 

-	انصح ببرنامج PTS الذي سبق وذكرته في الاختيارات السابقة عند الاستعداد للاختبار (يكفي عن غيره وضمان  لتجاوز الامتحان  في حال درسته جيداً بإذن الله)
-	وضع خطة لإتمام البرنامج التدريبي وتحديد يوم الاختبار في الخطة 
-	آكتب ملاحظاتك بشكل جيد و يفضل تكون في أحد برامج الملاحظات مثل  Onenote ليسهل العودة إليها و استخدامها في الإختبار.  
-	أجعل قوقل صديقك وطبق مهارة البحث عند عدم معرفة شيء معين 
-	مارس ماتعلمته جيداً و أرى عادة اللابز مرتين و بالأخص لاب الصندوق الأسود في windows  و  linux (مشابة للإختبار)
-	استمتع بالامتحان و خذ وقتك و لا تعجل الوقت وفير 
-	اذا انهيت الإجابة على جميع الاسئلة و تبقى وقت لديك عدّ و مارسه مره أخرى أرها فرصة جيدة لتثبيت ما تعلمت.


  أتمنى ان تكون تجربتي و ما تم تلخيصة مفيداً و معيناً .. كل التوفيق و السداد



