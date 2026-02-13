<div align="center">

# NEON TYPE RUN

### Arcade typing runner where your speed and accuracy are your weapon

[![HTML5](https://img.shields.io/badge/HTML5-Game-orange?style=for-the-badge&logo=html5)](#)
[![JS](https://img.shields.io/badge/Vanilla-JavaScript-f7df1e?style=for-the-badge&logo=javascript&logoColor=111)](#)
[![Vercel Ready](https://img.shields.io/badge/Vercel-ready-black?style=for-the-badge&logo=vercel)](#)

</div>

NEON TYPE RUN is a fast-paced browser game where you destroy enemies by typing words correctly. The cleaner and faster your input, the higher your combo, speed, crit chance, and score.

## Что это за игра

- Ты бежишь по неоновому треку и отбиваешь волны врагов набором слов.
- Каждая ошибка сбрасывает комбо и может перегреть систему (`Overheat`).
- Каждые несколько волн игра ускоряется, а на босс-волнах появляются усиленные цели.
- В конце сессии показываются `Score`, `Accuracy`, `WPM`, `CPM` и время.

## Основные механики

- `Combo`: усиливает темп, очки и шанс критического удара.
- `Targeting`: переключение цели `Tab` / `←` / `→`.
- `Elite` враги: требуют несколько слов подряд.
- `Boss` враги: появляются на волнах `5, 10, 15...`.
- Бонусы: `Heart`, `Focus`, `Dash`, `Shield`.
- Статистика сохраняется локально (`high score`, `best accuracy`).

## Управление

- `Typing` -> атака и продвижение по слову.
- `Esc` -> пауза.
- `Tab` или `←` / `→` -> смена цели.
- `Click/Tap` по экрану -> фокус ввода на мобильных и десктопе.

## Настройки в игре

- Язык словаря: `RU` / `EN`.
- Сложность: `Easy` / `Normal` / `Hard`.
- Аудио: `Master`, `SFX`, `Music`.
- Визуальные эффекты: `Ultra FX` toggle.

## Технологии

- Один `index.html` с Canvas-рендером и игровым циклом.
- Чистый JavaScript без фреймворков.
- Web Audio API для музыки и эффектов.
- `middleware.js` для security headers на Vercel Edge.

## Быстрый старт

```bash
# 1) Клонировать репозиторий
 git clone https://github.com/doyouknowwhatitis/neontype.git

# 2) Перейти в папку
 cd neontype

# 3) Установить зависимости
 npm install

# 4) Запустить локально через Vercel dev
 npx vercel dev
```

Открой `http://localhost:3000`.

## Запуск без Vercel

```bash
python3 -m http.server 8080
```

Открой `http://localhost:8080`.

## Деплой

Самый простой путь: импортировать репозиторий в Vercel и задеплоить как static project.

## Roadmap

- [ ] Добавить таблицу лучших результатов с глобальным лидербордом
- [ ] Сезонные режимы и ежедневные челленджи
- [ ] Новые типы врагов и модификаторы волн
- [ ] Отдельный режим тренировки слепой печати

---

<div align="center">
Built for flow state typing.
</div>
