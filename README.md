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
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Dribbble Clone</title>
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css"
    rel="stylesheet"
  />
  <style>
    .hero {
      background: url('https://i.pinimg.com/736x/c5/23/ef/c523ef19dd3ac5cbb427cd51225884de.jpg') center center/cover no-repeat;
      height: 400px;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .hero h1 {
      background-color: rgba(0, 0, 0, 0.5);
      padding: 1rem;
      border-radius: 10px;
    }
    .gallery img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
    }
    footer {
      background-color: #f8f9fa;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light shadow-sm">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">Dribbble Clone</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
    </div>
  </nav>

  <!-- Hero Section -->
  <div class="hero">
    <h1>Discover the World's Top Designers</h1>
  </div>

  <!-- Gallery Section -->
  <div class="container mt-5 gallery">
    <div class="row g-4">
      <div class="col-md-3 col-sm-6">
        <img src="https://i.pinimg.com/736x/35/41/f5/3541f51111a3f65ffa0e9389097e7b45.jpg" alt="Design 1" />
      </div>
      <div class="col-md-3 col-sm-6">
        <img src="https://i.pinimg.com/736x/b4/ca/96/b4ca96486909fb272ff26353bcf63c67.jpg" alt="Design 2" />
      </div>
      <div class="col-md-3 col-sm-6">
        <img src="https://i.pinimg.com/736x/30/0c/16/300c1690ed9e03a8a9be361a8e7243e8.jpg"  alt="Design 3"/>
      </div>
      <div class="col-md-3 col-sm-6">
        <img src="https://i.pinimg.com/736x/25/1b/f2/251bf282c0ec7a434d03f5a77f774983.jpg" alt="Design 4" />
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer>
    <p>Designed by Ezhil Nevedha K</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## OUTPUT:
![Screenshot 2025-05-13 223118](https://github.com/user-attachments/assets/f37dc8a2-20dd-43de-a568-c5a741386000)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
