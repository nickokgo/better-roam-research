# Better Roam Research

This is a team for Roam Research. Got feedback? **[Say hi on Twitter](https://twitter.com/linuz90).**

# How to use

1. Create a page named exactly `roam/css`

2. Paste this code inside it:

```
  - [[Better Roam Research]]
    - ```css @import url("https://linuz90.github.io/better-roam-research/src/css/main.css");```
```

The theme will change when I push updates in this repo ⚡️

More extensive guide [here](https://nesslabs.com/roam-research-themes-custom-styling-css).

# Preview

Light:

![](/assets/preview-light.png)

When Dark Mode is enabled on your computer:

![](/assets/preview-dark.png)

# Editing this theme

The working [SCSS](https://sass-lang.com/) file is [here](/main.scss).

**The compiled CSS** file is [here](/src/css/main.css). This CSS can be used with [Stylus](https://chrome.google.com/webstore/detail/stylus-beta/apmmpaebfobifelkijhaljbmpcgbjbdo?hl=en).

Command to compile using SASS:

`sass --sourcemap=none --no-cache --watch ./src/css/main.scss:./src/css/main.css`
