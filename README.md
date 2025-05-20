# Project Responsive Web Design using Bootstrap
## Date:

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

index.html

```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribbble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
</head>

<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light shadow-light">
    <div class="container">
      <a class="navbar-brand text-primary" href="#"><strong>Dribbble Clone</strong></a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link text-dark active" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-dark" href="#">Shots</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-dark" href="#">Designers</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-dark" href="#">Sign Up</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="text-center text-white"
    style="background-image: linear-gradient(to bottom right, #5c67f5, #7091ff); padding: 100px 0;">
    <div class="container">
      <h1 style="font-weight: bold; font-size: 2.5rem;">Discover the World’s Top Designers & Creatives</h1>
      <p style="font-size: 1.1rem;">Join the Dribbble community to showcase your work, inspire others, and find design
        inspiration.</p>
      <a href="#" class="btn btn-primary btn-lg mt-3">Get Started</a>
    </div>
  </section>

  <section class="featured-section">
    <div class="container">
      <h2 class="text-center text-primary mb-5">Featured UI/UX Shots</h2>
      <div class="row">
        <div class="col-md-4 mb-4">
          <div class="card border-light shadow">
            <img src="creativeapp.jpg" class="card-img-top" alt="Shot 1" style="height: 300px; width: 414px;">
            <div class="card-body">
              <h5 class="card-title text-primary">Creative App Interface</h5>
              <p class="card-text text-secondary">A brief description of the app interface design.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card border-light shadow">
            <img src="dashboard.jpg" class="card-img-top" alt="Shot 2" style="height: 300px; width: 414px;">
            <div class="card-body">
              <h5 class="card-title text-info">Modern Dashboard UI</h5>
              <p class="card-text text-secondary">A sleek, modern dashboard design for data visualization.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card border-light shadow">
            <img src="ecommerce.jpg" class="card-img-top" alt="Shot 3" style="height: 300px; width: 414px;">
            <div class="card-body">
              <h5 class="card-title text-success">E-commerce Web Design</h5>
              <p class="card-text text-secondary">An attractive e-commerce landing page for a smooth user experience.
              </p>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card border-light shadow">
            <img src="creativeweb.webp" class="card-img-top" alt="Shot 4" style="height: 300px; width: 414px;">
            <div class="card-body">
              <h5 class="card-title text-warning">Creative Web Design</h5>
              <p class="card-text text-secondary">An engaging design for a modern web experience.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card border-light shadow">
            <img src="mobileapp.avif" class="card-img-top" alt="Shot 5" style="height: 300px; width: 414px;">
            <div class="card-body">
              <h5 class="card-title text-danger">Mobile App Design</h5>
              <p class="card-text text-secondary">A stunning UI for a mobile application.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card border-light shadow">
            <img src="dark.png" class="card-img-top" alt="Shot 6" style="height: 300px; width: 414px;">
            <div class="card-body">
              <h5 class="card-title text-primary">Dark Theme Dashboard</h5>
              <p class="card-text text-secondary">A stylish dashboard with a dark theme.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card border-light shadow">
            <img src="portfolio.avif" class="card-img-top" alt="Shot 7" style="height: 300px; width: 414px;">
            <div class="card-body">
              <h5 class="card-title text-success">Portfolio Landing Page</h5>
              <p class="card-text text-secondary">A minimalistic landing page for personal portfolios.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card border-light shadow">
            <img src="3d.webp" class="card-img-top" alt="Shot 8" style="height: 300px; width: 414px;">
            <div class="card-body">
              <h5 class="card-title text-info">3D Design Concept</h5>
              <p class="card-text text-secondary">A visually appealing design with 3D elements.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer class="footer text-white" style="background-color: #333; padding: 30px 0; text-align: center;">
    <div class="container">
      <p>&copy; 2024 Dribbble Clone. All rights reserved.</p>
      <p>Created by Vishal V</p>
      <p>
        <a href="#" style="color: #b5b5b5;">Privacy Policy</a> |
        <a href="#" style="color: #b5b5b5;">Terms of Service</a>
      </p>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
```

signin.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Sign Up Page</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background: #000;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #fff;
        }
        .card {
            border-radius: 20px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
            background: #fff;
            color: #000;
        }
        .card-header {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 10px;
            text-align: center;
            font-size: 1.5rem;
            font-weight: bold;
            color: #000;
            background: #f8f9fa;
            border-top-left-radius: 20px;
            border-top-right-radius: 20px;
        }
        .card-header img {
            width: 30px;
            height: 30px;
        }
        .btn-primary {
            background-color: #000;
            border: none;
            color: #fff;
        }
        .btn-primary:hover {
            background-color: #333;
        }
        .form-control:focus {
            box-shadow: none;
            border-color: #000;
        }
        .link:hover {
            text-decoration: underline;
            color: #000;
        }
        .text-center a {
            color: #000;
        }
        .text-center a:hover {
            text-decoration: underline;
            color: #000;
        }
    </style>
</head>
<body>
    <div class="card p-4" style="width: 22rem;">
        <div class="card-header">
            Sign Up
        </div>
        <div class="card-body">
            <form>
                <div class="mb-3">
                    <label for="fullName" class="form-label">Full Name</label>
                    <input type="text" class="form-control" id="fullName" placeholder="Enter your full name" required>
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email address</label>
                    <input type="email" class="form-control" id="email" placeholder="Enter your email" required>
                </div>
                <div class="mb-3">
                    <label for="password" class="form-label">Password</label>
                    <input type="password" class="form-control" id="password" placeholder="Enter your password" required>
                </div>
                <div class="mb-3">
                    <label for="confirmPassword" class="form-label">Confirm Password</label>
                    <input type="password" class="form-control" id="confirmPassword" placeholder="Confirm your password" required>
                </div>
                <button type="submit" class="btn btn-primary w-100 mt-3">Sign Up</button>
            </form>
        </div>
        <div class="text-center mt-3">
            <span>Already have an account? <a href="login.html" target="_blank" class="text-decoration-none link">Login</a></span>
        </div>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

## OUTPUT:

![alt text](<Screenshot 2025-05-20 160311-1.png>)

![alt text](<Screenshot 2025-05-20 160328-1.png>)

![alt text](<Screenshot 2025-05-20 160414-1.png>)

![alt text](<Screenshot 2025-05-20 160457-1.png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
