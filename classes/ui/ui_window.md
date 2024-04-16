#### Класс CUIWindow

##### Описание:

Класс, представляющий базовую абстракцию окна в игре. Является классом самого верхнего уровня в иерархии UI-компонентов.

##### Свойства:

Данный класс не имеет свойств

##### Методы:

| Сигнатура                                                    | Возвращаемое значение | Описание                                     |
| ------------------------------------------------------------ | --------------------- | -------------------------------------------- |
| CUIWindow()                                                  | CUIWindow             | Новый экземпляр CUIWindow                    |
| WindowName()                                                 | string                | Имя окна                                     |
| GetFont()                                                    | CGameFont*            | Текущий шрифт                                |
| GetWidth() const                                             | number                | Ширина окна                                  |
| GetHeight() const                                            | number                | Высота окна                                  |
| IsAutoDelete()                                               | boolean               | Является ли окно автоматически удаляемым     |
| IsShown()                                                    | boolean               | Отображается ли окно                         |
| IsEnabled()                                                  | boolean               | Включено ли окно                             |
| SetWindowName(string *windowName*)                           | Нет                   | Установка имени                              |
| SetWidth(number *width*)                                     | Нет                   | Установка ширины                             |
| SetHeight(number *height*)                                   | Нет                   | Установка высоты                             |
| SetWndPos(number *x*, number *y*)                            | Нет                   | Установка позиции                            |
| SetWndSize(number *width*, number *height*)                  | Нет                   | Установка размера                            |
| SetAutoDelete(boolean *isAutoDelete*)                        | Нет                   | Установка окна, как автоматически удаляемого |
| SetPPMode()                                                  | Нет                   | Установка режима PP (?)                      |
| ResetPPMode()                                                | Нет                   | Сброс режима PP (?)                          |
| SetWndRect(number *x*, number *y*, number *width*, number *height*) | Нет                   | Установка оконной области                    |
| SetWndRect(Frect *windowRect*)                               | Нет                   | Установка оконной области                    |
| SetFont(CGameFont* *pFont*)                                  | Нет                   | Установка шрифта                             |
| Enable(boolean)                                              | Нет                   | Включение окна                               |
| Show(boolean *isShown*)                                      | Нет                   | Установка видимости                          |
| Init(number *x*, number *y*, number *width*, number *height*) | Нет                   | Инициализация окна                           |
| Init(Frect* *pWindowRect*)                                   | Нет                   | Инициализация окна                           |
| AttachChild(CUIWindow* *pChild*)                             | Нет                   | Прикрепить дочернее окно                     |
| DetachChild(CUIWindow* *pChild*)                             | Нет                   | Открепить дочернее окно                      |

<br/>

##### См. также:

- CGameFont
- Frect