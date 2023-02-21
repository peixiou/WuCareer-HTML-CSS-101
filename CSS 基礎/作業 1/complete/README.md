# CSS 基礎作業 1 - CSS 選擇器綜合練習

###### 作業層級

HTML/CSS 基礎 **/** CSS 基礎 **/** 作業 1

## 作業說明及相關資源

在這份作業中，你需要應用上一堂課所學到的知識，來選擇正確的答案

1. 請看下面的 html 以及 css 結構，哪些選項可以選取 class 名稱為 warning 的元素？

   **html 及 css 結構**

   ```html
   <p class="warning">Don't do it.</p>
   <p>Do it.</p>
   <p class="warning">Nooo, don't do it.</p>
   ```

   **選項**
   a. `.warning {}`
   b. `#warning {}`
   c. `warning {}`
   <br>

2. 請看下面的 html 以及 css 結構，哪些選項可以選取程式碼中的元素？

   **html 及 css 結構**

   ```html
   <img id="mainpic" src="cat.png" />
   ```

   **選項**
   a. `img {}`
   b. `#mainpic {}`
   c. `.mainpic {}`
   d. `[src] {}`
   e. `mainpic {}`
   <br>

3. 請看下面的 html 以及 css 結構，請問 h1 的元素最後會變成什麼顏色？

   **html 及 css 結構**

   ```html
   <div class="container">
     <div class="blog-container">
       <h1 class="title">This is the title of blog post</h1>
       <p>
         Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sapiente,
         illo.
       </p>
     </div>
   </div>
   ```

   ```css
   .container .blog-container h1 {
     color: green;
   }

   h1 {
     color: yellow;
   }

   .title {
     color: red;
   }

   [class] {
     color: black;
   }

   .blog-container [class] {
     color: blue;
   }
   ```

   **選項**
   a. 紅色 (red)
   b. 黃色 (yellow)
   c. 綠色 (green)
   d. 黑色 (black)
   e. 藍色 (blue)
   <br>

4. 承第 3 題 html 的結構，計算以下每個 css 的權重

   ```css
   /* 第 1 個要計算 css 選擇器的權重 */
   .container .blog-container h1 {
     color: green;
   }

   /* 第 2 個要計算 css 選擇器的權重 */
   h1 {
     color: yellow;
   }

   /* 第 3 個要計算 css 選擇器的權重 */
   .title {
     color: red;
   }

   /* 第 4 個要計算 css 選擇器的權重 */
   [class] {
     color: black;
   }

   /* 第 5 個要計算 css 選擇器的權重 */
   .blog-container [class] {
     color: blue;
   }
   ```

   <br>

5. 承第 3 題 html 的結構並觀察下面的 css 結構，請問 h1 的顏色為和？
   **html 及 css 結構**

   ```css
   .title {
     color: red;
   }

   [class] {
     color: black;
   }
   ```

   **選項**
   a. 紅色 (red)
   b. 黑色 (black)
   c. 不知道

## 作業驗收及提交

### 作業驗收標準

| 挑戰等級 | 驗收標準             | 敘述                                        |
| -------- | -------------------- | ------------------------------------------- |
| 銅牌     | 正確答對所有題目     | 能熟練掌握所有 css 選擇器知識並答對所有題目 |
| 銀牌     | 該作業無銀牌挑戰項目 | N/A                                         |
| 金牌     | 該作業無金牌挑戰項目 | N/A                                         |

### 作業提交

完成作業後休息一下，接著看詳解，了解一下自己的答案是不是跟自己寫的相同，如果有問題不要忘記要問像助教提問呦

#### 作業提交範本

- 第 1 題答案：a
- 第 2 題答案：a,b,d
- 第 3 題答案：c
- 第 4 題答案
  - 第 4-1 題權重：021
  - 第 4-2 題權重：001
  - 第 4-3 題權重：010
  - 第 4-4 題權重：010
  - 第 4-5 題權重：020
- 第 5 題答案：b
