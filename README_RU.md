# Тёмная тема для GoldenDict на Windows

Тема благополучно протестирована на GoldenDict 1.5.0-7 (Qt 5.12.3) на Windows 10, 8.1 и 7.  
_См. ниже снимки с экрана._  


## Установка

1. Скачиваем репозиторий: на [главной странице](https://github.com/yozhic/GoldenDict-Full-Dark-Theme) кнопка `Code`, далее из выпадающего меню `Download ZIP`. Распаковываем скачанный архив.  

2. Папки `styles` и `fonts` вместе со всем содержимым перемещаем в папку настроек GD — та, что открывается по команде меню `Справка` → `Папка конфигурации` (`Help` → `Configuration Folder`).  

   Если программа установлена в стандартном режиме, то `Папка конфигурации` располагается по адресу:  

   ```
   c:\Users\<user>\AppData\Roaming\GoldenDict\
   ```

   Если установка портабельная, то рядом с исполняемым файлом `GoldenDict.exe` в подпапке `portable`:  

   ```
   GoldenDict\portable\
   ```

3. Папку `icons` перемещаем в программную папку `GoldenDict`, рядом к исполняемому файлу `GoldenDict.exe`.  

   В этой папке содержится графический элемент для отображения областей захвата разделителей панелей, а также монохромные иконки для главного и всплывающего окон. Чтобы вернуть отображение стандартных иконок GD, нужно закомментировать или удалить соответствующие правила в `qt-style.css`: в комментариях отмечено, какие именно.  


## Цветовая палитра темы

В файле `qt-style.css` используются следующие цвета:  

Цвет      | Применение
:-------- | :-----------
`#2B3339` | основной фон  
`#232B30` | более тёмный фон в таблицах и некоторых полях ввода (в диалоге `Словари...`)  
`#4E5B65` | границы фреймов; подсветка неактивных элементов  
`#C7CBD3` | текст  
`#8E9CA8` | «притушенный» текст  
`#0080FF` | (сапфировый) акценты; подсветка активных элементов  
`#FFFFFF` | текст на сапфировом фоне  
`#006AD5` | (тёмно-сапфировый) выделения в списках  
`#A40000` | (рубиновый) подсветка в полях поиска при отрицательном результате; подсветка кнопок закрытия  
`#D3D6DC` | фон текста в статьях  
`#000000` | элементы при нажатии; некоторые рамки  
`#353F46` | заголовки колонок в таблицах  
`#3D464E` | фон кнопок активных словарей  

Можно настроить собственную цветовую палитру, заменив перечисленные коды своими при помощи инструмента Поиск/Замена в любом текстовом редакторе.  


## Индивидуальные настройки

В файле `article-style.css`:  

1. Можно заменить фоновое изображение в основной панели или настроить его прозрачность. См. комментарии в секции `ARTICLE WINDOW`.  
2. Можно заменить изображение для паттерна блоков свёрнутых статей. См. комментарии в секции `ARTICLE BOXES`.  

В файле `qt-style.css` настраиваются:  

1. Размер выпадающего списка групп словарей. Для этого нужно выполнить поиск по фразе `drop-down list size`, а затем отредактировать, закомментировать или удалить найденные правила.  
2. Гарнитуры шрифтов и их размеры. Для этого нужно выполнить поиск по слову `font`, а затем отредактировать, закомментировать или удалить найденные правила.  


## Снимки с экрана
### Главное окно
_Стартовый экран_  
![GoldenDict Dark theme](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_WELCOME.png)  

_Тема Dark_  
![GoldenDict Dark theme](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME.png)  

_Тема Dark Deep_  
![GoldenDict Dark Deep theme](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_DEEP_THEME.png)  

_Всплывающее окно перевода_  
![GoldenDict Dark Deep theme](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_SCAN_POPUP.png)  

### Дополнительные окна
_Окно Полнотекстовый поиск_  
![Full-text Search window](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_FTS.png)  

_Окно Заголовки словаря_  
![Dictionary Headwords window](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_Dic_Headwords.png)  

_Окно Информация о словаре_  
![Dictionary annotation window](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_About_Dic.png)  

_Окно Справка_  
![About window](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_About.png)  

_Диалог настроек `Словари...`_  
![Dictionaries... window](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_Dicts.png)  

_Диалог настроек `Параметры...`_  
![Preferences... window](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_Prefs.png)  


## Благодарности

Спасибо [KDAB](https://github.com/KDAB) за инспектор Qt-интерфейсов [GammaRay](https://github.com/KDAB/GammaRay) ❤  
Спасибо [robertknight](https://github.com/robertknight) за [Qt-Inspector](https://github.com/robertknight/Qt-Inspector)  
