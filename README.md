# Nonnon Test Labs

this is beta vesion for testing.<br>

MinGW 3.x is not supported 2020 Nov 30 release or earlier.<br>
MinGW 4.x cannot be uploaded by GitHub's size limit (25MB).<br>

# Instructions

1. download MinGW and Test .ZIP<br>
2. unlock security feature of Windows and unzip them (use arcdrop.exe if you want)<br>
3. set PATH like "C:\MinGW\bin;" see ProjectNonnon.txt for details<br>
4. run .BAT<br>
5. test it<br>

# Issues

[ All ]<br>

+ GDI+ DLL is important to work.<br>

[ Aug 10 ]<br>

+ BUGFIX : TxtBox : caret clamp problem.<br>
+ NEW_FEATURE : Fluent UI available.<br>
+ NEW_FEATURE : Nonnon Typing is released.<br>

[ Aug 11 ]<br>

+ BUGFIX : Win10 accent color support.<br>
+ BUGFIX : Watchcat : not beautiful when 1%.<br>

[ Aug 12 ]<br>

+ NEW_FEATURE : Fluent UI : popup menu available.<br>

[ Aug 13 ]<br>

+ NEW_FEATURE : Fluent UI : Context Menu : semi-transparent effect available.<br>

+ BUGFIX : Fluent UI : Context Menu : Win10 : when DPI is changed : drop shadow misbehaves.<br>
+ BUGFIX : Fluent UI : Context Menu : Accordion UI : drop shadow misbehaves.<br>
+ BUGFIX : Checkbox : margin between check and text is too narrow.<br>
+ BUGFIX : TxtBox : horizontal scrollbar : page is insufficient in some cases.<br>

[ Aug 14 ]<br>

+ NEW_FEATURE : Fluent UI : menu has blurred background.<br>
+ NEW_FEATURE : Fluent UI : menu disabled text color will be thinner.<br>

+ BUGFIX : IconButton : hover misbehave problem,<br>
+ BUGFIX : TxtBox : auto-scroll usability problem.<br>

[ Aug 15 ]<br>

BUGFIX : OrangeCat : Fluent UI : Simple Menu : Blurred Background : Accordion : not sync when changed.<br>
BUGFIX : TxtBox : auto-scroll : once fixed but not fixed yet.<br>
BUGFIX : Scrollbar : Fluent UI : not Dark Mode : edge color is inaccurate.<br>
BUGFIX : Icon Button : flashing when callback is heavy.<br>

[ Aug 17 ]<br>

NEW_FEATURE : win32/win_button.c : released : new version of win_iconbutton.c.<br>

BUGFIX : CatPad : crash when dragged.<br>

[ Aug 17 #2 ]<br>

BUGFIX : win32/win_button.c : non-darkmode : border is inaccurate.<br>
BUGFIX : win32/win_button.c : disabled state is not working.<br>

[ Aug 17 #3 ]<br>

BUGFIX : win32/win_button.c : disabled state misbehaves.<br>

[ Aug 18 ]<br>

NEW_FEATURE : win32/win_button.c : n_win_button_forced() : forced status change.<br>
NEW_FEATURE : win32/win_button.c : default state is supported.<br>
NEW_FEATURE : win32/win_button.c : Light Theme : more beautiful than older.<br>

BUGFIX : Nonnon Paint : on faster machine like VirtualBox : some UI disappears.<br>
BUGFIX : Nonnon Paint : Fluent UI : Classic : many bugs are fixed.<br>
BUGFIX : Nonnon Paint : icon buttons : not updated when wheeling.<br>
BUGFIX : TxtBox : left side margin is insufficient when horizontal scroll is needed.<br>
BUGFIX : win32/win_button.c : WinVista/7 : DWM : Fluent UI : corner problem.<br>
BUGFIX : Toolband : WinVista/7 : UxTheme : misbehave when inactive state.<br>

[ Aug 19 ]<br>

NEW_FEATURE : Fluent UI : Simple Menu : System Compliance : drop shadow on/off available.<br>
NEW_FEATURE : win32/win_button.c : faster than older.<br>
NEW_FEATURE : win32/win_simplemenu.c : experimental Aero Glass support is added.<br>

BUGFIX : Fluent UI : Simple Menu : Non-32bpp Display : crash.<br>
BUGFIX : Fluent UI : Simple Menu : many bugs are fixed.<br>
BUGFIX : OrangeCat : zebra stripe : background color is inaccurate.<br>

[ Aug 21 ]<br>

NEW_FEATURE : Nonnon Typing : initial screen is added.<br>
NEW_FEATURE : Simple Menu : Fluent UI : blur is revived.<br>

BUGFIX : Simple Menu : always drawn when calculation only.<br>

[ Aug 22 ]<br>

NEW_FEATURE : Marie : Popup : Fluent UI : implemented.<br>
NEW_FEATURE : Input Popup : Fluent UI : implemented.<br>
NEW_FEATURE : TxtBox : ONELINE_ROUNDRC : LISTBOX is supported.<br>
NEW_FEATURE : CatPad/Nyaurism/Pen Trainer : Fluent UI : round rect is implemented.<br>

BUGFIX : Simple Menu : Fluent UI : Blurred Background : slow sync problem.<br>
BUGFIX : win32/win_button.c : many bugs are fixed.<br>

[ Aug 23 ]<br>

NEW_FEATURE : Listbox : Fluent UI : round rect is implemented.<br>

BUGFIX : ProjectChecker : regression : pressing effect is broken.<br>
BUGFIX : TxtBox : NO_FOCUS_CHANGE : not working.<br>
BUGFIX : Fluent UI : border is not beautiful.<br>

[ Aug 24 ]<br>

NEW_FEATURE : Combobox : Fluent UI : round rect is implemented.<br>

BUGFIX : Button : logic : many bugs are fixed.<br>
BUGFIX : Rich Dialog : regression : title is missing.<br>

[ Aug 25 ]<br>

NEW_FEATURE : n_bmp_roundrect_detect() : 10% faster than older.<br>
NEW_FEATURE : Fluent UI : round parameter : re-tuend.<br>

BUGFIX : TxtBox : ONELINE : Fluent UI : Non-Darkmode : Corners : inaccurate color is used.<br>
BUGFIX : Nonnon Paint : Layer Window : Rename : position and size are inaccurate.<br>
BUGFIX : TxtBox : LISTBOX : regression : padding is not clipped.<br>
BUGFIX : Fluent UI : WinXP : many bugs are fixed.<br>
BUGFIX : Fluent UI : Win2000 : many bugs are fixed.<br>
BUGFIX : All : graphical glitch is reduced.<br>

[ Aug 26 ]

NEW_FEATURE : Fluent UI : Simple Menu : Aero Mode is implemented.<br>
NEW_FEATURE : TxtBox : USE_INPUT_POPUP is obsoleted, use AUTO_FOCUS_RECT instead.(default is off)<br>

BUGFIX : TxtBox and Input Popup : focus frame blinks.<br>
BUGFIX : Button : Dark Mode : WinVista : frame size is inaccurate.<br>

[ Aug 27 ]<br>

NEW_FEATURE : Calendar : Fluent UI : implemented.<br>
NEW_FEATURE : TxtBox : LISTBOX : Fluent UI : round rect selection is revived.<br>
NEW_FEATURE : All : GUI : more margin is added.<br>
NEW_FEATURE : Fluent UI : n_win_fluent_ui_draw_roundrect() : faster than older.<br>
NEW_FEATURE : Color Picker : Fluent UI : implemented.<br>
NEW_FEATURE : Combobox Popup : Fluent UI : implemented.<br>

BUGFIX : All : Fluent UI : round rect always when off by INI file.<br>
BUGFIX : TxtBox : Edit Box : right side margin is inaccurate.<br>
BUGFIX : Nonnon Paint : Resizer : controls blink when combo is selected.<br>
BUGFIX : Win95 : many bugs are fixed.<br>
BUGFIX : Combobox : typo in HWND property is fixed.<br>

[ Aug 28 ]<br>

NEW_FEATURE : Nonnon Paint : padding is added.<br>
NEW_FEATURE : Project Checker : padding is added.<br>
NEW_FEATURE : OrangeCat : Breadcrumb Address Band : DnD : wait available.<br>
NEW_FEATURE : Button : more robust than older.<br>

BUGFIX : Simple Menu : Win10 : Fluent UI : HRGN : black screen problem.<br>
BUGFIX : Simple Menu : WinVista/7 : Aero Mode : black screen problem.<br>
BUGFIX : Combobox : regression : Win2000 : HRGN : slide effect is not working.<br>
BUGFIX : Neko no Te : Input Popup : focus border misbehaves.<br>
