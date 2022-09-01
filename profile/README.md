# 自由鍵盤 - JYKB

自由鍵盤取自日文拼音 **「自(じ)由(ゆう)」** 其中轉換拼音後自(ji)由(yuu) 各取第一個字母為 JY。<br/> 如有其他願望功能，可以透過 [ISSUE](https://github.com/JYKB/JY60/issues) 告知，若您願意也可參加專案進行協同開發 !

## 設計初衷與理念

身為資訊電子相關的從業人員，自幹工具是一個很基本的能力。有鑑於近期發現市售鍵盤已經漸漸不敷使用，因此在好友圈發起「自己的鍵盤自己造」活動，將鍵盤模組化並具有高度的擴充性，讓使用者能夠自定義每一個按鍵，或是讓鍵盤變成心中理想的樣子。

鍵盤為現代資訊人每日比用的工具，可說是比筷子還重要，引用 HHKB 網站中

> アメリカ西部のカウボーイたちは、馬が死ぬと馬はそこに残していくが、どんなに砂漠を歩こうとも、鞍は自分で担いで往く。馬は消耗品であり、鞍は自分の体に馴染んだインタフェースだからだ。いまやパソコンは消耗品であり、キーボードは大切な、生涯使えるインタフェースであることを忘れてはいけない。 [[1]] \--- **東京大学 名誉教授 和田英一**  <BR>
> 中譯為 「美國西部牛仔所騎乘的馬死後會將馬留在原地，但無論他們使用什麼方式穿越沙漠，他們都會隨身攜帶馬鞍。
因為馬是消耗品，馬鞍才是你體內所熟悉的工具。別忘了!在現代電腦是消耗品，鍵盤才是重要的設備，可以用一輩子。」


<!-- 透過 [kailh 熱插拔](https://www.kailhswitch.com/mechanical-keyboard-switches/kailh-pcb-socket.html) 的軸體插座，提供使用這能夠隨心所欲的更換自己想要使用的軸體，開心使用什麼樣的機械軸就使用什麼樣的機械軸。 -->

## 鍵盤配列與定位板
鍵盤的組合由鍵盤定位板 [[2]]

[定位板機構圖輸出](http://builder.swillkb.com/)

1. [Default 60%](http://www.keyboard-layout-editor.com/##@@=~%0A%60&=!%0A1&=%2F@%0A2&=%23%0A3&=$%0A4&=%25%0A5&=%5E%0A6&=%2F&%0A7&=*%0A8&=(%0A9&=)%0A0&=%2F_%0A-&=+%0A%2F=&_w:2%3B&=Backspace%3B&@_w:1.5%3B&=Tab&=Q&=W&=E&=R&=T&=Y&=U&=I&=O&=P&=%7B%0A%5B&=%7D%0A%5D&_w:1.5%3B&=%7C%0A%5C%3B&@_w:1.75%3B&=Caps%20Lock&=A&=S&=D&=F&=G&=H&=J&=K&=L&=%2F:%0A%2F%3B&=%22%0A'&_w:2.25%3B&=Enter%3B&@_w:2.25%3B&=Shift&=Z&=X&=C&=V&=B&=N&=M&=%3C%0A,&=%3E%0A.&=%3F%0A%2F%2F&_w:2.75%3B&=Shift%3B&@_w:1.25%3B&=Ctrl&_w:1.25%3B&=Win&_w:1.25%3B&=Alt&_a:7&w:6.25%3B&=&_a:4&w:1.25%3B&=Alt&_w:1.25%3B&=Win&_w:1.25%3B&=Menu&_w:1.25%3B&=Ctrl) - 標準 60% 鍵盤配列
2. [HHKB](http://www.keyboard-layout-editor.com/##@_backcolor=%23ffffff%3B&@_c=%23a2a8b8&a:7&f:9%3B&=1u&_c=%23cccccc&f:5%3B&=&=&=&=&=&=&=&=&=&=&=&=&=&_f:9%3B&=1u%3B&@_c=%23a2a8b8&w:1.5%3B&=1.5u&_c=%23cccccc&f:5%3B&=&=&=&=&=&=&=&=&=&=&=&=&_c=%23a2a8b8&f:9&w:1.5%3B&=1.5u%3B&@_w:1.75%3B&=1.75u&_c=%23cccccc&f:5%3B&=&=&=&=&=&=&=&=&=&=&=&_c=%23a2a8b8&f:9&w:2.25%3B&=2.25u%3B&@_w:2.25%3B&=2.25u&_c=%23cccccc&f:5%3B&=&=&=&=&=&=&=&=&=&=&_c=%23a2a8b8&f:9&w:1.75%3B&=1.75u&=1u%3B&@_x:1.55%3B&=1u&_w:1.5%3B&=1.5u&_x:-0.04999999999999982&c=%23cccccc&w:6%3B&=6u&_x:0.05000000000000071&c=%23a2a8b8&w:1.5%3B&=1.5u&=1u) - Happy Hacking Keyboard ANSI 鍵盤配列
<!-- 3. [JD40](http://www.keyboard-layout-editor.com/##@@=Esc&=Q&=W&=E&=R&=T&=Y&=U&=I&=O&=P&=Back%3Cbr%3ESpace%3B&@_w:1.25%3B&=Tab&=A&=S&=D&=F&=G&=H&=J&=K&=L&_w:1.75%3B&=Enter%3B&@_w:1.75%3B&=Shift&=Z&=X&=C&=V&=B&=N&=M&=%3C%0A.&_w:1.25%3B&=Shift&=Fn%3B&@_w:1.25%3B&=Hyper&=Super&=Meta&_a:7&w:6.25%3B&=&_a:4&w:1.25%3B&=Meta&_w:1.25%3B&=Super) - 40鍵鍵盤 -->


<!-- 
電路板廠[[3]]
1. 奇立模型 - https://goo.gl/maps/jjevon7UdSWMWghs9
2. 亞勀工藝 - https://goo.gl/maps/9pSytQTwfC3bnu4b7
 -->
 
 


# <font size=5>參考資料</font>

<!-- **REFERENCE** -->
\[1] HHKB 日文官方網站, Available: https://happyhackingkb.com/jp/

\[2]  如何設計一把鍵盤 — 從一張定位板說起, Available: https://www.zfrontier.com/app/flow/2W1m0KppbMR5


<!-- HHKB 日文官方網站 -->
[1]: https://happyhackingkb.com/jp/

<!-- 如何设计一把键盘——从一张定位板说起 -->
[2]: https://www.zfrontier.com/app/flow/2W1m0KppbMR5

<!-- 从入门到开团跑路，深入套件设计及65开团预热 -->
[3]: https://www.zfrontier.com/app/flow/e1rpMAd9Nz75

<!-- PCB 廠商名單 -->
[PCB-Source]: https://hackmd.io/@openlabtaipei/rygQ7dcQBI
