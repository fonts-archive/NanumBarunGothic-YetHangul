# 나눔 바른 고딕 옛한글

[배포처 바로가기](https://hangeul.naver.com/font)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Nanum Barun Gothic YetHangul`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/NanumBarunGothic-YetHangul/NanumBarunGothic-YetHangul.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/NanumBarunGothic-YetHangul/NanumBarunGothic-YetHangul.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Nanum Barun Gothic YetHangul';
    font-weight: 400;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/NanumBarunGothic-YetHangul/NanumBarunGothic-YetHangul.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/NanumBarunGothic-YetHangul/NanumBarunGothic-YetHangul.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/NanumBarunGothic-YetHangul/NanumBarunGothic-YetHangul.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/NanumBarunGothic-YetHangul/NanumBarunGothic-YetHangul.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/NanumBarunGothic-YetHangul/subsets/NanumBarunGothic-YetHangul-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/NanumBarunGothic-YetHangul/subsets/NanumBarunGothic-YetHangul-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "Nanum Barun Gothic YetHangul", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
네이버에서 제작한 나눔 글꼴과 마루 부리 글꼴, 클로바 나눔손글씨(이하 네이버 글꼴)의 지적 재산권은 네이버와 네이버 문화재단에 있습니다.
네이버 글꼴은 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공되며 글꼴 자체를 유료로 판매하는 것을 제외한 상업적인 사용이 가능합니다.

네이버 글꼴은 본 저작권 안내와 라이선스 전문을 포함해서 다른 소프트웨어와 번들하거나 재배포 또는 판매가 가능하고 자유롭게 수정, 재배포하실 수 있습니다.
네이버 글꼴 라이선스 전문을 포함하기 어려울 경우 출처 표기를 권장합니다. 예) 이 페이지에는 네이버에서 제공한 나눔 고딕 글꼴이 적용되어 있습니다.

네이버 글꼴을 사용한 인쇄물, 광고물(온라인 포함)의 이미지는 나눔 글꼴 프로모션을 위해 활용될 수 있습니다.
이를 원치 않는 사용자는 언제든지 당사에 요청하실 수 있습니다.

정확한 사용 조건은 네이버 나눔 글꼴 라이선스 전문을 참고하시기 바랍니다.
네이버 마루 부리 글꼴과 클로바 나눔손글씨도 나눔 글꼴과 같은 오픈 라이센스 글꼴로 동일한 저작권 규정을 적용받습니다.
```
