# sagarhtml
<!DOCTYPE html>
<html lang="en">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Oswald">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open Sans">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
</head>
<title>Book Store </title>
<link rel="shortcut icon" href="image/book.jpg" />
<style>
h1,h2,h3,h4,h5,h6 {font-family: "Oswald"}
body {font-family: "Open Sans"}
.img{
  height:30px;
  width:30px;
}
.jumbotron {
      background-image: url("image/book.jpg");
      color: #fff;
	  height: 500px;
  }
  .carousel-control.right, .carousel-control.left {
     background-image: none;
     color: #f4511e;
  }
  .carousel-indicators li {
      border-color: #f4511e;
  }
  .carousel-indicators li.active {
      background-color: #f4511e;
  }
  .item h4 {
      font-size: 19px;
      line-height: 1.375em;
      font-weight: 400;
      font-style: italic;
      margin: 70px 0;
  }
  .item span {
      font-style: normal;
  }
  @media screen and (max-width: 768px) {
    .col-sm-4 {
      text-align: center;
      margin: 25px 0;
    }
  }
   .navbar {
      margin-bottom: 0;
      background-color: #f4511e;
      z-index: 9999;
      border: 0;
      font-size: 12px !important;
      line-height: 1.42857143 !important;
      letter-spacing: 4px;
      border-radius: 0;
	  
  }
  .navbar li a, .navbar .navbar-brand {
      color: #fff !important;
  }
  .navbar-nav li a:hover, .navbar-nav li.active a {
      color: #f4511e !important;
      background-color: #fff !important;
  }
  .navbar-default .navbar-toggle {
      border-color: transparent;
      color: #fff !important;
  }
  .list{
    margin-right: 20px;
  }
  .container{
     background-color: #fff ;
	 width: 100%;
  }

</style>
<body>
<body class="w3-light-grey">

<!-- Navigation bar with social media icons -->

<nav class="navbar navbar-default navbar-fixed-top">
<div class="w3-bar w3-black w3-hide-small">
  <div class="collapse navbar-collapse" id="myNavbar">
  <a href="index.htm" class="w3-bar-item w3-button"><img class="img" src="image/book.jpg"></a>
  <ul class="nav navbar-nav navbar-right">
   <li class="list"><a href="index.htm">HOME<span class="sr-only">(current)</span></a></li>
        <li class="list"><a href="#about">ABOUT</a></li>
        <li class="list"><a href="#service">SERVICES</a></li>
        <li class="list"><a href="#contact">CONTACT</a></li>
      </ul>
	  </div>
</div>
</nav>
<div class="w3-content" style="max-width:1600px">

  <!-- Header -->
  <header class="w3-container w3-center w3-padding-48 w3-white">
    <h1 class="w3-xxxlarge"><b>Welcome to my Book Store</b></h1>
    <h6>Designed by:<span class="w3-tag">Sagar Basnet</span></h6>
  </header>
  <!-- image header --> 
  <div class="jumbotron text-center">
  
  <h1>BOOK STORE</h1> 
  <p>Get your books</p> 
  <form class="form-inline">
    <div class="input-group">
      <input type="email" class="form-control" size="50" placeholder="Email Address" required>
      <div class="input-group-btn">
        <button type="button" class="btn btn-danger">Subscribe</button>
      </div>
	  
    </div>
	<br>
	<br>
	<br>
	
	<button type="button" class="btn btn-info btn-lg" data-toggle="modal" data-target="#myModal">Login</button>

  </form>
</div>
 <h2><center>What our admin says</center></h2>
 <hr style=" size:20px"">
  <div id="myCarousel" class="carousel slide text-center" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner" role="listbox">
      <div class="item active">
        <h4>"This site is the best. It provides u usuable books!"<br><span>Sagar Basnet, Admin</span></h4>
      </div>
      <div class="item">
        <h4>"One word... WOW!!"<br><span>Siddhartha Karki,Editor</span></h4>
      </div>
      <div class="item">
        <h4>"Best site for books"<br><span>Luvina Sharma, Editor</span></h4>
      </div>
    </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div>

 </div>
 <!-- Container (The Band Section) -->
<div id="about" class="container text-center">
  <h3>ABOUT US</h3>
  <p><em>We provide all of the books for your courses!</em></p>
  <hr style=" size:20px"">
  
  <br>
  <div class="row">
    <div class="col-sm-4">
      <p class="text-center"><strong>Sagar Basnet</strong></p><br>
      <a href="#demo" data-toggle="collapse">
        <img src="image/sagar.jpg" class="img-circle person" alt="Random Name" width="255" height="255">
      </a>
	  <br>
	  <br>
      <div id="demo" class="collapse">
        <p>Leader Admin</p>
        <p>B.Sc.CSIT Student</p>
        <p>Admin since 2017</p>
      </div>
    </div>
    <div class="col-sm-4">
      <p class="text-center"><strong>Siddhartha Karki</strong></p><br>
      <a href="#demo2" data-toggle="collapse">
        <img src="image/sid.jpg" class="img-circle person" alt="Random Name" width="255" height="255">
      </a>
	  <br>
	  <br>
      <div id="demo2" class="collapse">
        <p>Co-leader Admin</p>
        <p>B.Sc.CSIT Student</p>
        <p>Admin since 2017</p>
      </div>
    </div>
    <div class="col-sm-4">
      <p class="text-center"><strong>Luvina Sharma</strong></p><br>
      <a href="#demo3" data-toggle="collapse">
        <img src="image/luvi.jpg" class="img-circle person" alt="Random Name" width="255" height="255">
      </a>
	  <br>
	  <br>
      <div id="demo3" class="collapse">
        <p>Co-leader Admin</p>
        <p>B.Sc.CSIT Student</p>
        <p>Admin since 2017</p>
      </div>
    </div>
  </div>
</div>
 <!-- services -->
 <div id="service" class="services">
 <h2><center> Available Books</center></h2>
  <div class="row">
    <div class="col-md-4">
      <div class="thumbnail">
        <a href="image/book3.jpg" target="_blank">
          <img src="image/book3.jpg" alt="Lights" style="width:100%">
          <div class="caption">
            <p>Lorem ipsum donec id elit non mi porta gravida at eget metus.</p>
          </div>
        </a>
      </div>
    </div>
    <div class="col-md-4">
      <div class="thumbnail">
        <a href="image/book4.png" target="_blank">
          <img src="image/book4.png" alt="Nature" style="width:100%">
          <div class="caption">
            <p>Lorem ipsum donec id elit non mi porta gravida at eget metus.</p>
          </div>
        </a>
      </div>
    </div>
    <div class="col-md-4">
      <div class="thumbnail">
        <a href="image/book5.jpg" target="_blank">
          <img src="image/book5.jpg" alt="Fjords" style="width:100%">
          <div class="caption">
            <p>Lorem ipsum donec id elit non mi porta gravida at eget metus.</p>
          </div>
        </a>
      </div>
    </div>
  </div>
</div>
</div>
<!-- Container (Contact Section) -->
<div id="contact" class="container">
  <h3 class="text-center">Contact</h3>
  <p class="text-center"><em>Want update for Books!</em></p>

  <div class="row">
    <div class="col-md-4">
      <p>Need Books? Drop a note.</p>
      <p><span class="glyphicon glyphicon-map-marker"></span>Biratnagar-01, Morang, Nepal</p>
      <p><span class="glyphicon glyphicon-phone"></span>Phone: +9779816732840</p>
      <p><span class="glyphicon glyphicon-envelope"></span>Email: sagarbasnet1000@gmail.com</p>
    </div>
    <div class="col-md-8">
      <div class="row">
        <div class="col-sm-6 form-group">
          <input class="form-control" id="name" name="name" placeholder="Name" type="text" required>
        </div>
        <div class="col-sm-6 form-group">
          <input class="form-control" id="email" name="email" placeholder="Email" type="email" required>
        </div>
      </div>
      <textarea class="form-control" id="comments" name="comments" placeholder="Comment" rows="5"></textarea>
      <br>
      <div class="row">
        <div class="col-md-12 form-group">
          <button class="btn pull-right" type="submit">Send</button>
        </div>
      </div>
    </div>
  </div>
  <!-- popup model for sign up -->
  

  <!-- Modal -->
  <div class="modal fade" id="myModal" role="dialog">
    <div class="modal-dialog">
    
      <!-- Modal content-->
      <div class="modal-content">
        <div class="modal-header" style="padding:35px 50px;">
          <button type="button" class="close" data-dismiss="modal">&times;</button>
          <h4><span class="glyphicon glyphicon-lock"></span> Login</h4>
        </div>
        <div class="modal-body" style="padding:40px 50px;">
          <form role="form">
            <div class="form-group">
              <label for="usrname"><span class="glyphicon glyphicon-user"></span> Username</label>
              <input type="text" class="form-control" id="usrname" placeholder="Enter email">
            </div>
            <div class="form-group">
              <label for="psw"><span class="glyphicon glyphicon-eye-open"></span> Password</label>
              <input type="text" class="form-control" id="psw" placeholder="Enter password">
            </div>
            <div class="checkbox">
              <label><input type="checkbox" value="" checked>Remember me</label>
            </div>
              <button type="submit" class="btn btn-success btn-block"><span class="glyphicon glyphicon-off"></span> Login</button>
          </form>
        </div>
        <div class="modal-footer">
          <button type="submit" class="btn btn-danger btn-default pull-left" data-dismiss="modal"><span class="glyphicon glyphicon-remove"></span> Cancel</button>
          <p>Not a member?  <button type="button" class="btn btn-info btn-lg" data-toggle="modal" data-target="#myModals">Sign Up</button>

          <p>Forgot <a href="#">Password?</a></p>
        </div>
      </div>
      
    </div>
  </div> 
</div>
 
<script>
$(document).ready(function(){
    $("#myBtn").click(function(){
        $("#myModal").modal();
    });
});

</script>
<div class="container">
   <!-- Modal -->
  <div class="modal fade" id="myModals" role="dialog">
    <div class="modal-dialog">
    
      <!-- Modal content-->
      <div class="modal-content">
        <div class="modal-header">
          <button type="button" class="close" data-dismiss="modal">&times;</button>
          <h4 class="modal-title">Modal Header</h4>
        </div>
        <div class="modal-body">
          <p>Some text in the modal.</p>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
        </div>
      </div>
      
    </div>
  </div>
  

<div class="footer" style="width:100%">
<footer style="background-color:black;color:white;height:30px;">
<p><center>copyright @ www.bookstore.com</center></p>
</footer>
   
   
</div>
</body>
</html>
