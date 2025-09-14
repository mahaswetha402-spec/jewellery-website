
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Riddhi Siddhi Jewels</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
  <style>
    body { font-family: 'Poppins', sans-serif; }
    .navbar { background-color: #fff; box-shadow: 0 2px 5px rgba(0,0,0,0.1);}
    .hero img { height: 500px; object-fit: cover; }
    .categories img { border-radius: 50%; border: 2px solid #ccc; transition: 0.3s; }
    .categories img:hover { transform: scale(1.1); border-color: gold; }
    .product-card { border: 1px solid #eee; border-radius: 10px; transition: 0.3s; }
    .product-card:hover { transform: scale(1.02); box-shadow: 0 5px 15px rgba(0,0,0,0.1); }
    footer { background: #f8d3c6; padding: 40px 20px; }
    footer h6 { font-weight: 600; }
    .trending video { border-radius: 15px; margin: 5px; width: 200px; height: 350px; object-fit: cover; }
  </style>
</head>
<body>

<!-- Header -->
<nav class="navbar navbar-expand-lg px-4">
  <a class="navbar-brand" href="#">
    <img src="C:\Users\newba\OneDrive\文件\logo.jpg" alt="Riddhi Siddhi" height="50">
  </a>
  <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#menu">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="menu">
    <ul class="navbar-nav me-auto">
      <li class="nav-item"><a class="nav-link" href="#">Collections</a></li>
      <li class="nav-item"><a class="nav-link" href="#">Wedding</a></li>
      <li class="nav-item"><a class="nav-link" href="#">Gifting</a></li>
      <li class="nav-item"><a class="nav-link" href="#">Rings</a></li>
      <li class="nav-item"><a class="nav-link" href="#">Earrings</a></li>
    </ul>
    <form class="d-flex">
      <input class="form-control me-2" type="search" placeholder="Search for Gold, Diamond…">
      <button class="btn btn-outline-dark">Search</button>
    </form>
  </div>
</nav>

<!-- Hero Carousel -->
<div id="heroCarousel" class="carousel slide hero" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="C:\Users\newba\OneDrive\文件\banner.jpg" class="d-block w-50" alt="Jewelry Banner">
    </div>
    <div class="carousel-item">
      <img src="C:\Users\newba\OneDrive\文件\banner2.jpg" class="d-block w-50" alt="Jewelry Banner">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#heroCarousel" data-bs-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#heroCarousel" data-bs-slide="next">
    <span class="carousel-control-next-icon"></span>
  </button>
</div>

<!-- Collections -->
<div class="container text-center my-5">
  <h2>Discover Our Collections</h2>
  <div class="d-flex justify-content-center gap-4 flex-wrap categories mt-4">
    <div><img src="C:\Users\newba\OneDrive\文件\earing.jpg" width="100"><p>Earrings</p></div>
    <div><img src="C:\Users\newba\OneDrive\文件\chain.jpg" width="100"><p>Chain Pendant</p></div>
    <div><img src="C:\Users\newba\OneDrive\文件\handbag.jpg" width="100"><p>Handbags</p></div>
    <div><img src="C:\Users\newba\OneDrive\文件\bangles.jpg" width="100"><p>Bangles</p></div>
    <div><img src="C:\Users\newba\OneDrive\文件\ring.jpg" width="100"><p>Rings</p></div>
    <div><img src="C:\Users\newba\OneDrive\文件\mang.jpg" width="100"><p>Mangalsutra</p></div>
  </div>
</div>

<!-- Trending Looks -->
<div class="container my-5">
  <h2 class="mb-3">Trending Looks</h2>
  <div class="d-flex overflow-auto trending">
    <video src="look1.mp4" autoplay muted loop></video>
    <video src="look2.mp4" autoplay muted loop></video>
    <video src="look3.mp4" autoplay muted loop></video>
  </div>
</div>

<!-- Product Listing -->
<div class="container my-5">
  <h2>Necklace Sets</h2>
  <div class="row g-4 mt-3">
    <div class="col-md-3">
      <div class="product-card p-3">
        <img src="C:\Users\newba\OneDrive\文件\silver.jpg" class="w-100 mb-2">
        <h6>Silver Plated Necklace</h6>
        <p>₹233 <del>₹424</del> <span class="text-success">(45% OFF)</span></p>
        <button class="btn btn-dark w-100">Add to Cart</button>
      </div>
    </div>
    <div class="col-md-3">
      <div class="product-card p-3">
        <img src="C:\Users\newba\OneDrive\文件\rose.jpg" class="w-100 mb-2">
        <h6>Rose Gold Set</h6>
        <p>₹232 <del>₹464</del> <span class="text-success">(50% OFF)</span></p>
        <button class="btn btn-dark w-100">Add to Cart</button>
    </div>
    </div>
    <div class="container my-5">

  <div class="row g-4 mt-3">
    <div class="col-md-3">
      <div class="product-card p-3">
        <img src="C:\Users\newba\OneDrive\文件\kundan.jpg" class="w-100 mb-2">
        <h6>kundan</h6>
        <p>₹205 <del>₹324</del> <span class="text-success">(45% OFF)</span></p>
        <button class="btn btn-dark w-100">Add to Cart</button>
      </div>
    </div>
    <div class="container my-5">


    <div class="col-md-3">
      <div class="product-card p-3">
        <img src="C:\Users\newba\OneDrive\文件\pink.jpg" class="w-100 mb-2">
        <h6>Rose Gold Set</h6>
        <p>₹232 <del>₹464</del> <span class="text-success">(50% OFF)</span></p>
        <button class="btn btn-dark w-100">Add to Cart</button>
    </div>
    </div>
    <div class="container my-5">
    <!-- Add more products -->
  </div>
</div>


<!-- Footer -->
<footer class="text-center text-md-start">
  <div class="row">
    <div class="col-md-3">
      <h6>Associate With Us</h6>
      <p>Contact Us<br>Blog<br>About</p>
    </div>
    <div class="col-md-3">
      <h6>Policy Matters</h6>
      <p>Privacy<br>Terms<br>Shipping<br>Return</p>
    </div>
    <div class="col-md-3">
      <h6>Subscribe</h6>
      <input type="email" class="form-control mb-2" placeholder="Enter email">
      <button class="btn btn-dark w-100">Subscribe</button>
    </div>
    <div class="col-md-3">
      <h6>Follow Us</h6>
      <i class="fab fa-facebook fa-lg me-2"></i>
      <i class="fab fa-instagram fa-lg me-2"></i>
      <i class="fab fa-youtube fa-lg"></i>
    </div>
  </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>