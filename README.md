# Hyprland Theme Switcher

Простой переключатель тем для Hyprland, написанный полностью на shell. Меняет конфигурацию Waybar, Rofi, Kitty и самого Hyprland, а также автоматически меняет обои — всё одной командой.

## Что делает

При переключении темы скрипт обновляет конфиги следующих компонентов:

- **Hyprland** — основной конфиг композитора
- **Waybar** — панель
- **Rofi** — лаунчер
- **Kitty** — терминал
- **swaybg** — обои рабочего стола

## Доступные темы

| Тема | Команда |
|------|---------|
| cyberpunk | `thema cyberpunk` |
| hellokitty | `thema kitty` |
| dwinter | `thema deep-winter` |

## Установка

1. Клонируй репозиторий:
   ```bash
   git clone https://github.com/mayni3452/theme-changer.git
   cd репо
   ```

2. Запусти установочный скрипт:
   ```bash
   ./creator.sh
   ```

   Скрипт сам скопирует переключатель тем в `bin`, после чего команда `thema` станет доступна глобально.

## Использование

После установки просто вызывай:

```bash
thema <название_темы>
```

Например:

```bash
thema cyberpunk
```

## Требования

- Hyprland
- Waybar
- Rofi
- Kitty
- swaybg

## Лицензия

MIT (или укажи свою)
