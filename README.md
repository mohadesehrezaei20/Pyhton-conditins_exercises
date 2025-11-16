# Pyhton-conditins_exercises

---

# 1. تشخیص مثبت یا منفی

num = float(input("یک عدد وارد کنید: "))

if num > 0:
    print("عدد مثبت است")
else:
    print("عدد منفی است")
---

# 2. تشخیص مثبت یا منفی یا صفر

num = float(input("یک عدد وارد کنید: "))

if num > 0:
    print("عدد مثبت است")
elif num == 0:
    print("عدد صفر است")
else:
    print("عدد منفی است")
---

# 3. تشخیص زوج یا فرد

num = int(input("یک عدد وارد کنید: "))

if num % 2 == 0:
    print("عدد زوج است")
else:
    print("عدد فرد است")
---

# 4. دریافت سه عدد و پیدا کردن بزرگ‌ترین (یا کوچک‌ترین)

### بزرگ‌ترین:

a = float(input("عدد اول: "))
b = float(input("عدد دوم: "))
c = float(input("عدد سوم: "))

largest = a

if b > largest:
    largest = b
if c > largest:
    largest = c

print("بزرگترین عدد:", largest)
## کوچک‌ترین (در صورت نیاز):

smallest = a

if b < smallest:
    smallest = b
if c < smallest:
    smallest = c

print("کوچکترین عدد:", smallest)
---

# 5. دریافت عدد و تشخیص روز هفته

(فرض: 1 = شنبه، 2 = یکشنبه ... 7 = جمعه)

day = int(input("شماره روز هفته را وارد کنید (1 تا 7): "))

if day == 1:
    print("شنبه")
elif day == 2:
    print("یکشنبه")
elif day == 3:
    print("دوشنبه")
elif day == 4:
    print("سه‌شنبه")
elif day == 5:
    print("چهارشنبه")
elif day == 6:
    print("پنجشنبه")
elif day == 7:
    print("جمعه")
else:
    print("عدد نامعتبر است")
---

# 6. دریافت نام روز و مشخص کردن شماره روز

day = input("نام روز هفته را وارد کنید: ").strip()

if day == "شنبه":
    print("روز اول هفته")
elif day == "یکشنبه":
    print("روز دوم هفته")
elif day == "دوشنبه":
    print("روز سوم هفته")
elif day == "سه شنبه" or day == "سه‌شنبه":
    print("روز چهارم هفته")
elif day == "چهارشنبه":
    print("روز پنجم هفته")
elif day == "پنجشنبه":
    print("روز ششم هفته")
elif day == "جمعه":
    print("روز هفتم هفته")
else:
    print("نام روز نامعتبر است")
---

# 7. دریافت نمره و تعیین وضعیت دانش‌آموز

score = float(input("نمره را وارد کنید: "))

if 14 <= score < 16:
    print("وضعیت: C")
elif 16 <= score < 18:
    print("وضعیت: B")
elif 18 <= score <= 20:
    print("وضعیت: A")
else:
    print("نمره خارج از محدوده است")
---
