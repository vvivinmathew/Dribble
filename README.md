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
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <!-- Inline CSS for font and hover effect -->
    <style>
        body {
            font-family: 'Oswald', sans-serif;
        }
        .gallery-item {
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease;
        }
        .gallery-item:hover {
            transform: scale(1.05);
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }
        .gallery-img {
            width: 100%;
            height: auto;
        }
    </style>
    <!-- Google Font for Oswald -->
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@400;500;600&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand" href="#">Dribbble</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item"><a class="nav-link" href="#">Shots</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Designers</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Teams</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Community</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li>
                <li class="nav-item"><a class="btn btn-primary" href="#">Sign Up</a></li>
            </ul>
        </div>
    </nav>

    <!-- Main Content Section -->
    <div class="container mt-4">
        <div class="text-center mb-4 header-section">
            <h3>What are you working on?</h3>
            <p class="lead">Dribbble is show and tell for designers.</p>
        </div>

        <!-- Gallery Section -->
        <div class="row gallery-section">
            <!-- Gallery Items -->
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="1.webp" class="card-img-top gallery-img" alt="Design Thumbnail">
                    <div class="card-body text-center">
                        <p class="card-title">futuristic illustration</p>
                        <small class="text-muted">orbix</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="2.webp" class="card-img-top gallery-img" alt="Design Thumbnail">
                    <div class="card-body text-center">
                        <p class="card-title">christmas</p>
                        <small class="text-muted">threedee</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="3.webp" class="card-img-top gallery-img" alt="Design Thumbnail">
                    <div class="card-body text-center">
                        <p class="card-title">lost at the woods</p>
                        <small class="text-muted">muti</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="4.webp" class="card-img-top gallery-img" alt="Design Thumbnail">
                    <div class="card-body text-center">
                        <p class="card-title">winter cabin</p>
                        <small class="text-muted">tanner</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="5.webp" class="card-img-top gallery-img" alt="Design Thumbnail">
                    <div class="card-body text-center">
                        <p class="card-title">easy way to dine</p>
                        <small class="text-muted">wonders</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="6.webp" class="card-img-top gallery-img" alt="Design Thumbnail">
                    <div class="card-body text-center">
                        <p class="card-title">studio closed</p>
                        <small class="text-muted">multi</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="7.webp" class="card-img-top gallery-img" alt="Design Thumbnail">
                    <div class="card-body text-center">
                        <p class="card-title">winter valley</p>
                        <small class="text-muted">roman</small>
                    </div>
                </div>
            </div>
            <div class="col-md-3 col-sm-6 mb-4">
                <div class="card shadow gallery-item">
                    <img src="8.webp" class="card-img-top gallery-img" alt="Design Thumbnail">
                    <div class="card-body text-center">
                        <p class="card-title">evilground</p>
                        <small class="text-muted">limbo</small>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <p>© Dribbble.designed and developed by V.VIVIN MATHEW</p>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.bundle.min.js"></script>
</body>
</html>

CSS

/* Importing Oswald font */
@import url('https://fonts.googleapis.com/css2?family=Oswald:wght@400;500;600;700&display=swap');

/* Applying Oswald font globally */
body {
    font-family: 'Oswald', sans-serif;
    margin: 0;
    padding: 0;
}

/* Navbar Customization */
.navbar-nav {
    flex-direction: row;
}

.navbar-nav .nav-link {
    padding-left: 15px;
    padding-right: 15px;
}

/* Card adjustments */
.card-title {
    font-weight: bold;
    text-transform: uppercase;
}

.card-body {
    padding: 15px;
}

/* Gallery section adjustments */
.gallery-img {
    width: 100%;
    height: auto;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

/* Hover effect for the image */
.gallery-img:hover {
    transform: scale(1.1);  /* This makes the image enlarge */
    box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.3);  /* Adds a shadow to create the pop-up effect */
}

/* Main header section adjustments */
.header-section h3 {
    font-weight: bold;
}

.header-section p {
    font-size: 1.2em;
}

/* Responsive Design */
@media (max-width: 768px) {
    /* Adjust Navbar for smaller screens */
    .navbar-nav {
        flex-direction: column;
        text-align: center;
        padding: 10px 0;
    }

    .navbar-toggler {
        border-color: #fff;
    }

    /* Gallery items adjustment */
    .gallery-section {
        margin-top: 20px;
    }

    .col-md-3 {
        width: 100%;
    }

    .card-body {
        padding: 10px;
    }
}

@media (max-width: 480px) {
    /* Adjust text sizes and layout for very small screens */
    .header-section h3 {
        font-size: 1.5em;
    }

    .header-section p {
        font-size: 1em;
    }
}
```

## OUTPUT:

![alt text](<vivinapp/static/Screenshot 2024-12-23 135855.png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
