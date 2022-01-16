# websitetry
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Sena Yusufoglu</title>
    <link rel="stylesheet" href="css/style.css">
    
    <style type="text/css">
        section#top {background-color: navajowhite}
        section#left {background-color: burlywood; float:"left"}
        section#right {background-color: blanchedalmond; width: 130px}
        article#under{background-color: cornflowerblue; color: white}
        aside#leftmenu{float:right; background-color: black; color: whitesmoke; width:250px}
        header{background-color: darkgrey; border: 2px solid red; padding: 20px; font-size: 20px }
        footer{background-color: black ; color:antiquewhite; border-bottom-style: double; border: 3px solid violet; font-family: fantasy}
        figure{ text-align: center; border: 3px}
        figcaption{font-family: Geneva; font-weight: bold; color: blueviolet}
        aside{ text-align: right}
        form#contactfrom {background-color: aquamarine}
    </style>
    <!-- headedak, ma,n page ve photo. arasini acmayi basaramadim--> 
</head>
<!-- css kodu yazarken sonuna !important koyarsan onu en başa atar en baskın kod o olur --> 

<body>
    <header>
        <big><b> sena </b></big>
       <img src=""> place logo here 
        <nav>
            <a href="index.html"> Main Page </a>
            <a href="photography.html"> Photography</a>
        </nav>
        
        

    </header>
    
      
      
      <div id="out">
       <section id="top">
        
           <h1>Sena Yusufoglu
        </h1>
        <h3>Hello !</h3>
        </section> 
<section id="left">
        <p>I am a traveller, student, <a href="photography.html" target="_blank"> photographer </a> and illustrator from Turkey. Welcome to my website where you can find my photography and illustration work. </p>
        </section>
        <section id="right"
         
     
>         
           <p>If you have and reccomendationsi mail me! I would be happy to hear your reccomendations. </p>
        </section>
          
          <article id="under"> 
if you want to support my instagram, follow @senayusufoglu :)</article>
           
            
              <!-- to be changed later (photographerin altinin cizilmemesi icimn bi tag va rama anlamadim), article da sectionla ayni ise ariyor, genelde stiteyle direkt alakali degilde kullanici yrumlari vb icin kullanilir -->
        
        
        
        
        <div style=color:rosybrown> Contact me if you have any questions</div>
        <small>Please contact me if you want to use my work! </small>
        <div><strong> <em> “Photography is an austere and blazing poetry of the real.” </em></strong></div>
   
    
      </div>




    <ul>
        <li>Portraits</li>
        <li> Sceneries </li> <!-- did it for practice, to be deleted later, this is the unordered list tag-->

    </ul>
    <ol type="I">
        <li> merhaba</li>
        <li> selam </li>
    </ol>
    <!-- did it for practice, to be deleted later, this is the unordered / ordered list tag-->

    Click <a href="https://vsco.co/senayusufoglu" target="_blank"> here </a> to access to my VSCO blog.

    <table border=1 cellspacing=0>
        <tr>
            <th><b>date</b></th>
            <th><b>city</b></th>
        </tr>
        <tr>
            <td width=100 align=center> march 2019 </td>
            <td>rotterdam </td>
        </tr>
        <tr>
            <td width=100 align=center> april 2018 </td>
            <td> rome </td>
        </tr>
    </table>
    <!-- table tag practice, will be deleted or modified later -->

    <form action="" method="">

        <p>Login</p>
        Username: <input type="text" name="username" maxlength="15" placeholder="username"> <br />
        Password: <input type="password" name="password" placeholder="password"> <br />
        <input type="submit" value="Login">
    </form>

    <form action="" method="">
        <p>Sign Up</p>
        Name: <input type="text" name="name" maxlength="20" required autofocus> <br />

        E-mail: <input type="email" name="email"> <br />
        Phone: <input type="tel" name="phone"> <br />
        Username: <input type="text" name="username" maxlength="15"> <br />
        Password: <input type="password" name="password"> <br />
        <input type="submit" value="Submit">
    </form>

    <form action="" method="">
        Your Comments <br>
        <textarea name="text" rows="20" placeholder="..." maxlength="200">
        </textarea>

    </form>

    <form action="">
        Wish List
        <select name="wish"> Wish
            <optgroup label="art">
                <option value="photo"> Photo</option>
                <option value="illustration"> illustration</option>
            </optgroup>
            <optgroup label="info">
                <option value="how to"></option>
            </optgroup>
        </select>



    </form>

    <p>What do you want to see more on my blog?</p> <br />
    <input type="checkbox" name="wishes" value="reviews" checked> Reviews<input type="checkbox" name="wishes" value="photos"> Photos <input type="checkbox" name="wishes" value="illustrations">illustrations
    <br>


    <h6>Your gender? </h6><br><input type="radio" name="gender">Female <br> <input type="radio" name="gender"> Male
    <input type="reset" value="reset"> <!-- reset calismiyor -->
    <br> <br /> <!-- / ne fark yaratiyor ? -->



    <form action="photography.html" method="post">

        <input type="button" value="click me">
        <br>
        <input type="submit" value="send"> <!-- photography.html koyunca bisey oluyor ama ne oluyor anlamadim (submit formu karsi tarafa yollamak icin) -->

        <br>

        <input type="file">
        <br>
        <input type="reset" value="reset">




    </form>


    <form name="become-a-member" method="post" action="">
        <label for="name"> Your name: </label><input type="text" name="name" id="name" value=""> <!-- what does id stand for--> <br>
        <label for="surname"> Your surname: </label><input type="text" name="surname" id="surname" value="">


    </form>

    <!-- asagidaki  personal info formu olan form infoform.css dosyasiyla duzenlendi -->

    <form action="" method="">
        <link rel="stylesheet" href="css/infoform.css">
        <h4>Sign up</h4>
        <fieldset>
            <legend>
                Personal info
            </legend>
            Name: <input type="text" name="name" id="name"> <br>
            Surname: <input type="text" name="name" id="surname">
            Address: <textarea type="text" name="address" id="address"></textarea>
        </fieldset>

        <fieldset>
            <legend>
                interests
            </legend>
            <p><label for="photography">Photography</label> <input type="checkbox" name="interests" value="photography" id="photography"> </p>
            <p><label for="design ">Design</label><input type="checkbox" name="interests" value="design" id="design">
            </p>

        </fieldset>
        <fieldset>
            <legend> Other
            </legend>

            <p>Do you want to receive my newsletter? <label for="yes">Yes </label> <input type="checkbox" name="yes" id="yes"> </p>

        </fieldset>

        Become a member! <input type="submit" value="send">
    </form>

    <br><br><br>
    <form action="send.php" method="post" style=color:blueviolet>

        <!-- send.php dosyasi gercekten olsaydi submit e basildiginda onlari post methoduyla oraya gonderecekti-->

        username: <input type="text" name="username"> <br>
        password: <input type="password" name="password"> <br>
        1 <input type="checkbox" value="1" name="check">
        2<input type="checkbox" value="2" name="check">
        3<input type="checkbox" value="3" name="check">
        <br>
        <textarea name="message" rows="10"></textarea>
        <br>

        <input type="file"> <br><br>
        <input type="submit" value="send"> <br>
        <input type=reset value="reset">
        
    </form>

<br><br>


<aside id="rightmenu" > 
<ul> 
<li>instagram</li>
<li>linkedin</li>
    <li>facebook</li>
    <li>twitter</li>
</ul>

</aside>
<!-- aside etiketi calismiyor ?--> 



<figure> 
<img src="img/layoutSketch.jpg"
height=100 width=100>
<img src="img/webpage-rough-sketch.gif" height=100 width=100>

<figcaption> web design sketches</figcaption>

</figure>

<div class="contact"> 






<h4> Contact Form  
</h4>

<form id="contactform" method="post" action="">

 <input name="name" type="text" class="form-control" placeholder="Your Name" required> <br>
 <input name="email" type="email"  class="form-control" placeholder="Your Email" required><br>
  <textarea name="message"  class="form-control" placeholder="Your Message" rows="5" required> </textarea><br>
  <input type="submit"  class="form-control submit" value="SEND MESSAGE">
   
   
      </form>
<!-- bunlarin duzenleme css lerini ayri ayri dosyalara baglayamiyo muyuz ? --> 
</div>





<footer>
    all rights reserved.
</footer>






</body>
</html>
