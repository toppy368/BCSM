# Blog-Customized-Syntax-Museum (BCSM)
本專案在是Blog Customized Syntax Museum，簡稱為BCSM，BCSM也是Github上的專案名稱，讓路徑長度簡化一些，這裡將存放 [我的部落格] (http://www.toppy368.tw) 會用到及曾經使用過的語法，同時也會實驗各種可能導入Blog樣板的語法，簡單來說就是**語法倉庫、展示櫃及實驗室 !**  

目前已完成第一階段，設計出一個簡易的網站開發工具，[實驗室] (https://toppy368.github.io/BCSM/Laboratory.html) 及 [沙盒] (https://toppy368.github.io/BCSM/Sandbox.html)，語法會先在這個實驗室實驗  

等第一階段實驗接近完工且成功套用在 [部落格](http://www.toppy368.tw) 上時，會設計別的頁面充當展示櫃，日後可以拿出來用，其他訪客也能瀏覽展示櫃提供的語法，並複製出來給自己的Blog使用  

目前的語法有部分集中在 [這篇文章] (http://www.toppy368.tw/archives/2108) ，但因為不方便維護，所以特別寫了這個專案  

**現況：** 
目前為了導入需要，先成立實驗室、沙盒系統，未來再成立博物館展示櫃頁面及專案首頁目前為了導入需要，先成立實驗室、沙盒系統，未來再成立博物館展示櫃頁面及專案首頁(說明用)。  

##檔案及實際DEMO說明  
**branch:gh-pages tree：**  
https://github.com/toppy368/BCSM/tree/gh-pages

**Demo Hello World：**  
https://toppy368.github.io/BCSM/Laboratory.html  
**注意：**此檔案目前為"未成品"，先做出實驗用的網頁檔，並配合GitHub版本控制紀錄實驗過程的語法及程式碼，上面的原始碼可能會因為新需求而被洗掉(覆蓋)甚至刪除掉，不會永久保存，請注意 !  

**沙盒測試頁面：**  
https://toppy368.github.io/BCSM/Sandbox.html  

**注意：**  
1. 此檔案為"沙盒"也就是**測試頁面**，上面的原始碼可能會因為新需求而被洗掉(覆蓋)甚至刪除掉，不會永久保存，請注意 !   
2. 雖然本檔案的語法可能隨時會被蓋掉，不過採用了GitHub版本控制紀錄檔案變更過程，可透過Commit的機制查詢實驗過程的語法及程式碼  

##此專案的檔案名稱
README.MD：您目前觀看的這份檔案，專案的使用說明文件，說明每個檔案的用途  
Laboratory.html：實驗室，包含了沙盒的使用說明，並以iframe方式包覆者空白的Sandbox.html沙盒網頁  
Sandbox.html：如名稱的意思，本頁面提供了空白的HTML網頁**(不引入外部CSS及Bootstrap效果)**，用來試驗HTML、CSS效果，偶而也會實驗JavaScript語法，上面有Github的連結，可以直接預覽Commit後的實驗語法/程式碼的效果。如果語法/程式碼被覆蓋掉，因為GitHub的版本控制機制，能透過本分支的commits紀錄，瀏覽語法/程式碼的變化。  
LICENSE.txt：本專案以GNUv3方式授權釋出

##關於著作權的授權方式  
這個專案是為了自己的Blog開發方便所製作的專案，因此這個專案從一開始就採用開放原始碼的授權方式，以自由軟體授權方式釋出，你可以自由地複製由本專案所釋出的原始碼，也能透過GitHub的Clone的機制複製出來做實驗(**Laboratory.html 實驗室**及**Sandbox.html沙盒**都需配合GitHub才能記錄你的實驗過程)，唯獨希望大家也能以開源的方式釋出，成果讓其他部落客也能享受得到，也歡迎學術學校教學使用(歡迎推坑意味)  

本專案的版權宣告頁面在每個檔案的最底下(Sandbox.html作為語法測試用途，為了避免誤刪，所以以註解方式將授權內容寫在head內)，採用GNU的 [GPLv3 開源條款](http://www.gnu.org/licenses/gpl.html) 方式釋出，可以在專案資料夾的 LICENSE.txt 查看全文。