<div dir='rtl' align="center">
به نام پروردگار هدایت کننده به راه راست

  دانشگاه اصفهان

  ساختمان داده – دکتر رمضانی 

  پاییز ۰۲-۰۱

  پروژه سوم - ماشین حساب 


<img src="https://s25.picofile.com/file/8455118076/Picture55.png"  hieght="500"/>
  
  طراحان پروژه : امیرعلی گلی – محمد توکلی – علیرضا ساعی - حسین علیترکان
</div>


<div dir='rtl' align="justify">
  
### مبحث : پشته
  
اهداف پروژه :
+	کار با ساختمان داده پشته‌
+	آشنایی با عبارات میانوندی و پسوندی

 ----------
در این پروژه قرار است عملکرد یک ماشین حساب را شبیه سازی کنیم. عملیات جمع (+)، تفریق (-)، ضرب (*)، تقسیم (/)، توان (^) ، را باید پیاده سازی کنید. 

دقت داشته باشید که اعداد ورودی میتوانند از نوع اعشاری نیز باشد و برنامه شما باید "." (ممیز) را پشتیبانی کند.

  با توجه به اینکه ماشین حساب باید پرانتز گداری عبارات را نیز پشتیبانی کند با کمک ساختمان داده استک،  پرانتز گذاری و اولویت عبارات را محاسبه نمایید. 
 
کلاس ساختمان داده استک را باید خودتان پیاده سازی کنید و استفاده از کلاس های آماده برای آن مجاز نیست!

راهنمایی:
یکی از روش ها برای محاسبه عبارات تبدیل آن ها به فرم postfix است .

### مدیریت خطا
 اگر عبارت داده شده فرمت صحیح واستانداردی نداشته باشد مثلا پرانتز گذاری اشتباه باشد و یا عملگر ها درست استفاده نشده باشند باید ارور چاپ کرده و سپس آن را مدیریت نمایید.
 .مثال هایی از ورودی های نادرست که باید ارور چاپ کند:
 
 <div dir='ltr' align="justify">


 ```

 )(1+3)*2
 (((2+5)^2)+4
 3+5^
 +5^
 5/0

 ```


 </div>

### ورودی:
یک عبارت ریاضی شامل اعداد گویا و پرانتز "()" و عملگر های مورد نظر است که  به صورت یک رشته داده می شود.
### خروجی:
یک عدد که حاصل عبارت ریاضی داده شده است ویا پیغام ارور در صورت وجود خطا.
 
  <div dir='ltr' align="justify">


   ورودی1:

 ```
  (1+3) * 2^2
```

 عبارت خروجی 1:

```
  16
```

  ورودی2:

```
  -(-(2^3))/4+1 
```

  عبارت خروجی 2:

```
  3
```

  ورودی3:

``` 
  -(((1+2)*(-3))^(1+1)) 
```

  عبارت خروجی 3:

```
  -81
```

  ورودی4:

```
  )(2+3) 
```

  عبارت خروجی 4:

```
  error
```

  ورودی5:

```
  3+4^
```

  عبارت خروجی 5:

```
  error
```

  ورودی6:

```
  ((1.4+1.6)*10)/100 
``` 
   
  عبارت خروجی 6:

```
  0.3
```
  
  </div>

## تاریخچه
 ماشین حساب شما باید در هر مرحله از محاسبه وضعیت عبارت را چاپ کند  .

چاپ مراحل محاسبه:
 
 مرحله 1:

4*(2^3)<br>


 مرحله2:
 
 4*8<br>


 مرحله3:
 
 32<br>


 جواب نهایی:<br>


 32<br>
 <br>



## بخش امتیازی:
برای پیاده سازی این بخش شما باید  در منوی برنامه خود گزینه ای به نام "add new operator "داشته باشید تا با استفاده از ان بتوان عمگلر های دلخواه تعریف کرد و به ماشین حساب اضافه کرد و در محاسبات از انها استفاده کرد.
 نحوه تعریف اپراتور جدید به صورت زیر خواهد بود:

  <div dir='ltr' align="justify">
    
 add new operator <br>
a Comp b = 2*a+b<br>
 


 add new operator<br>
a trick b = a^b/b<br>


 
add new operator<br>
a square b = a^2+b^2<br>
  </div>
  
 ### سایر موارد اضافه  :
+ گرافیک زیبا برای خود ماشین حساب 
+  افزدون عملگرهای ماشین حساب علمی و وارد کردن توابع ریاضی (‌سینوس، مشتق) 
+ رسم نمودار توابع
<hr>


### نکات تکمیلی :
+ این پروژه بصورت تک نفری باید پیاده سازی شود.
+ بستر پیاده سازی پروژه روی گیت‌هاب می‌باشد.
+ سعی کنید هریک از بخش‌ها را در یک کامیت جداگانه انجام دهید.
+ رعایت اصول کدنویسی تمیز بخش بسیار زیادی از نمره را به خود اختصاص می‌دهد و درصورتی که کد کاملا به شکل غیراصولی پیاده سازی شده باشد. تحویل گرفته نمی‌شود.
+ استفاده از هر زبان، فریمورک و رابط‌های گرافیکی کاملا آزاد است.
+ به افرادی که از تکلنولوژی‌های جدید استفاده کنند، توکن تمدید اضافه‌تر داده خواهد شد.
+ با پیاده‌سازی هر مورد امتیازی یک توکن اضافه دریافت خواهید کرد.
+ قسمت محاسبه عبارت را نیز تحلیل زمانی کرده و تحلیل آن را در یک برنچ جداگانه نسبت به برنچ project کامیت و پوش نمایید.

 </div>


