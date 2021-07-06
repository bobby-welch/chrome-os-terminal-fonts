# Chrome OS Terminal Fonts

## Font details

* [JetBrains Mono](https://cdn.jsdelivr.net/gh/bobby-welch/chrome-os-terminal-fonts@main/chrome-os-terminal-fonts-jetbrains-mono.css)
* [Cascadia
    Code](https://cdn.jsdelivr.net/gh/bobby-welch/chrome-os-terminal-fonts@main/chrome-os-terminal-fonts-ms-cascadia-code.css)
* [PragmataPro](https://fsd.it/shop/fonts/pragmatapro/)
    

**NOTE**: One must use a raw github link for this to work.

## Set fonts for the Chrome OS terminal

* Open the JS terminal for the Chrome OS terminal via `ctrl-shift-J`
* Paste one of the following commands:

```javascript
// JetBrains Mono
term_.prefs_.set('user-css','https://cdn.jsdelivr.net/gh/bobby-welch/chrome-os-terminal-fonts@main/chrome-os-terminal-fonts-jetbrains-mono.css');

// MS Cascadia Code
term_.prefs_.set('user-css','https://cdn.jsdelivr.net/gh/bobby-welch/chrome-os-terminal-fonts@main/chrome-os-terminal-fonts-ms-cascadia-code.css');

// PragmataPro - This font is not free.  Purchase and update links.
term_.prefs_.set('user-css','https://cdn.jsdelivr.net/gh/bobby-welch/chrome-os-terminal-fonts@main/chrome-os-terminal-fonts-ms-cascadia-code.css');
```
