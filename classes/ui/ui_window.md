#### Класс CUIWindow

##### Описание:

Класс, представляющий базовую абстракцию окна в игре. Является классом самого верхнего уровня в иерархии UI-компонентов.

##### Свойства:

Данный класс не имеет свойств

##### Методы:

| Сигнатура                                                    | Возвращаемое значение |
| ------------------------------------------------------------ | --------------------- |
| CUIWindow()                                                  | CUIWindow             |
| GetFont()                                                    | CGameFont*            |
| SetWindowName(string *windowName*)                           | Нет                   |
| Enable(boolean)                                              | Нет                   |
| SetHeight(number *height*)                                   | Нет                   |
| SetAutoDelete(boolean *isAutoDelete*)                        | Нет                   |
| AttachChild(CUIWindow* *pChild*)                             | Нет                   |
| SetWndPos(number *x*, number *y*)                            | Нет                   |
| ResetPPMode()                                                | Нет                   |
| WindowName()                                                 | string                |
| DetachChild(CUIWindow* *pChild*)                             | Нет                   |
| SetPPMode()                                                  | Нет                   |
| SetFont(CGameFont* *pFont*)                                  | Нет                   |
| IsShown()                                                    | boolean               |
| Init(number *x*, number *y*, number *width*, number *height*) | Нет                   |
| Init(Frect* *pWindowRect*)                                   | Нет                   |
| SetWndRect(Frect *windowRect*)                               | Нет                   |
| SetWndRect(number *x*, number *y*, number *width*, number *height*) | Нет                   |
| GetHeight() const                                            | number                |
| SetWidth(number *width*)                                     | Нет                   |
| Show(boolean *isShown*)                                      | Нет                   |
| IsEnabled()                                                  | boolean               |
| SetWndSize(number *width*, number *height*)                  | Нет                   |
| GetWidth() const                                             | number                |
| IsAutoDelete()                                               | boolean               |

<br/>

См. также:

- CGameFont
- Frect