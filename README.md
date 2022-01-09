# IOT Final Topic
此為銘傳大學資工四甲陳睿哲同學及林頂曜同學共同撰寫之物聯網技術課程期末專題<br>
<br>
使用方式：<br>
依照 PPT 內圖片接好線路後，分別將 Part A 與 Part B 的程式碼燒入不同的 D1 Mini，並使用個人的無線網路基地台供 Part B 的 D1 Mini 使用，確認兩個 D1 Mini 作用的狀態下，對 Part A 的聲音感測器吹氣使紅外線發射器發射指定的紅外線訊號給 Part B 的 紅外線接收器接收，接收到訊號後會使氣體感測器開啟並做 10 次的 CO2 監測，若 CO2 氣體濃度高於特定值時，會利用 IFTTT 傳送 Line 訊息到私人手機上，並在訊息內警示使用者當前的氣體濃度，再者，若超標次數高於 5 次時會再利用 IFTTT 傳送不同的 Line 訊息到私人手機上，內容則會同時顯示氣體濃度及超標次數供使用者做為參考。
<br>
## Part A <br>
Part A.xml 為 聲控紅外線發射器 的 Flag's Block 程式碼 <br>
<br>
使用元件：<br>
紅外線發射器、D1 Mini、聲音感測器、LED 燈<br>
## Part B <br>
Part B.xml 為 紅外線接收與氣體監控器 的 Flag's Block 程式碼 <br>
<br>
使用元件：<br>
紅外線接收器、D1 Mini、氣體感測器、蜂鳴器、LED 燈 <br>

相關網路工具：<br>
IFTTT、Line
