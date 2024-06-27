# Charter

[배포처 바로가기](https://fontesk.com/charter-typeface/)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Charter`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Charter/Charter.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/Charter/Charter.css');
```

### CSS `@font-face`

```css
/* normal */
@font-face {
    font-family: 'Charter';
    font-weight: 400;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Charter/Charter-Regular.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Charter/Charter-Regular.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Charter/Charter-Regular.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Charter/Charter-Regular.ttf') format('truetype');
}
@font-face {
    font-family: 'Charter';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Charter/Charter-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Charter/Charter-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Charter/Charter-Bold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Charter/Charter-Bold.ttf') format('truetype');
}

/* Italic */
@font-face {
    font-family: 'Charter';
    font-weight: 400;
    font-style: italic;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Charter/CharterItalic-Regular.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Charter/CharterItalic-Regular.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Charter/CharterItalic-Regular.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Charter/CharterItalic-Regular.ttf') format('truetype');
}
@font-face {
    font-family: 'Charter';
    font-weight: 700;
    font-style: italic;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Charter/CharterItalic-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Charter/CharterItalic-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Charter/CharterItalic-Bold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Charter/CharterItalic-Bold.ttf') format('truetype');
}
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "Charter", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
Charter is a transitional serif typeface designed by Matthew Carter in 1987 for Bitstream Inc. The font based on Pierre-Simon Fournier’s characters, originating from the 18th century.

Charter font family includes Regular and Bold weights, including matching Italics. It was designed  as a body text font and remains suitable for printing on both modern high-resolution laser printers and lower resolution printers due to its strong, legible design.

There area also extended version XCharter with updated characters and extended language support.

Designed by: Matthew Carter
License: Free for commercial use
```
