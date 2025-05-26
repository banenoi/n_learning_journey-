# n_learning_journey-
Step one to learn python 
# Python Learning Journey

تعلم بايثون من الصفر حتى الإتقان - خطة منظمة ومرنة

---

## ✅ المرحلة 1: الأساسيات
- [✔️] المتغيرات (variables)
- [✔️] الإدخال والإخراج (input/output)
- [✔️] أنواع البيانات (data types)

## ✅ المرحلة 2: الشروط والحلقات
- [✔️] الجمل الشرطية (if/else)
- [✔️] العوامل المنطقية (logical operators)
- [✔️] الحلقات (while loop / for loop)

# Write Python 3 code in this online editor and run it.
import random
game=["rock","paper","scissors"]
computer=random.choice(game)

guess=input("Enter your guess (rock or paper or scissors)")
if computer==guess:
    print("we equal")
    print(f"the computer rsolt is {computer}")
elif computer=="rock"and guess=="paper"or computer=="paper" and guess=="scissors"or computer=="scissors"and guess=="rock":
    print("you win")
    print("the computer rsolt is",(computer))
else:
    print(" you lost")
    print(f"the computer rsolt is {computer} ")
الكود الي كتبته بالمرحة الثانية واجهت بعض المشاكل  
## ✅ المرحلة 3: القوائم والسلاسل
-[✔️] القوائم (lists)
 القوائم هي []
 الاداة []نقدر نطبع منه حسب رقم index او نغير الفاليو◀️ الاداة len() تعطي عدد العناصر الي بي لست ◀️ insert(index,value) تضيف عنصر جديد بعد ما تحدد رقم الاندكس والي تريد تضيفه مهمة جدا ◀️ 
 الاداة sort.() ترتب العناصر من الاصغر الى الاكبر ◀️ الاداة append () تضيف من خلال اسم الفاليو ◀️
 الاداة popتحذف من خلال رقم index◀️ الادوات (rmove)تحذف من خلال اسم value)
- [✔️] السلاسل النصية (strings)
السلاسل النصيه هي كل نص داخل علامة الاقتباس
نستطيع ان نطبع value من خلال [] ونضع index مالته ونستطيع ان نقطع من خلال [:] اي ان نضع اندكس ونترك اندكس وبهذا نقطع الكلمة ونستطيع ان نحسب الطول من خلال len()
وبعض دوال الي نستخدمها مع upper()تخلي كل الحروف كابتن .lower()تخلي كل الحروف صمول .title() تخلي اول حرف كابتن والباقي. صمول strip() زيل الفراغات replace.(old ,new)تستبدل الكلمه او الحرف من خلال اسم ونضيف الي نريده split() تقسم النص الى قائمة find("n") يطبع رقم الاندكس لاول ضهور للحرف او الكلمة count.() يحسب عدد الحروف كم مرة تكررت 
✔️[✔️] الـ tuples
    
    هي هاي الاقواس () ونرتب بيها او نحفظ بيها كلمات وجمل نستطيع ان نصل الى النص من خلال []ووضع رقم الاندكس نكدر نحسب الطول من خلال len() لاكن لا نستطيع الحذف او تعديل عل كلمه او اضافة يمكن تحويلها الى لست حتى تضيف وتحذف 
- [✔️] القواميس (dictionaries)
-  my_dict = {"key": "value"}
الوصول للقيمةmy_dict["key"]
تطبع القيمة المرتبطة بالمفتاح
تعديل قيمةmy_dict["key"] = "new value"
إضافة مفتاح/قيمةmy_dict["new_key"] = "value"
حذف مفتاحdel my_dict["key"]
جميع المفاتيحmy_dict.keys()
جميع القيمmy_dict.values()
جميع الأزواجmy_dict.items()
التحقق من وجود مفتاح"key" in my_dict


## ✅ المرحلة 4: الدوال والتعامل مع الملفات
- [x] إنشاء الدوال (functions)
- [x] try / except
- [x] التعامل مع الملفات (file handling)

## ✅ المرحلة 5: البرمجة الكائنية OOP
- [x] إنشاء الكلاسات (classes)
- [x] الدوال داخل الكلاس (__str__, وغيرها)
- [x] إنشاء أكثر من كائن
- [x] الوراثة (inheritance)

## ✅ المرحلة 6: مشاريع تطبيقية
- [x] الآلة الحاسبة (calculator.py)
- [x] مدير الطلاب (student_manager.py)
- [x] لعبة التخمين (guessing_game.py)

---

## ملاحظات:
- أي فكرة جديدة أو تمرين أضيفه داخل الملف المناسب حسب المرحلة.
- التزم بتنظيم الملفات والمجلدات.
- أراجع الكود بعد كل مرحلة.
