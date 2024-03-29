Project1: 比價網
初步: 特定商品的比較各個通路的價格、單位價格
例如: 顯示衛生棉每片多少錢、化妝品每g多少錢、衛生紙每抽多少錢

目前商品：
1. 蘇菲原生棉29cm（爬蟲成功：momo、屈臣氏官網、yahoo購物中心、家樂福線上購物）

欲比價通路的目錄：
1. Momo（bs只能爬蟲手機版，電腦版反爬蟲）
2. Pchome（反爬蟲）
3. yahoo購物中心
4. 屈臣氏官網
5. 寶雅官網
6. 康是美官網、蝦皮（反爬蟲）
7. 博客來（反爬蟲）
8. 實體店面（屈臣氏、康是美、寶雅）
9. 待定：全聯官網店面、家樂福官網店面

預計功能:
谷歌登入，可回報實體店面價格、回報錯誤。
（待設定：多少人回報價格後顯示在網站上，多少人回報錯誤後網站價格下架）
（實體價格以多久為單位顯示） 

期望進階功能:
1. 連結其他網站，谷歌地圖搜尋實體店面
2. 回傳兩年內價格


---
## Python project management

在這個專案中我們同時學習python的專案與套件管理
通常在開發python程式的過程中，我們會安裝許多套件，
但User或共同開發人員並不一定有安裝這些套件，
可能會導致程式無法執行，因此我們使用PIP＋虛擬環境去進行套件與專案管理
操作順序如下：
1. 開啟Terminal並進到專案的資料夾下, ```cd project1```
2. 建立一個新的虛擬環境，在terminal輸入 ```python3 -m venv venv```
3. 這個時候Python會在這個專案資料夾裡面建立一個新的編譯環境（會有一個新的資料夾venv出現)
4. 每次開發時，都需要先激活 venv 虛擬環境，在terminal輸入 ```source venv/bin/activate```
5. 安裝需要的套件，像是 ```pip install requests```
6. 進行開發
7. 結束開發並離開虛擬環境，在terminal輸入 ```deactivate```
   
如何讓其他開發人員知道我們使用的套件：
1. 進入虛擬環境
2. 在 terminal 輸入， ```pip freeze > requirements.txt```
3. 此時，pip會在資料夾內產生一個requirements.txt的檔案，裡面會列舉你安裝的套件
4. 上傳這個這個檔案到github或是其他repository management tools

---
## about project
<img width="1440" alt="截圖 2022-12-02 下午11 27 21" src="https://user-images.githubusercontent.com/104444259/205329879-a0da2a56-f1e4-4fdd-9f4b-ee1da95b0f6c.png">
<img width="1440" alt="截圖 2022-12-02 下午11 27 28" src="https://user-images.githubusercontent.com/104444259/205329903-432041b6-694f-4247-b323-b486d4e09571.png">
<img width="1440" alt="截圖 2022-12-02 下午11 27 34" src="https://user-images.githubusercontent.com/104444259/205329915-22296b79-250c-45b8-82ce-df846658c92c.png">
<img width="1440" alt="截圖 2022-12-02 下午11 27 41" src="https://user-images.githubusercontent.com/104444259/205329922-94455d20-8a8c-46c6-a9eb-64d1ba1c0f08.png">
<img width="1440" alt="截圖 2022-12-02 下午11 27 47" src="https://user-images.githubusercontent.com/104444259/205329930-f605aef7-20d5-4b61-a298-3b87dfe92ef4.png">
<img width="1440" alt="截圖 2022-12-02 下午11 27 54" src="https://user-images.githubusercontent.com/104444259/205329932-99a74ed3-4fa8-4fa0-8045-058ec252002e.png">
<img width="1440" alt="截圖 2022-12-02 下午11 28 01" src="https://user-images.githubusercontent.com/104444259/205329938-760bdd42-0c2e-499e-86bd-6a3c09385787.png">
<img width="1440" alt="截圖 2022-12-02 下午11 28 08" src="https://user-images.githubusercontent.com/104444259/205329951-07ba4772-9927-4d8c-851e-41d732e8253e.png">
<img width="1440" alt="截圖 2022-12-02 下午11 28 15" src="https://user-images.githubusercontent.com/104444259/205329954-fd0bee93-d0d7-4651-a04a-9a2f474a7020.png">
<img width="1440" alt="截圖 2022-12-02 下午11 28 21" src="https://user-images.githubusercontent.com/104444259/205329961-49b92a8d-e824-478e-bd0f-16a285d2bac3.png">
<img width="1440" alt="截圖 2022-12-02 下午11 28 28" src="https://user-images.githubusercontent.com/104444259/205329968-539fc825-4cad-44f3-9d4f-8490c3f59933.png">
<img width="1440" alt="截圖 2022-12-02 下午11 28 35" src="https://user-images.githubusercontent.com/104444259/205329975-59f47492-c5e8-4ec4-a948-60ff028c0e81.png">
<img width="1440" alt="截圖 2022-12-02 下午11 28 41" src="https://user-images.githubusercontent.com/104444259/205329983-f67abfb6-3ac2-41b2-bc38-f2162e04fd17.png">
<img width="1440" alt="截圖 2022-12-02 下午11 28 48" src="https://user-images.githubusercontent.com/104444259/205329985-ecfdb28b-4e2b-4b62-8b2f-f6d3b370b574.png">

