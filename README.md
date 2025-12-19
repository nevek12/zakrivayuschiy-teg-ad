# Закрывающий тег

Финальный проект модулей вёрстки курса Яндекс Практикум.

## О проекте

Проект представляет собой рефлексию учебного пути в веб-разработке. Восемь карточек описывают разные этапы обучения — от первого знакомства с HTML и CSS до финального проекта с анимациями и сложной вёрсткой.

## Технологии

* HTML5 (семантическая разметка)
* CSS3 (Flexbox, CSS Variables, Animations, Transitions)
* JavaScript (обработка событий, DOM-манипуляции)
* Адаптивная вёрстка (mobile-first, clamp())
* CSS-фильтры для изображений
* SVG-анимации
* Вариативные шрифты (Inter Variable)

## Особенности реализации

* Анимированная иконка лайка с SVG (hover, active, is-liked состояния)
* Модальное окно на элементе `<dialog>` с стилизацией `::backdrop`
* Прогрессивное улучшение через `@supports` для text-stroke
* Mix-blend-mode для эффектов кнопок
* Фиксированный фон с множественными градиентами
* Fluid typography с использованием `clamp()`
* Семантическая разметка и доступность

## Структура проекта

```
├── fonts/              # Вариативный шрифт Inter и Press Start 2P
├── images/             # Изображения карточек, favicon
├── scripts/            # JavaScript для like-функциональности
├── styles/
│   ├── globals.css     # CSS Reset
│   ├── variables.css   # CSS Custom Properties
│   ├── style.css       # Основные стили компонентов
│   └── animations.css  # Keyframe анимации
├── svg/                # SVG-иконки
└── index.html          # Главная страница
```

## Ссылки

* **Демо:** https://github.com/nevek12/zakrivayuschiy-teg-ad
* **Репозиторий:** https://github.com/nevek12/zakrivayuschiy-teg-ad

## Автор

**Nevolsky Vladislav** — [@nevek12](https://github.com/nevek12)
