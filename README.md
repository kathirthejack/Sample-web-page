# Sample-web-page
<!DOCTYPE html>


<html>


<head>
    <title>
        Simple company web page Template
    </title>
</head>


<body>
    <nav class="navbar background">
        <ul class="nav-list">
            <div class="logo">
                <img src="katlands.png">
            </div>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a href="#offer">offer</a></li>
           
        
        </ul>


        <div class="rightNav">
            <input type="text" name="search" id="search">
            <button class="btn btn-sm">Search</button>
        </div>
    </nav>
    <h2>Welcome to our KATLANDs Shop!</h2>
    <p>Welcome to our chocolate shopping store. Browse our collection below and enjoy your coco chocolate at KATLANDs.</p>
    <section class="firstsection">
        <div class="box-main">
            <div class="firstHalf">
                <h1 class="text-big" id="web">
                    Dark chocolate
                </h1>
                
                <p class="text-small">
                    Dark chocolate is a form of chocolate containing cocoa solids and cocoa butter without the milk or butter found in milk chocolate. Dark chocolate without added sweetener is known as bitter chocolate or unsweetened chocolate


                    
                </p>
                
                <img src="dark.jfif">
                <p style="background-image: url('dark.jpg');"></p>
               


            </div>
        </div>
    </section>


    <section class="secondsection">
        <div class="box-main">
            <div class="secondHalf">
                <h1 class="text-big" id="program">
                    reese's peanut butter cups
                    
                </h1>
                <p class="text-small">
                    Reese's peanut butter cups miniatures are the perfect combination of salty, sweet, and gluten free. Grab a handful for snacking on the go or sharing with love...
                    
                </p>
                


            </div>
        </div>
    </section>


    <section class="section">
        <div class="paras">
            <h1 class="sectionTag text-big">ferrero rocher</h1>


            <p class="sectionSubTag text-small">
                Ferrero Rocher was born in 1982 after a very long process of research and development for excellence. Thanks to its unique and exquisite recipe, the refined golden wrapper and a distinctive transparent box, Ferrero Rocher was recognized since its launch as a true symbol of Ferrero quality and excellence.
                
            </p>
            <img src="ferro.jfif">
            


        </div>


        <div class="thumbnail">
            
        </div>
    </section>
    <b>
    <section id="about">
        <h2>About Us</h2>
        <p>KATLANDs Dress collections is a high-end clothing store that offers everything from casual basics to luxurious statement pieces. If you’re looking for an elegant yet bold look, this is your go-to spot for quality pieces that will stand out.</p>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: katlandscustomer@gmai.com</p>
        <p>Phone: +1 (123) 950020027</p>
    </section>
</b>


   
<footer>
       <b> <p>&copy; 2023 ©KATHLANDs Shopping store . 
                      All rights reserved.</p>
                    </b>     
    </footer>


   
</body>


</html>
<style>
    * {
        margin: 0;
        padding: 0;
    }


    .navbar {
        display: flex;
        align-items: center;
        justify-content: center;
        position: sticky;
        top: 0;
        cursor: pointer;
    }


    .background {
        background: black;
        background-blend-mode: darken;
        background-size: cover;
        background-image: dark.jpg;
    }


    .nav-list {
        width: 70%;
        display: flex;
        align-items: center;
    }


    .logo {
        display: flex;
        justify-content: center;
        align-items: center;
    }


    .logo img {
        width: 180px;
        border-radius: 50px;
    }


    .nav-list li {
        list-style: none;
        padding: 26px 30px;
    }


    .nav-list li a {
        text-decoration: none;
        color: white;
        
    }


    .nav-list li a:hover {
        color: skyblue;
    }


    .rightnav {
        width: 30%;
        text-align: right;
    }


    #search {
        padding: 5px;
        font-size: 17px;
        border: 2px solid grey;
        border-radius: 9px;
    }


    .firstsection {
       <background-image:"dark.jpg">
        height: 400px;
    }


    .secondsection {
        background-color: olive;
        height: 400px;
    }


    .box-main {
        display: flex;
        justify-content: center;
        align-items: center;
        color: black;
        max-width: 80%;
        margin: auto;
        height: 80%;
    }


    .firsthalf {
        width: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }


    .secondhalf {
        width: 30%;
    }


    .secondhalf img {
        width: 70%;
        border: 4px solid white;
        border-radius: 150px;
        display: block;
        margin: auto;
    }


    .text-big {
        font-family: 'Piazzolla', serif;
        font-weight: bold;
        font-size: 35px;
    }


    .text-small {
        font-size: 18px;
    }


    .btn {
        padding: 8px 20px;
        margin: 7px 0;
        border: 2px solid white;
        border-radius: 8px;
        background: none;
        color: white;
        cursor: pointer;
    }


    .btn-sm {
        padding: 6px 10px;
        vertical-align: middle;
    }


    .section {
        height: 400px;
        display: flex;
        align-items: center;
        justify-content: center;
        max-width: 90%;
        margin: auto;
    }


    .section-Left {
        flex-direction: row-reverse;
    }


    .paras {
        padding: 0px 65px;
    }


    .thumbnail img {
        width: 250px;
        border: 2px solid black;
        border-radius: 26px;
        margin-top: 19px;
    }


    .center {
        text-align: center;
    }


    .text-footer {
        text-align: center;
        padding: 30px 0;
        font-family: 'Ubuntu', sans-serif;
        display: flex;
        justify-content: center;
        color: white;
    }
</style>


<style>
    body {
      background-image: url('qw.jpg');
      background-repeat: no-repeat;
      background-attachment: fixed;
      background-size: cover;
    }
    </style>
