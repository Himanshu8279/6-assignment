# 6-assignment

Q-1 

ANS   <!DOCTYPE>
   <html>
       <head>
                <title> navigation    </title>
                <link rel="stylesheet" href="6 assignment 1.css">

      </head>


<body>    
        <div class="navigation" >
         
        <a href="#"> Home </a>
        <a href="#"> About Us </a>
        <a href="#"> Contact</a>
        <a href="#"> Blog </a>
        <a href="#"> Login </a>
        </div>


</body>
</html>

style part =
* {
   margin: 0;
   font-family: Arial;
   }
.navigation{
        height: 60px;
        background-color: blue;
        color: white;
        border: 2px solid transparent;
        padding: 15px 25px;
        display: flex;
        justify-content: space-evenly;         
 }
.navigation:hover a {
   color: red;
}
a {
   color: black;
}


Q-2


<!DOCTYPE>
   <html>
       <head> 
             <title> question 2 </title>
             <link rel="stylesheet" href="6 assignment 2.css">
       </head>

  <body>
        <div class="centered-container">
        <img src="https://pwskills.com/images/pwskills_thumbnail.png">
    
        
        <p> <b>course name</b> : <p>PW skills full stack web development</p> 

       </div>




 </body>
 </html>

 style  part=


 body {

  margin:0px;
  padding: 0px;


}
.centered-container{
   
    height: 450px;
    padding-top:10px;
    margin-left: 340px;
    margin-right:340px;
    margin-top: 50px;
    background-color: red;
    color: black;
    text-align: center;
    border-radius: 10px;
    

}
.centered-container img{
         
 max-width: 100%;
 height: auto;
 border-style: solid;
 border-color: red;
 border-radius: 8px;

}


Q-3
<!DOCTYPE>
<html>
    <head>

     <title> 3 question  </title>
     <link rel="stylesheet" href="6 assignment 3.css" >
    </head>

<body>

     <div id="navbar">

        <a href="#" id="div1"> Home </a>
        <a href="#" id="div2"> About Us </a>
        <a href="#" id="div3"> Contact</a>
        <a href="#" id="div3"> Blog </a>
        <a href="#" id="div5"> Login </a>


        </div>





    </div>

</body>
<html>
 style code =
 *{
  padding: 0px;
  margin: 0px;

}
#navbar {

height: 60px;
background-color: black;
display: flex;

text-align: center;
justify-content : space-evenly;
    
}


#div1{ 

 color:white;
 border: 2px dashed yellow;
 background-color: green;
 padding-top:20px;
}
#div2{ 

 color:white;
 border: 2px dotted red;
 background-color: yellow;
 padding-top:20px;



}
#div3{ 

 color:white;
 border: 2px soloid green;
 background-color: blue;
 padding-top:20px;


}
#div4{ 

 color:white;
 border: 2px solid blue;
 background-color: green;
 padding-top:20px;


}
#div5{ 

 color:white;
 border: 2px solid orange;
 background-color: yellow;
 padding-top:20px;


}

