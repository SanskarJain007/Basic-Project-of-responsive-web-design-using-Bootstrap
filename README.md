# Basic-Project-of-responsive-web-design-using-Bootstrap
Code: -
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.bundle.min.js" integrity="sha384-pprn3073KE6tl6bjs2QrFaJGz5/SUsLqktiwsUTF55Jfv3qYSDhgCecCxMW52nD2" crossorigin="anonymous"></script>    
<title>Document</title>
</head>
<body>
   <div class="container-fluid">
    <div class="row">
        <div class="col-md-12">
            <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
                <div class="container-fluid">
                  <a class="navbar-brand" href="#">Navbar</a>
                  <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                  </button>
                  <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                      <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Home</a>
                      </li>
                      <li class="nav-item">
                        <a class="nav-link" href="#">Link</a>
                      </li>
                      <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                          Dropdown
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                          <li><a class="dropdown-item" href="#">Action</a></li>
                          <li><a class="dropdown-item" href="#">Another action</a></li>
                          <li><hr class="dropdown-divider"></li>
                          <li><a class="dropdown-item" href="#">Something else here</a></li>
                        </ul>
                      </li>
                      <li class="nav-item">
                        <a class="nav-link disabled">Disabled</a>
                      </li>
                    </ul>
                    <form class="d-flex" role="search">
                      <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                      <button class="btn btn-outline-success" type="submit">Search</button>
                    </form>
                  </div>
                </div>
              </nav>
        </div>
    </div>
     <div class="row">
        <div class="col-md-12">
            <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
                <div class="carousel-inner">
                  <div class="carousel-item active">
                    <img src="images/scott-webb-IZmPdbnb-3I-unsplash.jpg" class="d-block w-100" alt="...">
                  </div>
                  <div class="carousel-item">
                    <img src="images/scene.jpg" class="d-block w-100" alt="...">
                  </div>
                  <div class="carousel-item">
                    <img src="images/insung-yoon-kyQaQ25_NsA-unsplash.jpg" class="d-block w-100" alt="...">
                  </div>
                </div>
                <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
                  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                  <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
                  <span class="carousel-control-next-icon" aria-hidden="true"></span>
                  <span class="visually-hidden">Next</span>
                </button>
              </div>
        </div>
     </div>
   </div> 
   <div class="container">
    <div class="row">
        <div class="col-md-12">
            <h2 class="text-center text-primary">About me</h2>
            <p class="text-left ">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Facilis dolorem incidunt nobis, nostrum deserunt eligendi quisquam quos, temporibus et laudantium dolorum nulla quaerat, id libero assumenda placeat esse possimus! Illum!</p>
            <h2 class="text-center text-primary">Portfolio</h2>
        </div>
    </div>
    <div class="row">
        <div class="col-md-4">
            <div class="card">
                <img src="images/pexels-cesar-perez-733745.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Card title</h5>
                  <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                  <a href="#" class="btn btn-primary">Go somewhere</a>
                </div>
              </div>
        </div>
        <div class="col-md-4 "><div class="card">
            <img src="images/pexels-johannes-plenio-1103970.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Card title</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-primary">Go somewhere</a>
            </div>
          </div></div>
        <div class="col-md-4">
            <div class="card">
                <img src="images/pexels-maxime-francis-2246476.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Card title</h5>
                  <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                  <a href="#" class="btn btn-primary">Go somewhere</a>
                </div>
              </div>
        </div>
    </div>
    <div class="row mt-4">
        <div class="col-md-3 bg-primary">

        </div>
        <div class="col-md-9">
<p>Hello Everyone this is my first project using bootstrap, html and css. Hope you all like it.
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Suscipit sed quia dolorum soluta, similique porro iste, enim expedita optio a voluptates voluptas culpa rem, quos tenetur quibusdam? Corporis, numquam sunt? </p>
        </div>
    </div>
   </div>
   <div class="container-fluid">
    <div class="row">
        <div class="col-md-12 bg-dark text-light text-center p-4 mt-4">
            CopyRight @ Sanskar Jain
        </div>
    </div>
    
   </div>
</body>
</html>
