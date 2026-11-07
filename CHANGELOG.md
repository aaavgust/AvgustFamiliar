# Изменения / Changes

## 1.0.1 — 2026-11-07

**RU.** Окна — только перетаскивание, без горячих клавиш. Раскладка — исправлена работа: движок теперь на основе RuSwitcher; Fn и двойной ⌥ работают на настоящей клавиатуре, повторное нажатие возвращает текст, отмена больше не выключает исправление слов. Если нет доступа, это видно на экране раскладки и в панели, с кнопкой настроек; после выдачи доступа всё запускается само. Экраны открываются без пауз: самая долгая задержка главного потока за 10 000 тестовых действий снизилась с 142 до 57 мс.

**EN.** Windows — dragging only, no keyboard shortcuts. Layout — fixed: the engine is now based on RuSwitcher; Fn and double ⌥ work on a real keyboard, pressing again restores the text, and an undo no longer turns correction off for a word. Missing access is now shown on the Layout screen and in the panel, with a button to the settings; everything starts by itself once access is granted. Screens open without stalls: the longest main-thread pause over 10,000 test actions went from 142 ms to 57 ms.

## 1.0.0 — 2026-10-30

**RU.** Первый публичный выпуск: обслуживание Mac (умная проверка, очистка, защита, монитор, приложения, карта диска, дубликаты) и инструменты (окна, раскладка и сниппеты, буфер обмена, текст с экрана, «Не засыпать», блок клавиатуры, просмотр архивов). macOS 15+, процессор Apple.

**EN.** The first public release: Mac care (smart check, cleanup, protection, monitor, applications, disk map, duplicates) and tools (windows, keyboard layout and snippets, clipboard, text from screen, Stay awake, keyboard lock, archive preview). macOS 15+, Apple silicon.
