# Project Responsive Web Design using Bootstrap
## Date:
23/12/2024
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
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<!-- Top Bar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
        <a class="navbar-brand" href="#">Dribbble</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link active" href="#">Shots</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Designers</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Community</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Jobs</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Sign Up</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Sign In</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<!-- Banner Section -->
<header class="bg-light text-center py-5">
    <div class="container">
        <h1 class="display-4">What are you working on?</h1>
        <p class="lead">Dribbble is a show and tell for designers</p>
        <a href="#gallery" class="btn btn-primary btn-lg">learn more</a>
        <a href="#" class="btn btn-outline-secondary btn-lg">sign up</a>
    </div>
</header>

<!-- Gallery Section -->
<section id="gallery" class="bg-light py-5">
    <div class="container">
        <h2 class="text-center mb-4">Popular Shots</h2>
        <div class="row">
            <div class="col-md-3 col-sm-6 mb-4">
                <img src="1.webp" class="img-fluid rounded" alt="Design 1">
                <p class="mt-2 text-center">futuristic illution</p>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <img src="2.webp" class="img-fluid rounded" alt="Design 2">
                <p class="mt-2 text-center">merry christmas</p>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <img src="3.webp" class="img-fluid rounded" alt="Design 3">
                <p class="mt-2 text-center">in the woods</p>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <img src="4.webp" class="img-fluid rounded" alt="Design 4">
                <p class="mt-2 text-center">factory reset</p>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <img src="5.webp" class="img-fluid rounded" alt="Design 5">
                <p class="mt-2 text-center">portrait</p>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <img src="6.webp" class="img-fluid rounded" alt="Design 6">
                <p class="mt-2 text-center">studio closed</p>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <img src="7.webp" class="img-fluid rounded" alt="Design 7">
                <p class="mt-2 text-center">winter valley</p>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <img src="8.webp" class="img-fluid rounded" alt="Design 8">
                <p class="mt-2 text-center">evil ground</p>
            </div>
        </div>
    </div>
</section>

<!-- Footer -->
<footer class="bg-dark text-white text-center py-3">
    <div class="container">
        <p>Designed and developed by V.Vivin Mathew</p>
    </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```


## OUTPUT:

![alt text](<Screenshot 2024-12-24 052307.png>)
![alt text](<Screenshot 2024-12-24 052319.png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
