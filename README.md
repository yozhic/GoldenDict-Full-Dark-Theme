# Full Dark Theme for the GoldenDict interface on Windows

Tested on GoldenDict 1.5.0-7 (Qt 5.12.3) on Windows 10, 8.1 and 7.  

<sub>_For README in Russian see [here](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/README_RU.md)._</sub>  


## Installation

1. Move `styles` and `fonts` folders to the `GD Configuration Folder`.  

   If `GoldenDict` is installed by default, the `GD Configuration Folder` is located at the:

   ```
   c:\Users\<user>\AppData\Roaming\GoldenDict\
   ```

   For a portable installation, the `GD Configuration Folder` is located here:

   ```
   GoldenDict\portable\
   ```

2. Move the `icons` folder to the `GoldenDict` program folder: `c:\Program Files\GoldenDict\`.  

   To return to the original GD icons, you need to remove the appropriate rules in `qt-style.css` - see comments inside.  


## Main window background image

The Main Window background image can be replaced or its transparency can be adjusted. See the comments in the `ARTICLE WINDOW` section of the `article-style.css` file.  

You can also replace the pattern file for collapsed articles. See the corresponding comment in the `ARTICLE BOXES` section of the `article-style.css` file.  


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


You can change the color-code with the Find/Replace tool in any text editor.  


## Customization

In the file `qt-style.css` you can also customize:  

1. Drop-down lists size. Search by keyword `drop-down list size`. Then change, comment or delete the corresponding values.  
2. Font typefaces and size. Search by keyword `font`. Then change, comment or delete the corresponding values.  


## Screenshots
### Main window
_Welcome screen_  

![GoldenDict Dark theme](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_WELCOME.png)  

_Dark theme_  

![GoldenDict Dark theme](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME.png)  

_Dark Deep theme_  

![GoldenDict Dark Deep theme](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_DEEP_THEME.png)  

_Scan Pop-up window_  

![GoldenDict Dark Deep theme](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_SCAN_POPUP.png)  

### Modal Windows

_Full-text Search window_  

![Full-text Search window](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_FTS.png)  

_Dictionary Headwords window_  

![Dictionary Headwords window](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_Dic_Headwords.png)  

_Dictionary annotation window_  

![Dictionary annotation window](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_About_Dic.png)  

_`About` window_  

![About window](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_About.png)  

_`Dictionaries...` window_  

![Dictionaries... window](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_Dicts.png)  

_`Preferences...` window_  

![Preferences... window](https://github.com/yozhic/GoldenDict-Full-Dark-Theme/blob/main/screenshots/GD_WIN_DARK_THEME_Prefs.png)  


## Credits

Thanks to [KDAB](https://github.com/KDAB) for [GammaRay](https://github.com/KDAB/GammaRay) ❤️  
Thanks to [robertknight](https://github.com/robertknight) for [Qt-Inspector](https://github.com/robertknight/Qt-Inspector)  
