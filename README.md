# COS_website
https://cosjava26.github.io/COS_website/index.html

## 改版過程：
<p align="center">
  <img src="http://i.imgur.com/KajoSVQ.png">
</p> 

### Step1.接收需求，發現問題：
這個網站同時包含電腦版及手機版(獨立的兩個網站)，而隨著網站功能不斷的增加，程式碼及網站上的元件也一直增加，互相不能共用，導致難以維護，所以，開啟了整個網站的重構計劃。
<br />

### Step2.解決方案：
1. 元件的共用性使用(大小網獨立情況）
2. 減少 bootstrap lib 的使用( bootstrap 的肥大減量使用，改自刻共用元件..等等) 
3. 制定設計 guideline
<br />

### Step3.解決問題：
1. 不使用 bootstrap 整套框架，取用 bootstrap grid 的部分使用
2. css用 scss 好維護：
[scss 結構](/sass/create.scss)，並將css壓縮
3. 制定各頁面共通元件，並撰寫 guideline 文件:

    **Guideline線上連結：** https://company-86725.frontify.com/d/gKkScbE41w3W/style-guide
    - Brand/Logo：EZprice logo 使用規範
    - Colors：大網顏色制定(包含主色調、輔色、灰色的使用方法)
    - Typography：大網使用字體＆使用範例
    - Grid：大網 網格系統制定(html+scss)
    - icons：使用 web fonts(http://app.fontastic.me/)
    - tables：熱門關鍵字使用的 table
    - Form：search bar , input box, text area, checkbox
    - Buttons：前往賣場.看全部價格的按鈕樣式
    - label：贊助廣告 label tag. 關鍵字label tag
    - Cards：卡片樣式呈現
    - Pagination：頁碼呈現

