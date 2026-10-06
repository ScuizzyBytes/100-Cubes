# ⚡ COLOR GRID 100

> **Минималистичная казуальная игра-головоломка на Python с динамической системой сброса сетки.**

---

## 🎯 О проекте

**COLOR GRID 100** — это настольный кликер, построеный на сетке $10 \times 10$. Каждое нажатие превращает монохромную кнопку в яркий цветной куб. Главная цель — закрасить всё поле и запустить цепную реакцию сброса.

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![CustomTkinter](https://img.shields.io/badge/GUI-CustomTkinter-blueviolet?style=for-the-badge)
![License](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

---

## ⚡ Особенности

* 🎨 **100 интерактивных блоков:** Сетка $10 \times 10$ с мгновенной реакцией на клик.
* 🌈 **Неоновая палитра:** Генерирование случайных оттенков из заданного набора цветов.
* 🔄 **Автосброс (Auto-Reset):** Умный отслеживатель состояния через `.cget("fg_color")` — очищает поле, когда белых блоков не остаётся.
* 🛠 **Чистая архитектура:** Без громоздких счётчиков, с использованием `lambda capture` и генераторов списков.

---

## 🎮 Геймплей

1. Кликай по белым кубам на доске.
2. Закрашивай все 100 ячеек уникальными цветами.
3. Достигни 100% заполнения поля для автоматического сброса!

---

## 📦 Быстрый старт

### Требования
* Python 3.8 или выше
* Зависимости: `customtkinter`

### Установка и запуск

```bash
# 1. Клонируй репозиторий
git clone [https://github.com/your-username/color-grid-100.git](https://github.com/your-username/color-grid-100.git)

# 2. Перейди в папку с проектом
cd color-grid-100

# 3. Установи зависимости
pip install customtkinter

# 4. Запусти игру
python main.py
