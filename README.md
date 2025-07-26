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
