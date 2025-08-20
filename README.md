# QR Code Component

![QR Code Component Preview](./preview.jpg)

Адаптивный QR-код компонент, выполненный в рамках челленджа Frontend Mentor. Проект реализован с использованием семантичного HTML5 и современного CSS3 с применением Flexbox для создания центрированного и отзывчивого дизайна.

## 🚀 Демо

[Посмотреть живую демонстрацию]()

## 📋 Функциональность

- **Адаптивный дизайн** - корректное отображение на всех устройствах
- **Семантичная разметка** - использование HTML5 тегов для лучшей доступности
- **CSS Custom Properties** - переменные для удобного управления цветами
- **Mobile-first подход** - оптимизация под мобильные устройства
- **Современный CSS** - Flexbox для позиционирования элементов

## 🛠 Технологии

- **HTML5** - семантичная разметка
- **CSS3** - стилизация и адаптивность
- **Flexbox** - выравнивание и центрирование
- **CSS Custom Properties** - управление цветовой схемой
- **Google Fonts** - шрифт Outfit

## 📁 Структура проекта

```
qr-code-component/
├── index.html              # Основной HTML файл
├── styles/
│   ├── global.css          # Глобальные стили и сброс
│   └── style.css           # Основные стили компонента
├── images/
│   ├── image-qr-code.png   # QR-код изображение
│   └── favicon-32x32.png   # Фавикон
├── design/                 # Дизайн-макеты
└── style-guide.md          # Руководство по стилям

```

## 🎨 Дизайн-система

**Цветовая палитра:**
- Белый: `hsl(0, 0%, 100%)`
- Slate 300: `hsl(212, 45%, 89%)`
- Slate 500: `hsl(216, 15%, 48%)`
- Slate 900: `hsl(218, 44%, 22%)`

**Типографика:**
- Шрифт: Outfit (Google Fonts)
- Веса: 400, 700
- Размер текста: 15px (параграф)

## 🚀 Локальный запуск

1. Клонируйте репозиторий:
```bash
git clone https://github.com/Sergei-Popov/qr-code-component.git
```

2. Откройте проект:
```bash
cd qr-code-component
```

3. Запустите `index.html` в браузере или используйте локальный сервер:
```bash
# Используя Python
python -m http.server 3000

# Используя Node.js
npx serve .
```

## 📱 Адаптивность

Компонент адаптирован для следующих разрешений:
- **Мобильные устройства**: 375px и меньше
- **Десктоп**: 1440px и больше
- **Адаптивные точки**: все промежуточные разрешения

## 🔧 Особенности реализации

- **CSS Grid/Flexbox** для создания центрированного макета
- **Mobile-first медиа-запросы** для адаптивности
- **Семантичные HTML теги** (`main`, `article`) для лучшей доступности
- **CSS Custom Properties** для управления цветовой темой
- **Оптимизированные изображения** с правильными alt-атрибутами

## 📦 Развертывание

Проект можно развернуть на следующих платформах:

- [GitHub Pages](https://pages.github.com/)
- [Vercel](https://vercel.com/)
- [Netlify](https://www.netlify.com/)

## 🤝 Вклад в проект

1. Форкните проект
2. Создайте ветку для новой функции (`git checkout -b feature/AmazingFeature`)
3. Зафиксируйте изменения (`git commit -m 'Add some AmazingFeature'`)
4. Отправьте в ветку (`git push origin feature/AmazingFeature`)
5. Откройте Pull Request

## 📝 Автор

**Sergei Popov**
- GitHub: [@Sergei-Popov](https://github.com/Sergei-Popov)
- Frontend Mentor: [@Sergei-Popov](https://www.frontendmentor.io/profile/Sergei-Popov)

## 📝 Лицензия

Проект создан в образовательных целях в рамках челленджа [Frontend Mentor](https://www.frontendmentor.io).

## 🙏 Благодарности

- [Frontend Mentor](https://www.frontendmentor.io) за предоставление дизайна и челленджа
- Сообщество Frontend Mentor за поддержку и обратную связь
