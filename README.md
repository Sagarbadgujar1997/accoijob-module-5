<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Busness Landing Page</title>
   <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <!-- This header part containing nav elements and it sticky -->
    <header>
    <nav class="container">
        <div class="item">SK india</div>
        <div class="item menu-container">
            <a href="https://www.linkedin.com/home/">Home</a>
            <a href="https://www.linkgroup.com/about-us.html#:~:text=Link%20Group%20administers%20financial%20ownership,connect%20people%20with%20their%20assets.">About Us</a>
            <a href="https://www.linkedin.com/help/linkedin/answer/a522735/find-your-linkedin-public-profile-url?lang=en">Known more</a>
            <a href="https://www.linkedin.com/help/linkedin/answer/a518597/contact-linkedin-customer-service?lang=en">Contact Us</a>
        </div>
    </nav>
    </header>
    <hr>
    <body>
    <main >
        <nav>
        <section class="content1"> 
            <div><p id="heading">BUSINESS LANDING PAGE</p><h1 id="arrow" style="align-items:right;"><a id="arrow">&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&#x2193</a></h1>
            </div>
            <div>
            <img class="firstimg" src="https://images.pexels.com/photos/4158/apple-iphone-smartphone-desk.jpg?auto=compress&cs=tinysrgb&w=600" alt="Laptop">
            </div>
           </nav>
           <div class="content"></div>
           <h1>OUR SERVICES</h1>
           
         </section>
         <footer>
            <!-- insted of align ceter im using &nbsp to remember the id -->
                   <br> <form class="about" action="mail to:abc@gmail.com">
                     <div class="info"><h1 id="h3">&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspCONTACT US</h1><br></div>
                      <div class="contactus">
                         <label for="fname" ></label>
                         <input type="text" name="fname" id="fname" required placeholder="Full Name"> <br><br>
                         <label for="lname" ></label>
                         <input type="text" name="lname" id="lname" required placeholder="Last Name"><br><br>
                         <label for="email"></label>
                         <input type="email" name="email" id="email" required placeholder="Email Address"><br><br>
                         <label for="reason"></label>
                        <input type="text" name="reason" id="reason" required placeholder="Reason For Contacting"><br><br>
                        <button type="submit">Submit</button>
                      </div>
                    </form>
                </footer>
                .container{
    display: flex;
    justify-content: space-between;
    background-color: black;
    color: aliceblue;
    padding: 1em;
    font-size: 1.3em ;
    
}
.menu-container{
   height: 1.5vh;
    width: 40vw;
    display: flex;
    justify-content: space-evenly;
}
a{
    text-decoration: none;
    color: aliceblue;
}
*{
    margin: 0%;
}
/* this is for page i image and bussness landing page */
.content1{
    display: flex;
    justify-content: space-between;
    height: 85vh;
    background-color: black;
    color: aliceblue;
}
#heading{
    font-size: 12em;
    height: 180vh;
    margin-bottom: 15vh;
    padding: 60px;
    margin-left: 50px;
    
   
}
.firstimg{
    padding: 50px;
    margin-top: 35vh;
    margin-right: 15vw;
    height: 40vh;
    width: 30vw;
}
.about{
    background-color: black;
    padding: 40px;
    padding-left: 120px;
}
#h3{
    color: aliceblue;
    width: 100vw;
    justify-content: center;
}
input{
    width:80vw;
    padding-left: 10px;
    margin: 5px;
    height: 20px;
    /* background-color: black; */
    border: 1.5px solid white;
    
}
button{
    padding-left: 10px;
    height: 30px;
    margin: 5px;

}
.serve{
    margin: 40px;
    padding: 40px;
}
.content{
    font-size: 5em;
}
