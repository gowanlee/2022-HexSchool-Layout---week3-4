# 2022-HexSchool-Layout---week3-4

2022 六角切版直播班 - 第三、四週

本週學習重點：

<b>1. 響應式網頁</b>
  - 一定要將此段語法放在head（通常預設就會有了）
    - <meta name="viewport" content="width=device-width, initial-scale=1.0">
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
