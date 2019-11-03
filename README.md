<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Jason's JS Tutorial</title>
</head>
<link rel="stylesheet" href="Tutorial.css">
<script src="Tutorial.js"></script>
<link rel="stylesheet" href="animationcode.css">
<script src="http://code.jquery.com/jquery-1.10.1.min.js"></script> 
<body>
    <header> 
            <div class="title-container">
                <div class="title">
               <h1></h1>
            </div>
        </div>
    </header>
    <nav>
        <div class="navbar-container">
            <ul class="navbar">
                <li><marquee>Javascript Tutorial</marquee></li>
                <li class="nav-menu"><a href="#objects">Objects</a></li>
                <li><a href="#arrays">Arrays</a></li>
                <li><a href="#functions">Functions</a></li>
                <li><a href="#resources">Resources</a></li>
            </ul>
        </div>
    </nav>
    
    
    <div id="mySidebar" class="sidebar">
            <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
            <a href="#">Obligatory Sidebar</a>
            <a href="#resources">Resources</a>
            <a href="https://www.amazon.com" target = "blank">Shop Now</a>
          </div>
          
          <div id="main">
            <button class="openbtn" onclick="openNav()">&#9776; </button>
            
          </div>
    
    <div class="main-body">
        <div class="two-column">
            <div class="col1">
                <h2 id="objects">Objects</h2>
                <p><article>Objects are basically variable containers that house various information.  For example; a car has various properties. "car" would be your object and the variables could be: 'make,model,color'. Depending on the type of car, you would have different values.  (ex: 'Make' could be Ford, Toyota, or Chevrolet).  The object allows you to pair the various information together.'Make: Toyota; Model: Camry; Color: Gray;  )  I know you may feel a bit confused from my gross explanation of Objects. Have no fear young grasshopper!  Take a deep breath and click on the image to the right.</article></p>
            </div>  
            <div class="object-img">
                <a href="./img/Object.PNG" target ="_blank">
                    <img src="./img/Object.PNG" alt="objects">
                        </a>       
                </div>
            </div>
        <div class="two-column">
            <div class="col1">
                <h2 id="arrays">Arrays</h2>
                <p>
                        Arrays, being similar to objects, allow you to store information in a type container.  However, Arrays do not use the value pairs (as with objects), Arrays hold various "slots" for similar information You could have an array names ages, with various information such as 18, 21, 25, 40.  You could put all the ages in a container and access them when needed.  I know you may feel a bit confused from my gross explanation of Arrays. Have no fear young grasshopper!  Take a deep breath and click on the image to the right.</p>

            </div>
            <div class="array-img">
                    <a href="./img/Array.PNG" target ="_blank">
                            <img src="./img/Array.PNG" alt="array">
                            </a>

            </div>
        </div>
        <div class="two-column">
            <div class="col1">
                <h2 id="functions">Functions</h2>
                <p>Functions are pieces of code used to replicate results at any given moment.  Functions are often referred to as "if this, than that".  The function will return a message on the console, depending on the input. (ex: if x > 6, print "number is greater than 6".  Anytime a user inputs a number that is greater than 6, the function will always return the string, "number is greater than 6. I know you may feel a bit confused from my gross explanation of Functions. Have no fear young grasshopper!  Take a deep breath and click on the image to the right.
                    </p>

            </div>
            <div class="function-img">
                    <a href="./img/Function.PNG" target ="_blank">
                            <img src="./img/Function.PNG"  alt="function" target ="_blank">
                          </a>
            </div>
        </div>
    
                <div class="container">
                  <h2>Subscribe to our Newsletter</h2>
                  <p>...and everyone will get their parking pass</p>
                </div>
              
                <div class="container" style="background-color:white">
                  <input type="text" placeholder="Name" name="name" required>
                  <input type="text" placeholder="Email address" name="mail" required>
                  
                </div>
              
                <div class="container">
                  <input type="submit" value="Subscribe"> 
                </div>
            </div>
       <div class="col4">
                <h2 id="resources"><u>Additional Resources</u></h2>
            </div>  
        <div class="links">
            <div class="links1">
                    <a href="https://www.javascript.com" target ="_blank">
                        <img border="0" alt="javascript.com" target = "blank" src="./img/js-logo.png" width="300" height="100"></div></a>
            
            <div class="links2">
                    <a href="https://elevenfifty.org/" target ="_blank">
                        <img border="0" alt="elevenFifty" src="./img/Eleven.png" width="300" height="100">
                         </a></div>
            <div class="links3">             
                    <a href="https://css-tricks.com" target ="_blank">
                        <img border="0" alt="cssTricks" src="./img/css-tricks.png" width="300" height="100">
                        </a></div>
            <div class="links4">
                    <a href="https://developer.mozilla.org/en-US/" target ="_blank"> 
                        <img border="0" alt="mdn"  src="./img/mdn.png" width="300" height="100">
                        </a></div>
            </div>
     </div>
    </div>
    <div class="footer">
        <p>Copyright © 2019 JL's Happy Coding Corp, LLC.  All Rights Reserved</p>
    </div>
</body>
</div>
</html>
