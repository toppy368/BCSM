# Blog-Customized-Syntax-Museum (BCSM)
本專案在是Blog Customized Syntax Museum，簡稱為BCSM，BCSM也是Github上的專案名稱，讓路徑長度簡化一些，這裡將存放 [我的部落格] (http://www.toppy368.tw) 會用到及曾經使用過的語法，同時也會實驗各種可能導入Blog樣板的語法，簡單來說就是**語法倉庫、展示櫃及實驗室 !**  

##本專案的Branch路徑位置及透過瀏覽器預覽本專案的方法  
**公開展示頁面的 branch:gh-pages tree：**  
https://github.com/toppy368/BCSM/tree/gh-pages
###透過瀏覽器預覽本專案的方法  
**說明：**不好意思，因為本頁面其他功能還在開發中，目前尚未加入導覽欄設計，請大家根據以下的說明，手動變更路徑的方式以檢視其他頁面，等接近完工的第三階段時，會在各功能頁面上方增加導覽欄(Navbar)，謝謝 ! 

本專案的網頁檢視路徑為：  
`https://toppy368.github.io/BCSM/*`  
BCSM為本專案的Repositories資料夾，後面的`*`可用任何檔案代替，你可以接專案清單上的任一檔案  

例如 **當你想檢視實驗室預覽沙盒** 時，你可以使用以下路徑：  
https://toppy368.github.io/BCSM/Laboratory.html  
如果你想**預覽其他頁面**時，你可以上面網址中的`Laboratory.html`改成列表中的其他檔案，例如`Sandbox.html`，不過等到第三階段時，我開始在其他頁面增加導覽欄後，就可以直接用導覽欄點選到其他頁面了  


##本專案的開發進度解說及DEMO  
###開發進度說明
**[已完成] 第一階段：實驗室**  
目前**已完成第一階段**，這是最優先開發的主要功能，為了要測試某些以前用過的語法，但又不想被Blog樣板原有的CSS樣式干擾，所以設計出一個簡易的網站開發工具，[實驗室] (https://toppy368.github.io/BCSM/Laboratory.html) 及 [沙盒] (https://toppy368.github.io/BCSM/Sandbox.html) 頁面，語法會先在這個實驗室實驗，確認在空的HTML網頁可以順利的執行這些語法且沒有相容限制之後，再移植到其他空間並放到第二階段即將動工的展示間相關網頁。  

**[施工中] 第二階段：展示櫃**  
展示間已動工，正在思考雛形並設計架構，本頁面專門擺放實驗過後的語法，包含目前放在Blog的佈景語法還會加入一些新的自訂語法等，某些網站有自訂過的設定語法也會放進來，同時提供複製語法的欄位讓家可以自由運用。     

**[尚未施工] 第三階段：製作首頁並組合各階段內容**  
設計"首頁"及"導覽Bar"，"首頁"會告訴大家專案的用途及每一頁的功能，"導覽Bar"會串聯第一階段及第二階段的每個頁面及章節，同時也會將章節的id訂出來，供導覽頁的標籤使用，第三階段完成後，專案的全部內容就完成了 ! 

**現況：**目前正在施工第二階段  
###第一階段DEMO  
**實驗室 Laboratory.html：**  
https://toppy368.github.io/BCSM/Laboratory.html   

**沙盒 Sandbox.html：**  
https://toppy368.github.io/BCSM/Sandbox.html  

**注意：**  
1. 此檔案為"沙盒"也就是**測試頁面**，上面的原始碼可能會因為新需求而被洗掉(覆蓋)甚至刪除掉，不會永久保存，請注意 !   
2. 雖然本檔案的語法可能隨時會被蓋掉，不過採用了GitHub版本控制紀錄檔案變更過程，可透過Commit的機制查詢實驗過程的語法及程式碼  

###第二階段DEMO  
**導覽列 Navbar_demo.html：**  
https://toppy368.github.io/BCSM/Navbar_demo.html  

##此專案的檔案名稱  
1. README.MD：您目前觀看的這份檔案，專案的使用說明文件，說明每個檔案的用途  
2. Laboratory.html：實驗室，包含了沙盒的使用說明，並以iframe方式包覆者空白的Sandbox.html沙盒網頁  
3. Navbar_demo.html：第二階段的導覽列範例，說明了導覽頁的運作原理，及HTML語法的ID標籤(錨點)的運作原理，此範例可在接下來開發過程及開發結尾製作導覽列時參考用  
4. Sandbox.html：如名稱的意思，本頁面提供了空白的HTML網頁**(不引入外部CSS及Bootstrap效果)**，用來試驗HTML、CSS效果，偶而也會實驗JavaScript語法，上面有Github的連結，可以直接預覽Commit後的實驗語法/程式碼的效果。如果語法/程式碼被覆蓋掉，因為GitHub的版本控制機制，能透過本專案的commits紀錄，瀏覽語法/程式碼的變化。  
5. Showcase.html：展示櫃  
6. index.html：首頁，目前暫不開放（只有Hello World功能）  
7. LICENSE.txt：本專案以GNUv3方式授權釋出  
8. tmp.txt：一個提供暫時儲存程式碼的txt文字檔  

**注意：**本列表顯示是**目前**本專案的檔案，會隨者開發過程而修改，但不會顯示未來即將開發但未出現在本專案GitHub列表上的檔案  

##關於著作權的授權方式  
這個專案是為了自己的Blog開發方便所製作的專案，因此這個專案從一開始就採用開放原始碼的授權方式，以自由軟體授權方式釋出，你可以自由地複製由本專案所釋出的原始碼，也能透過GitHub的Clone的機制複製出來做實驗(**Laboratory.html 實驗室**及**Sandbox.html沙盒**都需配合GitHub才能記錄你的實驗過程)，唯獨希望大家也能以開源的方式釋出，成果讓其他部落客也能享受得到，也歡迎學術上學校教學或研究使用(歡迎推坑)  

本專案的版權宣告頁面在每個檔案的最底下(Sandbox.html作為語法測試用途，為了避免誤刪，所以以註解方式將授權內容寫在head內)，採用GNU的 [GPLv3 開源條款](http://www.gnu.org/licenses/gpl.html) 方式釋出，可以在專案資料夾的 LICENSE.txt 查看全文。