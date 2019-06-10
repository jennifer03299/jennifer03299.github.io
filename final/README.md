# Final Project - My TO-DO List
## 國企三 鄭婷心 B05704017

* 期末專題主題簡介:
一個簡單的todo-list，可以將to do項目加入、勾選已完成的項目及刪除不需要的項目，也可以選擇要記錄下每個項目的due date。Todo list下面有一個簡單的時間顯示器，讓使用者可以確認現在當下的時間。

* 怎麼使用這個網站:
在寫下todo-list之後跟due date之後按下加號就可以加入新的todo item，也可以選擇只寫下todo item但不寫due date

* 使用的技術
	1. javascript: 做出可以加入、刪除及打勾(完成或未完成)task的To-do list，利用getDate在下面顯示當前的時間
	2. jquery: 呼叫datepicker的jquery來讓due date的欄位可以讓日期直接從月曆中選取

* 網站的特色及亮點
	1. 只有在to-do的輸入欄內有東西時才有辦法將新的task加入到list中，如果只有to-do卻沒有日期時就不會出現"due at“的字樣
	2. 在沒有已完成的task時會顯示"Stop being lazy!"的字樣，而在沒有未完成的task時會顯示"I have nothing to do, hooray!"的字樣