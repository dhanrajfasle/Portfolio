# Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compability" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="portfolio/index.css" />

    <!-- Butstrap link provide online here -->
     <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" />

</head>
<body>
    <header class="header-section">
        <div class="container">
            <nav class="navbar navbar-expand-lg custon_nav-container">
                <div class="collapse navbar-collapse"
                id="navbarSupporttedcontent">
                <ul class="navbar-nav mx-auto">
                    <li class="nav-item active">
                        <a class="nav-link" href="index.html">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#page1">Skills</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#page2">Projects</a>"
                    </li>
                    <div class="nav-item">
                        <a class="nav-link" href="#page3">Contacts</a>"
                    </div>
                </ul>
                </div>
            </nav>
        </div>
    </header>

    <div id="main">
        <div id="page">

            <img src="portfolio/IMG_1310-01.jpeg" style="padding: 300px;
            border-radius: 50%;" alt="" />

            <div id="text">
                <h2>Hello</h2>
                <h1>I'm Dhanraj Fasle</h1>
                <h4>
                    I'm a passionate web developer with a keen eye for design and 
                    a flair for creating seamless, user-friendly digital experiences.
                    with a strong fundamental in front-end and back-end technologies,
                    I specialize in turning ideas into beautifully crafted web applications.
                </h4>
                <div id="buttons">
                    <button id="b2">
                        <a href="https://drive.google.com/file/d/1hn7R4ysA-mGB7eS2t94StCra1gwj-UDa/view?usp=drivesdk">RESUME</a>
                    </button>
                </div>
            </div>


            <!----------------------------------------->

            <div id="page1">
                <div id="right">
                    <div id="text1">
                        <h1>My Skills</h1>
                        <h4>
                            As a dedicated web developer, I've honed a versatile
                            skill set
                            that impowers we to bring creative versions to life in
                            the digital realm.
                            My proficiency spans both front-end and back-end technologies,
                            including HTML, CSS, JavaScript and a variety of populer frameworks and libraries.
                        </h4>
                    </div>
                </div>
                <div id="left">
                    <div class="box">
                        <h1> •Competatiive Programing</h1>
                        <p>
                            I regularly do competative coding since I love problem
                            solving.
                            I started my coding journy with CodeChef and HackerRank.
                        </p>
                    </div>
                    <div class="box">
                        <h1> •Design and devlopement</h1>
                        <p>
                            I have devloped projects (College Information ChatBot, Money Tracker WeApp) using web technologies.
                            Over time i have gained a wealth of experience design and development web application.
                        </p>
                    </div>
                    <div class="box">
                        <h1> •Java & DSA</h1>
                        <p>I'm Java and DSA Learning Enthusiast</p>
                    </div>
                </div>
            </div>

            <div id="page2">
                <div id="text4">
                    <h1>My Projects</h1>
                </div>

                <div id="project">
                    <div class="projects p1">
                        <div id="text3">
                            <h1>•College Imformation ChatBot</h1>
                        </div>
                        <div id="image">
                            <a href="Link_here">
                                <img src="portfolio/chatborimg.PNG" alt="This ChatBot devloped for Newly Admitted Students Helps" />
                            </a>
                        </div>
                    </div>
                    <div class="projects p2">
                        <div id="text3">
                            <h1>•Money Tracker WebApp</h1>
                        </div>
                        <div id="image">
                            <a href="Link_here">
                                <img src="portfolio/moneytrackerimg.PNG" alt="This is for calculation of Money Balance">
                            </a>
                        </div>
                       <!------- <div class="projects p3">
                            <div id="text3">
                                <h1>Travel & Tourism Managment System</h1>
                            </div>
                            <div id="image">
                                <a href="Link_here">
                                    <img src="portfolio/travelimg.png" alt="Provide Online Booking features">
                                </a>
                            </div>-->
                        </div>
                    </div>
                </div>


                <section class="end">
                    <div id="page3" class="contact-me">
                        <br /><br />
                        <h2>Get In Touch</h2>
                        <br />
                        
                        <h2 class="collab">Lets collab and do a Project</h2>
                        <br />

                        <p>Contact Me</p>
                        <br />

                        <a class="btn" href="https://www.linkedin.com/in/dhanraj-fasle-5b0b1a238/?lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3BA2c%2Fq6mRRfOckOsALwfLVg%3D%3D">
                            <img src="portfolio/circle-linkedin-512.webp" width="40px" height="40px">
                        </a>
                        <a class="btn" href="https://github.com/dhanrajfasle">
                            <img src="portfolio/GitHub-img.png" width="40px" height="40px">s
                        </a>
                        <a class="btn" href="fasledhanraj@gmail.com">
                            <img src="portfolio/gmail-img.png" width="40px" height="40px">
                        </a>
                        <a class="btn" href="https://whatsapp.com/dl/">
                            <img src="portfolio/whats aap.jfif" width="40px" height="40px">
                        </a>
                        <a class="btn" href="https://www.facebook.com/share/FMmEwj8sHeKDGYPe/?mibextid=qi2Omg">
                            <img src="portfolio/fb.png" width="40px" height="40px">
                        </a>
                    </div>

                    <div class="botton-container">
                        <div style="width: 50px; margin-left: auto; margin-right: auto;">
                            <br>
                            <p class="copyright">@DhanrajFasle</p>
                        </div>
                    </div>
                </section>
            </div>

</body>
</html>
*{
    margin: 0%;
    padding: 0%;
    box-sizing: border-box;
    font-family: montserrat;
}
html,body{
    height: 100%;
    width: 100%;
}
#main{
    position: relative;
    overflow: hidden;
}
#page{
    position: relative;
    height: 100vh;
    width: 100vw;
    background-color: rgb(255, 255, 255);
}
#page>img{
    position: absolute;
    right: 5%;
    top: 52%;
    transform: translateY(-50%);
    width: 60%;
}
#page>#nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0px 30px;
    position: absolute;
    z-index: 9;
    height: 10%;
    width: 100%;
}
#center-nav{
    display: flex;
    gap: 20%;
    text-align: center;
}
#center-nav>a{
    text-decoration: none;
    color: #219384;
    font-weight: 500;
    font-size: 18px;
    text-align: center;
}
#nav>input{
    padding: 10px 5px;
    border-radius: 10px;
    border: 1px solid #dadada;
    text-transform: uppercase;
}
#text{
    padding: 30px 50px;
    position: relative;
    top: 18%;
    left: 8%;
    height: 75%;
    width: 35%;
    scale: 1.1;
}
#text>h1{
    font-size: 60px;
    line-height: 1;
    margin-top: 20px;
}
#text>h4{
    margin-top: 30px;
    color: purple;
    font-size: 17px;
    font-weight: 500;
}
#buttons{
    position: absolute;
    left: 0%;
    bottom: 18%;
    height: 20%;
    width: 100%;
}
#buttons>button{
    padding: 10px 22px;
    border-radius: 10px;
    border: none;
    font-weight:500;
}
#buttons>button>a{
    font-size: 20px;
    color: wheat;
}
#buttons>#b2{
    margin-left: 20px;
    background-color: #000000;
}
#page1{
    position: relative;
    height: 100vh;
    width: 100vw;
    background-color: #c3cefe;
    /*padding: 50px;*/
}
#page1>#left{
    position: absolute;
    right: 5%;
    height: 90%;
    top: 50%;
    transform: translateY(-50%);
    width: 35%;
}
#left>.box{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0px 20ox;
    height: 33.3%;
    width: 100%;
    border-top: 2px solid #000;
}
#left>.box>h4{
    font-size: 30px;
}
#left>.box>h1{
    font-size: 35px;
}
#left>.box>p{
    margin-left: 20px;
}
#text1{
    margin: 50px 50px;
    height: 30%;
    width: 50%;
    position: absolute;
    z-index: 9;
}
#text1>h1{
    font-size: 60px;
    margin-top: 20px;
}
#text1>h4{
    font-size: 30px;
    color: black;
    font-weight: 500;
    width: 70%;
    margin-top: 50px;
}
#text1>h5{
    color: #8873EF;
    transform: rotate(-20deg);
    position: absolute;
    left: -2%;
}

#page2{
    position: relative;
    height: 100vh;
    width: 100vw;
    background-color: #e4b7ec;
}
#project{
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 50%;
    width: 90%;
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
    bottom:5% ;
}
.projects{
    border-top: 2px solid #000;
    height: 100%;
    width: 31%;
}
#text3{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0px 20px;
    height: 30%;
    width: 100%;
}
#image{
    height: 70%;
    width: 100%;
}
#image>img{
    height: 100%;
    width: 100%;
    object-fit: cover;
}
.p1 img{
    height: 200px;
    width: 300px;
}
.p2{
    position: relative;
    top: -20%;
}
.p3{
    position: relative;
    top: -50%;
}
#text4{
    position: absolute;
    top: 10%;
    left: 5%;
    height: 20%;
    width: 30%;
}
#text4>h1{
    margin-top: 20px;
    font-size: 50px;
}
/*#text4>h5{
    color: #8873EF;
    transform: rotate(-20deg);
    position: absolute;
    top: 0%;
    left: 0%;
}*/


.end{
    background-color: #bab0ee;
    text-align: center;
    padding-bottom: 50px;

}
.contact-me p{
    font-size: 40px;
}
.contact-me h2{
    font-size: 50px;
}
.contact-me p{
    font-size: 40px;
}
.contact-me{
    width: 100%;
    height: 570px;
    font-weight: bold;
    position: relative;
}
.collab{
    font-size: 3.1rem;
    font-family: 'montserrat', sans-serif;
    display: block;
    margin: 100px auto;
    padding: 30px 0;
}
.copyright{
    color: white;
    font-size: 1.2rem;
    margin: 0;
    padding: 8px 0 8px 0;

}
.end{
    padding: 7px 7px;
}
.btn > img{
    border-radius: 50%;
    position: relative;
    bottom: 40px;
}
/*.profile-text{
    font-size: 1.3rem;
}
.profile-div{
    padding: 0 18%;
    text-align: center;
    align-items: center;
}
a{
    text-decoration: underline;
    color: #0765a0;
    font-size: large;
}
.break{
    height: 2px;
}
#hello{
    font-size: 2rem;
}*/
.nav-item >a{
    color: #3e3e3e !important;
    font-size: 1.2rem;
    font-weight: 600;
    margin: 7px 20px;
    text-transform: uppercase;
}
.header-section{
    background-color: #2222221f;
}
