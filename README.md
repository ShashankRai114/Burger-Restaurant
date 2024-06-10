<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Burger Restaurant</title>
    <link
      href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css"
      rel="stylesheet"
    />
    <link
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css"
      rel="stylesheet"
    />
    <style>
      .hero-section {
        background-image: url("burger 4.jpg");
        background-size: cover;
        background-position: center;
        color: white;
        text-align: center;
        padding: 100px 0;
      }
      .order-btn {
        background-color: red;
        border: black;
        padding: 10px 30px;
        color: white;
        font-size: 18px;
        margin-top: 20px;
        transition: 0.2s;
      }
      .our-chef,
      .best-burger,
      .big-burger,
      .statistics,
      .popular-package,
      .updates {
        padding: 50px 0;
      }
      .statistics h1 {
        font-size: 48px;
      }
      .footer {
        background-color: black;
        color: white;
        padding: 50px 0;
      }
      .navbar-custom {
        background-color: black;
        opacity: 0.65;
        padding-top: 10px;
        position: fixed;
        top: 0;
        width: 100%;
        z-index: 1000;
      }
      .navbar-custom .navbar-brand {
        color: white;
      }
      .navbar-custom .nav-link {
        color: white;
        font-size: larger;
        font-family: sans-serif;
      }
      .navbar-custom .navbar-toggler-icon {
        color: wheat;
        opacity: 100%;
      }
    </style>
  </head>
  <body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark navbar-custom">
      <div class="container">
        <a class="navbar-brand" href="#"
          ><img src="apple-touch-icon.png" alt="Logo" style="width: 40px"
        /></a>
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div
          class="collapse navbar-collapse justify-content-end"
          id="navbarNav"
        >
          <ul class="navbar-nav">
            <li class="nav-item active">
              <a class="nav-link" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Product</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Promo</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <!-- Hero Section -->
          
    <div class="hero-section">
      <div class="container">
        <h1>Get Cashback up to 50%</h1>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse
          consectetur justo eu nunc consequat.
        </p>
        <button class="order-btn">ORDER NOW</button>
      </div>
    </div>

    <!-- Our Chef Section -->
    <div class="our-chef text-center">
      <div class="container">
        <h2>Our Chef</h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus
          lacinia odio vitae vestibulum vestibulum.
        </p>
        <div class="row">
          <div class="col-md-4">
            <img src="1.jpg" class="rounded-circle" alt="Chef 1" />
            <h3>Aiden Hunter</h3>
            <p>Founder</p>
          </div>
          <div class="col-md-4">
            <img src="chef3.jpg" class="rounded-circle" alt="Chef 2" />
            <h3>Ethel Ramsey</h3>
            <p>Co-Founder</p>
          </div>
          <div class="col-md-4">
            <img src="chef333.jpg" class="rounded-circle" alt="Chef 3" />
            <h3>Fannie Stewart</h3>
            <p>Co-Founder</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Best Burger Section -->
    <div class="best-burger bg-danger text-white text-center">
      <div class="container">
        <h2>Best Burger</h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus
          lacinia odio vitae vestibulum vestibulum.
        </p>
        <img
          src="burger1.jpg"
          class="img-fluid rounded-circle"
          alt="Best Burger"
        />
        <button class="order-btn mt-3">ORDER NOW</button>
      </div>
    </div>

    <!-- Big Burger Section -->
    <div class="big-burger text-center">
      <div class="container">
        <h2>Big Burger</h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus
          lacinia odio vitae vestibulum vestibulum.
        </p>
        <img
          src="burgeer3.jpg"
          class="img-fluid rounded-circle"
          alt="Big Burger"
        />
        <button class="order-btn mt-3">ORDER NOW</button>
      </div>
    </div>

    <!-- Statistics Section -->
    <div class="statistics bg-danger text-white text-center">
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <h1>7k</h1>
            <p>Customer</p>
          </div>
          <div class="col-md-4">
            <h1>109</h1>
            <p>Outlets</p>
          </div>
          <div class="col-md-4">
            <h1>35</h1>
            <p>Country</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Popular Package Section -->
    <div class="popular-package text-center">
      <div class="container">
        <h2>Popular Package</h2>
        <div class="row">
          <div class="col-md-4">
            <div class="card">
              <div class="card-body">
                <h3>PACKAGE I</h3>
                <img
                  src="apple-touch-icon.png"
                  alt="Logo"
                  style="width: 40px"
                />
                <p>$10.00</p>
                <button class="order-btn">ORDER NOW</button>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card">
              <div class="card-body">
                <h3>PACKAGE II</h3>
                <img
                  src="apple-touch-icon.png"
                  alt="Logo"
                  style="width: 40px"
                />
                <p>$20.00</p>
                <button class="order-btn">ORDER NOW</button>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card">
              <div class="card-body">
                <h3>PACKAGE III</h3>
                <img
                  src="apple-touch-icon.png"
                  alt="Logo"
                  style="width: 40px"
                />
                <p>$30.00</p>
                <button class="order-btn">ORDER NOW</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Updates Section -->
    <div class="updates text-center">
      <div class="container">
        <h2>Don't miss Our Update</h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus
          lacinia odio vitae vestibulum vestibulum.
        </p>
        <div class="input-group mb-3">
          <input type="text" class="form-control" placeholder="Your Email" />
          <div class="input-group-append">
            <button class="btn btn-danger" type="button">SUBSCRIBE</button>
          </div>
        </div>
      </div>
    </div>

    <!-- Footer Section -->
    <div class="footer text-center">
      <div class="container">
        <div class="row">
          <div class="col-md-3">
            <h4>Title Here</h4>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam
              at dignissim nunc, id maximus ex. Etiam nec dignissim elit, at
              dignissim enim.
            </p>
            <div>
              <a href="#"><i class="fab fa-facebook-f"></i></a>
              <a href="#"><i class="fab fa-twitter"></i></a>
              <a href="#"><i class="fab fa-instagram"></i></a>
              <a href="#"><i class="fab fa-youtube"></i></a>
            </div>
          </div>
          <div class="col-md-3">
            <h4>About</h4>
            <p>History</p>
            <p>Our Team</p>
            <p>Brand Guidelines</p>
            <p>Terms & Condition</p>
            <p>Privacy Policy</p>
          </div>
          <div class="col-md-3">
            <h4>Services</h4>
            <p>How to Order</p>
            <p>Our Product</p>
            <p>Order Status</p>
          </div>
        </div>
      </div>
    </div>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
  </body>
</html>
