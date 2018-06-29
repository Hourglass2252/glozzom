<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.13/css/all.css" integrity="sha384-DNOHZ68U8hZfKXOrtjWvjxusGo9WQnrNx2sqG0tfsghAvtVlRW3tvkXWZh58N9jp"
    crossorigin="anonymous">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css" integrity="sha384-WskhaSGFgHYWDcbwN70/dfYBj47jz9qbsMId/iRN3ewGhXQFZCSftd1LZCfmhktB"
    crossorigin="anonymous">
  <link rel="stylesheet" href="css\style.css">
  <title>Glozzom</title>
</head>

<body>
  <!-- NAVBAR -->
  <nav class="navbar navbar-expand-sm navbar-dark bg-dark">
    <div class="container">
      <a href="index.html" class="navbar-brand">Glozzom</a>
      <button class="navbar-toggler" data-toggle="collapse" data-target="#navbarCollapse">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarCollapse">
        <ol class="navbar-nav ml-auto">
          <li class="nav-item active">
            <a href="index.html" class="nav-link">Home</a>
          </li>
          <li class="nav-item">
            <a href="about.html" class="nav-link">About Us</a>
          </li>
          <li class="nav-item">
            <a href="services.html" class="nav-link">Services</a>
          </li>
          <li class="nav-item">
            <a href="blog.html" class="nav-link">Blog</a>
          </li>
          <li class="nav-item">
            <a href="contact.html" class="nav-link">Contact</a>
          </li>
        </ol>
      </div>
    </div>
  </nav>

  <!-- SHOWCASE SLIDER -->
  <section id="showcase">
    <div id="myCarousel" class="carousel slide" data-ride="carousel">
      <ol class="carousel-indicators">
        <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
        <li data-target="#myCarousel" data-slide-to="1"></li>
        <li data-target="#myCarousel" data-slide-to="2"></li>
      </ol>
      <div class="carousel-inner">
        <div class="carousel-item carousel-img-1 active">
          <div class="container">
            <div class="carousel-caption d-none d-sm-block text-right mb-5">
              <h1 class="display-3">Heading One</h1>
              <p class="lead">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Culpa at voluptatem veniam molestiae officia corporis eius totam aliquid optio similique.</p>
              <a href="#" class="btn btn-danger btn-lg">Sign Up Now</a>
            </div>
          </div>
        </div>

      <div class="carousel-item carousel-img-2">
        <div class="container">
          <div class="carousel-caption d-none d-sm-block mb-5">
            <h1 class="display-3">Heading Two</h1>
            <p class="lead">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Culpa at voluptatem veniam molestiae officia corporis eius totam aliquid optio similique.</p>
            <a href="#" class="btn btn-primary btn-lg">Learn More</a>
          </div>
        </div>
      </div>
      <div class="carousel-item carousel-img-3">
        <div class="container">
          <div class="carousel-caption d-none d-sm-block text-right mb-5">
            <h1 class="display-3">Heading Three</h1>
            <p class="lead">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Culpa at voluptatem veniam molestiae officia corporis eius totam aliquid optio similique.</p>
            <a href="#" class="btn btn-success btn-lg">Learn Mores</a>
          </div>
        </div>
      </div>
     </div>
     <a href="#myCarousel" data-slide="prev" class="carousel-control-prev">
       <span class="carousel-control-prev-icon"></span>
     </a>
     <a href="#myCarousel" data-slide="next" class="carousel-control-next">
       <span class="carousel-control-next-icon"></span>
     </a>
    </div>
  </section>

  <!-- HOME ICON SECTION -->
  <section id="home-icons" class="py-5">
    <div class="container">
      <div class="row">
        <div class="col-md-4 mb-4 text-center">
          <i class="fas fa-cog fa-3x mb-2"></i>
          <h3>Turning Gears</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Id, molestiae.</p>
        </div>
        <div class="col-md-4 mb-4 text-center">
          <i class="fas fa-cloud fa-3x mb-2"></i>
          <h3>Sending Data</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Id, molestiae.</p>
        </div>
        <div class="col-md-4 mb-4 text-center">
          <i class="fas fa-cart-plus fa-3x mb-2"></i>
          <h3>Making Money</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Id, molestiae.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- HOME HEADING SECTION -->
  <section id="home-heading" class="p-5">
    <div class="dark-overlay">
      <div class="row">
        <div class="col">
          <div class="container pt-5">
            <h1>Are You Ready to Get Started</h1>
            <p class="d-none d-md-block">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ex libero unde deserunt amet voluptate eaque dolores et est, quas laudantium maxime quam ipsum, fuga doloribus.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- INFO SECTION -->

  <section id="info" class="py-3">
    <div class="container">
      <div class="row">
        <div class="col-md-6 align-self-center">
          <h3>Lorem ipsum.</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima ea mollitia nobis, vero, harum totam provident in possimus laudantium officiis illum unde perspiciatis quo fuga.</p>
          <a href="about.html" class="btn btn-outline-danger btn-lg">Learn More</a>
        </div>
        <div class="col-md-6">
          <img src="../img/laptop.png" alt="" class="img-fluid">
        </div>
      </div>
    </div>
  </section>

<!-- VIDEO SECTION -->
<section id="video-play">
  <div class="dark-overlay">
    <div class="row">
      <div class="col">
        <container class="p-5">
          <a href="#" class="video" data-video="https://www.youtube.com/embed/ZXsQAXx_ao0"
            data-toggle="modal" data-target="#videoModal">
              <i class="fas fa-play fa-3x my-3"></i>
            </a>
            <h1>See What We Do</h1>
        </container>
      </div>
    </div>
  </div>
</section>

<!-- VIDEO MODAL -->
  <div class="modal fade" id="videoModal">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-body">
          <button class="close" data-dismiss="modal">
            <span>&times;</span>
          </button>
          <iframe src="" frameborder="0" height="250" width="100%" allowfullscreen></iframe>
        </div>
      </div>
    </div>
  </div>



  <script src="http://code.jquery.com/jquery-3.3.1.min.js" integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8="
    crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49"
    crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/js/bootstrap.min.js" integrity="sha384-smHYKdLADwkXOn1EmN1qk/HfnUcbVRZyYmZ4qpPea6sjB/pTJ0euyQp0Mk8ck+5T"
    crossorigin="anonymous"></script>

  <script>
    // Get the current year for the copyright
    $('#year').text(new Date().getFullYear());

  // CONFIGURE SLIDER
  $('.carousel').carousel({
    interval: 6000,
    pause: 'hover',
  });

  $(function() {
      $(".video").click(function () {
        var theModal = $(this).data("target"),
        videoSRC = $(this).attr("data-video"),
        videoSRCauto = videoSRC + "?modestbranding=1&rel=0&controls=0&showinfo=0&html5=1&autoplay=1";
        $(theModal + ' iframe').attr('src', videoSRCauto);
        $(theModal + ' button.close').click(function () {
          $(theModal + ' iframe').attr('src', videoSRC);
        });
      });
    });
  </script>
</body>

</html>
