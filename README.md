# Qarshi Ish

Qarshi shahri uchun ish izlovchilar va ish beruvchilarni bog'laydigan sayt. Hammasi bitta serverda ishlaydi.

## Qanday ishlaydi

1. Ish beruvchi e'lon beradi va ish haqidagi barcha ma'lumotni (maosh, talablar, ish vaqti, manzil) yozadi. Manzil ishchilarga ko'rinmaydi.
2. Ish izlovchi istalgan vaqtda kirib, ishlarni qidiradi va ariza yuboradi.
3. Ariza ish beruvchiga yetib boradi va ular o'rtasida chat ochiladi.
4. Ish beruvchi ishchini ma'qul topsa, manzil chatda yuboriladi va e'lon olib tashlanadi.

## Ishga tushirish

Faqat Python 3 kerak, qo'shimcha paket o'rnatish shart emas.

```
python3 app.py
```

Keyin brauzerda `http://localhost:8000` ni oching. Boshqa port uchun: `PORT=8080 python3 app.py`.

Ma'lumotlar `ish.db` faylida (SQLite) saqlanadi. U birinchi ishga tushishda avtomatik yaratiladi va `.gitignore` orqali GitHub'ga yuklanmaydi.
