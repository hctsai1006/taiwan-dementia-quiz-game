<div align="center">

# **【左右為難】台灣在地化失智症長者互動問答遊戲**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) 
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) 
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) 
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) 
[![Website](https://img.shields.io/badge/Website-blue?style=for-the-badge&logo=githubpages&logoColor=white)](https://hctsai1006.github.io/taiwan-dementia-quiz-game/)

</div>

這是一款專為台灣失智症長者及高齡族群設計的互動式團體問答遊戲。此專案旨在透過在地化的生活主題、高對比的視覺設計與真實圖片，提供一個有趣、無壓力且富有懷舊感的認知刺激活動。

遊戲玩法簡單直覺，活動帶領者可透過投影幕展示題目，引導長者以「左右跳」的身體活動方式作答，不僅活化大腦，也增加了肢體運動的機會，促進身心健康與社交互動。

## **專案特色**

* **專為長者設計**：採用超大字體、高對比色彩及清晰的版面配置，確保視覺友善。  
* **台灣在地化內容**：題目皆為台灣長輩熟悉的日常用品、食物及生活情境，充滿親切感與懷舊感。  
* **真實圖片取代圖示**：使用真實世界的物品照片，幫助長者連結現實生活經驗，降低認知負荷。  
* **簡單直覺的操作**：僅需透過「上一張」、「下一張」及「顯示答案」按鈕即可操作，對帶領者非常友善。  
* **輕量化與易於部署**：整個遊戲僅由一個 index.html 檔案構成，無需安裝任何軟體，可輕鬆部署至免費的 GitHub Pages。

## **目標對象**

* 失智症及認知功能障礙的長者  
* 日照中心、長照據點、社區關懷據點的活動帶領者  
* 希望陪伴家中長輩進行認知活動的家屬及照護者

## 如何使用
您可以透過以下兩種方式來使用這個遊戲：

### 方式一：直接在電腦上開啟 (離線使用)
1. 點擊此儲存庫右上方的綠色按鈕 Code -> Download ZIP 將專案下載到您的電腦。
2. 解壓縮下載的檔案。
3. 直接用網頁瀏覽器（如 Google Chrome、Edge 或 Firefox）打開 index.html 檔案即可開始遊戲。

### 方式二：透過線上網址遊玩 (推薦)
您可以直接點擊下方的連結，在任何有網路的裝置上進行遊戲：

> ➡️ [點此開始遊戲](https://hctsai1006.github.io/taiwan-dementia-quiz-game/)

## **如何客製化題目**

如果您想新增或修改題目，過程非常簡單：

1. 用純文字編輯器（如記事本、VS Code）打開 index.html 檔案。
2. 找到 <script> 區塊中的題目資料陣列 (例如 xuanyu_set1)。
3. 陣列中的每一個 {...} 就是一道題目，您可以直接修改裡面的文字或圖片路徑。
4. 若要新增題目，只需複製其中一個 {...} 物件，貼到陣列的最後，並修改成您要的內容即可。

```
// 範例：一道題目的結構
{   
    topic: "這是廚房用品嗎？",      // 題目的問句  
    item: "鍋子",                  // 物品名稱  
    isCorrect: true,              // 答案是否為「是」 (true 或 false)  
    image: "圖片的網址或相對路徑" // 對應的圖片路徑  
}
```

## 授權許可
本專案採用 MIT License 授權。
