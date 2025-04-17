# Arcify

Arcify transforms Firefox into a sleek, minimal interface inspired by Arc Browser. It customizes the tab area, address bar, bookmarks, and private browsing appearance to create a more modern and polished look. Ideal for users who want a cleaner, Arc-like browsing experience while keeping the power of Firefox.

![Arcify's screenshot](https://raw.githubusercontent.com/anton0kurilov/arcify/refs/heads/main/.github/screenshot.png)

## Installation

> ⚠️ Arcify requires **Firefox 136 or later** and works best with **Vertical Tabs** enabled.

### 1. Enable Vertical Tabs

Arcify is designed with Firefox’s new vertical tab layout in mind. To enable it:

1. Open `about:config` in Firefox.
2. Search for `browser.tabs.vertical`.
3. Set it to `true`.

(You may also need to restart Firefox.)

### 2. Set up userChrome.css

Arcify is a **userChrome.css** theme. To use it:

1. Enable userChrome styles:
   - Go to [`userchrome.org`](https://www.userchrome.org/how-create-userchrome-css.html) and follow the quick setup guide.
   - In short:
     - Create a `chrome` folder inside your Firefox profile directory.
     - Place the `userChrome.css` file inside that folder.
     - Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true` in `about:config`.

2. Copy the contents of `userChrome.css` into your `chrome` folder.
3. Restart Firefox.
4. Done!
