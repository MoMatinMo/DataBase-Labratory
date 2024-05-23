# DataBase-Labratory
# Mohammad Matin Mohammadi
The Homeworks And Researches Of Database Class At Shamsipour University
Created By Mohammad Matin Mohammadi 

<div dir="rtl"> 
  <h1>تفاوت sql  و nosql</h1>
بانک‌های اطلاعاتی SQL به صورت اصلی با عنوان بانک اطلاعاتی رابطه‌ای یا RDBMS شناخته می‌شود؛ بانک‌های اطلاعاتی NoSQL به عنوان بانک اطلاعاتی غیر رابطه‌ای و توزیع شده شناخته می‌شود.
بانک‌های اطلاعاتی SQL داده‌ها را در جداول و ستون ها ذخیره می‌کند، در بانک‌های اطلاعاتی NoSQL ذخیره سازی مبتنی بر سندات، key-valueها، گراف‌ها و wide-column است.
بانک‌های اطلاعاتی SQL تمرکز و تاکید بسیاری روی موضوع ACID که مخفف (Atomicity, Consistency, Isolation and Durability) است تمرکز دارد، درحالیکه NoSQL روند CAP را اجرا می‌کند که مخفف (Consistency, Availability and Partition tolerance) است. 
برای محیط‌هایی با تراکنش بسیار زیاد، بانک‌های اطلاعاتی SQL توانایی بهتری را از خودشان نشان داده‌اند، این مورد برای اپلیکیشن‌هایی با حجم داده بالا بسیار مناسب هستند.
مقیاس‌پذیری در بانک‌های اطلاعاتی مدل رابطه‌ای بسیار سخت است و تقریبا نیاز دارد که کلیت بانک اطلاعاتی را تغییر دهید، این در حالی‌ست که تغییر دادن و توسعه یک بانک اطلاعاتی در سیستم بانک‌های اطلاعاتی NoSQL بسیار ساده‌تر و روند آسان‌تری دارد.
  <h3>-----------------------------------------------------------------------------------------------------------------------------</h3>
  <div dir="rtl">  
  <h1>مقایسه oracle , mysql , sqlserver</h1>
  
در مورد SQL Server باید بگویم این نرم افزار دارای قیمت بالایی هست که برخی فکر میکنند MySql و Sql Server یکی هستند اما این اشتباه است و این دو با هم رقیب هستند یعنی توسط دو شرکت رقیب ساخته شده است البته در مقایسه MySql و SQL Server باید بگویم بطور کلی، MS SQL Server امکانات بیشتری از MySQL داره ولی در Ranking بانک اطلاعاتی MySql رتبه دوم را به خود اختصاص داده است لازم به ذکره که مجانی بودن MySQL باعث شده که در کارهای با حجم متوسط، بیشتر از MySql استفاده شه.
نصب اوراكل از SQL Server بسيار مشكل‌تر است و البته كار كردن با اوراکل بسیار سخت تر ولی SQL Server همانند تمامی محصولات مایکروسافت به سمت user friendly رفته و کار با تمامی محصولات مایکروسافت بسیار ساده تر و کاربر پسند تر است و این یکی از دلایلی است که اکثر برنامه نویسان به سمت SQL Server گرایش پیدا میکنند.
Rank Of Databases:
1-Oracle -> Relational DBMS        Score ->1459.79
2-Mysql  -> Relational DBMS        Score ->1258.58
3-Microsoft Sql Server             Score ->1200.05
<h3>-----------------------------------------------------------------------------------------------------------------------------</h3>

<h1>Caching Server</h1>
کش سرور (Cache Server) یک سرور شبکه یا سرویس در سرور است که صفحه‌های وب و محتوای اینترنت را در خود ذخیره می‌کند؛ این کار باعث می‌شود تا در دفعات بعدی مراجعه به یک صفحه، درخواست کاربر براساس اطلاعات ذخیره‌شده در حافظه پنهان یا همان Cache، خوانده شوند. این موضوع باعث می‌شود که سرعت بارگذاری صفحات وب با سرعت بیشتری انجام شود. درواقع زمانی که کاربر برای اولین بار به یک سایت مراجعه کند، مرورگر او درخواستی را به سرور ارسال می‌کند.

<h1>Log Stash</h1>
  يک موتور پردازش رويداد است که توسط شرکت Elasticsearch، Kibana و غيره توسعه يافته است. Logstash اغلب به عنوان يک بخش کليدي از پشته ELK يا Elastic Stack استفاده مي شود، بنابراين هم افزايي قوي با اين فناوري ها ارائه مي دهد.

شما مي توانيد از Logstash براي پردازش انواع مختلف رويدادها استفاده کنيد، و يک رويداد مي تواند چيزهاي زيادي باشد.

مي‌توانيد گزارش‌هاي دسترسي يا خطا را از يک سرور وب پردازش کنيد، يا مي‌توانيد رويدادها را از يک برنامه تجارت الکترونيک به Logstash ارسال کنيد، مانند زماني که سفارشي دريافت شد يا پرداختي پردازش شد.

مي‌توانيد داده‌ها را از فايل‌ها دريافت کنيد (فايل‌هاي مسطح، JSON، XML، CSV، و غيره)، داده‌ها را از طريق HTTP يا TCP دريافت کنيد، داده‌ها را از پايگاه‌هاي داده بازيابي کنيد و موارد ديگر.

سپس Logstash شما را قادر مي سازد تا رويدادها را قبل از ارسال به مقصد مورد نظر خود پردازش و دستکاري کنيد، مانند Elasticsearch، OpenSearch،


<h1>Data Warehouse</h1>
انـبـار داده بـه مجـموعـه‌ای از داده‌هــا گفـتـه می‌شود که از منابع مختلف اطلاعاتی سازمان جمع‌آوری، دسته‌بندی و ذخیره می‌شود.
انبار داده یا Data Warehouse پایگاه داده‌ای است که برای گزارش‌گیری و تحلیل داده به کار می‌رود و بعنوان هسته اصلی یک سیستم هوش تجاری BI به شمار می‌آید. به عبارت دیگر انبار داده یک مخزن داده مرکزی از داده‌های تجمیع شده است که از سیستم‌ها و منابع مختلف سازمان جمع‌آوری شده است.

</div>
<div dir="rtl"> 
<h1>استاندارد پایگاه داده برای یک فروشگاه</h1>
ساختار پایگاه داده فروشگاه آنلاین باید بسیار در دسترس، تحمل پذیر در برابر خطا، و بسیار پاسخگو باشد تا تجربه خریدی روان و لذت بخش را به مشتریان ارائه دهد. هنگام طراحی ساختار پایگاه داده فروشگاه آنلاین، می توان آن را به سه جزء اصلی برای دسته بندی و درک بهتر ساختار داده زیربنایی تقسیم کرد:

داده های ایستا
داده های نشست
داده های پردازش شده

 
1. داده های ایستای فروشگاه آنلاین
این مؤلفه شامل داده های تا حدی ثابت است که مشتری تنها برای بازیابی آنها در هنگام تعامل با فروشگاه آنلاین به آن نیاز دارد. داده ها در انواع جداول زیر ذخیره می شوند:

2. داده های نشست فروشگاه آنلاین
این مهمترین جزء پایگاه داده فروشگاه آنلاین است که در آن تمام تعاملات زنده (جزئیات جلسه) زمانی که مشتری در حال تعامل با فروشگاه آنلاین است ذخیره می شود.

3.داده های پردازش شده فروشگاه آنلاین
هنگامی که مشتری یک تراکنش را تکمیل کرد، باید اطلاعات سفارش را با انتقال داده های جلسه به فضای ذخیره دائمی به طور دائم ذخیره کنیم. علاوه بر این، ما باید جزئیات پرداخت را نیز ذخیره کنیم.

<h3>-----------------------------------------------------------------------------------------------------------------------------</h3>
 <div dir="ltr">  
   <h1>Data Types In Database</h1>
  <h2> Numeric Data Types<h2>
Numeric data types are used to store numbers. They can be further categorized into:
Integer: Stores whole numbers without decimal points.
Decimal/Float: Stores numbers with decimal points.
Double: Stores double-precision floating-point numbers.

 Character Data Types
Character data types are used to store text values. Common character data types include:
Char: Fixed-length character strings.
Varchar: Variable-length character strings.
Text: Used for large text data.

 Date and Time Data Types
Date and time data types are used to store temporal data. Common date and time data types include:
Date: Stores date values.
Time: Stores time values.
Datetime/Timestamp: Stores both date and time values.

 Binary Data Types
Binary data types are used to store binary data like images, files, etc. Common binary data types include:
Blob: Stores large binary objects.
Binary: Fixed-length binary data.
Varbinary: Variable-length binary data.
</div>


