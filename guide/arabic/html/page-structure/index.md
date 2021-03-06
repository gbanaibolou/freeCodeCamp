---
title: Page Structure
localeTitle: هيكل الصفحة
---
## هيكل الصفحة

لإنشاء صفحاتك في `HTML` ، تحتاج إلى معرفة كيفية تنظيم صفحة `HTML` ، حيث أن هيكلية الصفحة تتبع الترتيب التالي:

 `<!DOCTYPE html> 
 <html> 
  <head> 
    <title>Title of the Page</title> 
  </head> 
  <body> 
    <!-- Content --> 
  </body> 
 </html> 
` 

1 - يجب أن تكون العبارة `<!DOCTYPE html>` دائما أول من يظهر على صفحة `HTML` وتخبر المتصفح بنسخة اللغة المستخدمة. في هذه الحالة ، نعمل باستخدام `HTML5` .

2º - تخبر العلامات `<html>` و `</html>` متصفح الويب الذي تبدأ به شفرة `HTML` وينتهي بها.

3º - تحتوي العلامات `<head>` و `</head>` على معلومات حول موقع الويب ، وهو مثال: style ، meta-tags ، scripts ، الخ ...

4º - تخبر العلامات `<title>` و `</title>` المتصفح عن عنوان الصفحة. يمكن رؤية العنوان من خلال تحديد علامة التبويب في متصفح الإنترنت الخاص بك. النص الذي تم تعريفه بين هذه العلامات هو أيضًا النص المستخدم كعنوان بواسطة محركات البحث عندما يعرض الصفحات في نتائج البحث.

5º - بين علامتي `<body>` و `</ body>` ، يتم وضع محتوى الصفحة ، وهو ما يتم عرضه في المتصفح.

### التغييرات في HTML5

#### مقدمة من العلامات الدلالية

بدلاً من استخدام `<div>` لكل حاوية أخرى ، فهناك العديد من الدلالات الدلالية (تساعد هذه العلامات المحاكيات التي يتم استخدامها بشكل مرئي اختلال العلامات) مثل `<header>` `<footer>` . لذلك فمن المستحسن استخدام هذه العلامات بدلا من عام `<div>` .

#### معلومات اكثر:

[HTML: مقدمة](https://www.w3schools.com/html/html_intro.asp)