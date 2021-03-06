# Week_5
<h3>要求三-基本SQL指令</h3>

<h4>Q1.使用 INSERT 指令新增一筆資料到 user 資料表中，這筆資料的 username 和password 欄位必須是 ply。接著繼續新增至少 4 筆隨意的資料。</h4>

<p>新增第一筆資料</p>
<img width="572" alt="3-1" src="https://user-images.githubusercontent.com/77678349/112742666-fdd5b280-8fc2-11eb-866f-996e493d04f7.png">

<p>發現第一筆資料寫錯，修改第一筆資料</p>
<img width="571" alt="3-1修改資料" src="https://user-images.githubusercontent.com/77678349/112742729-c0bdf000-8fc3-11eb-920c-8bf219ae308a.png">

<p>新增其他三筆資料</p>
<img width="570" alt="3-1鍵入其它三筆資料" src="https://user-images.githubusercontent.com/77678349/112742740-ce737580-8fc3-11eb-906c-ccfdd8435a0e.png">

<h4>Q2.使用 SELECT 指令取得所有在 user 資料表中的使用者資料。</h4>

<p>發現少新增一筆資料，再新增，並且取得所有資料</p>
<img width="567" alt="3-2" src="https://user-images.githubusercontent.com/77678349/112742743-d3382980-8fc3-11eb-9782-5b0145fc09f7.png">

<h4>Q3.使用 SELECT 指令取得 user 資料表中總共有幾筆資料。</h4>
<img width="569" alt="3-3" src="https://user-images.githubusercontent.com/77678349/112743144-57d87700-8fc7-11eb-99ca-c11d061f9820.png">

<h4>Q4.使用 SELECT 指令取得所有在 user 資料表中的使用者資料，並按照 time 欄位，由近到遠排序。</h4>
<img width="569" alt="3-4" src="https://user-images.githubusercontent.com/77678349/112743217-f533ab00-8fc7-11eb-8c7e-44d66b5e6996.png">

<h4>Q5.使用 SELECT 指令取得 user 資料表中第 2 ~ 4 共三筆資料，並按照 time 欄位，由近到遠排序。</h4>
<img width="570" alt="截圖 2021-03-29 上午12 10 45" src="https://user-images.githubusercontent.com/77678349/112758920-43c26300-9023-11eb-90b2-85a7070b136a.png">

<h4>Q6.使用 SELECT 指令取得欄位 username 是 ply 的使用者資料。</h4>
<img width="572" alt="3-6" src="https://user-images.githubusercontent.com/77678349/112743529-b3583400-8fca-11eb-87fb-6923bc5c45d2.png">

<h4>Q7.使用 SELECT 指令取得欄位 username 是 ply、且欄位 password 也是 ply 的資料。</h4>
<img width="570" alt="3-7" src="https://user-images.githubusercontent.com/77678349/112743539-c3701380-8fca-11eb-9194-4cb0af6e48cb.png">

<h4>Q8.使用 UPDATE 指令更新欄位 username 是 ply 的使用者資料，將資料中的 name 欄位改成【丁滿】。</h4>
<p>更改後，再使用SELECT檢查結果</p>
<img width="570" alt="3-8" src="https://user-images.githubusercontent.com/77678349/112743649-b273d200-8fcb-11eb-80f5-87079c509a38.png">

<h4>Q9.使用 DELETE 指令刪除所有在 user 資料表中的資料。</h4>
<p>刪除後，再使用SELECT檢查結果</p>
<img width="572" alt="3-9" src="https://user-images.githubusercontent.com/77678349/112743736-75f4a600-8fcc-11eb-90a5-be15527a0a8e.png">
<hr/>


<h3>要求四-結合資料表 SQL JOIN 的操作</h3>
<h4>Q1.在資料庫中，建立新資料表，取名字為message。資料表中必須包含以下欄位設定</h4>
<img width="571" alt="4-1" src="https://user-images.githubusercontent.com/77678349/112746040-1227a880-8fdf-11eb-8efb-05a53f05f8e4.png">

<h4>Q2.使用 SELECT 搭配 JOIN 的語法，取得所有留言，資料中須包含留言會員的姓名。</h4>
<p>先在user資料表重新放入資料(因為在要求三最後刪掉了)</p>
<img width="569" alt="4-2-1" src="https://user-images.githubusercontent.com/77678349/112748028-c29ba980-8feb-11eb-9d98-c8c53cb0ffd2.png">
<p>在message資料表試著先加入第一筆資料</p>
<img width="571" alt="4-2-2" src="https://user-images.githubusercontent.com/77678349/112748046-d8a96a00-8feb-11eb-89c6-ac6b6987b24a.png">
<p>接著在message資料表加入其他筆資料</p>
<img width="566" alt="4-2-3" src="https://user-images.githubusercontent.com/77678349/112748056-e2cb6880-8feb-11eb-8a0e-3c2a055be5f3.png">
<p>以SELECT搭配JOIN語法取得會員姓名和留言</p>
<img width="568" alt="4-2-4" src="https://user-images.githubusercontent.com/77678349/112748071-ff67a080-8feb-11eb-81de-c2890261db17.png">

<h4>Q3.使用 SELECT 搭配 JOIN 的語法，取得 user 資料表中欄位 username 是 ply 的所有留言，資料中須包含留言會員的姓名。</h4>
<img width="570" alt="4-3" src="https://user-images.githubusercontent.com/77678349/112748577-22478400-8fef-11eb-9168-9e77f4961a18.png">

