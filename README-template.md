# Frontend Mentor - QR code component solution

Это решение челленджа [QR code component на Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor челленджи помогают улучшить навыки программирования путем создания реалистичных проектов.

## Содержание

- [Обзор](#обзор)
  - [Скриншот](#скриншот)
  - [Ссылки](#ссылки)
- [Процесс разработки](#процесс-разработки)
  - [Построено с использованием](#построено-с-использованием)
  - [Что я изучил](#что-я-изучил)
  - [Дальнейшее развитие](#дальнейшее-развитие)
  - [Полезные ресурсы](#полезные-ресурсы)
- [Автор](#автор)
- [Благодарности](#благодарности)

## Обзор

### Скриншот

![QR Code Component](./design/desktop-design.jpg)

Адаптивный QR-код компонент с центрированным макетом, реализованный с использованием современного CSS и семантичного HTML.

### Ссылки

- URL решения: [GitHub Repository](https://github.com/Sergei-Popov/qr-code-component)
- URL живого сайта: [Vercel Pages Demo](https://qr-code-component-two-virid.vercel.app)

## Процесс разработки

### Построено с использованием

- Семантичная HTML5 разметка
- CSS Custom Properties (переменные)
- Flexbox для центрирования и выравнивания
- Mobile-first подход к дизайну
- Google Fonts (Outfit)
- БЭМ методология для именования классов

### Что я изучил

В процессе работы над этим проектом я закрепил знания по:

**Центрированию элементов с Flexbox:**
```css
.main {
  height: 95%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
```

**Использованию CSS Custom Properties:**
```css
:root {
  --color-white: #fff;
  --color-black: #1F314F;
  --color-gray: #68778D;
}
```

**Семантичной HTML разметке:**
```html
<main class="main">
  <article class="card">
    <img src="./images/image-qr-code.png" alt="QR code image" class="card__image">
    <div class="description">
      <h2 class="card__heading">Improve your front-end skills by building projects</h2>
      <p class="card__text">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div>
  </article>
</main>
```

### Дальнейшее развитие

В будущих проектах планирую сосредоточиться на:

- Изучении CSS Grid для более сложных макетов
- Углублении знаний в области доступности (accessibility)
- Практике работы с CSS анимациями и переходами
- Изучении препроцессоров CSS (Sass/SCSS)

### Полезные ресурсы

- [CSS Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - отличное руководство по Flexbox
- [MDN CSS Custom Properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) - документация по CSS переменным
- [Google Fonts](https://fonts.google.com/) - для подключения веб-шрифтов

## Автор

**Sergei Popov**
- GitHub: [@Sergei-Popov](https://github.com/Sergei-Popov)
- Frontend Mentor: [@Sergei-Popov](https://www.frontendmentor.io/profile/Sergei-Popov)

## Благодарности

Спасибо команде Frontend Mentor за создание интересных и образовательных челленджей, которые помогают развивать навыки frontend разработки на практических проектах.
