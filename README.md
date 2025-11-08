# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Solution URL](https://github.com/Aeroxol/blog-preview-card-main)
- Live Site URL: [Live site URL](https://aeroxol.github.io/blog-preview-card-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

#### **css 프리셋 재사용**

자주 사용되는 css 스타일을 재사용하는 방법을 배웠다.

```css
.text_preset_3_bold {
  font-size: 14px;
  color: hsl(0, 0%, 7%);
  font-family: "Figtree", sans-serif;
  font-weight: 800;
  line-height: 150%;
  letter-spacing: 0px;
}
```

자주 사용하는 스타일인 text_preset_3_bold를 위와같이 정의한다.

```html
<main>
  <div class="card">
    ...
    <div class="content">
      <div class="category">
        <!-- 프리셋 사용 1 -->
        <span class="text_preset_3_bold">Learning</span>
      </div>
      ...
    </div>

    <div class="author">
      ...
      <!-- 프리셋 사용 2 -->
      <span class="text_preset_3_bold">Greg Hooper</span>
    </div>
  </div>
</main>
```

프리셋을 적용할 텍스트에 해당 class를 적용한다.

#### **figma 사용법**

figma에 레이어 정보가 상세하게 나와있다. 블록 구조가 미리 정의되어 있어 참고할 수 있다.

#### **hover, cursor**

css의 정의자 뒤에 `:hover`를 붙이면 마우스를 올렸을 때 적용할 임시 스타일을 정의할 수 있다.

스타일에 `cursor: pointer`를 적용하면 마우스를 올렸을 때 커서를 pointer로 바꿀 수 있다.