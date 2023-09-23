# Тёмная тема для GoldenDict на Windows
<sup>[ [en](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/tree/main) | ru ]</sup>  
Тема благополучно протестирована на:  

- GoldenDict 1.5.0-8 (коммит [f303bb4](https://github.com/goldendict/goldendict/commit/f303bb4accea2de7afdeeab2c31aa7ccc1ff2ebc))  
- Qt 5.12.3  
- Windows 10, 8.1 и 7  

> [!WARNING]  
> Для использования в других конфигурациях и на других операционных системах могут понадобиться исправления.  

## Установка

Скачиваем репозиторий: на [главной странице](https://github.com/yozhic/GoldenDict-Full-Dark-Theme) кнопка `Code`, далее из выпадающего меню `Download ZIP`. Распаковываем скачанный архив.  

### Стандартная установка

Папки `fonts` и `styles` с содержимым перемещаем в папку настроек GD (та, что открывается по команде меню `Справка`/`Help` → `Папка конфигурации`/`Configuration Folder`):  

```
c:\
 └─ Users\
     └─ <user>\
         └─ AppData\
             └─ Roaming\
                 └─ GoldenDict\
                     ├─ fonts\   ←
                     ├─ index\
                     ├─ styles\  ←
                     ├─ config
                     └─ ...
```

Папку `icons` с содержимым перемещаем в папку GD, рядом к исполняемому файлу `GoldenDict.exe`:  

```
c:\
 └─ Program Files\
     └─ GoldenDict\
         ├─ audio\
         ├─ bearer\
         ├─ content\
         ├─ ...
         ├─ icons\  ←
         ├─ ...
         ├─ GoldenDict.exe
         └─ ...
```

### Портативная установка

Папки `fonts`, `icons` и `styles` с содержимым перемещаем в папку с программой, соблюдая следующую структуру:  

```
GoldenDict\
    ├─ audio\
    ├─ bearer\
    ├─ content\
    ├─ ...
    ├─ icons\          ←
    ├─ ...
    ├─ platforms\
    ├─ portable\
    │      ├─ cache\
    │      ├─ fonts\   ←
    │      ├─ index\
    │      ├─ styles\  ←
    │      ├─ config
    │      └─ ...
    ├─ ...
    ├─ sqldrivers\
    ├─ styles\
    ├─ ...
    ├─ GoldenDict.exe
    └─ ...
```


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

1. Можно заменить фоновое изображение в основной панели или настроить его прозрачность: _см. [здесь](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/GoldenDict/styles/Dark/article-style.css#L76)._  
2. Можно заменить изображение для заливки блоков свёрнутых статей: _см. [здесь](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/GoldenDict/styles/Dark/article-style.css#L348)._  
3. Можно заменить иконки файлов звука и видео: _см. примеры в папке [`extras`](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/tree/main/GoldenDict/extras)._  

В файле `qt-style.css`:  

1. Можно настроить размер выпадающего списка групп словарей. Для этого выполняем поиск по фразе `drop-down list size`, а затем редактируем, комментируем или удаляем найденные правила.  
2. Можно настроить гарнитуры шрифтов и их размеры. Для этого выполняем поиск по слову `font`, а затем редактируем, комментируем или удаляем найденные правила.  


## Внешний вид
### Главное окно

_Стартовый экран_  

![Вид главного окна сразу после старта программы](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_WELCOME.png)  

_Тема Dark_  

![Вид главного окна с применённой темой Dark](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME.png)  

_Тема Dark Deep_  

![Вид главного окна с применённой темой Dark Deep](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_DEEP_THEME.png)  

_Всплывающее окно перевода_  

![Вид всплывающего окна перевода с применённой темой Dark Deep, Ctrl+C+C](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_SCAN_POPUP.png)  

### Вспомогательные окна

_Окно полнотекстового поиска_  

![Вид окна полнотекстового поиска, Ctrl+Shift+F](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_FTS.png)  

_Окно заголовков словаря_  

![Вид окна заголовков словаря](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_Dic_Headwords.png)  

_Окно информации о словаре_  

![Вид окна информации о словаре](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_About_Dic.png)  

_Окно информации о программе_  

![Вид окна информации о программе](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_About.png)  

_Диалог настройки словарей_  

![Вид диалога настройки словарей](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_Dicts.png)  

_Диалог настроек программы_  

![Вид диалога настроек программы](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_Prefs.png)  


## Благодарности

Спасибо [KDAB](https://github.com/KDAB) за инспектор Qt-интерфейсов [GammaRay](https://github.com/KDAB/GammaRay) ❤  
Спасибо [robertknight](https://github.com/robertknight) за [Qt-Inspector](https://github.com/robertknight/Qt-Inspector)  
