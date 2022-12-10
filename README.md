<!DOCTYPE html>
<html lang="en">

<head>
    
    <title>Restaurant Website</title>
    <style>
        body 
        
      {background-image: url('https://images.unsplash.com/photo-1559305616-3f99cd43e353?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1935&q=80');
            background-size: cover;
           
            height:200vh;
            background-repeat: no-repeat;} 
        

        p {
            color: rebeccapurple;
        }

        header {
            color: black;
            font-size: large;
            text-align: center;
        }
        .nav-flex-row{
            display: inline-block;
        }
        .navbar{

    background-color: rgba(242, 189, 99, 0.782);
    border-radius: 20px;
    
 }
 .navbar li{
     float: left; 
     list-style: none;
     margin: 15px 25px;
 }

.navbar li a{
    padding: 5px 5px;
    text-decoration: none;
    color: black;
}
.navbar li a:hover{
   color: aliceblue;

}
.navbar ul{
    overflow: auto;
}
p{color: black;font-size: 25px;}
h1{
    font-size: larger;

}
h1 span{
font-family: cursive;
}
#m1{background-image: url("image12.jpg");font-size: 40px;}
#m2{float: right;}
    </style>
</head>

<body>
    <header>
        <nav class="navbar">
            <ul>
                <li><a href="restaurant.html">Home</a></li>
                <li><a href="about.html">About us</a></li>
                <li><a href="onlonebooking.html">Online Booking</a></li>
                <li><a href="Contact.html">Contact us</a></li>
                <div class="search">
                    <input type="text" name="search" id="search" placeholder="Search">
                      </form>
                </div>
            </ul>
        </nav>
    </header>
    <section class="section-intro">
        <header>
            <h1 id="m1"><marquee direction= right><center>SV-<span>Restaurant</span></center></marquee></h1>
        </header>
    </section>
    <p><i>At our Restaurant, we’re serving up more than what you've expected. In fact, our Restaurant is famous for
        "Tandoori Chicken" and it is one of our unexpected specialties. Reminiscent of butcher shops back in the day,
        each slow-smoked, sizzling prime chop measures seven-fingers high. Our signature recipe, that we have perfected
        for more than four decades, is rubbed with a secret blend of seasonings, cured and roasted on a rotisserie with
        pecan wood for up to six hours before it’s topped with signature herb-garlic butter, then carved tableside.</p>
        <div id="m2">
            <p>
            <h1>Dish Of The Day.</h1>
            <h1 style="color: red;">Samosas</h1>
            </p>
            <img src="https://www.blueosa.com/wp-content/uploads/2020/07/top-10-indian-dishes-samosas.jpg"
                alt="Image of samosas." width="200px" height="200px">
            </div>
   
    <h1 style="color: white;">"Welcome To Our Restaurant."</h1>
   
    <h3 style="color: #1a237e">Our Specialities.</h3>
</i>
    <p>
    <ol>
        <li>Fine Dining</li>
        <li>Fast Casual</li>
        <li>Family Style Types Of Restaurants</li>
        <li>Fast Food</li>
        <li>Cafe</li>
        <li>Pub</li>
    </ol>
    </p>
    
       <p style="padding: 10px; border: 3px solid black; font-size: larger; font-family: Arial, Helvetica, sans-serif; background-color: violet;">
        Special Offer:- 50% On Chicken Makhani, 40% on Aloo gobi, 40% on Naan and Matar paneer.</p>
        <button type="button" class="button" >
            <a href="feedback.html">Feedback</a>
              </button> 
</body>

</html>
