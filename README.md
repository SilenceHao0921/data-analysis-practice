# data-analysis-practice
Jupyter notebooks for learning pandas, matplotlib, and data science basics.
📘 Data Analysis & Python Practice

這個專案紀錄了我在 Python / Pandas / NumPy / Matplotlib 學習過程中的練習 Notebook，內容包含文字資料處理、影像矩陣處理、股市資料分析與資料視覺化。

## 📘 Notebook List

1. [01 字串解析並存入-字典和串列-結構](#01-字串解析並存入-字典和串列-結構)  
2. [02-1 灰階圖片展現](#02-1-灰階圖片展現)  
3. [02-2 照片範例](#02-2-照片範例)  
4. [03 影像處理-文字資料處理](#03-影像處理-文字資料處理)  
5. [04-1 計算平均與年齡-用numpy篩出100分](#04-1-計算平均與年齡-用numpy篩出100分)  
6. [04-2 影像矩陣轉換練習](#04-2-影像矩陣轉換練習)  
7. [05 從文字檔到-dataframe-成績統計與年齡計算](#05-從文字檔到-dataframe---成績統計與年齡計算)  
8. [06 pandas練習-股價資料清理與學生年齡計算](#06-pandas練習-股價資料清理與學生年齡計算)  
9. [07-1 pandas-模組合併股票-csv-檔為範例](#07-1-pandas-模組合併股票-csv-檔為範例)  
10. [07-2 xlsx-資料排版練習](#07-2-xlsx-資料排版練習)  
11. [08 遊客資料分析](#08-遊客資料分析)


# 01 ~ 03. 字串與影像處理

## 01-字串解析並存入-字典和串列-結構
→ 文字檔解析，轉換為串列 / 字典結構。

[01 字串解析並存入 (字典和串列) 結構](01字串解析並存入(字典和串列)結構.ipynb) 


## 02-1 灰階圖片展現
→ 使用 NumPy 建立矩陣並顯示灰階圖像。

[02-1 灰階圖片展現](02-1灰階圖片展現.ipynb) 

<img width="395" height="428" alt="image" src="https://github.com/user-attachments/assets/2f053234-e5ca-4451-a7c8-8c23b88d7eef" />
<img width="662" height="763" alt="image" src="https://github.com/user-attachments/assets/4006470b-f816-4849-a40b-09fa11cc3165" />


## 02-2 照片範例
→ 讀取 JPG 圖片並進行矩陣處理。

[02-2 照片範例](02-2照片範例.ipynb)

<img width="544" height="320" alt="image" src="https://github.com/user-attachments/assets/0ca63018-84f1-49c6-9e15-4ae1c12d8eb0" />
<img width="722" height="195" alt="image" src="https://github.com/user-attachments/assets/f8313ce4-6be9-4945-8bc4-918c5c62b4fd" />


## 03-影像處理-文字資料處理
→ 綜合練習：影像矩陣操作 + 學生資料解析。

[03 影像處理-文字資料處理](03影像處理-文字資料處理.ipynb)

<img width="568" height="299" alt="image" src="https://github.com/user-attachments/assets/facf8dbf-c361-4e6e-92a1-0774ae08cbed" />


# 04 ~ 05. 學生資料處理

## 04-1 讀取文字學生成績-用NumPy篩出100分學生

[04-1 計算平均與年齡-用NumPy篩出100分](04-1計算平均與年齡-用NumPy篩出100分.ipynb)


## 04-2 影像矩陣轉換練習

[04-2 影像矩陣轉換練習](04-2影像矩陣轉換練習.ipynb)


## 05-從文字檔到 DataFrame：成績統計與年齡計算

[05 從文字檔到 DataFrame - 成績統計與年齡計算](05從文字檔到DataFrame-成績統計與年齡計算.ipynb)

### 整潔資料(Tidy Data)
**是一種數據組織的標準，強調資料表的每一列、每一行、每一個儲存格都有特定的意義**
。 具體來說，整潔資料需要符合以下三個條件：每個變數是一個欄(column)，每個觀察值是一個列(row)，每個值是一個單一的儲存格。

**以下是整潔資料的詳細解釋：**

- **每個變數是一個欄(column):**
    也就是說，資料表中的每一欄都代表一個單獨的變數，例如：年齡、性別、身高等等。 這樣可以確保每個變數都有明確的定義，並且方便後續的分析和操作。
    
- **每個觀察值是一個列(row):**
    每一列代表一個單獨的觀察值或個案，例如：一個人的資料、一筆交易記錄等等。 這樣可以確保同一個觀察值的相關資料都被放在同一列，方便分析和比較。
    
- **每個值是一個儲存格(cell):**
    每個儲存格只包含一個數值，不能包含多個數值或文字。 這樣可以避免混淆和錯誤。


# 06 ~ 08. 股價與資料分析

## 06-Pandas 資料處理：股價 CSV 清理與 K 線圖繪製

[06 Pandas練習-股價資料清理與學生年齡計算](06Pandas練習-股價資料清理與學生年齡計算.ipynb)

<img width="653" height="465" alt="image" src="https://github.com/user-attachments/assets/6db6a1b0-571c-4209-b2af-ddb8968aac52" />
<img width="653" height="463" alt="image" src="https://github.com/user-attachments/assets/cdc528db-7d42-4d97-bd66-9d4f072cfb75" />


## 07-1 pandas 模組合併股票 CSV 檔為範例

[07-1 Pandas 模組合併股票 CSV 檔為範例](07-1pandas模組合併股票CSV檔為範例.ipynb)

<img width="721" height="347" alt="image" src="https://github.com/user-attachments/assets/443e3e51-3178-40cf-befd-2ec2a0fff921" />
<img width="754" height="366" alt="image" src="https://github.com/user-attachments/assets/1a00b840-8caa-4ef5-ac4d-f58cee121dcf" />


## 07-2 XLSX 資料排版練習

[07-2 XLSX 資料排版練習](07-2XLSX資料排版練習.ipynb)


## 08-遊客資料分析 → Excel 資料清理、樞紐化、折線圖與圓餅圖展示

[08 遊客資料分析](08遊客資料分析.ipynb)

<img width="749" height="425" alt="image" src="https://github.com/user-attachments/assets/deafc09b-1c7f-4cec-be61-216e29b66baf" />
<img width="735" height="604" alt="image" src="https://github.com/user-attachments/assets/1c3f0357-6e66-4a80-acca-f34aa9f39fe6" />
<img width="615" height="592" alt="image" src="https://github.com/user-attachments/assets/25ce7675-80a1-4110-893a-719781cc6ad4" />


## 技術重點

Pandas：資料清理、型別轉換、DataFrame 操作
NumPy：矩陣運算、影像處理
Matplotlib / mplfinance：資料視覺化、股價 K 線圖
Excel / CSV / TXT：不同來源資料的讀取與轉換

## 專案目標

本專案的目的是透過實作Notebook，練習Python的資料處理與視覺化技巧，包含：
- 文字解析 (String Parsing)
- 影像矩陣處理 (Image Processing)
- 股價數據分析 (Stock Data Analysis)
- Excel / CSV / TXT 檔案讀取與轉換

- ## 📝 心得

透過這些練習，除了Pandas、NumPy 和 Matplotlib 的基本操作，也學到:

資料處理比想像中複雜不同來源（TXT、CSV、Excel、影像）需要不同方法清理與轉換。
同一組資料，透過折線圖、圓餅圖或 K 線圖，能帶來完全不同的洞察。
很多問題解決後，都變成了寶貴的學習記錄。
每次練習的目標都是把資料轉換成資訊，再進一步成為知識。  
這些經驗讓我對「資料分析流程」有更完整的認識，也更有信心挑戰未來更進階的專案。

