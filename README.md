# 2022-HexSchool-Layout---week3-4

2022 六角切版直播班 - 第三、四週

本週學習重點：

<b>1. 響應式網頁</b>
  - width是固定寬度，響應式網頁要用max-width才不會出現x軸
  - img max-width:100% height:auto 可以當作css reset

<b>2. css權重</b>
  - HTML 標籤：1 分
  - class 選擇器：10 分
  - ID 選擇器：100 分
  - inline style：1000 分
  - !important：10000 分

<b>3. 斷點規劃</b>
  - PC - 1200px
  - iPad - 992px
  - iPad以下 - 767px
  - iPhone 6 Plus - 414px (視專案族群)
  - iPhone 6 - 375px (視專案族群)
  - iPhone 5、SE - 320px

<b>4. gulp環境部署、git指令上傳開發環境至GitHub、gulp指令上傳至GitHub Pages</b>
  - <a href="https://hackmd.io/yWpLNMPRT2yvIR4Zq_idGw?view">參考流程（第一次）</a>
  - 更新上傳資料
    - 更新畫面（GitHub Pages）
      - gulp build
      - gulp deploy
    - 更新開發環境 （GitHub Main）
      - git add .
      - git commit -m "可自由打更新內容名稱"
      - git push
      
<b>5. 將每一頁都會出現的區塊可以用EJS做版型管理 例如：表頭、表尾</b>

<b>6. 用scss管理css</b>
  - <a href="https://docs.google.com/presentation/d/11-HFPxkmVj5b6WP50zkKB_GtccvynUu3GaDeALaLpd0/edit#slide=id.p42">ppt基本介紹</a>
  - <a href="https://courses.hexschool.com/courses/1eebd3/lectures/11953744">影片介紹</a>
 
 -------------------------------------
 
 下方提供關於作業細節的建議：

<b>整體</b>

1. .container 設定依照設計稿，應為

.container {
	margin: 0 auto;
	padding: 0 12px;
	max-width: 1320px;
}
可參考每日任務 Day23

https://hackmd.io/GQUnJGzdR6SSQDnlZdWwqA#RWD-%E6%8E%92%E7%89%88%E9%96%93%E8%B7%9D



<b>index.html</b>

1. .index-banner 內容不需要使用 padding 來推，給以給予一個固定高度 787px，

然後再使用 flex 語法讓內容垂直置中，水平靠右



<b>product-optical.html</b>

<b>product-sunglasses.html</b>

1. 「BJ41600S」屬於商品名稱，可以使用標題標籤來增加語意，優化 SEO



<b>store-detail.html</b>

1. .store-list 結構並非列表的 ul li，可使用 div 就好

2. 該頁面的門市照片可以使用背景圖片的方式製作來避免圖片擠壓變形

https://i.imgur.com/mMxqq5q.png



<b>blog.html</b>

1. 手機版型的 nav 要消失

2. 變為平板以下，more 連結要變成小寫

可參考文件 https://developer.mozilla.org/zh-CN/docs/Web/CSS/text-transform



<b>blog-detail.html</b>

1. 內文可以使用 img+p 就好，因為文章內容不屬於 ul li 列表



<b>Q&A.html</b>

1. p 段落文字要使用 br 斷行較符合設計稿的樣式
