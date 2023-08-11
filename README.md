# JohnTheRipper in Arabic
في هذا المقال راح اتكلم عن اداة john the ripper 

هي اداة مفتوحة المصدر وتقوم مهمة هذه الاداة بكسر كلمات المرور عن طريق ثلاث طرق مختلفة.
اول استعمال لهذه الاداة كان على نظام اليونكس لكن تم تطويره حتى اصبحت تعمل على خمسة عشر نظام تشغيل مختلف.

تتوفر نسخة مدفوعة من هذه الاداة بمميزات اكثر من النسخة المجانية.

يتم استخدام الاداة من خلال ال CMD ولكن هناك نسخة تسمى Johnny تتوفر فيها واجهة مستخدم.

ابرز نقاط قوة اداة john the ripper تتلخص في :
1- انها قوية في كسر كلمات المرور.
2-سريعة في كسر كلمات المرور.
3-استخدام الاداة في مختلف انظمة التشغيل.
4- انها توفر نسخة مجانية و نسخة مدفوعه.
5- تقوم بكسر كلمات المرور بأكثر من طريقة.
6- التحديثات المستمرة للأداة.


ابرز عيوب اداة john the ripper تتلخص في : 
1- صعبة الاستخدام بالنسبة للمبتدئين.
2- يتم استخدامها لأهداف ضارة.
3- تاخذ وقت كبير لكسر كلمات المرورة المعقدة.
4- تستهلك الكثير من موارد الجهاز في عملية كسر كلمات المرور.


john the ripper
تكسر كلمات المرور عبر ثلاث طرق:

1- brute-force:
هذا النمط يدعى بالقوة الغاشمة ، ويعتبر هذا النمط بطيء مقارنة بالانماط الاخرى.
يعمل هذا النمط على تخمين كلمة المرور ويقوم بتجربة كل حرف وكل رقم حتى يخرج بهاش مساوي للهاش المطلوب كسره.
هذا النمط يستهلك موارد و كثيره و وقت كبير لكنه سيكسر كلمة المرور مهما طال الوقت.

العوامل المؤثرة في هذا النمط :
- طول كلمة المرور : كل ما طالت كلمة المرور استغرق هذا النمط وقت اكبر لكسرها.
- تعقيد كلمة المرور : كل ما كانت كلمة المرور تحتوي على حروف كبيره و صغيره ورموز وارقام كان كسرها صعب. 
- نوع الهاش المستخدم : بعض الهاشات تكون سهلة الكسر ولا تحتاج وقت كبير.

2- dictonary attack
في هذا النمط يتم وضع قاموس لأشهر كلمات المرور المستخدمة ، ويعتبر هذا النمط سريع نسبياً.
لأنه يتم مقارنة هاش كلمة المرور المراد كسرها بكل هاش موجودة في القاموس اذا تساوت الهاش يتم الحصول على كلمة المرور ، لكن نسبة نجاحها تكون معدومة في حال كانت كلمة المرور غير مدرجة في القاموس.


العوامل المؤثرة في هذا النمط :
-حجم القاموس.
-تعقيد كلمة المرور.
-نوع الهاش المستخدم.


3- single crack 
هذا النمط هو الاسرع بين الانماط ، لكنه هو يملك اقل نسبة نجاح في كسر كلمات المرور.

يقوم مستخدم الاداة بإعطاء الاداة اسم المستخدم او اسم الشخص المطلوب.
فتقوم الاداة بتحويل اسم المستخدم الى كلمة مرور عن طريق اضافة بعض الرموز على اسم او الارقام.

مثلاً لنفترض ان اسم المستخدم هو Faisal.

يقوم النمط على اضافة رموز او ارقام ل اسم المستخدم وتحويله الى هاش ومقارنته مع كلمة المرور المراد كسرها اذا تساوت يتم الحصول على كلمة المرور 

النمط يحول اسم المستخدم Faisal الى Fai5al او Faisal123 او Faisal321 وهكذا ...




الخلاصة :
تعد (John the Ripper) أحد أفضل أدوات الأمان التي يمكن استخدامها لاختراق كلمات المرور
و من اهم المقاييس لقياس قوة كلمات المرور .



المراجع :

John the Ripper website: https://www.openwall.com/john/
John the Ripper manual: https://www.openwall.com/john/doc/
John the Ripper tutorial: https://www.esecurityplanet.com/products/john-the-ripper/
