<p align="center">
  <img src="https://github.com/FOSSEON/LISTED.CSS/blob/main/LISTED-SCREENSHOT.png"/>
</p>

<div align="center">
  
The CSS layout config of the [FOSSEON blog](https://listed.to/@FOSSEON) hosted on [Listed](https://listed.to):</div>

```
---
metatype: css
---

@media (prefers-color-scheme: dark) {
  :root {
    --border: 1px solid hsla(0, 0%, 100%, 0.16);
    --color-default: #000000;
    --color-primary: #8000FF;
    --color-primary-opacity-8: rgba(147, 192, 255, 0.08);
    --color-neutral: #000000;
    --color-neutral-darker: #8000FF;
    --color-contrast: #FFFFFF;
    --color-contrast-opacity-8: hsla(0, 0%, 100%, 0.08);
    --color-contrast-opacity-16: hsla(0, 0%, 100%, 0.16);
    --color-contrast-opacity-36: hsla(0, 0%, 100%, 0.36);
    --color-contrast-opacity-86: hsla(0, 0%, 100%, 0.86);
    --post-code-background-color: #8000FF;
    --post-code-border-color: #8000FF;
  }
}

@media (min-width: 992px) {
  .header-author-info__items {
    flex-direction: column;
  }

  .header-image-container {
    width: 51%;
    min-width: 0%;
    margin-right: unset;
    margin-bottom: inherit;    
    height: 150px;
  }
}
```
<div align="center">
  
Documentation on [how to stylize your Listed blog](https://standardnotes.com/help/66/how-do-i-change-the-colors-fonts-and-general-layout-of-my-listed-blog), by [Standard Notes](https://standardnotes.com/).</div>
