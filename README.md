# Sublime text dasturi uchun lotin->kiril va kiril->lotinga o'giruvchi kichik plugin.

**O'rnatish**
Dastur menyusidan `Tools->Developer->New plugin`bo'limiga kirib transliterator.py fayli saqlanadi.

Yuqoridagi menyudan qayta `Preferences->Key Bindings`sozlamariga kirib quyidagi sozlama kiritiladi va plugin ish holatiga tayyor.
    [
    { "keys": ["ctrl+alt+l"], "command": "transliterator", "args": {"do":"latin"} },
    { "keys": ["ctrl+alt+k"], "command": "transliterator", "args": {"do":"cyrillic"} }
    ]

**Ishga tushirish**

*Kerakli matnlarni tanlash va `ctrl+alt+l` yoki `ctrl+alt+k` kombinatsiyasini terish kifoya*
