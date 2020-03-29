<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!--Conter start--> 
 <div class="content">
     <!--header start-->
        <header>

          <img  class="img" src="IMG_20200306_190604.jpg">
          <div class="header">
              <h1>Al-Amin Islam</h1>
              <h2>Web designer</h2>


          </div>
          <div class="header1">
              <p><a href="mailto:msasakibalamin0">Email: msasakibalamin0@gmail.com</a></p>
              <p><a href="htpps://msainfo.tk">Website: msainfo.tk</a></p>
              <p><a href="tele:+8801762868864">Phone: +8801762868864</a></p>
              
              

          </div>
        </header>
        <!--header End-->
        <div class="div-clear">


        </div>
        
        <hr>

        <main>
            
            <section id="section">
                <div class="content">
                    <div class="left">
                        <h3>Personal Information</h3>
                    </div>
                    <div class="right">
                       Address: Puranapoil, Joypurhat Sadar(Bangladesh) <br/>
                       Sex: Male  <br/>
                       Date of birth: 25/03/2000 <br/>
                       Nationality: Bangladeshi  <br/>
                    </div>
                </div> 
            </section>

        <hr class="common-hr">




        <section id="section">
            <div class="content">
                <div class="left">
                    <h3>Skill</h3>
                </div>
                <div class="right">
                   <ul type="1">
                       <li >Microsoft Office<progress min="0" max="100" value="70"></progress> 70%</li>
                       <li>HTMl <progress min="0" max="100" value="50"></progress>50%</li>
                       <li>CSS <progress min="0" max="100" value="50"></progress>50%</li>
                       <li>Python<progress min="0" max="100" value="30"></progress>30%</li>
                       <li>Java<progress min="0" max="100" value="20"></progress>20%</li>
                       <li>C#<progress min="0" max="100" value="20"></progress>20%</li>
                   </ul>
                   
                </div>
            </div> 
        </section>
        <hr class="common-hr">




        <section id="section">
                <div class="content">
                    <div class="left">
                        <h3>Education</h3>
                    </div>
                    <div class="right">
                        <div class="right1">
                            <h4>Computer Science & Engineeing</h4>
                            <h5>2017-2018  CGPA : 3.88/4.00</h5>
                            <P>Leading College</P>
                            <p> Dinajpur Polytechinal Institue, Dinajpur</p>
                            <p><a href="https://www.dpi.edu.bd">https://www.dpi.edu.bd</a></p>

                        </div> 
                        <div class="right2">
                            <h4>Secondary School Certificate</h4>
                            <h5>2015-2016 GPA : 4.68</h5>
                            <P>Leading School</P>
                            <p>Shyampur High School, Joypurhat</p>
                            <p><a href="https://msainfo.tk">https://msainfo.tk</a></p>


                        </div>

                       
                    </div>
                </div> 
            </section>
            <hr class="common-hr">






                
        </main> <!--main end-->
        

       

        <footer class="bottom"> <!--footer start -->
            <a href="htpps://facebook.com/msasakibalamin1">Facebook</a>
            <a href="https://www.youtube.com/channel/UC9-70ntuFavnwi88IMVTGSw">Youtube</a>
            <a href="https://twitter.com/msasakibalamin">Twitter</a>
            <a href="https://www.instagram.com/msa_sakib_alamin/">Instagram</a>
            <p> Copyright &copy Al-Amin Islam 2020 </p>

            
         
         
        </footer> <!--footer end-->






 </div>
 <!--Conterner End-->

</body>



</html>


*{
    margin:0;
    padding:0;
}
body{
    background-color:#EEE;
    font-family: 'Times New Roman', Times, serif;

}

.content{
    max-width: 100%;
    background: #E4F9F5;
    margin:0 auto;
    padding:20px;

}
header{

}
.img{
    height: 100px;
    width: 100px;
    border:3px solid white;
    border-radius:50px;
    float: left;

}
.header{
    float:left;
    padding:30px;

}
h1,h2,h3,h4,h5,h6{
    color: #11999e;
}
.header1{
    float: right;
    padding:30px;


}
.header1 a{
    text-decoration: none;
    color:teal;
    font-weight: bold;

}  
.header1 a:hover{
    text-decoration: underline;
    color:tomato;
}
.div-clear{
    clear:both;
}
hr{
    border:solid black 3px;
    width:1000%;
    margin: 15px auto;
    border-bottom: none;
}

#section{

}
.content{

}
.left{
    width: 30%;
    float:left;

}
.right{
    width: 70%;
    float:left;

}

.common-hr{
    border:solid black 2px;
    border-bottom: none;
    width:100%;
    margin: 5% auto;
   
}
.common-hr{
    border:solid black 2px;
    border-bottom: none;
    width:100%;
    margin: 8% auto;
   
}

.right1{
    float:left;
    width:45%;
}
.right2{
    float:right;
    width: 45%;
}

.bottom{
    background: black;
    text-align:center;
    padding: 10px;
}
 .bottom a{
     color:white;
     text-decoration: none;
     margin:20px;
 }
 .bottom p{
     color:white;
     margin-top:20px;
 }
