# 網頁切版直播班 Vite 範例 - Bootstrap 版本

## 我修改了哪些部分
  - _variables.scss 的 $theme-colors 將主色輔色變成變數
  - $enable-rounded 變成 false 就沒有圓角了
  - $body-bg 由white換成 #f3f1e5
  - $body-color 由$gray-900換成 #030303
  - $headings-margin-bottom: 0 !default; 移除標題的margin-bottom
  - $paragraph-margin-bottom: 0 !default; 移除P的margin-bottom
  - $link-decoration: none !default; 由underline 變成 none a就沒有下底線了 
  - $font-family-sans-serif
  - $spacer 可改間距
  - $font-sizes 可改字大小
  - 最常用就是字，間距，顏色


## 心得
- 不要寫死寬，讓row 跟 col 自動 RWD
- 學到重點:
- 1.用偽元素做hover
.hover-bg-yellow{
  position:relative;  
  &:hover:before{
    content: "";
    position:absolute;
    background-color: yellow;
    width: 29px;
    height: 29px;
    border-radius: 50px;
    left:-8px;
    z-index: -1;
  }
}

- 2.手機漢堡選單如何製作
- d-md-none

- 3. 在login頁面
- 因為bootstrap5 是mobile first 
- mt-md-60 mt-24
- 用這個寫法就不用@media


-網站:https://iamreneewang.github.io/vitehw6/


#留意X軸問題
使用F12觀察並且修正
