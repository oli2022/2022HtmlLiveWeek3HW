# 2022切版直播班-第三週作業-眼鏡形象網站

[第三週作業](https://xd.adobe.com/view/5b20cbc4-5c64-4b67-814e-633b078a8cd4-0e73/grid/)  

## 繳交內容
您的 Discord 名稱
您的作業等級，請見下方等級表，例如 LV1
作業網址：請提供 GitHub Pages 以及 Github Repo 連結，以方便助教與講師檢視（可以參考「Github Pages 免費架站空間教學」上傳方式）
訓練菜單：請到此*連結*挑選 2~3 個訓練菜單，並回報您增加哪些技能的熟練度。


## 作業等級表
LV1：只做 header 與 footer 的 RWD
LV2：任選一頁，僅做 PC 版型（header 與 footer 需含 RWD）
LV3：任選一頁，整頁都需含 RWD
LV4：做二~三頁以上的 RWD
LV5：所有頁面都有設計


## 作業提醒
正確設定 container，左右需留 12px 的 padding
內層容器需以 % 為單位設計，不可以寫死寬度！！！
伸縮時不可以出現 x 軸與跑版的狀況
頁數需以實際網站頁數計算
需至少完成 Lv1 作業需求
需使用線上圖示 Material Design Icons
作業須符合此作業規範

## 第 1 頁 / 共 25 頁
讓圖片去掉週邊的區塊
```css
img{
  display: block;
}
```
### wrap 最外層

### header
logo 要連結並藏h1
```css
    text-indent: 101%; /* 首行縮排*/
    white-space: nowrap;    /* 不要讓文字斷行*/
    overflow: hidden;   /*把文字隱藏起來*/
```
連結去底線
```css
text-decoration: none;
```
## banner 
"立即購買"要連結

文字疊在圖片上面
```css
.banner img {
    position: relative;
    z-index: 1;
}
.banner ul {
    width: 80%;
    position:absolute;
    z-index: 2;
    display: flex;
    flex-direction: column;
}
```
## introduce
行距1.5倍
```css 
line-height: 24px;
```

## product

## joinProduct
文字置中
```css
text-align: center;
```
