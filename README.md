# `user.js`

Tweaking `about:config` to enhance/[harden](https://brainfucksec.github.io/firefox-hardening-guide) Firefox.

31% faster according to [Speedometer 3.0](https://browserbench.org/Speedometer3.0/).

## Usage

1. Download the [user.js](https://raw.githubusercontent.com/Eccys/user.js/main/user.js) file:
```sh
curl -O https://raw.githubusercontent.com/Eccys/user.js/main/user.js
```
2. Type `about:profiles` in the URL bar and open the root directory.
3. Move `user.js` to the root directory for your chosen profile.

It's recommended to use [uBlock Origin](https://ublockorigin.com/) alongside this.

## Sections
The user.js is divided into subcategories to make editing and revising it easier. You're welcome 💝
### **FASTFOX (Performance Enhancements)**:

Prioritizes speed by adjusting cache sizes, image rendering, and network connections. Enables GPU-accelerated rendering and limits prefetching to reduce unnecessary data use.

### **SECUREFOX (Privacy & Security)**:

Blocks tracking and prioritizes HTTPS connections. Disables telemetry and data collection features, including safe browsing and crash reporting and enforces stricter cookie management and blocking mixed content.

### **PESKYFOX (Interface Clean-Up)**:

Removes unwanted Mozilla UI elements, disables location tracking and notifications, and removes [Pocket](https://www.mozilla.org/en-US/firefox/pocket/) and other sponsored content on new tabs.

### **Custom Overrides**:

Contains personal settings, such as clearing browsing data on shutdown, disabling auto-form fill, enabling container tabs, and site-specific permissions.

Please, go through this section and adjust it according to your needs.

## Goals

1. **Minimalism**: get what isn't needed out of the way.
2. **Efficiency**: unleash Firefox's ability to be fast and performant.
3. **Privacy**: protect your data without causing site breakage.

Inspired by [Betterfox](https://github.com/yokoffing/Betterfox).
