# Project Responsive Web Design using Bootstrap
## Date:26.12.2024

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
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Dribble.io</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  </head>
  <body>
    <nav class="navbar navbar-expand-sm navbar-dark bg-dark">
      <div class="container">
        
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
                <a href="#" class="nav-link" style="color: aqua;">Dribble</a>
              </li>
            <li class="nav-item">
              <a href="#" class="nav-link active" aria-current="page">Shots</a>
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link">Designer</a>
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link">Sign up</a>
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link">Sign in</a>
            </li>
          </ul>
          <div class="ms-auto">
            <form class="d-flex" role="search">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-primary" type="submit">Search</button>
            </form>
          </div>
        </div>
      </div>
    </nav>


  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>


<div class="container mt-4">
    <div class="text-center mb-4 header-section" style="width: 300;"height="200"></div>
    <center>
        <h3>What are you working on?</h3>
        <p class="lead">Dribbble is show and tell for designers.</p>
        </center>
    </div>
    <center>
    <a href="#" class="btn btn-primary">Learn More</a>
    <a href="#" class="btn btn-primary">Popular</a>
    <a href="#" class="btn btn-primary">Designs</a>
    </center>
    <br>
    <div class="row gallery-section">
        <div class="col-md-3 col-sm-6 mb-4">
            <div class="card shadow gallery-item">
                <img src="web 2.jpeg" class="card-img-top gallery-img" alt="Design Thumbnail">
                <div class="card-body text-center">
                    <p class="card-title">Famous</p>
                    <small class="text-muted">Infullmobile</small>
                </div>
            </div>
        </div>
        <div class="col-md-3 col-sm-6 mb-4">
            <div class="card shadow gallery-item">
                <img src="web 3.jpeg" class="card-img-top gallery-img" alt="Design Thumbnail">
                <div class="card-body text-center">
                    <p class="card-title">SHOES</p>
                    <small class="text-muted">WOODLAND</small>
                </div>
            </div>
        </div>
        <div class="col-md-3 col-sm-6 mb-4">
            <div class="card shadow gallery-item">
                <img src="web 2.jpeg" class="card-img-top gallery-img" alt="Design Thumbnail">
                <div class="card-body text-center">
                    <p class="card-title">Famous</p>
                    <small class="text-muted">Infullmobile</small>
                </div>
            </div>
        </div>
        <div class="col-md-3 col-sm-6 mb-4">
            <div class="card shadow gallery-item">
                <img src="web 5.jpeg" class="card-img-top gallery-img" alt="Design Thumbnail">
                <div class="card-body text-center">
                    <p class="card-title">Hero</p>
                    <small class="text-muted">Heroine</small>
                </div>
            </div>
        </div>
        <div class="col-md-3 col-sm-6 mb-4">
            <div class="card shadow gallery-item">
                <img src="web 0.jpeg" class="card-img-top gallery-img" alt="Design Thumbnail">
                <div class="card-body text-center">
                    <p class="card-title">Paperpillar</p>
                    <small class="text-muted">Dora</small>
                </div>
            </div>
        </div>
        <div class="col-md-3 col-sm-6 mb-4">
            <div class="card shadow gallery-item">
                <img src="web 10.jpeg" class="card-img-top gallery-img" alt="Design Thumbnail">
                <div class="card-body text-center">
                    <p class="card-title">Baby</p>
                    <small class="text-muted">Bheem</small>
                </div>
            </div>
        </div>
        
        <div class="col-md-3 col-sm-6 mb-4">
            <div class="card shadow gallery-item">
                <img src="web 8.jpeg" class="card-img-top gallery-img" alt="Design Thumbnail">
                <div class="card-body text-center">
                    <p class="card-title">Jansi</p>
                    <small class="text-muted">princee</small>
                </div>
            </div>
        </div>
        
        <div class="col-md-3 col-sm-6 mb-4">
            <div class="card shadow gallery-item">
                <img src="web 7.jpeg" class="card-img-top gallery-img" alt="Design Thumbnail">
                <div class="card-body text-center">
                    <p class="card-title">Angel</p>
                    <small class="text-muted">Janani</small>
                </div>
            </div>
        </div>
        <footer>
            <center>
            <p>Designed and developed by Jansi Rani(24900239)</p></center>
        </footer>
    </div>
</div>
```

## OUTPUT:
c:\Users\Admin\Pictures\Screenshots\Screenshot (115).png
c:\Users\Admin\Pictures\Screenshots\Screenshot (116).png

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
