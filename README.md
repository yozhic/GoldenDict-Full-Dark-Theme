<sup>[ en | [ru](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/README_RU.md) ]</sup>  
# GoldenDict Windows Full Dark Theme
This theme has been successfully tested on:  

- GoldenDict 1.5.0-8 (commit [f303bb4](https://github.com/goldendict/goldendict/commit/f303bb4accea2de7afdeeab2c31aa7ccc1ff2ebc))  
- Qt 5.12.3  
- Windows 10, 8.1 and 7  

> [!WARNING]  
> Fixes may be required for use in other configurations and on other operating systems.  


## Installation

Download [source code](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/archive/refs/heads/main.zip) and unzip the archive.  

### Standard setup

Move `fonts` and `styles` folders to:  

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

Move `icons` folder to:  

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

### Portable setup

Move `fonts`, `icons` and `styles` folders to:  

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


## Color palette

Colors used in `qt-style.css`:  

Color     | Description
:-------- | :-----------
`#2B3339` | main background  
`#232B30` | darker background in tables and some input fields  
`#4E5B65` | frame lines; unfocused elements highlighting  
`#C7CBD3` | text  
`#8E9CA8` | dimmed text  
`#0080FF` | (brigth blue) accents & hovers  
`#FFFFFF` | text on brigth blue background  
`#006AD5` | (dimmed blue) list selections  
`#A40000` | (rubin) highlighting in the search field in case of a negative result; accent on close buttons  
`#D3D6DC` | articles background  
`#000000` | pressed elements; some borders  
`#353F46` | tables headers  
`#3D464E` | accents in dictionaries buttons  


You can change the color by find/replace its code in any text editor.  


## Customization

In `article-style.css` you can also customize:  

1. Main window background image or its transparency: see [here](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/GoldenDict/styles/Dark/article-style.css#L76).  
2. Pattern for collapsed articles: see [here](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/GoldenDict/styles/Dark/article-style.css#L360).  
3. Icons for sound and video files: see examples in the [`extras`](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/tree/main/GoldenDict/extras) folder.  

In `qt-style.css` you can also customize:  

1. Drop-down lists size. Search by keyword `drop-down list size`. Then change, comment or delete the corresponding values.  
2. Font typefaces and size. Search by keyword `font`. Then change, comment or delete the corresponding values.  


## Screenshots
### Main window

_Welcome screen_  

![Welcome screen](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_WELCOME.png)  

_Dark theme_  

![Dark Main window](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME.png)  

_Dark Deep theme_  

![Dark Deep Main window](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_DEEP_THEME.png)  

_Scan Pop-up window_  

![Dark Deep Scan Pop-up](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_SCAN_POPUP.png)  

### Modal Windows

_Full-text Search window_  

![Dark Full-text Search](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_FTS.png)  

_Dictionary Headwords window_  

![Dark Headwords](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_Dic_Headwords.png)  

_Dictionary annotation window_  

![Dark Annotation](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_About_Dic.png)  

_About window_  

![Dark About](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_About.png)  

_Dictionaries window_  

![Dark Dictionaries](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_Dicts.png)  

_Preferences window_  

![Dark Preferences](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_Prefs.png)  


## Credits

Thanks to [KDAB](https://github.com/KDAB) for [GammaRay](https://github.com/KDAB/GammaRay) ❤  
Thanks to [robertknight](https://github.com/robertknight) for [Qt-Inspector](https://github.com/robertknight/Qt-Inspector)  
