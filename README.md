# Project Responsive Web Design using Bootstrap
# Date:22/05/25
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribbble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg  bg-light">
    <div class="container">
      <a class="navbar-brand" href="#">Dribbble Clone</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto ">
          <li class="nav-item"><a class="nav-link" href="#">Explore</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Sign In</a></li>
          <li class="nav-item"><a class="btn btn-primary" href="#">Sign Up</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <div class="container text-center my-5">
    <h1 class="display-4">DISCOVER THE WORLDS TOP DESIGNERS & CREATIVES</h1>
    <p class="lead">Showcase your work, discover inspiration, and connect with the creative community.</p>
    <a href="#" class="btn btn-primary btn-lg">VIEW</a>
  </div>

  <!-- Featured Designs -->
  <div class="container my-5">
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card">
          <img src="original-ab9a8b324ec408ab1df66aff79301f03.png" class="card-img-top" alt="Design 1">
          <div class="card-body">
            <h5 class="card-title"> Robotic Surgery</h5>
            <p class="card-text">Health care is, at its core, human-centered; however, patients and providers are finding that artificial intelligence (AI) is becoming more and more present in all aspects of health.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="stockmarket.png" class="card-img-top" alt="Design 2">
          <div class="card-body">
            <h5 class="card-title">Stock market</h5>
            <p class="card-text">The stock market as a whole is an exchange mechanism that helps investors buy and sell shares in publicly traded companies. </p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="living.png" class="card-img-top" alt="Design 3">
          <div class="card-body">
            <h5 class="card-title">Living with Nature</h5>
            <p class="card-text">By choosing plastic free options, you can reduce waste and help protect the planet. Explore a wide range of plastic free products</p>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="container my-5">
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card">
          <img src="ai power.png" class="card-img-top" alt="Design 1">
          <div class="card-body">
            <h5 class="card-title">AI Powered pattern</h5>
            <p class="card-text">An AI pattern generator uses machine learning algorithms to create patterns and designs from basic inputs.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="ai.jpg" class="card-img-top" alt="Design 2">
          <div class="card-body">
            <h5 class="card-title">Empowering Minds with Intelligenct BCI</h5>
            <p class="card-text">BCI is an artificial intelligence (AI) system that can identify patterns within the brain signals. BCI helps measure brain activity and takes out the features.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="watch.png" class="card-img-top" alt="Design 3">
          <div class="card-body">
            <h5 class="card-title">SmartWatch</h5>
            <p class="card-text">A smartwatch is a portable wearable computer that resembles a wristwatch,Most modern smartwatches are operated via a touchscreen.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
        
            

  <!-- Footer -->
  <footer class="bg-secondary py-4">
    <div class="container text-center">
      <p class="mb-0">&copy; Devloped by : K.Sivaharibalan(24007220)</p>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

# OUTPUT:
![image](https://github.com/user-attachments/assets/bc7535c9-8710-4f00-8c62-50ad034c2ba6)

![image](https://github.com/user-attachments/assets/32b28375-5d93-4e46-bef3-da230540b5cf)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
