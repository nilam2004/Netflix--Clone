# Netflix--Clone
#HTML CODE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NETFLIX</title>
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet">
      <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Open+Sans&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class=" top-head">
        <div class="container">
            <nav class="navbar">
                <svg  width="150px"  fill="#E50815" viewBox="0 0 111 30" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" class="default-ltr-cache-1d568uk ev1dnif1"><g><path d="M105.06233,14.2806261 L110.999156,30 C109.249227,29.7497422 107.500234,29.4366857 105.718437,29.1554972 L102.374168,20.4686475 L98.9371075,28.4375293 C97.2499766,28.1563408 95.5928391,28.061674 93.9057081,27.8432843 L99.9372012,14.0931671 L94.4680851,-5.68434189e-14 L99.5313525,-5.68434189e-14 L102.593495,7.87421502 L105.874965,-5.68434189e-14 L110.999156,-5.68434189e-14 L105.06233,14.2806261 Z M90.4686475,-5.68434189e-14 L85.8749649,-5.68434189e-14 L85.8749649,27.2499766 C87.3746368,27.3437061 88.9371075,27.4055675 90.4686475,27.5930265 L90.4686475,-5.68434189e-14 Z M81.9055207,26.93692 C77.7186241,26.6557316 73.5307901,26.4064111 69.250164,26.3117443 L69.250164,-5.68434189e-14 L73.9366389,-5.68434189e-14 L73.9366389,21.8745899 C76.6248008,21.9373887 79.3120255,22.1557784 81.9055207,22.2804387 L81.9055207,26.93692 Z M64.2496954,10.6561065 L64.2496954,15.3435186 L57.8442216,15.3435186 L57.8442216,25.9996251 L53.2186709,25.9996251 L53.2186709,-5.68434189e-14 L66.3436123,-5.68434189e-14 L66.3436123,4.68741213 L57.8442216,4.68741213 L57.8442216,10.6561065 L64.2496954,10.6561065 Z M45.3435186,4.68741213 L45.3435186,26.2498828 C43.7810479,26.2498828 42.1876465,26.2498828 40.6561065,26.3117443 L40.6561065,4.68741213 L35.8121661,4.68741213 L35.8121661,-5.68434189e-14 L50.2183897,-5.68434189e-14 L50.2183897,4.68741213 L45.3435186,4.68741213 Z M30.749836,15.5928391 C28.687787,15.5928391 26.2498828,15.5928391 24.4999531,15.6875059 L24.4999531,22.6562939 C27.2499766,22.4678976 30,22.2495079 32.7809542,22.1557784 L32.7809542,26.6557316 L19.812541,27.6876933 L19.812541,-5.68434189e-14 L32.7809542,-5.68434189e-14 L32.7809542,4.68741213 L24.4999531,4.68741213 L24.4999531,10.9991564 C26.3126816,10.9991564 29.0936358,10.9054269 30.749836,10.9054269 L30.749836,15.5928391 Z M4.78114163,12.9684132 L4.78114163,29.3429562 C3.09401069,29.5313525 1.59340144,29.7497422 0,30 L0,-5.68434189e-14 L4.4690224,-5.68434189e-14 L10.562377,17.0315868 L10.562377,-5.68434189e-14 L15.2497891,-5.68434189e-14 L15.2497891,28.061674 C13.5935889,28.3437998 11.906458,28.4375293 10.1246602,28.6868498 L4.78114163,12.9684132 Z"></path></g></svg>
                <div class="right-half">
                  <div class="dropdown-container">
                      <!--span class="material-icons language">language</span-->
                      <select  class="language">
                          <option value="English">English</option>
                          <option value="Hindi">Hindi</option>
                </select>
                      <!--span class="material-icons">arrow_drop_down</span-->
                    
                <button style="color: white; border-radius: 6px; width:60px;"> Sing In</button>
            </div>
           </div>
        </nav>
    <div class="contant">
        <h1>Unlimited movies, TV shows and more</h1>
        <p>Watch anywhere. Cancel anytime.</p>
        <p>Ready to watch? Enter your email to create or restart your membership.</p>
       <div class="email-container">
        <input placeholder="Email Adderess">
        <button class="btn get-started-btn">Get Start <span class="material-icons">chevron_right</span></button>
       </div> 
    </div>
 </div>
</header> 
<section class="first-section">
    <div class="left-item">
<h1>Enjoy on your TV</h1>
<p>Watch on smart TVs,PlayStation ,Xbox ,Chromecast , Apple TV, Blu-ray players and more.</p>
    </div>
    <div class="right-item">
<img src="layer2.png" alt="">
<video muted loop autoplay>
    <source src="video-tv.m4v">
</video>
    </div>
</section>
<section class="second-section">
    <div class="left-item static-left-item">
        <img src="layer3.jpg" alt="">
        <div class="layout">
         <img src="danger image.png" alt="">
         <p>Stranger Things<span>Downloading...</span></p>
        
        </div>
        <!--div data-uia="nmhp-card-animation-asset-motion" class="default-ltr-cache-xfttou e15c37ii6"><div class="default-ltr-cache-1cn8kex"><img data-uia="nmhp-card-animation-asset-animation" alt="" src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/boxshot.png" class="default-ltr-cache-1t1z3a4"></div><div class="default-ltr-cache-tcf860"><div id="" class="default-ltr-cache-162uqtg e15c37ii4" data-uia="">Stranger Things</div><div id="" class="default-ltr-cache-44ib4m e15c37ii3" data-uia="">Downloading...</div></div><div data-uia="nmhp-card-animation-asset-custom" aria-hidden="true" class="default-ltr-cache-1q4up1i e15c37ii5"></div></div-->
    </div>
    <div class="right-item">
       <h1>Download your shows to watch offline</h1>
       <p>Save your favourites easily and always have something to watch.</p>
    </div>
</section> 
<section class="third-section">
<div class="left-item">
   <h1>Watch everywhere</h1>
   <p>Stream unlimited movies and TV shows on your phone, tablet, laptop, and TV.</p>
</div>
    <div class="right-item">
      <img src="layer4.png" alt="">
       <video muted loop autoplay width="400px" style="top:60px; left:18%">
     <source src="video2.m4v">
       </video>
    </div>
</section>
<section class="third-section">
    <div class="right-item static-left-item">
        <img src="layer5.png" alt="">
        <!--div data-uia="nmhp-card-animation-asset-motion" class="default-ltr-cache-xfttou e15c37ii6"><div class="default-ltr-cache-1cn8kex"><img data-uia="nmhp-card-animation-asset-animation" alt="" src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/boxshot.png" class="default-ltr-cache-1t1z3a4"></div><div class="default-ltr-cache-tcf860"><div id="" class="default-ltr-cache-162uqtg e15c37ii4" data-uia="">Stranger Things</div><div id="" class="default-ltr-cache-44ib4m e15c37ii3" data-uia="">Downloading...</div></div><div data-uia="nmhp-card-animation-asset-custom" aria-hidden="true" class="default-ltr-cache-1q4up1i e15c37ii5"></div></div-->
    </div>
    <div class="left-item">
       <h1>Create profiles for kids</h1>
       <p>Send children on adventures with their favourite characters in a space made just for them—free with your membership.</p>
    </div>
</section>
<section class="faq-container" style="color: white;">
    <h1>Frequently Asked Questions</h1>
    <div class="faq">
        <p>What is Netflix ?</p>
        <span class="material-icons">add</span>
    </div>
    <div class="faq">
        <p>How much does Netflix cost ?</p>
        <span class="material-icons">add</span>
    </div>
    <div class="faq">
        <p>Where can I watch ?</p>
        <span class="material-icons">add</span>
    </div>
    <div class="faq">
        <p>How do I cancle ?</p>
        <span class="material-icons">add</span>
    </div>
    <div class="faq">
        <p>What can I watch on Netflix ?</p>
        <span class="material-icons">add</span>
    </div>
    <div class="faq">
        <p>Is Netflix good for kids ?</p>
        <span class="material-icons">add</span>
    </div>
    <p>Ready to watch? Enter your email to create or restart your membership.</p>
    <div class="email-container">
        <input placeholder="Email Adderess">
        <button class="btn get-started-btn">Get Start <span class="material-icons">chevron_right</span></button>
       </div>
</section>
<footer class="footer-conntainer">
    <p> <a href="#">Questions? Call 000-800-919-1694</a></p>
    <div class="links-container">
        <div class="links-item">
        <a href="#">FAQ</a>
        <a href="#">Media Centre</a>
        <a href="#">Ways to Watch</a>
        <a href="#">Cookie Preferences</a>
        <a href="#">Speed Test</a>
    <select  class="language">
            <option value="English">English</option>
            <option value="Hindi">Hindi</option>
    </select>
         <P>Netflix India</P>
    </div>
        <div class="links-item">
            <a href="#">Help Centre</a>
            <a href="#">Investor Relations</a>
            <a href="#">Terms of Use</a>
            <a href="#">Corporate Information</a>
            <a href="#">Legal Notices</a>
        </div>
        <div class="links-item">
                <a href="#">Account</a>
                <a href="#">Job</a>
                <a href="#">Privacy</a>
                <a href="#">Contact Us</a>
                <a href="#">Only on Netflix</a>
            </div>
    </div>
</footer>
</body>
</html>

#CSS CODE
*{
  margin: 0;
  padding: 0;
  font-family: 'Open Sans', sans-serif;
}
body{
    background-color: black;
}
.top-head, .first-section ,.second-section,.third-section,.faq-container{
    border-bottom: 5px solid #535251;
}
.top-head{
    background-image: url("header.jpg");
    height: 700px;
    background-color: rgba(0,0,0,0.4);
}
.container{
    height: 700px;
    background-color: rgba(0,0,0,0.4);
    color:white;
}
.language,.drop-down{
    background-color: rgba(0,0,0,0.4);
    color:white;
    padding: 5px 15px;
    position:relative;
}

.dropdown-container{  
    padding-right:100px;
    display:flex;
    position: static; 
}
.navbar{
    padding: 15px;
    padding-left: 200px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.right-half{
    border:2px ;
    display: flex;
    gap: 40px;
}
button{
    height:36px;
    background-color:rgb(204, 5, 5);
}
.contant{
   text-align: center;
   display: flex;
   margin: 20vh auto;
   width: 60%;
   text-align: center;
   flex-direction: column;
}
.contant h1,.contant p{
    margin-top: 30px;
}
.contant h1{
    font-size: 50px;
    font-weight:bolder;
}
.contant p{
    font-size: 24px;
    font-weight: bold;
}
.email-container{
width: 70%;
height:50px;
gap: 30px;
margin-top:20px;
display: flex;
margin-left:200px;
}
.email-container > input{
    flex-grow: 1;
    background-color: rgba(0,0,0,0.7);
    border: 1px solid #535251;
    padding: 0 10px;
    border-radius: 5px;
}
.btn{
    height: 50px;
    width: 160px;
    border-radius: 5px;
    color: white;
    padding-bottom: 10px;
    background-color: rgb(241, 13, 13);
}
.get-started-btn{
font-size: 20px;
align-items: center;
display: flex;
font-weight:bold;
font-family:sans-serif;
padding-left: 28px;
padding-top: 7px;
}
.first-section ,.third-section{
    display: flex;
    align-items: center;
    padding: 0px 80px;
    gap: 100px;
}
.left-item{
    color: white;
}
.left-item h1,.right-item h1 
{
    margin-bottom: 20px;
    font-size: 50px;
    font-weight:bolder;
    color: white;
}

.left-item p,.right-item p{
    font-size: 24px;
    color: white;
}
.right-item  {
    position: relative;
}
.right-item >video{
    position: absolute;
    left: 80px;
    top: 90px;
    z-index: -1;
}
.second-section{
    display: flex;
    align-items:center;
    padding: 0px 80px;
    gap: 100px;
    padding-bottom:87px ;
}
.layout{
     border: 2px solid rgb(117, 110, 110);
     position: absolute;
     left: 22%;
     right: 0;
     bottom: 0;
     display: flex;
     justify-content: center;
     align-items: center;
     gap: 50px;
     width: 58%;
     height: 100px;
     border-radius: 22px;
     background-color:rgba(0,0,0,0.9);
}
.static-left-item{
    position: relative;
    height:120;
    border-radius: 2px;
}
.layout img {
    width: 58px;
    align-items: center;
    padding-top: 15px;
    padding-bottom:15px ;
}
.layout p span{
 color: blue;
}
.layout p{
    font-size: 20px;
    display: flex;
    flex-direction: column;
}
.right-item >video{
    position: absolute;
    left: 80px;
    top: 90px;
    z-index: -1;
    justify-content:center;
}
.faq-container{
    padding: 40px 100px;
    display: flex;
    flex-direction: column;
    align-items:center;
    gap: 10px;
}
.faq-container > h1{
    font-size:50px;
    margin-bottom: 20px;
    }
.faq >p,.faq >span{
font-size: 28px;
}
.faq:hover{
    background-color: #736c6c;
}
.faq-container  >p {
    font-size: 30px;
    margin: 20px 0;
}
.faq{
display: flex;
justify-content: space-between;
align-self: stretch;
padding: 20px;
background-color: #2D2D2D;
border-radius: 2px;
transition-duration: 0.5s;
}
.faq p{
    font-size: 22px;
}
.faq span{
    font-size: 30px;
}
.faq-container >p {
    font-size: 30px;
    margin-top: 30px;
    margin-bottom: 0;
}
.footer-conntainer{
    height: 300px;
    padding: 130px;
}
.footer-conntainer >p{
   margin-bottom: 40px;
}
.footer-conntainer,.footer-conntainer a{
  color: #AFAFAF;
}
.links-container{
    display: flex;
    gap: 260px;
    justify-content:flex-start;
}
.links-item{
    display: flex;
    flex-direction: column;
    gap: 18px;
   
}
