# Chrome OS Terminal Fonts

## Font details

* [JetBrains Mono](https://cdn.jsdelivr.net/gh/bobby-welch/chrome-os-terminal-fonts@main/chrome-os-terminal-fonts-jetbrains-mono.css)
* [Cascadia
    Code](https://cdn.jsdelivr.net/gh/bobby-welch/chrome-os-terminal-fonts@main/chrome-os-terminal-fonts-ms-cascadia-code.css)
* [PragmataPro](https://fsd.it/shop/fonts/pragmatapro/)

**NOTE**: One must use a raw link for this to work.

## Set fonts for the Chrome OS terminal

* Open the JS terminal for the Chrome OS terminal via `ctrl-shift-J`
* Paste one of the following commands into the JS terminal:

```javascript
// JetBrains Mono
term_.prefs_.set('user-css','https://cdn.jsdelivr.net/gh/bobby-welch/chrome-os-terminal-fonts@main/chrome-os-terminal-fonts-jetbrains-mono.css');
```

```javascript
// MS Cascadia Code
term_.prefs_.set('user-css','https://cdn.jsdelivr.net/gh/bobby-welch/chrome-os-terminal-fonts@main/chrome-os-terminal-fonts-ms-cascadia-code.css');
```

```javascript
// PragmataPro - This font is not free.  Purchase and update links.
term_.prefs_.set('user-css','https://cdn.jsdelivr.net/gh/bobby-welch/chrome-os-terminal-fonts@main/chrome-os-terminal-fonts-pragmata-pro-with-ligatures.css');
```

```javascript
// PragmataProMono - This font is not free.  Purchase and update links.
term_.prefs_.set('user-css','https://cdn.jsdelivr.net/gh/bobby-welch/chrome-os-terminal-fonts@main/chrome-os-terminal-fonts-pragmata-pro-mono-with-ligatures.css');
```
