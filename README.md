# Keepsake — Responsive Landing Page

Адаптивний односторінковий лендінг дизайн-агенції **Keepsake** (Mobile First, HTML5, CSS Grid/Flexbox, CSS-змінні, WebP).

## Посилання
* **Живий сайт (GitHub Pages):** https://bodnarihor-tech.github.io/landing-keepsake/
* **Репозиторій:** https://github.com/bodnarihor-tech/landing-keepsake

## Основні рішення та технології
- **Підхід Mobile First:** базові стилі розраховані на мобільні екрани (від `320px` / `375px`), адаптація реалізована через `@media (min-width: 768px)` та `@media (min-width: 1280px)`, максимальна ширина контейнера — `1100px`.
- **CSS-змінні (`:root`):** кольорова палітра дизайн-системи, шрифти (`Oswald`, `Open Sans`, `Dancing Script`) та ключові відступи винесені у змінні.
- **Розкладка:** Flexbox для навігації, хедера, карток послуг, статистики, відгуків, журналу та футера; CSS Grid для сітки портфоліо (`aspect-ratio` для пропорцій карточок).
- **Інтерактивність без JS:** мобільне меню та фільтрація робіт за категоріями (`data-category`) реалізовані через стани `:checked ~`.
- **Доступність і оптимізація:** семантичні теги, `aria-*` атрибути, видимі стани `:focus-visible` / `:focus-within`, інлайн-SVG та зображення у форматі `.webp`.