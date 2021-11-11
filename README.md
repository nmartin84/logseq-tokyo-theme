# Tokyo Night
Ported from Obsidian, all credits for the theme and its colors go to the original author [URL](https://github.com/RuslanGagushin/Tokyo-Night-Obsidian-Theme)... My focus was to make this theme module enough that you can adjust several aspects of the theme from inside your `custom.css` without breaking your other themes.
![Tokyo Night/Day](images/TokyoNight_Day.png)

## Getting Started
- From Logseq, open the plugins panel, navigate to marketplace, and select install on the Tokyo Theme.
- (Optional)
  - Clone this repo to your computer.
  - Install the theme as a Plugin inside LS and you're set to go.

## Additioanl color themes
- Tokyo themes now comes with other popular themes from VSCode and DOOM Emacs. You can find a selection of color themes when you open the Themes panel in Logseq.

## Feedback
- Feedback is welcome! If you have suggestions feel free to submit a PR.

# Snippets
These are optional snippets that you can add to your custom.css if you want the extra flashy stuff.

**inline code blinking cursor**  
![picture 2](images/ae1d6a1a7a3e631a1d8f39d505814c2c3f0ccc59b2275a4551809c8d60b617af.png)  

```css
:not(pre)>code::after {
    font-family: "Font Awesome 5";
    font-weight: 900;
    font-size: 100%;
    content: "|";
    position: relative;
    top: -1px;
    color: var(--cd-standby-color-1);
    animation: pulse2 linear 1s infinite;
    margin-right: 2px;
    margin-left: 2px;
}
```

**right carrot arrow prefixed to block references**  
![picture 1](images/a2d30c8229e0bb81fe4491bde0175d7d995c4b1403215d4af48f942fcdc5e6a5.png)  

```css
.block-ref:before {
    content: "\f105";
    color: var(--cd-standby-color-1);
    font-size: 100%;
    padding-right: 0.2em;
}
```
