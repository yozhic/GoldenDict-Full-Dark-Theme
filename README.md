# Full dark theme for the GoldenDict interface on Windows

_Version 1.9 from 07.06.2021_  

Tested on GoldenDict 1.5.0-RC2-422 (Qt 5.12.3) on Windows 10, 8.1 and 7. See screenshots below.  

## Installation

Copy `Dark` and `Dark-Deep` folders to the `styles` folder in the `GoldenDict` configuration folder.  

If `GoldenDict` is installed by default, the `styles` folder is located at the:  
```
c:\Users\<user>\Application Data\GoldenDict\styles\
```

For a portable installation, the `styles` folder is located here:  
```
GoldenDict\portable\styles\
```

To make the new icons work, you must move the `icons` folder to the `GoldenDict` program folder. For example, `c:\Program Files\GoldenDict\icons\`.  

To return to the original icons, you need to remove the appropriate rules in `qt-style.css` - see comments.  

## Main window background image

The Main Window background image can be replaced or its transparency can be adjusted. See the comments in the `Basics` section of the `article-style.css` file.  

You can also replace the pattern file for collapsed articles. See the corresponding comment in the `Articles` section of the `article-style.css` file.  

## Color palette

Colors used in `qt-style.css`:  

`#2B3339`
: main background  

`#232B30`
: darker background in tables and some input fields (in the `Dictionaries...` preferences)  

`#4E5B65`
: frame lines; unfocused elements highlighting  

`#C7CBD3`
: text  

`#0080FF`
: (brigth blue) accents & focused selections  

`#A40000`
: (rubin) highlighting in the search field in case of a negative result; accents on close buttons  

You can change the color-code with the Find/Replace tool in any text editor.  

## Customization

In the file `qt-style.css` you can also customize:  

1. Drop-down lists size. Search by keyword `drop-down list size`. Then change, comment or delete the corresponding values.  
2. Font typefaces and size. Search by keyword `font`. Then change, comment or delete the corresponding values.  

## Screenshots
### Dark theme
![GoldenDict Dark theme](GD_WIN_DARK_THEME.png)  
_GoldenDict Dark theme_  

### Dark Deep theme
![GoldenDict Dark Deep theme](GD_WIN_DARK_DEEP_THEME.png)  
_GoldenDict Dark Deep theme_  

### Modal Windows
![Full-text Search window](GD_WIN_DARK_THEME_FTS.png)  
_Full-text Search window_  

![Dictionary Headwords window](GD_WIN_DARK_THEME_Dic_Headwords.png)  
_Dictionary Headwords window_  

![Dictionary annotation window](GD_WIN_DARK_THEME_About_Dic.png)  
_Dictionary annotation window_  

![About window](GD_WIN_DARK_THEME_About.png)  
_About window_  

![Dictionaries... window](GD_WIN_DARK_THEME_Dicts.png)  
_Dictionaries... window_  

![Preferences... window](GD_WIN_DARK_THEME_Prefs.png)  
_Preferences... window_  

## Credits

Thanks to [robertknight](https://github.com/robertknight) for his [Qt-Inspector](https://github.com/robertknight/Qt-Inspector).  
