#### Класс CUIStatic

Класс, представляющий абстракцию статического элемента управления в игре.

##### Наследуется от:

CUIWindow

##### Свойства

Данный класс не имеет свойств 

##### Методы:

| Сигнатура                                                    | Возвращаемое значение | Описание                                       |
| ------------------------------------------------------------ | --------------------- | ---------------------------------------------- |
| CUIStatic()                                                  | CUIStatic             | Новый экземпляр CUIStatic                      |
| GetTextY()                                                   | number                | Позиция текста по оси Y                        |
| GetTextX()                                                   | number                | Позиция текста по оси X                        |
| GetText()                                                    | string                | Текст                                          |
| GetColor() const                                             | number                | Цвет элемента управления                       |
| GetHeading()                                                 | number                | Размер заголовка                               |
| GetClipperState()                                            | boolean               | Обрезается ли элемент управления               |
| GetTextAlign()                                               | number                | Выравнивание текста в элементе управления      |
| GetStretchTexture()                                          | boolean               | Растянута ли текстура по элементу управления   |
| SetTextX(number *posX*)                                      | Нет                   | Установка позиции текста по оси X              |
| SetTextY(number *posY*)                                      | Нет                   | Установка позиции текста по оси Y              |
| SetTextST(string *stringId*)                                 | Нет                   | Установка текста из словаря ресурсов           |
| SetHeading(number *heading*)                                 | Нет                   | Установка величины заголовка                   |
| SetColor(number *color*)                                     | Нет                   | Установка цвета  элемента управления           |
| SetText(string *text*)                                       | Нет                   | Установка текста                               |
| SetTextAlign(number *alignment*)                             | Нет                   | Установка выравнивания текста                  |
| SetStretchTexture(boolean *isStretched*)                     | Нет                   | Установка растяжения текстуры                  |
| ClipperOn()                                                  | Нет                   | Включение обрезания элемента управления        |
| ClipperOff()                                                 | Нет                   | Отключение обрезания элемента управления       |
| SetTextColor(number *a*, number *r*, number *g*, number *b*) | Нет                   | Установка цвета текста                         |
| Init(string *textureName*, number *x*, number *y*, number *width*, number *height*) | Нет                   | Инициализация статического элемента управления |
| SetOriginalRect(number *x*, number *y*, number *width*, number *height*) | Нет                   | Установка оригинальной области                 |
| SetTextureOffset(number *x*, number *y*)                     | Нет                   | Установка смещения текстуры                    |
| InitTexture(string *textureName*)                            | Нет                   | Инициализация текстуры                         |



##### Методы, унаследованные от CUIWindow:

| Сигнатура                                                    | Возвращаемое значение | Описание                                     |
| ------------------------------------------------------------ | --------------------- | -------------------------------------------- |
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