# Solve_SSRF_in_Burbsuite_Arabic

بسم الله الرحمن الرحيم

ما هي أداة Burp suite؟

أداة Burp Suite و هي أداة اختراق و حماية متاحة لكل من نظام اللينكس، الـ Mac OS و أيضا الويندوز تم تطويرها من طرف شركةPortswigger .
وهي برمجية متاحة بـ 3 نسخ منها الـ Professional والـ Enterprise والـ Community، كل من نسخة Pro وEnterprise مدفوعتين ويمكن تجربتهما بالمجان لفترة محدودة، ونسخة Community متاحة بشكل مجاني مع نقص في بعض البرمجيات والخصائص.
في الغالب نجد نسخة الـ Community في أنظمة مختلفة جاهزة كنظام Kali Linux.
أداة Burp Suite هي أداة اختراق لتطبيقات الويب و تعتمد على عدة تقنيات تؤهلها لتصير كذلك و تعتبر واحدة من اشهر أدوات الاختراق في العالم لذلك. 

شرح خطوات تطبيق ثغرة   SSRFباستخدام أداة Burpsuite 
اللاب الأول:

1-ضبط اعداداتFoxyproxy  على المتصفح

2- ضبط اعدادات Burpsuite 

3- الضغط على Proxy للتفعيل

4- الضغط على intercept on

5 reload target page تحديث صفحة الويب المستهدفه

6- الضغط على right click  ومن ثم اختيار  send intercept to repeater. 

7-ومن ثم تحديد الرابط المرفق تحت مسمى Stckapi  و right click وعمل dencode 

8- تغيير رابط StckApi  الى change url to http://localhost/admin  

9- تحديد رابط stockapi وright click  وعمل encode

10-ومن ثم click  على send intercept

تهانينا لقد نجح الهجوم.















![image](https://github.com/1mubark/Solve_SSRF_in_Burbsuite_Arabic/assets/141992293/3c3e0bab-16a2-4226-8af7-6f7c4188d6ff)

