<i id="top"></i>
# Core documentation

> [!NOTE]
> **Am** - высокоуровневый нативно-компилируемый язык программирования со статической типизацией

> [!IMPORTANT]
> Если у вас есть вопросы вы можете написать на почту: [amproglang@gmail.com](mailto:amproglang@gmail.com)

## Оглавление
- [Как начать](#how-to-start)
  - [Установка](#download)
    - [Windows](#dl-win)
    <!-- Я случайно сделал опечатку, но теперь Linix это стиль :) -->
    - [Linux](#dl-linix)
  - [Проверка](#check-for-install)
  - [Первый запуск](#first-start)
- [Типы данных](#datatypes)
  - [Строки](#type-string)
  - [Числа](#types-number)
    - [Целые](#type-int)
    - [Дробные](#type-float-double)
  - [Булевые значения](#type-bool)
  - [Массивы](#type-array)
  - [Словари](#type-dict)
  - [Пустоты](#type-void)
  - [Автоматический](#type-default)
- [Переменные](#variables)
  - [Объявление](#var-declar)
  - [Переназначение](#var-redeclar)
  - [Затенение](#var-shadowing)
  - [Смена типа](#var-retype)
  - [Очистка](#var-clear)
- [Операторы](#operators)
  - [Категория: По назначению](#as-intend)
    - [Арифметические](#ops-math)
    - [Логические](#ops-logic)
    - [Сравнения](#ops-eqs)
  - [Категория: По использованию](#as-use)
    - [Унарные](#ops-unary)
    - [Бинарные](#ops-binary)
    - [Тернарные](#ops-ternary)
  - [Общая таблица операторов](#table-of-ops)
- [Пространства](#spaces) 
  - [Создание](#space-add)
  - [Проверки](#space-check)
  - [Совмещение](#space-use)

<i id="how-to-start"></i>
## Как начать

<i id="download"></i>
### Установка

<i id="dl-win"></i>
#### Установка для Windows
1. Перейдите на [GitHub Releases для Am](https://github.com/amfpl/am/releases)
2. Найдите нужную<b><sup>*</sup></b> вам версию
3. Установите `amc-*_setup.exe`
4. Запустите установленный файл
5. Выберите путь установки
6. Готово!

> [!IMPORTANT]
> <b><sup>*</sup></b> Если вы не знаете какую версию установить, то рекомендуем последнюю версию с пометкой `stable`

<i id="dl-linix"></i>
#### Установка для Linux
1. Перейдите на [GitHub Releases для Am](https://github.com/amfpl/am/releases)
2. Найдите нужную<b><sup>*</sup></b> вам версию
3. Установите `amc-*_setup`
4. Запустите установленный файл
5. Выберите путь установки
6. Готово!

> [!IMPORTANT]
> <b><sup>*</sup></b> Если вы не знаете какую версию установить, то рекомендуем последнюю версию с пометкой `stable`

<i id=""></i>