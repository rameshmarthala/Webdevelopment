# Webdevelopment
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8" />
    <title>An Autonomous Institution In Ap 
    </title>
    <style>
    .Nav{
        display:flex;
        color: white;
        background-color: black;
        position: static;
        list-style-type: none;
       
        

    }
    .Links{
        display: inline-block;
        width:max-content;
    
    }
    .Links li,a{
        list-style-type: none;
        display: inline-block;
        align-items: center;
        margin: 2%;
        color: whitesmoke;
        /* float:left; */
        align-content: space-between;
        padding: 1%;
        text-decoration: none;
        /* flex-wrap: wrap; */
        margin-top: 0.5%;
        
    }
    .Links>ul{
        margin-top: 4%;
        padding-left: 0%;
    }
    .Links li a:hover{
        
        border: 2px solid white;
        border-radius: 30%;
        transition: all 0.5s;
        color:navajowhite;
        background-color: black;

    }
    .banner p{
        position: absolute;
        top: 35%;
        left:30%;

    }
    .slides{
        position: relative;
        margin-top: 1%;
        border: 2px solid #79e0ee;
        box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
        height: 70vh;
        overflow: hidden;
    }
    .slide{
        position: absolute;
        height: 100%;
        overflow: hidden;
        opacity: 0;
        inset: 0;
        animation: slide-show 30s infinite;
    }
    .slide-2{
        animation-delay: 4s;
    }
    .slide-3{
        animation-delay: 8s;
    }
    .slide-4{
        animation-delay: 15s;
        overflow: hidden;
    }
    @keyframes slide-show {
        0%{
            opacity: 0;

        }
        20%,40%{
            opacity:1;
            scale: 1.03;

        }
        50%{
            opacity: 1;
            scale: 1.05;
            fill-opacity: inherit;
        }
        70%{
            opacity: 0;
            scale: 1.05;
        }
        
    }
    .slide img{
        width: 100%;
        height: 100%;
        object-fit: contain;
        padding: 1%;
        padding-bottom: 1%;
        
        object-position: center;
        overflow: hidden;
    }
    .Student{
        display:inline-block;
        float: left;
        flex-direction: row;
        border: 2px solid black;
        color: black;
        position: relative;
        margin-top: 1%;
        width: 100%;
    }
    .Verification >ul>li{
        display:inline-block;
        align-items: center;
        color: black;
        align-content: space-around;
        padding-inline: 10%;

    }
    .Verification>ul{
        padding-left: 10%;
    }
    .latestNews{
        margin-top: 1%;
        display: inline-block;
        border: 2px solid black;
        width: 100%;
        max-height: 7.5vh;
    
    }
    .latestNews>p{
        margin-top: 0%;
        text-align: center;
        padding: 1%;
        border: 2px solid black;
        background-color:black ;
        color: white;
        width: 6%;
        height: 3vh;
        overflow: hidden;
    }
    marquee{
        position: absolute;
        top: 113%;
        font-weight: 300%;
        margin-right: 2%;
        margin-left: 8%;
    }
    
    .dept{
        display: -webkit-inline-flex;
        border:2px solid black;
        width: 100%;
        height: 18vh;
        padding-top: 0.10%;
        padding-bottom: 0.4%;
        vertical-align: middle;
        float:left;
        text-align: center;
        align-items: center;
        align-content: center;
        color:black;
        flex-grow: initial;  
    
    }
    .dept>h2{
        
        display: -webkit-inline-flex;
        /* position: relative;
        top: 30%;
        flex-wrap: wrap; */
        vertical-align: middle;
        float:right;
        clear: both;
        text-align: center;
        align-items: center;
        align-content: center;
    

    }
    .dept,h2:hover{
        color:black;
        cursor:pointer;
    }
    .depts{
        display: -webkit-inline-flex;
        padding-block: 10%;
        padding-right: 8%;
    }
    .depts>img,h2{
        padding-right: 9%;
        block-size: 100%;
        
    }
    .dept>p{
        display: inline-flex;
        flex-direction: column;
        align-items: center;
        align-content: center;
        /* float: middle; */
        height: 13vh;
        /* height: 183px; */
        overflow:initial;
        flex-wrap: nowrap;
        flex-direction: column;
        background-color: black;
        color: white;
        padding: 1%;
        /* line-break:anywhere; */
        
    }
    .depthead{
        position: relative;
        text-align: center;
        text-indent: 0%;
        height: 15vh;
        padding: 2%;
        text-align: end;
    }
    .depthead:hover{
        color: tomato;
    }
    .para{
        /* z-index: -1; */
        border: 3px solid black;
        margin-top: 10%;
        width: 100%;
        padding-bottom: 1%;
        text-align: justify;
        background-color:cadetblue;
        color: black;
        font-weight: bolder;
        animation-direction: reverse;
    }
    .collegeranks{
        display: inline-block;
        width: 100%;
        height: 30vh;
        margin-top: 2%;
        text-align: center;
        align-items: center;
        align-content: center;
        /* border: 3px solid black; */
        overflow:visible;
        background-color: cadetblue;
    }
    
    .details{
        position:absolute;
        left: 30%;
        display: -webkit-inline-flex;
        align-items: center;
    }
    .details1{
        
        align-items: center;
        padding-inline: 21%;
        align-content: space-between;
        
    }
    .foot{
        position: relative;
        top: 80%;
        padding:0%;
        width: 98%;
        background-color: cadetblue;
        padding: 1%;

    }
    .footer{
        display: flex;
        align-items: center;
        align-content: center;
        /* border: 3px solid black; */
        align-content: space-between;
        padding-inline: 18%;
        margin-right: 3%;
        width:initial;
    }
    .footerdetails{
        padding-right: ;
        width: 100%;
        display: inline-block;
        align-items: center;
        align-content: center;
    }
    </style>
    <script src="https://kit.fontawesome.com/f7524d70a7.js" crossorigin="anonymous"></script>
</head>
<body>
    <div class="Nav">
        <img src="C:\Users\ravir\Downloads\AITS-logo.png"/>
        <p style="font-size: large;">Annamacharya<br>Institute of <br> Technology&Sciences<br>Rajampet<br>ESTD..1998</p>
    <div class="Links" style="width: 60000px;">
        
        <ul>
            <li ><a  href="#">HOME</a></li>
            <li><a href="#">ABOUTUS</a></li>
            <li><a href="#">CONTACT</a></li>
            <li><a href="#">EXAMINATION</a></li>
            <li><a href="#">NEWSLETTER</a></li>
            <li><a href="#">SUBSCRIBE</a></li>
            <li><a href="#">LOGIN</a></li>
        </ul>
    </div>
    </div>
    <div class="slides" >
        <div class="slide slide-1">
        <img style="width: 100%;" src="C:\Users\ravir\Downloads\aits banner2.jpg"/>
        </div>
        <div class="slide slide-2">
            <img src= "https://aitsrajampet.ac.in/images/banners/Banner-6.jpg"/>
        </div>
        <div class="slide slide-3">
            <img src= "https://aitsrajampet.ac.in/images/banners/Banner-4.jpg"/>
        </div>
        <div class="slide slide-4">
            <img src= "https://aitsrajampet.ac.in/images/banners/AUTONOMOUS.jpg"/>
        </div>
        
<!--         
        <h2>
            <p>
                Welcome <br> To <br> Aits
            </p>
        </h2> -->
    
    </div>
    <div class=" Student">
        <div class="Verification">
            <ul>
                <li> 
                    <i class="fa-solid fa-graduation-cap"></i>
                    <a href="" style="color: black;">Student Verification</a></li>
                <li>
                    <i class="fa-solid fa-money-bill-transfer"></i>
                    <a href="" style="color: black;">Payment Verification</a></li>
                <li>
                    <i class="fa-solid fa-building-columns"></i>
                    <a href="" style="color: black;">Placement Verification</a></li>
            </ul>
        </div>
    </div>

    <div class="latestNews">
        <p>Latest News</p>
    </div>
    <div class="lastestNews1">
            <marquee> Hey Hii</marquee>
    </div>

    <div class="dept">
        <p class="depthead">  Avilable <br> Branches</p>
     <div class="depts">
        <div class="img"> 
            <h2> Branch of B.tech</h2>
        </div>
        <div class="img">
           <h2> Branch of Mca</h2>
        </div>
        <div class="img">
            <h2>Branch of Mba</h2>
        </div>
        <div class="img">
            <h2>Branch of M.tech</h2>
        </div>
        <div class="img">
            <h2>Branch of Pharma</h2>
        </div>
     </div>
    </div>
    <div class="para">
        <h1 id="head" style="color: black;">Welcome to AITS :: Rajampet</h1>
        Annamacharya Institute of Technology & Sciences, Rajampet is an AUTONOMOUS institution and is affiliated to JNTU, Anantapur. The institute was started in the year 1998 under the auspices of Annamacharya Educational Trust in picturesque surrounding on a spacious 30 acre campus near Tallapaka, the birth place of Annamacharya, the renowned saint poet.<br><br>

        The Institute is well located on Hyderabad – Chennai Highway.<br><br>

        Sri. C. Gangi Reddy garu, Hon’ Secretary of Annamacharya Educational Trust. He was born in the year 1954 to Choppa Narayana Reddy and Choppa Rajamma at near Tallapala Village
    </div>
    <div class="collegeranks">
        <!-- <h2 style="text-align: center;"> TOP  ENGINEERING COLLEGE IN AP</h2> -->
        <h1> TOP ENGINEERING COLLEGE IN AP</h1>
        <div class="details">
            
        <div class="details1">
            <i class="fa-solid fa-person fa-beat fa-lg"></i>
            <h3>Faculty</h3>
            <p>250</p>
        </div>
        <div class="details1">
            <i class="fa-solid fa-book-open fa-flip"></i>
            <h3>Courses</h3>
            <p>15</p>
        </div>
        <div class="details1">
            <i class="fa-solid fa-people-arrows fa-bounce"></i>
            <h3>students</h3>
            <p>3500+</p>
        </div>
        <div class="details1">
            <i class="fa-solid fa-square-poll-vertical fa-flip"></i>
            <h3>Results</h3>
            <p>100%</p>
        </div>
    </div>

<div class="foot">
    <h1 style="text-align: center;"> Contact Details </h1>
    <div class="footer">
        
        <div class="footerdetails">
            <i class="fa-solid fa-location-dot"></i>
            <p> Annamacharya Instiute of <br> Technology and Sciences <br>Thallapaka Panchayat,New <br>Boyanapalli <br>Rajampet,Kadapa Dist,AndhraPradhesh</p>
        </div>
        <div class="footerdetails">
            <i class="fa-solid fa-phone"></i>
            <p style="margin-bottom: 0%;"> Security Office : <b>xxx-xxx-xxxx</b></p><br>
             Office : <b>xxx-xxx-xxx</b>
        </div>
        <div class="footerdetails">
            <h4> Follows Us On</h4>
            <a href=""><i class="fa-brands fa-instagram"></i></a>&nbsp;&nbsp;
            <a href=""><i class="fa-brands fa-twitter"></i></a>&nbsp;&nbsp;
            <a href=""><i class="fa-brands fa-facebook"></i></a>&nbsp;&nbsp;
            <a href=""><i class="fa-brands fa-linkedin"></i></a>&nbsp;&nbsp;
            <a href=""><i class="fa-brands fa-youtube"></i></a>&nbsp;&nbsp;
            
            <!-- <a href="www.instagram.com" style="color: black;"> instagram</a>
            <a href="www.facebook.com" style="color: black;"> facebook</a>
            <a href="www.instagram.com" style="color: black;"> instagram</a>
            <a href="www.instagram.com" style="color: black;"> instagram</a>
            <a href="www.instagram.com" style="color: black;"> instagram</a>  -->
            
            
            
        </div>
    </div>
</div>
</body>
</html>
