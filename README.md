# Orchis Sublime Text Theme

A set of custom UI themes for Sublime Text 2/3  that match [Orchis GTK+ theme](http://mokaproject.com/orchis-gtk-theme/), based on [Spacegray](https://github.com/kkga/spacegray).

*The theme is no longer maintained, as the GTK+ theme is no longer being developed, sorry.*

## Themes

### Orchis Dark

Default flavour.

![image](Screenshots/orchis-dark.png)

### Orchis Light

Default flavour, light variation. 

![image](Screenshots/orchis-light.png)

You might want to disable the `GTKDarkThemeVariantSetter` package in order to get *light* title bars instead of the default *dark* ones (*GNU/Linux specific*).

### Orchis Dark Legacy

Dark variation. You shall use it if you set your Window Theme to Orchis Dark.

![image](Screenshots/orchis-dark-legacy.png)

*The font used in the screenshots is __Monaco__; the colour scheme, __Solarized__ (available via Package Control).*

## How to Install

### Via Package Control

The easiest way to install is using [Sublime Package Control](https://sublime.wbond.net), where Orchis is listed as `Theme - Orchis`.

1. Open Command Palette using menu item `Tools -> Command Palette...` (<kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>).
2. Choose `Package Control: Install Package`
3. Find `Theme - Orchis` and hit Enter

### Manual

You can also install the theme manually:

1. [Download the .zip](https://github.com/aldomann/sublime-orchis/archive/master.zip)
2. Unzip and rename the folder to `Theme - Orchis`
3. Copy the folder into `Packages` directory, which you can find using the menu item `Sublime Text -> Preferences -> Browse Packages...`

### Git Installation

Alternatively, if you are a git user, you can install the theme and keep up to date by cloning the repo directly into your Packages directory in the Sublime Text application settings area.

1. Open a Terminal.
2. Move to the `Packages` directory (you can find its location by choosing `Package Control: Browse Packages` in the `Command Palette`).
3. Run `git clone https://github.com/aldomann/sublime-orchis.git`.

## How to Activate

Activate the UI theme by modifying your user preferences file, which you can find using the menu item `Sublime Text -> Preferences -> Settings - User`.

*Alternatively you might want to use [Themr](https://sublime.wbond.net/packages/Themr) (available via Package Control) to change the UI theme easily.*

***Note: Don't forget to restart Sublime Text after activating the theme.***

### Settings for Orchis Dark

```
{
  "theme": "Orchis Dark.sublime-theme"
}
```

### Settings for Orchis Light

```
{
  "theme": "Orchis Light.sublime-theme"
}
```

### Settings for Orchis Dark Legacy

```
{
  "theme": "Orchis Dark Legacy.sublime-theme"
}
```
