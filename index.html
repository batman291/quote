<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html>
<head>
<meta content='width=device-width, initial-scale=1' name='viewport'/>
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" />
<title>
Random Quote Generator | Sata
</title>
<!-- Bắt đầu viết Css cho web -->
<b:skin>
<![CDATA[
 /* Chèn CSS vào đây */
@import 'https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap';*{margin:0;padding:0;box-sizing:border-box;font-family:poppins,sans-serif}body{display:flex;align-items:center;justify-content:center;min-height:100vh;padding:0 10px;background:#5372f0}::selection{color:#fff;background:#5372f0}.wrapper{width:605px;background:#fff;border-radius:15px;padding:30px 30px 25px;box-shadow:0 12px 35px rgba(0,0,0,.1)}header,.content :where(i,p,span){color:#202842}.wrapper header{font-size:35px;font-weight:600;text-align:center}.wrapper .content{margin:35px 0}.content .quote-area{display:flex;justify-content:center}.quote-area i{font-size:15px}.quote-area i:first-child{margin:3px 10px 0 0}.quote-area i:last-child{display:flex;margin:0 0 3px 10px;align-items:flex-end}.quote-area .quote{font-size:22px;word-break:break-all;text-align:center}.content .author{display:flex;font-size:18px;margin-top:20px;font-style:italic;justify-content:flex-end}.author span:first-child{margin:-6px 5px 0 0;font-family:monospace}.wrapper .buttons{border-top:1px solid #ccc}.buttons .features{display:flex;margin-top:20px;align-items:center;justify-content:space-between}.features ul{display:flex}.features ul li{margin:0 5px;height:47px;width:47px;display:flex;cursor:pointer;color:#5372f0;list-style:none;border-radius:50%;align-items:center;justify-content:center;border:2px solid #5372f0;transition:all .3s ease}.features ul li:first-child{margin-left:0}ul li:is(:hover,.active){color:#fff;background:#5372f0}ul .speech.active{pointer-events:none}.buttons button{border:none;color:#fff;outline:none;font-size:16px;cursor:pointer;padding:13px 22px;border-radius:30px;background:#5372f0}.buttons button.loading{opacity:.7;pointer-events:none}@media(max-width:450px){.wrapper{padding:25px 25px 20px}.wrapper header{font-size:29px}.quote-area .quote{font-size:20px;word-break:keep-all}.content .author{font-size:16px}.quote-area i{font-size:12px}.features ul li{margin:0 3px;height:45px;width:45px}.buttons button{font-size:15px;padding:12px 20px}}
]]></b:skin>
</head>
<!-- Bắt đầu phần hiển thị trên web -->
<body>
<div class="wrapper">
<header>Quote of the Day</header>
<div class="content">
<div class="quote-area">
<i class="fas fa-quote-left"></i>
<p class="quote">Please click the "New Quote" button to get a new Quote !</p>
<i class="fas fa-quote-right"></i>
</div>
<div class="author">
<span>__</span>
<span class="name">NgHoàng</span>
</div>
</div>
<div class="buttons">
<div class="features">
<ul>
<li class="speech"><i class="fas fa-volume-up"></i></li>
<li class="copy"><i class="fas fa-copy"></i></li>
<li class="twitter"><i class="fab fa-twitter"></i></li>
</ul>
<button>New Quote</button>
</div>
</div>
</div>
<b:section class='navbar' id='navbar' maxwidgets='1' showaddelement='yes'>
</b:section>
</body>
<script>
const quoteText=document.querySelector(".quote"),quoteBtn=document.querySelector("button"),authorName=document.querySelector(".name"),speechBtn=document.querySelector(".speech"),copyBtn=document.querySelector(".copy"),twitterBtn=document.querySelector(".twitter"),synth=speechSynthesis;function randomQuote(){quoteBtn.classList.add("loading");quoteBtn.innerText="Loading...";fetch("https://free-quotes-api.herokuapp.com/").then(response=>response.json()).then(result=>{quoteText.innerText=result.quote;authorName.innerText=result.author||"No Author";quoteBtn.classList.remove("loading");quoteBtn.innerText="New Quote";});}
speechBtn.addEventListener("click",()=>{if(!quoteBtn.classList.contains("loading")){let utterance=new SpeechSynthesisUtterance(`${quoteText.innerText} by ${authorName.innerText}`);synth.speak(utterance);setInterval(()=>{!synth.speaking?speechBtn.classList.remove("active"):speechBtn.classList.add("active");},10);}});copyBtn.addEventListener("click",()=>{navigator.clipboard.writeText(quoteText.innerText);});twitterBtn.addEventListener("click",()=>{let twitterUrl=`https://twitter.com/intent/tweet?url=${quoteText.innerText}`;window.open(twitterUrl,"_blank");});quoteBtn.addEventListener("click",randomQuote);
</script>
<!-- Kết thúc phần hiển thị trên web -->
</html>
