# LOWINU

Одностраничный сайт мемкоина LOWINU — низкополигональный шиба, живущий на минимальных настройках графики.

## Что где менять
Всё в блоке `SETTINGS` в самом верху `index.html`:

```js
window.CONTRACT = "";   // адрес контракта
window.TWITTER  = "";   // ссылка на X
window.BUY      = "";   // ссылка на покупку
window.DEX      = "";   // ссылка на график
```

## Деплой
Статика без сборки. GitHub → Vercel → Import, Framework Preset = Other,
build command не нужен, output directory — корень.

## Файлы
- `index.html` — весь сайт (стили и скрипты инлайном)
- `lowinu.webp` — персонаж с прозрачным фоном
- `favicon.png`
