<!DOCTYPE html>
<html>
  <head>
    <title>W3.CSS Template</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <style>
    body, h1,h2,h3,h4,h5,h6 {font-family: "Montserrat", sans-serif}
    .w3-row-padding img {margin-bottom: 12px}
    /* Set the width of the sidebar to 120px */
    .w3-sidebar {width: 120px;background: #222;}
    /* Add a left margin to the "page content" that matches the width of the sidebar (120px) */
    #main {margin-left: 120px}
    /* Remove margins from "page content" on small screens */
    @media only screen and (max-width: 600px) {#main {margin-left: 0}}
    </style>
  </head>
<body class="w3-black">

<!-- Icon Bar (Sidebar - hidden on small screens) -->
<nav class="w3-sidebar w3-bar-block w3-small w3-hide-small w3-center">
  <!-- Avatar image in top left corner -->
  <img src="./Images/bl1.jpg" style="width:100%">
  <a href="#" class="w3-bar-item w3-button w3-padding-large w3-black">
    <i class="fa fa-home w3-xxlarge"></i>
    <p>HOME</p>
  </a>
  <a href="#about" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-user w3-xxlarge"></i>
    <p>ABOUT</p>
  </a>
  <a href="#photos" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-eye w3-xxlarge"></i>
    <p>PHOTOS</p>
  </a>
  <a href="#contact" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-envelope w3-xxlarge"></i>
    <p>CONTACT</p>
  </a>
</nav>

<!-- Navbar on small screens (Hidden on medium and large screens) -->
<div class="w3-top w3-hide-large w3-hide-medium" id="myNavbar">
  <div class="w3-bar w3-black w3-opacity w3-hover-opacity-off w3-center w3-small">
    <a href="#" class="w3-bar-item w3-button" style="width:25% !important">HOME</a>
    <a href="#about" class="w3-bar-item w3-button" style="width:25% !important">ABOUT</a>
    <a href="#photos" class="w3-bar-item w3-button" style="width:25% !important">PHOTOS</a>
    <a href="#contact" class="w3-bar-item w3-button" style="width:25% !important">CONTACT</a>
  </div>
</div>

<!-- Page Content -->
<div class="w3-padding-large" id="main">
  <!-- Header/Home -->
  <header class="w3-container w3-padding-32 w3-center w3-black" id="home">
    <h1 class="w3-jumbo"><span class="w3-hide-small">I'm</span> Amit Patil.</h1>
    <p>Web Developer.</p>
    <img src="./Images/bl1.jpg" alt="boy" class="w3-image" width="992" height="1108">
  </header>

  <!-- About Section -->
  <div class="w3-content w3-justify w3-text-grey w3-padding-64" id="about">
    <h2 class="w3-text-light-grey">About Amit Patil</h2>
    <hr style="width:200px" class="w3-opacity">
    <p>Hello, I'm Amit Patil, a passionate web developer hailing from Sangli. With a solid foundation in Computer Science, I earned my Master's degree from Chhatrapati Shivaji Maharaj University, Kolhapur. My journey into the world of programming was further enriched by completing a Python course at Naresh IT, Hyderabad.
    <h4 style=color:"Gray";><strong>Expertise</strong></h4>
    <p>
      Drawing from over 2 years of experience in the field, I specialize in crafting dynamic and visually appealing websites. My proficiency lies in HTML, CSS, and JavaScript, allowing me to create engaging user experiences and interactive interfaces. Additionally, I have extensive experience in PHP and WordPress development, where I've honed my skills to deliver high-quality solutions tailored to meet the unique needs of my clients. Moreover, my deep understanding of server architecture and database connectivity ensures seamless functionality and robust performance in every project I undertake.
    </p>
    <h4 style=color:"Gray";><strong>Educational Background</strong></h4>
    <p>
      Master of Computer Applications (MCA), Chhatrapati Shivaji Maharaj University, Kolhapur (2022)<br>
      Bachelor of Computer Applications (BCA), GACC,Sangli (2019)
    </P>
    <h4 style=color:"Gray";><strong>Passion and Dedication</strong></h4>
    <p>Driven by a relentless pursuit of excellence, I approach each project with creativity, dedication, and attention to detail. My commitment to staying updated with the latest industry trends and technologies empowers me to deliver cutting-edge solutions that surpass expectations.
    </p>
    <h4 style=color:"Gray";><strong>Portfolio</strong></h4>
    <p>Take a glimpse into my portfolio to explore a diverse range of projects I've had the privilege to work on. From responsive websites to custom web applications, each endeavor reflects my passion for innovation and my unwavering commitment to client satisfaction.
    </p>
    </p>
    <h3 class="w3-padding-16 w3-text-light-grey">My Skills</h3>
    <p class="w3-wide">Website Development</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:95%"></div>
    </div>
    <p class="w3-wide">Application Development</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:85%"></div>
    </div>
    <p class="w3-wide">Software Development</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:80%"></div>
    </div><br>
    
    <div class="w3-row w3-center w3-padding-16 w3-section w3-light-grey">
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">11+</span><br>
        Partners
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">55+</span><br>
        Projects Done
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">89+</span><br>
        Happy Clients
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">150+</span><br>
        Meetings
      </div>
    </div>

    <button class="w3-button w3-light-grey w3-padding-large w3-section">
      <i class="fa fa-download"></i> Download Resume
    </button>
    
    <!-- Grid for pricing tables -->
    <h3 class="w3-padding-16 w3-text-light-grey">What We Offer</h3>
    <div class="w3-row-padding" style="margin:0 -16px">
      <div class="w3-half w3-margin-bottom">
        <ul class="w3-ul w3-white w3-center w3-opacity w3-hover-opacity-off">
          <li class="w3-dark-grey w3-xlarge w3-padding-32">Website Design & Development</li>
          <li class="w3-padding-16">Website Development</li>
          <li class="w3-padding-16">Application Development</li>
          <li class="w3-padding-16">Software Development</li>
          
          <li class="w3-light-grey w3-padding-24">
            <button class="w3-button w3-white w3-padding-large w3-hover-black">Sign Up</button>
          </li>
        </ul>
      </div>

      <div class="w3-half">
        <ul class="w3-ul w3-white w3-center w3-opacity w3-hover-opacity-off">
          <li class="w3-dark-grey w3-xlarge w3-padding-32">Digital Marketing</li>
          <li class="w3-padding-16">Search Engine Optimization</li>
          <li class="w3-padding-16">Social Media Marketing</li>
          <li class="w3-padding-16">Graphic Designing</li>
          <li class="w3-light-grey w3-padding-24">
            <button class="w3-button w3-white w3-padding-large w3-hover-black">Sign Up</button>
          </li>
        </ul>
      </div>
    <!-- End Grid/Pricing tables -->
    </div>
    <h3 class="w3-padding-24 w3-text-light-grey">My Reputation</h3>
    <p>
      <strong>About Me/Us Section:</strong> Include a dedicated section on your website that provides an overview of who you are or your company's values and principles. This section can highlight your commitment to professionalism, integrity, and excellence.

      </P>
    <!-- Testimonials -->
    
    <!--
    <h3 class="w3-padding-24 w3-text-light-grey">My Reputation</h3>  
    <img src="https://www.w3schools.com/w3images/bandmember.jpg" alt="Avatar" class="w3-left w3-circle w3-margin-right" style="width:80px">
    <p><span class="w3-large w3-margin-right">Chris Fox.</span> CEO at Mighty Schools.</p>
    <p>John Doe saved us from a web disaster.</p><br>
    
    <img src="https://www.w3schools.com/w3images/avatar_g2.jpg" alt="Avatar" class="w3-left w3-circle w3-margin-right" style="width:80px">
    <p><span class="w3-large w3-margin-right">Rebecca Flex.</span> CEO at Company.</p>
    <p>No one is better than John Doe.</p>-->
  <!-- End About Section -->
  </div>
  
  <!-- Portfolio Section -->
  <div class="w3-padding-64 w3-content" id="photos">
    <h2 class="w3-text-light-grey">My Photos</h2>
    <hr style="width:200px" class="w3-opacity">

    <!-- Grid for photos -->
    <div class="w3-row-padding" style="margin:0 -16px">
      <div class="w3-half">
        <img src="./Images/cafe.jpg" style="width:100%">
        <img src="./Images/DSC_0270.jpg" style="width:100%">
        <img src="./Images/Shirdi.jpg" style="width:100%">
      </div>

      <div class="w3-half">
        <img src="./Images/IMG-20170806-WA0062.jpg" style="width:100%">
        <img src="./Images/IMG-20220504-WA0000.jpg" style="width:100%">
        <img src="./Images/IMG_20180115_093907.jpg" style="width:100%">
        <img src="./Images/IMG_20180116_120708.jpg" style="width:100%">
      </div>

      <div class="w3-row-padding" style="margin:0 -16px">
      <div class="w3-half">
        <img src="./Images/IMG_20230723_165615" style="width:100%">
        <img src="./Images/IMG_2207.jpg" style="width:100%">
        <img src="./Images/IMG_5603-1.jpg" style="width:100%">
        <img src="./Images/Images/IMG_9048.jpg" style="width:100%">
      </div>

      <div class="w3-half">
        <img src="./Images/IMG-20170806-WA0045.jpg" style="width:100%">
        <img src="./Images/Images/IMG_9060.jpg" style="width:100%">
        <img src="./Images/Images/IMG_9067.jpg" style="width:100%">
        <img src="./Images/Images/IMG_9224.jpg" style="width:100%">
        <img src="./Images/Screenshot_20220...tos.jpg" style="width:100%">
        <img src="./Images/Mall.png" style="width:100%">
      </div>

    <!--  <div class="w4-half">
        <img src="./Images/IMG_20230723_165615.jpg" style="width:100%">
        <img src="./Images/IMG_2207.jpg" style="width:100%">
        <img src="./Images/IMG_5603-1.jpg" style="width:100%">
        <img src="./Images/IMG_9048.jpg" style="width:100%">
      </div>

      <div class="w4-half">
        <img src="./Images/IMG_9060.jpg" style="width:100%">
        <img src="./Images/IMG_9067.jpg" style="width:100%">
        <img src="./Images/IMG_9224.jpg" style="width:100%">
        <img src="./Images/Mall.png" style="width:100%">
        <img src="./Images/Screenshot_20220...tos.jpg" style="width:100%">
        <img src="./Images/IMG-20170806-WA0045.jpg" style="width:100%">
      </div>-->
    <!-- End photo grid -->
    </div>
  <!-- End Portfolio Section -->
  </div>

  <!-- Contact Section -->
  <div class="w3-padding-64 w3-content w3-text-grey" id="contact">
    <h2 class="w3-text-light-grey">Contact Me</h2>
    <hr style="width:200px" class="w3-opacity">

    <div class="w3-section">
      <p><i class="fa fa-map-marker fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Pune</p>
      <p><i class="fa fa-phone fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Phone: 7028148584</p>
      <p><i class="fa fa-envelope fa-fw w3-text-white w3-xxlarge w3-margin-right"> </i> Email: info.iandme@gmail.com</p>
    </div><br>
    <p>Let's get in touch. Send me a message:</p>

    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Email" required name="Email"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Subject" required name="Subject"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Message" required name="Message"></p>
      <p>
        <button class="w3-button w3-light-grey w3-padding-large" type="submit">
          <i class="fa fa-paper-plane"></i> SEND MESSAGE
        </button>
      </p>
    </form>
  <!-- End Contact Section -->
  </div>
  
<!-- Footer. This section contains an ad for W3Schools Spaces. You can leave it to support us. -->
<footer class="w3-content w3-padding-64 w3-text-grey w3-xlarge">
  <i class="fa fa-facebook-official w3-hover-opacity"></i>
  <i class="fa fa-instagram w3-hover-opacity"></i>
  <i class="fa fa-snapchat w3-hover-opacity"></i>
  <i class="fa fa-pinterest-p w3-hover-opacity"></i>
  <i class="fa fa-twitter w3-hover-opacity"></i>
  <i class="fa fa-linkedin w3-hover-opacity"></i>
 <p class="w3-small">This website was made with W3schools Spaces. Make your own free website today!</p>
 <a class="w3-button w3-round-xxlarge w3-small w3-light-grey" href="#contact" target="_blank">Start now</a> 
 <!-- End footer -->
</footer>

<!-- END PAGE CONTENT -->
</div>

</body>
</html>
