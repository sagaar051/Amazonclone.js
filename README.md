<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Amazon Clone</title>

  
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css" rel="stylesheet"/>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css"/>


  <style>
    .product-img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-top-left-radius: 0.5rem;
      border-top-right-radius: 0.5rem;
    }
  </style>
</head>
<body>


<nav class="navbar navbar-dark bg-dark p-3">
  <div class="container-fluid">
    <a href="#" class="navbar-brand">Amazon</a>
    <button class="btn btn-warning">Login</button>
  </div>
</nav>


<section class="p-4">
  <h1>Products</h1>
  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus ipsum officiis ut reiciendis architecto assumenda.</p>
</section>


<section class="container mb-5">
  <div class="row g-4">

    <!-- PRODUCT CARD START -->
    <div class="col-md-3">
      <div class="card h-100">
        <img src="https://laptopmedia.com/wp-content/uploads/2023/03/3-7-e1678204949389.jpg" class="product-img" />
        <div class="card-body text-center">
          <h5 class="card-title">Asus Vivobook</h5>
          <h6 class="text-danger"><i class="bi bi-currency-rupee"></i> 30000</h6>
          <p class="card-text">Powerful performance with great display.</p>
          <button class="btn btn-primary">Buy Now</button>
        </div>
      </div>
    </div>
    <!-- PRODUCT CARD END -->

    <!-- Copy and change only content inside below cards -->
    <div class="col-md-3">
      <div class="card h-100">
        <img src="https://m.media-amazon.com/images/I/61n2MIzbupL.jpg" class="product-img" />
        <div class="card-body text-center">
          <h5 class="card-title">Galaxy Buds</h5>
          <h6 class="text-danger"><i class="bi bi-currency-rupee"></i> 6000</h6>
          <p class="card-text">Wireless sound with noise cancellation.</p>
          <button class="btn btn-primary">Buy Now</button>
        </div>
      </div>
    </div>

    <div class="col-md-3">
      <div class="card h-100">
        <img src="https://timex.ph/cdn/shop/products/TW2V40500_1800x1800.jpg?v=1667376015" class="product-img" />
        <div class="card-body text-center">
          <h5 class="card-title">Timex Watch</h5>
          <h6 class="text-danger"><i class="bi bi-currency-rupee"></i> 5000</h6>
          <p class="card-text">Elegant and water resistant design.</p>
          <button class="btn btn-primary">Buy Now</button>
        </div>
      </div>
    </div>

    <div class="col-md-3">
      <div class="card h-100">
        <img src="https://www.bigw.com.au/medias/sys_master/images/images/hea/h27/12034942074910.jpg" class="product-img" />
        <div class="card-body text-center">
          <h5 class="card-title">JBL Headphones</h5>
          <h6 class="text-danger"><i class="bi bi-currency-rupee"></i> 3500</h6>
          <p class="card-text">Powerful bass and immersive sound.</p>
          <button class="btn btn-primary">Buy Now</button>
        </div>
      </div>
    </div>

    <div class="col-md-3">
      <div class="card h-100">
        <img src="https://tse4.mm.bing.net/th/id/OIF.fxMfPMntqylMPXIidmBWsQ?rs=1&pid=ImgDetMain&o=7&rm=3" class="product-img" />
        <div class="card-body text-center">
          <h5 class="card-title">Galaxy Z Fold</h5>
          <h6 class="text-danger"><i class="bi bi-currency-rupee"></i> 70000</h6>
          <p class="card-text">Next-gen foldable smartphone from Samsung.</p>
          <button class="btn btn-primary">Buy Now</button>
        </div>
      </div>
    </div>

    <div class="col-md-3">
      <div class="card h-100">
        <img src="https://storage.beko.co.uk/blomberg2018products/large/Blomberg_WashingMachine_LWF28442B_Black_AngledClosed.jpg" class="product-img" />
        <div class="card-body text-center">
          <h5 class="card-title">Whirlpool Machine</h5>
          <h6 class="text-danger"><i class="bi bi-currency-rupee"></i> 27000</h6>
          <p class="card-text">High efficiency and auto mode washing.</p>
          <button class="btn btn-primary">Buy Now</button>
        </div>
      </div>
    </div>

    <div class="col-md-3">
      <div class="card h-100">
        <img src="https://lg-sks-content.s3.us-west-1.amazonaws.com/2022-10/sks-city-refrigeration-lifestyle-6-48_site_0_2.jpeg" class="product-img" />
        <div class="card-body text-center">
          <h5 class="card-title">Refrigerator</h5>
          <h6 class="text-danger"><i class="bi bi-currency-rupee"></i> 15000</h6>
          <p class="card-text">Smart cooling and energy efficient.</p>
          <button class="btn btn-primary">Buy Now</button>
        </div>
      </div>
    </div>

    <div class="col-md-3">
      <div class="card h-100">
        <img src="https://assets.adidas.com/images/w_1880,f_auto,q_auto/6e8801647b9f4ead8519afd2010a8463_9366/IF0642_04_standard.jpg" class="product-img" />
        <div class="card-body text-center">
          <h5 class="card-title">Adidas Shoes</h5>
          <h6 class="text-danger"><i class="bi bi-currency-rupee"></i> 10000</h6>
          <p class="card-text">Comfortable, stylish running shoes.</p>
          <button class="btn btn-primary">Buy Now</button>
        </div>
      </div>
    </div>

  </div>
</section>


<footer class="bg-dark text-center text-white p-4">
  <p class="mb-0">Developed by Sagar Gouda © 2025</p>
</footer>

</body>
</html>
