web link: http://127.0.0.1:3000/index.html?vscode-livepreview=true
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Responsive Website</title>

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- Custom CSS -->
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">TANGO PROTEIN</a>

            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="#">T Protein bars</a>
                    </li>

                    <li class="nav-item">
                        <a class="nav-link" href="#">T Protein Powder</a>
                    </li>

                    <li class="nav-item">
                        <a class="nav-link" href="#">T Protein Chocolatss</a>
                    </li>


                </ul>
            </div>
        </div>
    </nav>

    <!-- Carousel -->
    <div id="carouselExample" class="carousel slide" data-bs-ride="carousel">

        <div class="carousel-inner">

            <div class="carousel-item active">
                <img src="images/bp1.webp" class="d-block w-100" alt="Slide 1">
            </div>

            <div class="carousel-item">
                <img src="images/pb2.webp" class="d-block w-100" alt="Slide 2">
            </div>

            <div class="carousel-item">
                <img src="images/pb3.webp" class="d-block w-100" alt="Slide 3">
            </div>

        </div>

        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
            <span class="carousel-control-prev-icon"></span>
        </button>

        <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
            <span class="carousel-control-next-icon"></span>
        </button>

    </div>

    <!-- Grid System and Cards -->
    <div class="container mt-5">

        <div class="row">

            <!-- Card 1 -->
            <div class="col-md-4 mb-4">
                <div class="card shadow">
                    <img src="images/pdr1.webp" class="card-img-top" alt="Card 1">

                    <div class="card-body">
                        <h5 class="card-title">Protein Powder</h5>

                        <p class="card-text">
                            Pure Protein. Pure Performance.
                        </p>

                        <a href="#" class="btn btn-primary">Tap To Order</a>
                    </div>
                </div>
            </div>

            <!-- Card 2 -->
            <div class="col-md-4 mb-4">
                <div class="card shadow">
                    <img src="images/pdr2.webp" class="card-img-top" alt="Card 2">

                    <div class="card-body">
                        <h5 class="card-title">Protein Powder</h5>

                        <p class="card-text">
                            Premium Protein for Peak Performance.
                        </p>

                        <a href="#" class="btn btn-success">Tap To Order</a>
                    </div>
                </div>
            </div>

            <!-- Card 3 -->
            <div class="col-md-4 mb-4">
                <div class="card shadow">
                    <img src="images/pdr3.webp" class="card-img-top" alt="Card 3">

                    <div class="card-body">
                        <h5 class="card-title">Protein Powder</h5>

                        <p class="card-text">
                            From First Workout to Personal Best—We've Got Your Protein Covered.
                        </p>

                        <a href="#" class="btn btn-danger">Tap To Order</a>
                    </div>
                </div>
            </div>

        </div>

    </div>

    <!-- Grid System and Cards -->
    <div class="container mt-5">

        <div class="row">

            <!-- Card 1 -->
            <div class="col-md-4 mb-4">
                <div class="card shadow">
                    <img src="images/cho1.webp" class="card-img-top" alt="Card 1">

                    <div class="card-body">
                        <h5 class="card-title">Protein Chocolates</h5>

                        <p class="card-text">
                            Enjoy the rich taste of chocolate while fueling your muscles with high-quality protein.
                        </p>

                        <a href="#" class="btn btn-primary">Tap To Order</a>
                    </div>
                </div>
            </div>

            <!-- Card 2 -->
            <div class="col-md-4 mb-4">
                <div class="card shadow">
                    <img src="images/cho2.webp" class="card-img-top" alt="Card 2">

                    <div class="card-body">
                        <h5 class="card-title">Protein Chocolates</h5>

                        <p class="card-text">
                            Deliciously smooth, packed with protein, and made to support your fitness journey.
                        </p>

                        <a href="#" class="btn btn-success">Tap To Order</a>
                    </div>
                </div>
            </div>

            <!-- Card 3 -->
            <div class="col-md-4 mb-4">
                <div class="card shadow">
                    <img src="images/cho3.webp" class="card-img-top" alt="Card 3">

                    <div class="card-body">
                        <h5 class="card-title">Protein Chocolates</h5>

                        <p class="card-text">
                            Enjoy delicious protein-rich chocolates for a tasty treat.
                        </p>

                        <a href="#" class="btn btn-danger">Tap To Order</a>
                    </div>
                </div>
            </div>

        </div>



    </div>
    <!-- Footer -->
    <footer class="bg-dark text-white text-center p-3 mt-5">
        <p>© TANGO PROTEIN </p>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>

</html>>>
