# firefox-simple-blur
A very simple translucent userchrome theme for firefox. It literally does not get any simpler than this.

- Tested on Linux (KDE Plasma) only. I don't know if this works anywhere else.
- Just like every other userchrome theme, you have to configure the blur yourself on your setup
  - On KDE Plasma, Use the [force blur kwin script](https://store.kde.org/p/1294604/)
    - There's an issue where turning off native title bar makes background opaque again, but I found a workaround:
      - `(right click on the native title bar) > More actions > Configure Special Application Settings...` This will open a window allowing you to add kwin window rules.
      - `Add Proprety... > (search for 'active opacity') > (force it to 99%)`
      - The window will always be 1% transparent, but it's impossible to notice, especially with blur
- You can (and should) also customize the main background color:
    ```css
    /* Main window background */
    #main-window {
      background-color: rgba(0,0,0,0.65) !important;
      ...
    }
    ```
