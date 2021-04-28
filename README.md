<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <style>* {
        box-sizing: border-box;
    }
    body {
        margin: 0px;
        padding: 0px;
        font: poppins;
    }
    #main{
        width: 100%;
        height: 50vh;
        position: relative;
    }
    
    nav{
        display: flex;
        justify-content: space-around;
        align-items: center;
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        background-color: white;
        box-shadow: 5px 10px 30px rgba(0, 0, 0, 0.02);
        z-index: 1;
    
    }
    .logo img{
        height: 45px;
    
    }
    .menu{
        list-style: none;
        display: flex;
    
    }
    .menu li a{
        height: 40px;
        line-height: 43px;
        margin: 3px;
        padding: 0px 22px;
        display: flex;
        font-size: 0.8em;
        text-transform: uppercase;
        font-weight: 500;
        letter-spacing: 1px;
        color: grey;
    
    }
    a{
        text-decoration: none;
    
    }
    .hey{
        color: #39bfbd;
        font-weight: 500;
        font-size: 0.9em;
        border-bottom: 2px solid #39bfbd;
    }
    
    .image{
        width: 500px;
        height: 500px;
    
    }
    .image img{
        width: 100%;
        height: 100%;
        object-fit: contain;
    
    }
    .content{
        display: flex;
        width: 90%;
        justify-content: space-around;
        align-items: center;
        position: absolute;
        left: 50%;
        right: 50%;
        transform:translate(-50%, -50%);
    }
    
    .main-text{
        width: 500px;
    
    }
    .main-text h1{
        font-size: 3.5em;
        color: #1c3548;
        margin: 0px 0px 10px 0px;
        line-height: 60px;
    
    }
    .main-text p{
        color: grey;
    }
    .resume-bin{
        width: 190px;
        height: 44px;
        display: flex;
        justify-content: center;
        align-items: center;
        color: white;
        background-color: #1db096;
        border-radius: 20px;
        box-shadow: 5px 10px 30px rgba(24, 130, 119, 0.2);
    }
    .resume-bin:hover{
        background-color: #23CDAF;
        transition: all ease 0.2s;
    }
    .menu li a:hover{
        background-color: #23bdaf;
        color: white;
        box-shadow: 5px 10px 30px rgba(24, 130, 119, 0.2);
        transition: all ease 0.2s;
    }</style>
    <title>Rock Resume</title>
    <!-- <link rel="stylesheet" href="project.css" type="text/css" /> -->
</head>
<body>
    <section id="main">
        <nav>
            <a href="#" class="logo">
                <img src="https://th.bing.com/th/id/OIP.cCqDf0Ak05-SXjQJPqr2mgHaBq?w=340&h=78&c=7&o=5&pid=1.7" alt="Logo of Rock project">
            </a>
            <span class="menu-space">

            </span>
            <ul class="menu">
                <li><a href="#">Home</a></li>
                <li><a href="#">Skills</a></li>
                <li><a href="#">Recent</a></li>
                <li><a href="#">Clients</a></li>
                <li><a href="#">Contacts</a></li>
            </ul>
            <a href="#" class="hey"><strong>Say Hi!</strong></a>
        </nav>
    </section>

    <div class="content">
        <div class="image">
            <img src="https://th.bing.com/th/id/OIP.SayjQM2YwrX3woUaw8WVPgHaFS?w=182&h=130&c=7&o=5&pid=1.7" alt="Rock">
        </div>
        <div class="main-text">
            <h1>Hello, I am The <br> Rock</h1>
            <p>Hey in this video I will be showing you guyes how to build a website using only HTML and CSS</p>
            <a href="#" class="resume-bin">See My Resume</a>
        </div>
    </div>
    
</body>
</html>


