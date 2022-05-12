# firefox-blur
A very simple translucent userchrome theme for firefox.

- Tested on Linux (KDE Plasma) only
- Does not include blur, instructions depend on your setup
  - On KDE Plasma, Use the [force blur kwin script](https://store.kde.org/p/1294604/)
- Turning off native title bar makes background opaque, but I found a workaround on KDE Plasma:
  - `(right click on the native title bar) > More actions > Configure Special Application Settings...`
  - `Add Proprety... > (search for 'active opacity') > (force it to 99%)`
- Tbh I find this css pretty ugly with most themes, So I made my own using Firefox Color. I'll upload mine once I complete it.
- You can also customize the main background color:
```css
/* Main window background */
#main-window {
  background-color: rgba(0,0,0,0.65) !important;
}
```
