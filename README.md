# Project Responsive Web Design using Bootstrap
## Date:27.12.2024

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .card-img-top {
            height: 200px;
            object-fit: cover;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand fw-bold text-danger" href="#">Dribbble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto">
                    <li class="nav-item"><a class="nav-link text-white" href="#">Shots</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Designers</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Teams</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Community</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Jobs</a></li>
                </ul>
                <div class="d-flex">
                    <a class="btn btn-outline-light me-2" href="#">Sign in</a>
                    <a class="btn btn-outline-light me-2" href="#">Sign Up</a>
                </div>
                <input type="search" class="form-control w-auto ms-2" placeholder="Search">
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="bg-white py-5">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6 text-center text-md-start">
                    <h1 class="display-4 fw-bold">What are you working on?</h1>
                    <p class="my-3">Dribbble is a show-and-tell platform for designers.</p>
                    <div>
                        <button class="btn btn-secondary me-2">Learn More</button>
                        <button class="btn btn-primary">Sign up</button>
                    </div>
                </div>
                <div class="col-md-6 text-center">
                    <img src="Beige Reminder Note Quote Instagram Post.png" class="img-fluid" alt="Design Work" style="height: 45vh;">
                </div>
            </div>
        </div>
    </section>

    <!-- Shots Section -->
    <section class="py-5">
        <div class="container">
            <div class="row mb-4">
                <div class="col-md-4">
                    <h2 class="fw-bold">Popular</h2>
                </div>
                <div class="col-md-4 text-center">
                    <button class="btn btn-outline-dark">Now</button>
                    <button class="btn btn-outline-dark">Shots</button>
                </div>
            </div>
            <div class="row g-4">
                <div class="col-md-3 col-sm-6">
                    <div class="card">
                        <img src="Brown Simple Interior Design Poster.png" class="card-img-top" alt="Shot 1">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Awe Design Studio</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card">
                        <img src="Beige Vintage Photo Collage Scrapbook Instagram Post.png" class="card-img-top" alt="Shot 2">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Russlan silz</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card">
                        <img src="Green Dog Emoji Slider Pets Interactive Instagram Story.png" class="card-img-top" alt="Shot 3">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Alfrey Davilla</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card">
                        <img src="https://cdn.dribbble.com/users/1739084/screenshots/4448965/kyzzlj.jpg?resize=400x300&vertical=center" class="card-img-top" alt="Shot 4">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 MakeReign</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card">
                        <img src="https://cdn.dribbble.com/users/140043/screenshots/9106916/dribbble_4_compressed.png?resize=400x300&vertical=center" class="card-img-top" alt="Shot 5">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Mattias Johannson</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card">
                        <img src="Text on Rectangle iPhone Layout.png" class="card-img-top" alt="Shot 6">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Jan Losert</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card">
                        <img src="Black and White Minimal Lead Magnet Promo Instagram Story.png" class="card-img-top" alt="Shot 7">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Wkio</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card">
                        <img src="https://cdn.dribbble.com/userupload/10964296/file/original-ffa83431e0b8639f6d1036a0f80c76ae.png?resize=400x300&vertical=center" class="card-img-top" alt="Shot 8">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Romain Tystramm</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white py-3">
        <div class="container text-center">
            <p class="mb-0">Designed and developed by SATHISH.B (24900077)</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (98).png>)
![alt text](<Screenshot (97).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
