# «Сложно сосредоточиться»

Адаптивная страница со светлой и тёмной темой.

Лонгрид о том, почему трудно концентрироваться: многозадачность, дофамин, еда, гаджеты. Страница автоматически подстраивается под тему устройства, а тему можно переключить вручную.

**Демо:** [julijasidorak22-prog.github.io/slozhno-sosredotochitsya-fd](https://julijasidorak22-prog.github.io/slozhno-sosredotochitsya-fd/)

## Что сделано

- **Адаптивная вёрстка** по принципу mobile-first: медиазапросы для планшета (от 768px) и десктопа (от 1024px)
- **Темизация на CSS-переменных:** цвета вынесены в `variables.css`, светлая и тёмная темы лежат в отдельных файлах
- **Автоматический выбор темы** по настройкам системы через `prefers-color-scheme`
- **Резиновая типографика** на `clamp()`: размеры шрифта плавно меняются между брейкпоинтами
- **Раскладка блоков** на CSS Grid
- **Моноширинный шрифт** IBM Plex Mono, подключённый через `@font-face`

> Скрипт переключения темы (`scripts/script.js`) предоставлен в стартовом коде курса. Моя часть: вёрстка, адаптив и темы.

## Стек

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![БЭМ](https://img.shields.io/badge/%D0%91%D0%AD%D0%9C-000000?style=for-the-badge)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

HTML5 · CSS3 (Grid, медиазапросы, custom properties, `clamp()`) · БЭМ · Git

## Как запустить

Откройте [демо](https://julijasidorak22-prog.github.io/slozhno-sosredotochitsya-fd/) или склонируйте репозиторий и откройте `index.html` в браузере:

```bash
git clone https://github.com/julijasidorak22-prog/slozhno-sosredotochitsya-fd.git
```

Чтобы проверить адаптив, сузьте окно или включите режим устройства в DevTools.
