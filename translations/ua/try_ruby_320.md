---
lang:   UA
title:  Бути чи не бути
answer:
load:   poem = "Моя канапка випала у мене з рук. \nІ моя канапка полетіла на Місяць. \nБла, бла, бла\n"
ok:
error:
---

Одна маленька деталь, яку ми не обговорили – це аргументи методів.
Пам'ятаєш, як ми змінили вміст поеми, використовуючи цей метод:
__poem.gsub("канапка", "грушка")__

Метод gsub вимагає два аргументи, які ми передали як рядки в круглих дужках.
__Аргументи кажуть методові, що саме йому робити.__

### Круглі дужки
Насправді, в більшості випадків Ruby не проти, якщо ти пропустиш дужки. Таким чином, це теж спрацює:
__poem.gsub "канапка", "грушка"__

Ми також вже використовували й інший метод з параметром. Багато разів. Але це не так очевидно:

    puts "Hello"
    puts("Hello")

Так, __puts__ це теж метод. Хочеш писати puts з круглими дужками або без – для Ruby байдуже,
але варіант без дужок простіше читати і трохи економить час набору коду!

> Висновок полягає в тому, що ти можеш робити все, що завгодно з круглими дужками, поки код читається красиво.

### Тож бути чи не (бути)?

Хочеш ще трохи Шекспіра? Читай далі.
