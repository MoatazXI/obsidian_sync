اي حاجه بنعملها فالداتابيز ب create تعتبر اوبجكت 
زي table  , view , sequence , index , synonym , function , stored procedure


كل اوبجكت ليه مسار بيتسمي بيه 
\[ServerName].\[DbName].\[SchemaName].\[ObjectName]

يعني انا كنت بستخدم from اسم الجدول مباشرة بس مش ده الطبيعي كان لازم يسبقها باقي الداتا علشان اجيب الجدول صح
ف انا كنت عامل كونيكت علي السيرفر ف هو عارف اسم السيرفر ضمنيا
وعامل use للداتابيز ف برضو عارفها ضمنيا
والdefault schema اسمها dbo ف هو عارفها ضمنيا
علشان كده لما كنت بكتب اسم الجدول مباشرة كان هو عارف انهي جدول
لاكن لو الجدول في schema ,db , server مختلف كان لازم اكتب المسار بتاعه الي يوصلني للاوبجكت بالظبط


اقدر اعمل كويري علي جداول مختلفه من سيرفرات او داتابيز مختلفه ب اني اكتب المسار بتاعهم