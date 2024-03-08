# hackthon-project



project title;-  travel and toursium.

project number:-  32.



<!DOCTYPE html>
<html>
<head>
  <!-- Link to the CSS file -->
  <link rel="stylesheet" href="styles.css">
  <!-- Add a title for the website -->
  <title>Student Innovation Travel & Tourism Software</title>
</head>
<body>
  <!-- Create a header for the website -->
  <header>
    <!-- Add a logo for the website -->
    <img src="https://tse3.mm.bing.net/th?id=OIP.kXCVab42euiDk2mReUSSoQHaHa&pid=Api&P=0&h=180" alt="Logo" id="logo">
    <!-- Add a navigation menu for the website -->
    <nav>
      <ul>
        <!-- Add links to other pages of the website -->
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="blog.html">Blog</a></li>
      </ul>
    </nav>
    <!-- Remove the login and search button from the header -->
  </header>
  <!-- Create a main section for the website -->
  <main>
    <!-- Add a banner for the website -->
    <div id="banner">
      <!-- Add a headline for the website -->
      <h1>Student Innovation Travel & Tourism Software</h1>
      <!-- Add a subheading for the website -->
      <h2>A solution/idea that can boost the current situation of the tourism industries</h2>
    </div>
    <!-- Add the login and search button below the banner -->
    <div id="login-search">
      
      <input type="text" id="search" placeholder="Search...">
      <button id="login">search</button>
    </div>
    <!-- Add a content section for the website -->
    <div id="content">
      <!-- Add a paragraph for the website -->
      <p>Welcome to our website, where we showcase our innovative software that can help the tourism industries, including hotels, travel, and others. Our software is designed by students who are passionate about travel and technology. We aim to provide a platform that connects travelers with the best destinations, experiences, and services. We also offer information about all the tourism and some places to visit, which you can access by clicking on the images below.</p>
      <!-- Add a grid of images for the website -->
      <div id="content">
        <!-- Add a paragraph for the website -->
        <p>Welcome to our website, where we showcase our innovative software that can help the tourism industries, including hotels, travel, and others. Our software is designed by students who are passionate about travel and technology. We aim to provide a platform that connects travelers with the best destinations, experiences, and services. We also offer information about all the tourism and some places to visit, which you can access by clicking on the images below.</p>
        <!-- Add a grid of images for the website -->
        <div id="grid">
          <!-- Add an image for each place to visit -->
          <div class="image">
            <img src="https://tse4.mm.bing.net/th?id=OIP.4ZbTNT7QGrXXwgyXCOw2_AHaE8&pid=Api&P=0&h=180" alt="Paris" target="_blank">
            <a href="https://en.wikipedia.org/wiki/Tirupati">tirupathi</a>
          </div>
          <div class="image">
            <img src="https://tse2.mm.bing.net/th?id=OIP.IbhyiMHJsmWBJKtES_b7UwHaFj&pid=Api&P=0&h=180" alt="New York"  target="_blank">
            <a href="https://r.search.yahoo.com/_ylt=Awr1QYShY.tlfmgZ.gW7HAx.;_ylu=Y29sbwNzZzMEcG9zAzEEdnRpZAMEc2VjA3Ny/RV=2/RE=1709954081/RO=10/RU=https%3a%2f%2fen.wikipedia.org%2fwiki%2fPadmanabhaswamy_Temple/RK=2/RS=TX7v53yI99rxFD3l7BHivuq6tYk-">padmanabhaswamy temple</a>
          </div>
          <div class="image">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d1/Ram_Janmbhoomi_Mandir%2C_Ayodhya_Dham.jpg/417px-Ram_Janmbhoomi_Mandir%2C_Ayodhya_Dham.jpg" alt="Tokyo">
            <a href="https://en.wikipedia.org/wiki/Ayodhya"  target="_blank">ayodhya</a>
          </div>
          <div class="image">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/94/The_Golden_Temple_of_Amrithsar_7.jpg/330px-The_Golden_Temple_of_Amrithsar_7.jpg" alt="Sydney">
            <a href="https://en.wikipedia.org/wiki/Golden_Temple"  target="_blank">golden temple</a>
          </div>
        </div>
      </div>
  
  </main>
  <!-- Create a footer for the website -->
  <footer>
    <!-- Add some information for the website -->
    <p>© 2024 Student Innovation Travel & Tourism Software. All rights reserved.</p>
    <!-- Add some social media links for the website -->
    <div id="social">
      <a href="https://www.facebook.com"><img src="facebook.png" alt="Facebook"></a>
      <a href="https://www.twitter.com"><img src="twitter.png" alt="Twitter"></a>
      <a href="https://www.instagram.com"><img src="instagram.png" alt="Instagram"></a>
    </div>
  </footer>
</body>
</html>






     css code





     /* Style the body of the website */
body {
    background-image: url('http://www.pixelstalk.net/wp-content/uploads/2016/08/Desktop-Best-And-Website-background-2560x1600.jpg'); /* Replace 'background-image.jpg' with the path to your background image */
    background-size: cover; /* Cover the entire background */
    background-repeat: no-repeat; /* Do not repeat the background image */
    background-position: center; /* Center the background image */
    color: #333; /* Text color for better readability on the background image */
    font-family: Arial, sans-serif; /* Choose an appropriate font-family */
}

.login{
    border: 1px solid black;
    width: 400px;
    height: 500px;
    background: url('http://www.pixelstalk.net/wp-content/uploads/2016/08/Desktop-Best-And-Website-background-2560x1600.jpg');
    color: white;
    border-radius: 20px;
    box-shadow: 0px 0px 20px 5px rgba(0, 0, 0, 0.75);
    background-size: cover;
    background-position: center;
    overflow: hidden;
    
}
/* Style the login and search button of the website */
#login-search {
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 20px;
    padding: 10px;
  }
  
  /* Style the login button of the website */
  #login {
    width: 80px;
    height: 40px;
    background-color: #04AA6D;
    border: none;
    border-radius: 5px;
    color: white;
    font-weight: bold;
    cursor: pointer;
    margin-right: 10px;
  }
  
  /* Style the login button on hover of the website */
  #login:hover {
    background-color: #03a55a;
  }
  
  /* Style the search input of the website */
  #search {
    width: 150px; /* Reduce the width */
    height: 20px; /* Reduce the height */
    padding: 5px;
    border: 1px solid #ccc;
    border-radius: 5px;
  }
  
  /* Make the search bar responsive using media queries */
  @media (max-width: 600px) {
    /* Stack the login and search button vertically */
    #login-search {
      flex-direction: column;
    }
  
    /* Add some margin and padding for the login and search button */
    #login {
      margin: 10px;
      padding: 10px;
    }
  
    #search {
      margin: 10px;
      padding: 10px;
    }
  }
  

form{
    display: block;
    box-sizing: border-box;
    padding: 40px;
    width: 100%;
    height: 100%;
    backdrop-filter: brightness(40%);
    display: flex;
    flex-direction: column;
    gap: 5px;
}
h1{
    font-weight: normal;
    font-size: 24px;
    text-shadow: 0px 0px 2px rgba(0, 0, 0, 0.5);
    margin-bottom: 60px;
}
label{
    color: rgba(255, 255, 255, 0.8);
    text-transform: uppercase;
    font-size: 10px;
    letter-spacing: 2px;
    padding-left: 10px;
}
input{
    background : rgba(255, 255, 255, 0.3);
    height: 40px;
    line-height: 40px;
    border-radius: 20px;
    padding: 0px 20px;
    border: none;
    margin-bottom: 20px;
    color: white;
}
button{
    background: rgb(45,126,231);
    height: 40px;
    line-height: 40px;
    border-radius: 40px;
    border: none;
    margin: 10px 0px;
    box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.3);
    color: white;
    font-size: 12px;
    text-transform: uppercase;
}
body {
    margin: 0;
    font-family: Arial, sans-serif;
  }
  
  /* Style the header of the website */
  header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: #333;
    color: white;
    padding: 10px;
  }
  
  /* Style the logo of the website */
  #logo {
    width: 100px;
    height: 100px;
  }
  
  /* Style the navigation menu of the website */
  nav {
    display: flex;
  }
  
  /* Style the navigation menu list of the website */
  nav ul {
    display: flex;
    list-style: none;
    margin: 0;
    padding: 0;
  }
  
  /* Style the navigation menu list items of the website */
  nav li {
    margin: 10px;
  }
  
  /* Style the navigation menu links of the website */
  nav a {
    color: white;
    text-decoration: none;
  }
  
  /* Change the color of links on hover */
  nav a:hover {
    color: #04AA6D;
  }
  
  /* Style the login and search button of the website */
  #login-search {
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 20px;
    padding: 10px;
  }
  
  /* Style the login button of the website */
  #login {
    width: 80px;
    height: 40px;
    background-color: #04AA6D;
    border: none;
    border-radius: 5px;
    color: white;
    font-weight: bold;
    cursor: pointer;
    margin-right: 10px;
  }
  
  /* Style the login button on hover of the website */
  #login:hover {
    background-color: #03a55a;
  }
  
  /* Style the search input of the website */
  #search {
    width: 150px; /* Reduce the width */
    height: 20px; /* Reduce the height */
    padding: 5px;
    border: 1px solid #ccc;
    border-radius: 5px;
  }
  
  /* Style the banner of the website */
  #banner {
    background-image: url("banner.jpg");
    background-size: cover;
    background-position: center;
    height: 500px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  
  /* Style the headline of the website */
  h1 {
    color: white;
    font-size: 48px;
    text-shadow: 2px 2px 4px black;
  }
  
  /* Style the subheading of the website */
  h2 {
    color: white;
    font-size: 24px;
    text-shadow: 2px 2px 4px black;
  }
  
  /* Style the content section of the website */
  #content {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
  }
  
  /* Style the paragraph of the website */
  p {
    font-size: 18px;
    line-height: 1.5;
  }
  
  /* Style the grid of images of the website */
  #grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-gap: 20px;
  }
  
  /* Style the image of the website */
  .image {
    position: relative;
  }
  
  /* Style the image link of the website */
  .image a {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    background-color: rgba(0,0,0,0.5);
    color: white;
    text-align: center;
    padding: 10px;
    text-decoration: none;
  }
  
  /* Style the image link on hover of the website */
  .image a:hover {
    background-color: rgba(0,0,0,0.8);
  }
  
  /* Style the footer of the website */
  footer {
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: #333;
    color: white;
    padding: 10px;
  }
  
  /* Style the social media links of the website */
  #social {
    display: flex;
  }
  
  /* Style the social media links of the website */
  #social a {
    margin: 10px;
  }
  
  /* Style the social media images of the website */
  #social img {
    width: 30px;
    height: 30px;
  }
  
  /* Make the website responsive using media queries */
  @media (max-width: 600px) {
    /* Change the grid of images to one column */
    #grid {
      grid-template-columns: 1fr;
    }}
  
    /* Reduce the size of the logo */
    #logo {
      width: 50px;
      height: 50px;
    }
  
    /* Reduce the size of the headline and subheading */
    h1 {
      font-size: 36px;
    }
  
    h2 {
      font-size: 18px;
    }
  
    /* Reduce the size of the login and search button */
    #login {
      width: 60px;
      height: 30px;
    }
  
    #search {
      width: 100px; /* Reduce the width */
      height: 15px; /* Reduce the height */
      padding: 5px;}
  /* Define the fade animation */
@keyframes fade {
    0% { opacity: 0; }
    50% { opacity: 1; }
    100% { opacity: 0; }
  }
  
  /* Apply the animation to the images */
  .image img {
    animation: fade 4s infinite;
  }
  
  /* Add some delay for each image */
  .image:nth-child(1) img {
    animation-delay: 0s;
  }
  
  .image:nth-child(2) img {
    animation-delay: 1s;
  }
  
  .image:nth-child(3) img {
    animation-delay: 2s;
  }
  
  .image:nth-child(4) img {
    animation-delay: 3s;
  }
  /* Style the body of the website */
body {
    margin: 0;
    font-family: Arial, sans-serif;
  }
  
  /* Style the header of the website */
  header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: #333;
    color: white;
    padding: 10px;
  }
  
  /* Style the logo of the website */
  #logo {
    width: 100px;
    height: 100px;
  }
  /* Style the login and search button of the website */
#login-search {
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 20px;
    padding: 10px;
  }
  
  /* Style the login button of the website */
  #login {
    width: 80px;
    height: 40px;
    background-color: #04AA6D;
    border: none;
    border-radius: 5px;
    color: white;
    font-weight: bold;
    cursor: pointer;
    margin-right: 10px;
  }
  
  /* Style the login button on hover of the website */
  #login:hover {
    background-color: #03a55a;
  }
  
  /* Style the search input of the website */
  #search {
    width: 150px; /* Reduce the width */
    height: 20px; /* Reduce the height */
    padding: 5px;
    border: 1px solid #ccc;
    border-radius: 5px;
  }
  
  /* Make the search bar responsive using media queries */
  @media (max-width: 600px) {
    /* Stack the login and search button vertically */
    #login-search {
      flex-direction: column;
    }
  
    /* Add some margin and padding for the login and search button */
    #login {
      margin: 10px;
      padding: 10px;
    }
  
    #search {
      margin: 10px;
      padding: 10px;
    }
  }
  
  
  /* Style the navigation menu of the website */
  nav {
    display: flex;
  }
  
  /* Style the navigation menu list of the website */
  nav ul {
    display: flex;
    list-style: none;
    margin: 0;
    padding: 0;
  }
  
  /* Style the navigation menu list items of the website */
  nav li {
    margin: 10px;
  }
  
  /*
