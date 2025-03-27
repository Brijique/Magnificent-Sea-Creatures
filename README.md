# Magnificent-Sea-Creatures
Magnificent Sea Creatures - Celebrating the Magic of Marine Life Bootstrap CDN assignment
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Magnificent Sea Creatures</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <header>
        <nav class="navbar navbar-expand-lg">
            <div class="container-fluid">
              <a class="navbar-brand" href="#"><img src="images/blue-logo.jpg" alt="blue fish logo"></a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                  <li class="nav-item">
                    <a class="nav-link" aria-current="page" href="#">Home</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Blog</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">About</a>
                  </li>
                  </li>
                </ul>
              </div>
            </div>
          </nav>
    </header>
    <main>
        <section id="landing-container">
            <h1>Magnificent Sea Creatures</h1>
            <h2>Celebrating the Magic of Marine Life</h2>
        </section>
        <section id="featured">
             <h3>Featured Creatures</h3>
             <div class="container-fluid">
                <div class="row">
                  <div class="col-12 col-md-6 col-lg-3">
                    <div class="card">
                        <img src="images/clownfish-img.jpg" class="card-img-top" alt="clownfish-img">
                        <div class="card-body">
                          <h5 class="card-title">Card title</h5>
                          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                          <a href="#" class="btn btn-primary">Go somewhere</a>
                        </div>
                      </div>
                  </div>
                  <div class="col-12 col-md-6 col-lg-3">
                    <div class="card">
                        <img src="images/seahorse-img.jpg" class="card-img-top" alt="seahorse-img">
                        <div class="card-body">
                          <h5 class="card-title">Card title</h5>
                          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                          <a href="#" class="btn btn-primary">Go somewhere</a>
                        </div>
                      </div>
                  </div>
                  <div class="col-12 col-md-6 col-lg-3">
                    <div class="card">
                        <img src="images/seaturtle-img.jpg" class="card-img-top" alt="seaturtle-img">
                        <div class="card-body">
                          <h5 class="card-title">Card title</h5>
                          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                          <a href="#" class="btn btn-primary">Go somewhere</a>
                        </div>
                      </div>
                  </div>
                  <div class="col-12 col-md-6 col-lg-3">
                    <div class="card">
                        <img src="images/whale-img.jpg" class="card-img-top" alt="whale-img">
                        <div class="card-body">
                          <h5 class="card-title">Card title</h5>
                          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                          <a href="#" class="btn btn-primary">Go somewhere</a>
                        </div>
                      </div>
                  </div>
                </div>
              </div>
        </section>
    </main>
    <footer></footer>
    <div id="myCarousel" class="carousel slide" data-bs-ride="carousel">
        <!-- Indicators -->
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="0" class="active"></button>
          <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="1"></button>
          <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="2"></button>
        </div>
    
        <!-- Slides -->
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="images/marine-bg.jpg" alt="Marine" class="d-block w-100">
            <div class="carousel-caption">
              <h5>Marine</h5>
              <p>Experience the tranquility of the marine.</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="images/reef.jpg" alt="Reef" class="d-block w-100">
            <div class="carousel-caption">
              <h5>Reef</h5>
              <p>Explore the bustling life of reefs.</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="images/karl-callwood-2jZY2KUofY8-unsplash.jpg" alt="Sea Floor" class="d-block w-100">
            <div class="carousel-caption">
              <h5>Starry Sky</h5>
              <p>Discover the wonders of the sea.</p>
            </div>
          </div>
        </div>
    
        <!-- Controls -->
        <button class="carousel-control-prev" type="button" data-bs-target="#myCarousel" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#myCarousel" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    
      <!-- Bootstrap Bundle JS -->
      <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
    </body>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js" integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.min.js" integrity="sha384-0pUGZvbkm6XF6gxjEnlmuGrJXVbNuzT9qBBavbLwCsOGabYfZo0T0to5eqruptLy" crossorigin="anonymous"></script>
  </body>
</html>
