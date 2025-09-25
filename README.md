<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css" type="text/css">
</head>
<body>
    <header>
        <div class="container">
        <div class="logo">
            <img src="logo.png" alt="">
        </div>
            <div class="options">
                <ul class="list">
                    <li><a href="" class="mrp-btn">Revised MRPs</a></li>
                    <li><a>Home</a></li>
                    <li><a>Company</a></li>
                    <li><a>Brands</a></li>
                    <li><a>Business</a></li>
                    <li><a>News Room</a></li>
                    <li><a>Sustainability</a></li>
                    <li><a> Careers</a></li>
                    <li><a>Contact Us</a></li>
                </ul>                
            </div>
            </div>
    </header>
    <div class="img-col">
        <img class="f-img" src="063929FROOTI_Digital_2024_PAPL-WEB_1.jpg" alt="">
    </div>
    <div class="row">
        <div class="col1">
            <div class="blu-img">
                <h1>Live the Frooti Life</h1>
            </div>    
        </div>
        <div class="col2">
            <p>The love story between Frooti and India began <br> in 1985. Today, Frooti rules the hearts of <br> millions of mango lovers around the world. Just <br> a swig of the rich and juicy Frooti is akin to the <br> joyful experience of slurping on the real king of <br> fruits. Made with real mango pulp from the <br> freshest of mangoes, Frooti satisfies the <br> craving for this popular seasonal fruit <br> throughout the year. It’s juicy and flavourful <br> mango taste not just rejuvenates the taste <br> buds, but is the perfect thirst-quencher that <br> refreshes you in no time.</p>
            <p>Led by innovation, Frooti is the first drink to <br> disrupt the beverage market in India with many <br> “firsts”. Frooti was the first brand to be <br> introduced in Tetra Pak in India, pioneering the <br> concept of ‘on-the-go’. It was the first brand to <br> unveil the PET bottle and TCA Tetra Pak as <br> well. With these unique innovations in <br> packaging, Parle Agro kept India’s popular <br> mango drink fresh and accessible to <br> consumers across India.</p>
            <p>Frooti available in 65ml, 125ml, and 200ml <br> Carton Pack and also in PET bottles of 125ml, <br> 250ml, 300ml, 600ml, 1.2Ltr, and 1.8Ltr PET.</p>
            <div class="icons">
                <ul class="sociel">
                <li><img class="sc-img" src="download.png" alt=""></li>
                <li><img class="sc-img" src="download (1).png" alt=""></li>
                <li><img class="sc-img" src="download (2).png" alt=""></li>
                <li><img class="sc-img" src="youtube.png" alt=""></li>
            </ul>
            </div>
        </div>
        
    </div>
    <div class="last-img">
        <img src="093629FROOTI_Pack_Digital_1920x1080_2023.jpg" alt="">
    </div>
    <footer>
        <div class="col3">
            <p>Corporate Head Office <br>
Parle Agro Private Limited, <br>
off Western Express Highway, <br>
Sahar-Chakala Road, Parsiwada, <br>
Andheri (E), Mumbai 400 099. <br></p>

<p>2019, Parle Agro© All rights reserved.</p>
        </div>
        <div class="col4">
            <p>If you have a particular query, please select the concerned <br> department:</p>
            <a href="index.html">Exports: exports@parleagro.com</a> <br>
            
            <a href="index.html">Preforms: preforms@parleagro.com</a> <br>
            <a href="index.html">Consumer Cell: consumercell@parleagro.com</a> <br>
            <a href="index.html">Media Queries: corpcomm@parleagro.com</a>
        </div>
        <div class="col5">
            <p>Our Policy: <strong class="strong">Vigil Mechanism Policy</strong> </p>
            <p><strong class="strong">Annual Return</strong></p>
            <p>Get in touch: <br>
            T: 022 - 6734 8000</p>
            <p>E: <strong class="strong">info@parleagro.com</strong> <br>Follow us : Instagram, Twitter and Linkedin</p>
         <div class="last-icon">
            <img src="download.png" alt="">
            <img src="download (2).png" alt="">
            <img src="download (1).png" alt="">
            </div>
                
        </div>

    </footer>

    body{
    margin: 0 auto;
    
}
.container{
    width: 100%;
    background-color: #0a0b27;
    height: 35px;
    display: flex;
    justify-content: center;
}
.logo{
    display: flex;
    justify-content: start;
}

.logo img{
    width: 60px;
    padding-top: 20px;
    position: relative;
    right: 80px;
    bottom: 8px;
}
.options ul{
    list-style: none;
    display: flex;
    justify-content: center;
    color: white  ;
    font-size: 8px;
    gap: 15px;
    font-family: Arial, Helvetica, sans-serif;
    position: relative;
    left: 80px;
    top: 5px;

}   
.options ul :hover{
    color: red;
}
.mrp-btn {
    background-color: rgb(191, 0, 0);
    color: white;
    font-size: 8px;
    font-weight: bold;
    padding: 8px 15px;
    border-radius: 6px;
    text-decoration: none;
    display: inline-block;
    margin-top: -8px; 
}

.mrp-btn:hover {
    background-color: #0a0b27;
}
.img-col{
    width: 100%;
    height: 427px;
    object-fit: cover;
    align-items: center;
    margin: 0 auto;
}
.f-img{
    width: 100%;
    margin: 0;

}
.row{
    width: 100%;
    height: 550 px;
    display: flex;
    justify-content: start; 
    

    
}
.col1{
    width: 50%;
    height: 530px;
    background-color: #f09130; 
    
    
}
.blu-img{
    width: 80px;
    height: 223px;
    margin-left: 145px;
    background-image: url(0345263FA8DB.png);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    position: relative;
    margin-top: 110px;
}
.blu-img h1{
    display: flex;
    justify-content: start;
    color: #fff;   
    width: 190px;
    padding-top: 70px;
}
.col2{
    width: 50%;
    height: 94%;
    padding-top: 35px;
}
.col2 p{
    font-size: 12px;
    display: flex;
    justify-content: center;
    font-family: Arial, Helvetica, sans-serif   ;
    padding-top: 10px;
}
.icons{
    width: 40%;
    height: 20px;

    
}
.sociel {
    
    list-style: none  ;
    display: flex;
    margin-left: 31px;
}
.sc-img{
    width: 85%;
    height: 75%;

}
.last-img{
    width: 100%;
    height: 100%;

}
.last-img img{
    width: 100%;
    height: 100%;

}
footer{
    max-width: 90%;
    margin: 0 auto;
    height: 35vh;
}
.col3{
    width: 33%;
    height: 100%;
    font-size: 7px;
    font-family: Arial, Helvetica, sans-serif;
    float: left;
    margin-top: 20px;
}
.col4{
    width: 33%;
    height: 100%;
    float: left;
    margin-top: 20px;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 7px;
    
}
.col5{
    width: 33%;
    height: 100%;
    float: left;
    margin-top: 20px;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 7px;
}
.col4 a{
    color: black;
    text-decoration: none;
    font-weight: bolder;
    line-height: 11px;
    margin: 0;
}
.col4 a:hover{
    color: red;
}.col5 .strong:hover{
    color: red;
}
.last-icon{
   height: 25px;
    width: 100px;
    float: left; 
}
.col5 .last-icon img{
    height: 18px;
    width: 18px;
    float: left;
}
    

</body>
</html>
