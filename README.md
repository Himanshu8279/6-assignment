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

Q-4 

<!DOCTYPE>
<html>
<head>

       <title> 4 question</title>
   <link rel="stylesheet" href="6 assignment 4.css">



</head>
       <body>
             
              <div>image </div>

      </body>
</html>

stylesheet= 
div{

    width:400px;
    height: 400px;
    color: red;
    background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRJv5tdHBqqhjVy1zhBc8b83WikBBgrLdNV6Q&s"); 
    background-size: cover;
    text-align: center;
    position: absolute;
    top: 100px;
    left:150px;
    border:2px solid yellow;
    border-radius: 50%;
   
}

Q 5 

<!DOCTYPE>
<HTML>
      <head>
             <title> 5 question   </title>

      </head>
<link rel="stylesheet" href="6 assignment 5.css">


  <body>

          <h1> google font </h1>
       
        
          

        <div>

       
              

       </div>

   <p>  Google Fonts is a library of free and open-source font families, an interactive web directory for browsing 
        the library, and APIs for using the fonts via CSS and Android. It was launched in 2010 and has since become 
        a key resource for web developers and designers. With Google Fonts, you can enhance the readability and design 
        of your website by choosing from hundreds of fonts that are optimized for performance and quality across all 
        devices and platforms.</p>



   </body>
</HTML>


stylesheet
body {
            margin: 0;
            padding: 0;
            font-family: 'Montserrat', sans-serif;
            background-color: #f5f5f5;
            text-align: center;
}
div{
            width: 500px;
            height: 300px;
            margin: 20px auto;
            background-image: url("https://storage.googleapis.com/gd-prod/images/a910d418-7123-4bc4-aa3b-ef7e25e74ae6.60c498c559810aa0.webp");
            background-size: cover;
}
h1 {
            font-family: 'Oswald', sans-serif;
            margin-top: 40px;
            font-size: 3em;
            color: #333;
}
p{
    line-height: 2;
    padding: 0 40px;
    font-size: 1.1em;
    color: #333;

}
