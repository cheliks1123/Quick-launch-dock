Quick Launch Dock demo - dragging a shortcut onto the dock](https://raw.githubusercontent.com/cheliks1123/Quick-launch-dock/main/quck-lauch-dock.gif)

*Drag a shortcut onto the dock and it stays there. Click an icon to launch it.*

A slim, smoothly animated dock that lives on the edge of your screen and gives you
one-click access to your favourite programs, files and folders. Think of it as a
tiny launcher bar with "+" slots: drop a shortcut onto it, or click "+" and pick a
program, and it stays there until you remove it.

## Features

- **Add programs your way**
  - Drag and drop shortcuts, executables, files or folders onto the dock.
  - Click the **+** slot to choose a program in a file dialog (shortcuts are kept as shortcuts, so their icons stay correct).
  - Right-click the **+** slot to paste a path from the clipboard (quotes and `%ENVIRONMENT%` variables are handled).
- **One-click launch** — click an icon to start it. The working directory is set automatically.
- **Right-click menu** on any icon: Open, Run as administrator, Show in folder, Move up / Move down, Remove.
- **Persistent list** — your slots are saved by Windhawk and restored after a restart.
- **Auto-hide** — the dock collapses into a thin strip and smoothly slides out when you move the mouse to the screen edge.
- **Smooth animations** — slide-in/out, hover highlight fade, icon zoom on hover, appear/disappear and re-ordering animations. Frames are synchronized with your monitor's refresh rate, so it stays smooth on 60/144/240 Hz displays.
- **High-quality rendering** — anti-aliased rounded corners and high-quality icon scaling (GDI+), per-pixel transparent window, DPI-aware sizes.
- **Fullscreen aware** — optionally hides itself while a fullscreen app or game is active.
- **Fully themeable** — background, hover, accent (plus sign and handle) and border colors are configurable (`#RRGGBB`).
- **Left or right edge**, adjustable icon size, tooltips with the item name.
- Does not use the taskbar, does not hook any functions and does not modify system files. Disabling the mod removes the dock completely.

## How to use

1. Enable the mod. A dock appears at the right edge of the primary monitor (vertically centered).
2. Drag a shortcut/program/folder onto it, or click **+**.
3. Click an icon to launch. Right-click an icon for more actions.
4. With auto-hide enabled, move the cursor to the screen edge to reveal the dock.

## Settings

| Setting | Description |
| --- | --- |
| Screen side | Right or left edge of the primary monitor. |
| Icon size | Icon size in pixels at 100% DPI (16–96). Scales with system DPI. |
| Auto-hide | Collapse to a thin strip until the cursor touches the edge. |
| Hide when a fullscreen app is active | Hides the dock above fullscreen windows/games. |
| Animations | Turns all animations on or off. |
| Background / Hover / Accent / Border color | Colors in `#RRGGBB` format. Invalid values fall back to the defaults. |

## Notes and limitations

- The mod runs as a standalone tool in its own dedicated process (it is not injected into Explorer and hooks nothing), so a problem in the mod can never affect the Windows shell, and only one instance is ever running.
- Drag and drop from windows running **as administrator** is blocked by Windows (UIPI). Use the **+** button in that case.
- The dock is placed on the **primary** monitor. With auto-hide and another monitor attached on the same side, the cursor may pass the edge too quickly to reveal the dock — disable auto-hide there.
- The number of slots is limited by the screen height.
- Slots are stored as file paths. If a file is moved or deleted, its icon becomes generic until you remove it.

---

# Панель быстрого запуска

Тонкая плавно анимированная панель у края экрана для быстрого запуска любимых
программ, файлов и папок. По сути — мини-лаунчер с «плюсиками»: перетащи на него
ярлык или нажми «+» и выбери программу — она останется на панели, пока ты сам её не уберёшь.

## Возможности

- **Добавление как удобно**
  - Перетаскивание ярлыков, exe-файлов, файлов и папок прямо на панель.
  - Клик по **+** — выбор программы через диалог (ярлыки сохраняются как ярлыки, поэтому иконки остаются правильными).
  - ПКМ по **+** — вставить путь из буфера обмена (кавычки и переменные вида `%APPDATA%` обрабатываются).
- **Запуск в один клик** — рабочая папка выставляется автоматически.
- **Контекстное меню** на любой иконке: Открыть, Запуск от имени администратора, Показать в папке, Переместить выше / ниже, Удалить.
- **Список сохраняется** — слоты хранятся в Windhawk и восстанавливаются после перезагрузки.
- **Автоскрытие** — в покое панель сворачивается в тонкую полоску и плавно выезжает, когда подводишь курсор к краю экрана.
- **Плавные анимации** — выезд и сворачивание, плавная подсветка, увеличение иконки при наведении, анимации появления, удаления и перестановки. Кадры синхронизированы с частотой монитора, поэтому всё плавно на 60/144/240 Гц.
- **Качественная отрисовка** — сглаженные скруглённые углы и качественное масштабирование иконок (GDI+), окно с попиксельной прозрачностью, учёт DPI.
- **Полноэкранные приложения** — при желании панель сама прячется, пока открыта полноэкранная программа или игра.
- **Настраиваемые цвета** — фон, подсветка, акцент (плюс и полоска) и рамка задаются в формате `#RRGGBB`.
- **Левый или правый край**, размер иконок, подсказки с названием элемента.
- Не использует панель задач, не перехватывает функции и не меняет системные файлы. При отключении мода панель полностью исчезает.

## Как пользоваться

1. Включи мод. У правого края основного монитора по центру по вертикали появится панель.
2. Перетащи на неё ярлык, программу или папку либо нажми **+**.
3. Клик по иконке — запуск. ПКМ по иконке — дополнительные действия.
4. При включённом автоскрытии подведи курсор к краю экрана, чтобы показать панель.

## Настройки

| Настройка | Описание |
| --- | --- |
| Сторона экрана | Правый или левый край основного монитора. |
| Размер иконок | Размер в пикселях при 100% DPI (16–96), масштабируется вместе с DPI системы. |
| Автоскрытие | Сворачивать в тонкую полоску, пока курсор не коснётся края. |
| Прятать в полноэкранных приложениях | Скрывает панель поверх полноэкранных окон и игр. |
| Анимации | Включает и выключает все анимации. |
| Цвета фона / подсветки / акцента / рамки | Формат `#RRGGBB`. При неверном значении используется цвет по умолчанию. |

## Примечания и ограничения

- Мод работает как самостоятельный инструмент в собственном процессе (он не внедряется в проводник и ничего не перехватывает), поэтому сбой мода не может повлиять на оболочку Windows, а одновременно запущена всегда только одна копия.
- Перетаскивание из окон, запущенных **от имени администратора**, блокируется Windows (UIPI). В этом случае используй кнопку **+**.
- Панель располагается на **основном** мониторе. При автоскрытии и втором мониторе с той же стороны курсор может проскакивать край слишком быстро — в таком случае отключи автоскрытие.
- Количество слотов ограничено высотой экрана.
- Слоты хранятся как пути к файлам. Если файл перенесён или удалён, иконка станет стандартной, пока ты не уберёшь слот.

