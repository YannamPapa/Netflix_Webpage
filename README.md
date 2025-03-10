# Netflix_Webpage
"A Netflix-inspired webpage built using HTML and CSS, featuring a sleek design that replicates the popular streaming platform's interface."
//.......................................HTML CODE........................................................................................//
<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <title>Netflix Website Clone - Easy Tutorials</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="header">
    <nav>
       <img src="D:\html project\netflix-img\images\logo.png" class="logo"> 
       <div>
         <button class="language-btn" >English <img src="D:\html project\netflix-img\images\down-icon.png"></button>
         <button> Sign In</button>
       </div>
    </nav>
    <div class="header-content">
        <h1>Unlimited movies, TV shows and more</h1>
        <h3>Starts at ₹149. Cancel at any time.</h3>
        <p>Ready to watch? Enter your email to create or restart your membership.</p>
        <form class="email-signup">
            <input type="email" placeholder="Email  address" required>
            <button type="submit">Get Started</button>
        </form>
    </div>
</div>  
<div class="features">
    <div class="feature">
       <div class="text-col">
        <h2>Enjoy on your TV</h2>
        <p>Watch on smart TVs, PlayStation, Xbox, Chromecast, Apple TV, Blu-ray players and more.</p> 
       </div>
       <div class="img-col">
        <img src="D:\html project\netflix-img\images\feature-1.png">
       </div>
    </div>
        <div class="feature">
    <div class="text-col">
        <h2>Download your shows to watch offline</h2>
        <p>Save your favourites easily and always have something to watch.</p>
       </div>
       <div class="img-col">
        <img src="D:\html project\netflix-img\images\feature-2.png">
     </div>
    </div>
     
        <div class="feature">
     <div class="text-col">
        <h2>Watch everywhere</h2>
        <p>Stream unlimited movies and TV shows on your phone, tablet, laptop and TV.</p>
       </div>
       <div class="img-col">
        <img src="D:\html project\netflix-img\images\feature-3.png">
     </div>
        </div>
     <div class="feature">
     <div class="text-col">
        <h2>Create profiles for kids</h2>
        <p>Send kids on adventures with their favourite characters in a space made just for them — free with your membership.</p>
       </div>
       <div class="img-col">
        <img src="D:\html project\netflix-img\images\feature-4.png">
    </div>
    </div>
    
</div>

<div class="faq">
    <h2>Frequently Asked Questions</h2>
    <ul class="accordion">
        <li>
            <input type="radio" name="accordion" id="first">
            <label for="first">What is Netflix?</label>
            <div class="content">
                <p>Netflix is a streaming service that offers a wide variety of award-winning TV shows, movies, anime, documentaries and more – on thousands of internet-connected devices.

                    You can watch as much as you want, whenever you want, without a single ad – all for one low monthly price. There's always something new to discover, and new TV shows and movies are added every week!</p>
            </div>

        </li>
        
        <li>
            <input type="radio" name="accordion" id="second">
            <label for="second">How much does Netflix cost?</label>
            <div class="content">
                <p>Watch Netflix on your smartphone, tablet, Smart TV, laptop, or streaming device, all for one fixed monthly fee. Plans range from ₹149 to ₹649 a month. No extra costs, no contracts.</p>
            </div>

        </li>

        <li>
            <input type="radio" name="accordion" id="third">
            <label for="third">Where can I watch</label>
            <div class="content">
                <p>Watch anywhere, anytime. Sign in with your Netflix account to watch instantly on the web at netflix.com from your personal computer or on any internet-connected device that offers the Netflix app, including smart TVs, smartphones, tablets, streaming media players and game consoles.

                    You can also download your favourite shows with the iOS or Android app. Use downloads to watch while you're on the go and without an internet connection. Take Netflix with you anywhere.</p>
            </div>

        </li>

        <li>
            <input type="radio" name="accordion" id="fourth">
            <label for="fourth">How do I cancle</label>
            <div class="content">
                <p>Netflix is flexible. There are no annoying contracts and no commitments. You can easily cancel your account online in two clicks. There are no cancellation fees – start or stop your account anytime.</p>
            </div>

        </li>

        
        <li>
            <input type="radio" name="accordion" id="fifth">
            <label for="fifth">What can I Watch On Netflix</label>
            <div class="content">
                <p>Netflix has an extensive library of feature films, documentaries, TV shows, anime, award-winning Netflix originals, and more. Watch as much as you want, anytime you want.</p>
            </div>

        </li>
    </ul>
    <small>Ready to watch? Enter your email to create or restart your membership.</small>
    <form class="email-signup">
        <input type="email" placeholder="Email  address" required>
        <button type="submit">Get Started</button>
    </form>        
</div>
<div class="footer">
    <div class="footer">
        <h2>Questions? Call 000-000-000-000</h2>
        
        <div class="link-container">
            <div class="col">
                <a href="#">FAQ</a>
                <a href="#">Investor Relations</a>
                <a href="#">Privacy</a>
                <a href="#">Speed Test</a>
            </div>
    
            <div class="col">
                <a href="#">Help Center</a>
                <a href="#">Cookies Preferences</a>
                <a href="#">Jobs</a>
                <a href="#">Legal Notices</a>
            </div>
    
            <div class="col">
                <a href="#">Account</a>
                <a href="#">Ways to Watch</a>
                <a href="#">Corporate Information</a>
                <a href="#">Only on Netflix</a>
            </div>
    
            <div class="col">
                <a href="#">Media Centre</a>
                <a href="#">Terms of Use</a>
                <a href="#">Contact Us</a>
            </div>
        </div>
    
        <button class="language-btn">English <img src="D:\html project\netflix-img\images\down-icon.png"></button>
        <p>class="copyright-txt">Netflix India</p>
   
        </button>
    </div>

    //......................................................................CSS CODE......................................................................//

    *{
    margin: 0;
    padding: 0;
    font-family: 'poppins',sans-serif;
    box-sizing: border-box;
}
body{
    background:  #000;
    color: #fff;
}
.header{
    width: 100%;
    height: 100vh;
    background-image: linear-gradient(rgba(0,0,0,0.7),rgba(0,0,0,0.7)) ,url("D:/html project/netflix-img/images/header-image.png");
    background-size: cover;
    background-repeat: center;
    padding: 10px 8%;
    position: relative;
}
nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 10px 0;
}
.logo{
    width: 150px;
    cursor: pointer;
}
nav button{
    border: 0;
    outline: 0;
    background: #db0001;
    color: #fff;
    padding: 7px 20px;
    font-size: 12px;
    border-radius: 4px;
    margin-left: 10px;
    cursor: pointer;
}
.language-btn{
    display: inline-flex;
    align-items: center;
    background: transparent;
    border: 1px solid #fff;
    padding: 7px 10px;
}
.language-btn img{
    width: 10px;
    margin-left: 10px;
}
.header-content{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    text-align: center;
    margin-top: 100px;

}
.header-content h1{
    font-size: 60px;
    line-height: 70px;
    font-weight: 600;
    max-width: 650px;

}
.header-content h3{
    font-weight: 400;
    margin-bottom: 20px;
}
.email-signup{
    background: #fff;
    border-radius: 4px;
    display: flex;
    align-items: center;
    margin-top:30px;
    overflow: hidden;
}
.email-signup input{
    flex: 1;
    border: 0;
    outline: 0;
    margin-left: 20px;
}
.email-signup button{
    background: #db0001 ;
    border: 0;
    outline: 0;
    color: #fff;
    font-size: 16px;
    cursor: pointer;
    padding: 15px 30px;

}

/*--------------------features---------------*/
.features{
    padding: 50px 12%;
    font-size: 22px;
}
.feature{
    display: flex;
    width: 100%;
    align-items: center;
    flex-wrap: wrap;
    padding: 50px 0;
    justify-content: space-between;
}
 .text-col{
    flex-basis: 50%;
    margin-bottom: 20px;
    text-align: left;
   
}
.img-col{
    flex-basis: 50%;
    margin: bottom 20px;
}
.img-col img{
    display: block;
    width: 90%;
    margin: auto;
}
.feature:nth-child(odd){
    flex-direction: row-reverse;
}
.features .h2{
    font-size: 50px;
    font-weight: 600;
    margin-bottom: 20px;
}

/*---------------------faq---------------------------*/
.faq {
    padding: 10px 12%;
    text-align: center;
    font-size: 18px;
}

.faq h2 {
    font-weight: 500;
    font-size: 40px;
}

.accordion {
    margin: 60px auto;
    width: 100%;
    max-width: 750px;
}

.accordion li {
    list-style: none;
    width: 100%;
    padding: 5px;
}

.accordion li label {
    display: flex;
    align-items: center;
    padding: 20px;
    font-size: 18px;
    font-weight: 500;
    background: #303030;
    color: white;
    margin-bottom: 2px;
    cursor: pointer;
    position: relative;
    transition: background 0.3s ease-in-out;
}

.accordion li label:hover {
    background: #505050;
}

.accordion li label::after {
    content: '+';
    font-size: 34px;
    position: absolute;
    right: 20px;
    transition: transform 0.3s;
}

input[type="radio"] {
    display: none;
}

.accordion .content {
    background: #303030;
    color: white;
    text-align: left;
    padding: 0 20px;
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.5s ease-in-out, padding 0.3s;
}


input[type="radio"]:checked + label + .content {
    max-height: 300px; 
    padding: 20px;
}


input[type="radio"]:checked + label::after {
    content: 'x';
}
.faq .email-signup{
    max-width: 600px;
    margin: 20px auto 60px;
}
.faq small{
    font-size: 13px;

}
/* ---------------footer-----------------------*/
.footer {
    padding: 50px 15% 10px;
    border-top: 6px solid #333;
    color: #777;
    text-align: center; /* Center the links */
}

/* Flex container for links */
.footer .link-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between; /* Ensures equal spacing */
    max-width: 1000px;
    margin: auto;
    gap: 40px; /* BIG space between links */
}

/* Styling each link */
.footer .link-container a {
    text-decoration: none;
    color: #777; /* Keeps links always #777 */
    font-size: 16px;
    font-weight: bold;
    padding: 10px 30px; /* Adds BIG space around links */
    display: inline-block;
}

/* Responsive Design */
@media (max-width: 768px) {
    .footer .link-container {
        flex-direction: column;
        align-items: center;
    }
    .footer .link-container a {
        display: block;
        margin-bottom: 20px; /* Adds extra space for small screens */
    }
}
.footer .language-btn{
    color: #fff;
    padding: 10px 20px;
    border-radius: 3px;
}
.copyright-txt{
    font-size: 14px;
    margin-top: 20px;
    margin-bottom: 10px;
}

/*---------media-queries-for-small-screen---------*/
@media only screen and (max-width: 600px){
    .logo{
        width:100px;

    }
    nav button{
        padding: 5px 10px;

    }
    nav .language-btn{
        padding: 4px 8px;

    }
    .header-content{
        position: unset;
        transform: none;
        padding-top: 150px;
    }
    .header-content h1{
        font-size: 30px;
    }
    .email-signup button{
        font-size: 12px;
        padding: 10px 15px;
    }
    .text-col
}





    
