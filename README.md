# suirenHP
<html lang="ja" data-loaded="false" data-scrolled="false" data-spmenu="closed">
<head>

<meta charset="UTF-8">
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!--ここから上はお決まりの定型文です-->


<!--ここからが表現の書式などを決めるcssという部分-->

<style type="text/css">
p {
color: #0000ff;
font-size: 1.5em;
}


.red {color:#ff0000;}
.grey {color:#ffffff; background:#999999;}
.snow {color:#fffafa;}
.yellow {color:#ff0000; background:#ffff00;}
.blue {color:#0000ff;}
.white {color:#ffffff;}
.waku {border:2px dotted #99cc66;
line-height: 200%;
padding: 10px;}


main {
background-color: rgba(255, 255, 255, 0.5);
}

section {
background-color: rgba(0, 225, 0, 0.3);
}


/* 点滅 */
.blinking{
-webkit-animation:blink 1.5s ease-in-out infinite alternate;
-moz-animation:blink 1.5s ease-in-out infinite alternate;
animation:blink 1.5s ease-in-out infinite alternate;
}
@-webkit-keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}
@-moz-keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}
@keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}

#wrap {background:none} /*PC用の背景はオフ*/

/*背景を表示させる部分*/
/*
body::before {
content:"";
display:block;
position:fixed;
top:0;
left:0;
z-index:-1;
width:100%;
height:100vh;
background:url(https://www.usuiren.com/images/top/top1.) center/cover no-repeat;
-webkit-background-size:cover;/*Android4*/
/*}*/


a.p:hover {
position: relative;
text-decoration: none;
}
a.p span {
display: none;
position: relative;
top: -0.5em;
left: 2em;
}
a.p:hover span {
border: none;
display: block;
width: 800px;
}


@media screen and (min-width: 540px),
screen and (orientation: landscape) {
p.note { display: none; }
}


    
.media-container {
  width: 100%;
  max-width: 900px;
  margin: 0 auto;
}

.responsive-media {
  width: 100%;
  display: block;
}

.youtube-wrapper {
  position: relative;
  width: 100%;
  padding-bottom: 56.25%; /* 16:9比率 */
  height: 0;
}

.youtube-wrapper iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: none;
}

#main {
    width: 100%;
    max-width: 100%;
}

.section {
    width: 100%;
}


.schedule-area {
    width: 100%;
}

.schedule-area table {
    width: 100%;
}

table {
  width: 100%;           /* 枠いっぱいに広げる */
  border-collapse: collapse; /* 枠線を重ねてきれいにする */
  table-layout: auto;    /* コンテンツに合わせて幅を調整 */
}

th, td {
  padding: 12px 15px;    /* 上下12px、左右15pxの余白 */
  border: 1px solid #ccc; /* 枠線が見えるようにする */
  text-align: center;      /* 中央揃え */
}

.auto-style1 {
	font-style:normal;
	font-family:"UD デジタル 教科書体 NP-B";
	font-size:28pt;
}
.auto-style2 {
	font-style:normal;
	font-family:"UD デジタル 教科書体 NP-B";
	font-size:14pt;
}
.auto-style3 {
	font-style:normal;
	font-family:"UD デジタル 教科書体 NP-B";
	font-size:12pt;
}
.auto-style4 {
	margin-top: 5px;
	margin-bottom: 5px;
}
.auto-style5 {
	font-style:normal;
	font-family:"UD デジタル 教科書体 NP-B";
	font-size:16pt;
}




#bg-video{
    position:fixed;
    top:0;
    left:0;

    width:100%;
    height:100%;

    object-fit:cover;

    z-index:-2;
}

#overlay{
    position:fixed;
    top:0;
    left:0;

    width:100%;
    height:100%;

    background:rgba(255,255,255,0.5);

    z-index:-1;

    pointer-events:none;
}
    
</style>
<!--
<link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/css/lightbox.css" rel="stylesheet">
-->
</head>

<body>



<video id="bg-video" autoplay muted loop playsinline>
    <source src="https://torokoid.github.io/usurer_temp/background.mp4" type="video/mp4">
</video>

<div id="overlay"></div>

<p class="note">
モバイル端末をお使いの場合は、画面を横向きにすると
背景画像の横方向がご覧頂けます。
</p>


<!--ここ上は、ほぼそのまま使います！-->


<!--QRコードの挿入例-->
<p align="left"> <img src="QR_2026Sep08_.png" alt="アクセス用QRコード" width="100">QR for Access</p><!--
<p align="right"><marquee direction="left" scrollamount="20" width="30%">宇都宮市水泳連盟</marquee></p>
-->

<!--流れ文字の挿入例-->
<!--
<h1><span class="yellow"><marquee behavior="left">!!! GitHubで立ち上げる宇都宮市水泳連盟HPの叩き台です !!!</marquee></span></h1>
-->

<!--ヘッダー-->
<div id="header" class="clearfix">
  <p><img src="https://www.usuiren.com/images/top/top_logo.png" height="70" style="float: left" width="70"></p>
  <h1 class="auto-style1">宇都宮市水泳連盟</h1>
</div>

<!--メインビジュアル-->
<div id="mainVisual">
  <div class="inner">  
  	  <table style="width: 100%">
		  <tr>
			  <td><img src="top1.jpg" class="auto-style4" width="310"></td>
			  <td><img src="top2.jpg" class="auto-style5" width="310"></td>
			  <td><img src="top3.jpg" class="auto-style4" width="310"></td>
		  </tr>
	  </table>  
  	</div>
</div>
<!--メインビジュアル終了-->
<!--コンテンツ-->
<div id="contents" class="clearfix">
  <!--メイン-->
  <div id="main">
    <div class="desc">
      <p class="auto-style">
      <u>このホームページでは、本連盟での活動について情報発信を目的として公開しています。</u>
      </p>
    </div>
 

<br><br>   
    <div class="topics">
      <h2>お知らせ<span>News &amp; Tpoics</span></h2>
      <dl class="auto-style">        
      
		<h2><dt>2026.08.25</dt>
        <dd><a>年間予定表</a>を更新しました。
        <br>
        </dd></h2>
                

 
             
        
      </dl>
    </div>
</div>
    </div>
  <!--メイン終了-->


<br><br>
<!--ビジュアル-->
<div id="ttl_catch">
  <h2 class="auto-style2"><b>活動方針</b></h2>
</div>
<!--ビジュアル終了-->
  <!--メイン-->
  <div>
    <div class="section">
      <p class="auto-style"><br>
      本連盟は、宇都宮市内の水泳及び水泳競技の健全な普及発展とよき水泳指導者の育成につとめ、<br>
      水泳を通じて市民の体力向上と純粋なるスポーツ精神の涵養を図ることを目的として、活動しています。</p>
    </div>
  </div>
  <!--メイン終了-->

<br><br>
<!--ビジュアル-->
<div id="ttl_catch">
  <h2 class="auto-style"><b>年間予定</b></h2>
</div>
<!--ビジュアル終了-->
<!--メイン-->
  <div id="main">
    <div class="section">
      <p class="auto-style5">■令和8年度　年間予定表■<br></p>
      <br>
		<div class="media-container">
        <table>
			<tr style="text-align:center">
				<td class="auto-style2"><b>事業名</b></td><td class="auto-style2"><b>期日</b></td><td class="auto-style2"><b>場所</b></td>
			</tr>
			<tr>
				<td>役員会</td><td>4月18日（土）</td><td>中央生涯学習センター</td>
			</tr>
			<tr>
				<td>定期総会</td>	<td>4月18日（土）</td><td>中央生涯学習センター</td>
			</tr>
			
			<tr>
				<td>市民大会前レッスン会</td><td>6月20日（土）<br><a href="市民大会事前レッスン会要項.pdf">市民大会事前レッスン会要項(pdf)</a><br><a href="https://docs.google.com/forms/d/e/1FAIpQLSctMDSxYsLVicJC8jNxzTMdv6sZ_xg6HAlj-Y4fVRnAz0gwOA/viewform">上記資料のQRコードリンク先申し込みフォーム</a></td><td>日環アリーナ栃木</td>
			</tr>
			
			<tr>
				<td>市民水泳大会</td><td>6月28日（日）<br><a href="2026市民大会要項.pdf">大会要項(pdf)</a><br><a href="2026年市民大会申込書.xlsx">申込用紙(Excel)</a><br><a href="https://www.usuiren.com/event/2026市民大会2次要項.pdf">2026市民大会2次要項(pdf)</a><br><a href="https://www.usuiren.com/event/2026市民大会リレーオーダー用紙.pdf">2026市民大会リレーオーダー用紙(pdf)</a><br><a href="https://www.usuiren.com/event/2026大会広告案内.xls">大会広告案内(Excel)</a></td><td>ドリームプールかわち</td>
			</tr>
			<tr>
				<td>ジュニア水泳教室</td><td>今年度は駅東公園プールが<br>使用出来ないため中止となります</td><td>駅東公園プール</td>
			</tr>
			
			<tr>
				<td>小学生大会前レッスン会</td><td>8月29日（土）</td><td>日環アリーナ栃木</td>
			</tr>
			
			<tr>
				<td>市小学生水泳大会</td><td>9月6日（日）<br><a href="2026小学生大会要項.pdf">大会要項(pdf)</a><br><a href="2026年小学生大会申込書.xlsx">申込用紙(Excel)</a><br><a href="https://www.usuiren.com/event/2026小学生大会2次要項.pdf">2026小学生大会2次要項</a><br><a href="https://www.usuiren.com/event/2026小学生大会リレーオーダー用紙.pdf">2026小学生大会リレーオーダー用紙</a><br><a href="2026大会広告案内.xls">大会広告案内(Excel)</a></td><td>ドリームプールかわち</td>
			</tr>

		</table>
		</div>
    </div>
    </div>

　<div class="section">
  <p><span class="yellow">記入した申し込み用紙は下記「メール送信」をクリックして開くメールにて受け付けます</span></p>
  
     <p><a href="mailto:usuiren7777@gmail.com">メール送信 ← クリック</a></p>

</div>

    <div class="section">
      <div class="section">
      <h6><p class="auto-style">
      大会要綱及び申込み用紙をダウンロードしてご利用下さい。<br>
      ご利用中のパソコンのセキュリティーよりダウンロードが出来ない場合があります。<br>
      セキュリティー設定の変更後、再度お試し下さい。</p>
      <p class="auto-style">
      <br>
      コンテンツ内にはPDF形式で掲載しているものがあります。<br>
      表示・印刷にはAdobe Acrobat Readerが必要です。<br>
      （無償配布されています。下のロゴをクリックして下さい。）<br>
      <a href="https://get.adobe.com/jp/reader/"><img src="Acrobat_Reader_web_button.png"></a>
      </p></h6>
      </div>
    </div>

  <!--メイン終了-->

<br><br><br><br>
<!--ビジュアル-->
<div id="ttl_catch">
  <h2 class="auto-style2"><b>お問い合わせ</b></h2>
</div>
<!--ビジュアル終了-->
<!--メイン-->
  <div id="main">
    <div class="section">
      <br>
      <p class="auto-style"><u>水泳連盟の活動に関するお問い合わせ、及び各種、水泳大会申込み及びお問い合わせを承っております。</u></p>
      <br>
      <p class="auto-style">宇都宮市水泳連盟事務局<br>〒320-0043<br>宇都宮市桜5-2-5　（ビッグツリースポーツクラブ内）</p>
      <p class="auto-style">
	  <img src="icon_tel.gif" class="auto-style5">&emsp;TEL:028-639-7777<br>
	  <a href="mailto:usuiren7777@gmail.com">お問い合わせメール作成は ← ここをクリック</a>

  <!--メイン終了-->

<br><br>
<!--ビジュアル-->
<div id="ttl_catch">
  <h2 class="auto-style">リンク</h2>
</div>
<!--ビジュアル終了-->
<!--メイン-->
  <div id="main">
    <div class="section">
      <p class="auto-style">&emsp;<u>■県庁・市役所関連■</u><br></p>
      <p class="auto-style">
      &emsp;&emsp;<a href="http://www.pref.tochigi.lg.jp/"><img src="link_bnr2.png"></a><br>
      &emsp;&emsp;<a href="http://www.pref.tochigi.lg.jp/">栃木県</a><br>
      &emsp;&emsp;<a href="https://www.city.utsunomiya.tochigi.jp/"><img src="link_bnr3.png"></a><br>
      &emsp;&emsp;<a href="https://www.city.utsunomiya.tochigi.jp/">宇都宮市</a><br></p>
      <br>
      <p class="auto-style">&emsp;<u>■水泳関連■</u><br></p>
      <p class="auto-style">
      &emsp;&emsp;<a href="http://www.swim.or.jp/"><img src="link_bnr1.gif"></a><br>
      &emsp;&emsp;<a href="http://www.swim.or.jp/">日本水泳連盟</a><br>
      &emsp;&emsp;<a href="http://www.tochigi-swim.com/">栃木県水泳連盟</a><br></p>
    </div>
  </div>
  <!--メイン終了-->
















<!--
<br><br><br>
<h2><span class="yellow">GitHubで立ち上げる宇都宮市水泳連盟HPの叩き台でした<br>Thank you for reading this far.</span></h2>

<br><br><br><br><br>
<h2><span class="yellow">
<a href="https://torokoid.github.io/Mashiko_himawari_3/" target="_blank">クリックでメニューページに戻ります</a>
</span></h2>
-->

<br><br><br>








<br><br><br><br><br><br><br><br><br>





<br><br>

<br><br><br><br><br><br>

<!--本体はここまで-->


<!--画面に空白地帯を作って、背景が見えるようにしています-->
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>



<!-- フッタ -->
<footer>
<p>Copyright 2026/09/08 宇都宮市水泳連盟</p>
</footer>

<!--HPにさまざまなJavaScriptを呼び込むための書式--><!--
<script src="https://code.jquery.com/jquery-1.12.4.min.js" type="text/javascript"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/js/lightbox.min.js" type="text/javascript"></script>

<script type='text/javascript' src='https://torokoid.github.io/shiba/jquery.js?ver=1.12.4'></script>
<script src="https://torokoid.github.io/shiba/jquery.goup.min.js"></script>
<script src="https://torokoid.github.io/shiba/my.js"></script>
-->
