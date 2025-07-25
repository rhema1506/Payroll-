# 🧾 Простая система расчёта заработной платы на Python

**Простая система управления зарплатой**, написанная на **Python**, которая позволяет вводить основные данные сотрудника и параметры оплаты. Система автоматически рассчитывает валовую зарплату, налоговые вычеты, чистую зарплату, присваивает уникальный номер сотрудника и отображает дату выплаты.

Подходит для обучения, микробизнеса или начинающих разработчиков, изучающих основы логики расчёта зарплаты и программирования на Python.

---

## 📌 Возможности

- ✅ Ввод данных сотрудника:
  - Имя
  - Адрес
  - Почтовый индекс (ZIP-код)
  - Пол
  - Имя работодателя
  - Основная зарплата
  - Сверхурочная оплата
- 🆔 Автоматическое присвоение уникального номера сотрудника
- 💵 Расчёт заработной платы:
  - Валовая зарплата (основная + сверхурочная)
  - Налог на зарплату (по умолчанию 15%)
  - Чистая зарплата (после налога)
- 🗓️ Назначение текущей даты как дня выплаты
- 📋 Отображение полной информации в консоли

---

## 🛠 Принцип работы

### 💰 Расчёты

- **Валовая зарплата** = Основная зарплата + Сверхурочные
- **Налог на зарплату** = 15% от валовой зарплаты *(можно изменить в коде)*
- **Чистая зарплата** = Валовая зарплата - Налог
- **Дата выплаты** = Текущая дата системы

### 🎯 Пример

#### Ввод: python Payroll-Systems.py 
or 
run the python file 
