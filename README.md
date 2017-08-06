# EZprice 比價網 
https://ezprice.com.tw/

**遇到問題：**
1. 網站重構，速度過慢
2. 頁面元件無法重複使用

**解決方法：**
1. 不使用 bootstrap 整套框架，取用 bootstrap grid 的部分使用即可
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

