TinDog Starting Files
<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>TinDog</title>

  <!-- CDN links for adding bootstrap -->

  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/css/bootstrap.min.css" integrity="sha384-B0vP5xmATw1+K9KRQjQERJvTumQW0nPEzvF6L/Z6nronJ3oUOFUFpCjEUQouq2+l" crossorigin="anonymous">
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-Piv4xVNRyMGpqkS2by6br4gNJ7DXjqk09RmUpJ8jgGtD7zP9yug3goQfGII0yAns" crossorigin="anonymous"></script>
  
  <!-- css stylesheet link -->
  
  <link rel="stylesheet" href="css/styles.css">

  <!-- cdn link of site font awesome for icons at the download buttons -->

  <script src="https://kit.fontawesome.com/c5329c5b20.js" crossorigin="anonymous"></script>

  <!-- Google fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@900&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Lilita+One&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Ubuntu&display=swap" rel="stylesheet">
</head>

<body>

  <section id="title">
    <div class="container-fluid">
      <!-- Nav Bar -->

      <nav class="navbar navbar-expand-lg navbar-dark">
        <a class="navbar-brand" href="">tindog</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ml-auto">
              <li class="nav-item">
                  <a class="nav-link" href="#footer">Contact</a>
              </li>
              <li class="nav-item">
                  <a class="nav-link" href="#pricing">Pricing</a>
              </li>
              <li class="nav-item">
                  <a class="nav-link" href="#cta">Download</a>
              </li>
          </ul>
        </div>
      </nav>


      <!-- Title -->

      <div class="row">
        <div class="col-lg-6">
          <h1>Meet new and interesting dogs nearby.</h1>
          <!-- this i tag class is the code of apple icon in the download button -->
          <!-- also "download-button" in the class name is a custom class so it will be easy to add  specific padding which we may not
             want to add for other buttons in th future by using btn class -->
          <button type="button" class ="btn btn-dark btn-lg download-button"> <i class="fa-brands fa-apple"></i> Download</button>
          <button type="button" class ="btn btn-outline-light btn-lg download-button"> <i class="fa-brands fa-google-play"></i> Download</button>
        </div>
        <div class="col-lg-6">
          <img class="title-image" src="images/iphone6.png" alt="iphone-mockup">
        </div>
      </div>
    </div>
  </section>


  <!-- Features -->

  <section id="features">

    <div class ="row">
      <!-- feature-box is a custom class for styling the css part -->
      <div class=" feature-box col-md-4">
        <i class=" icon fa-solid fa-circle-check fa-4x"></i>
        <h3> Easy to use.</h3>
        <p>So easy to use, even your dog could do it.</p>
      </div>
      <div class=" feature-box col-md-4">
        <i class=" icon fa-solid fa-bullseye fa-4x"></i>
        <h3>Elite Clientele</h3>
        <p>We have all the dogs, the greatest dogs.</p>
      </div>
      <div class=" feature-box col-md-4">
        <i class=" icon fa-solid fa-heart fa-4x"></i>
        <h3>Guaranteed to work.</h3>
        <p>Find the love of your dog's life or your money back.</p>
      </div>
    </div>
  </section>


  <!-- Testimonials -->

  <section id="testimonials">

    <div id="testimonial-carousel" class="carousel slide" data-ride="false">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <h2 class="testimonial-text">I no longer have to sniff other dogs for love. I've found the hottest Corgi on TinDog. Woof.</h2>
          <img class="testimonial-image" src="images/dog-img.jpg" alt="dog-profile">
          <em>Pebbles, New York</em>
        </div>
        <div class="carousel-item">
          <h2 class="testimonial-text">My dog used to be so lonely, but with TinDog's help, they've found the love of their life. I think.</h2>
          <img class="testimonial-image" src="images/lady-img.jpg" alt="lady-profile">
          <em>Beverly, Illinois</em>
        </div>
      </div>
      <a class="carousel-control-prev" href="#testimonial-carousel" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon"></span>
      </a>
      <a class="carousel-control-next" href="#testimonial-carousel" role="button" data-slide="next">
    <span class="carousel-control-next-icon"></span>
      </a>
    </div>
    
  </section>


  <!-- Press -->

  <section id="press">
    <img class="press-image" src="images/techcrunch.png" alt="tc-logo">
    <img class="press-image" src="images/tnw.png" alt="tnw-logo">
    <img class="press-image" src="images/bizinsider.png" alt="biz-insider-logo">
    <img class="press-image" src="images/mashable.png" alt="mashable-logo">

  </section>


  <!-- Pricing -->

  <section id="pricing">

    <h2>A Plan for Every Dog's Needs</h2>
    <p>Simple and affordable price plans for your and your dog.</p>

  <div class="row">
    <div class="pricing-column col-lg-4 col-md-6">
    <div class="card" style="width: 18rem;">
      <div class="card-header">
        <h3>Chihuahua</h3>
      </div>
      <div class="card-body">
        <h2>Free</h2>
        <p>5 Matches Per Day</p>
        <p>10 Messages Per Day</p>
        <p>Unlimited App Usage</p>
        <button class=" btn btn-lg btn-block btn-outline-dark" type="button">Sign Up</button>
      </div>
    </div>
  </div>

  <div class="pricing-column col-lg-4 col-md-6">
    <div class="card" style="width: 18rem;">
      <div class="card-header">
        <h3>Labrador</h3>
      </div>
      <div class="card-body">
        <h2>$49 / mo</h2>
        <p>Unlimited Matches</p>
        <p>Unlimited Messages</p>
        <p>Unlimited App Usage</p>
        <button class=" btn btn-lg btn-block btn-dark" type="button">Sign Up</button>
      </div>
    </div>
    </div>

    <div class="pricing-column col-lg-4">
    <div class="card" style="width: 18rem;">
      <div class="card-header">
        <h3>Mastiff</h3>
      </div>
      <div class="card-body">
        <h2>$99 / mo</h2>
        <p>Pirority Listing</p>
        <p>Unlimited Matches</p>
        <p>Unlimited Messages</p>
        <p>Unlimited App Usage</p>
        <button class=" btn btn-lg btn-block btn-dark" type="button">Sign Up</button>
      </div>
    </div>
  </div>
  </div>

  </section>


  <!-- Call to Action -->

  <section id="cta">

    <h3 class="hello">Find the True Love of Your Dog's Life Today.</h3>
    <button class="download-button btn btn-lg btn-dark" type="button"> <i class="fa-brands fa-apple"></i> Download</button>
    <button class="download-button btn btn-lg btn-light" type="button"> <i class="fa-brands fa-google-play"></i> Download</button>

  </section>


  <!-- Footer -->

  <footer id="footer">

    <i class="social-icon fa-brands fa-facebook"></i>
    <i class="social-icon fa-brands fa-twitter"></i>
    <i class="social-icon fa-brands fa-instagram"></i>
    <i class="social-icon fa-solid fa-envelope"></i>
    <p>© Copyright TinDog</p>

  </footer>

</body>

</html>
