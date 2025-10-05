# Project Responsive Web Design using Bootstrap
# Date:05/10/2025
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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribbble Clone</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      scroll-behavior: smooth;
      background-color: rgb(233, 233, 129);
    }
    section {
      padding: 60px 0;
    }
    .hero {
      background-color: #ea4c89; /* Dribbble pink */
      color: rgb(142, 219, 230);
      text-align: center;
      padding: 100px 20px;
    }
    .shot-card img {
      border-radius: 10px;
    }
    footer {
      background-color: #343a40;
      color: rgb(117, 178, 235);
      padding: 20px 0;
    }
  </style>
</head>
<body>

  <!-- ✅ Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light shadow-sm fixed-top">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">DribbbleClone</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link" href="#shots">Shots</a></li>
          <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- ✅ Hero Section -->
  <section class="hero" id="home">
    <div class="container">
      <h1 class="display-4 fw-bold">Discover Creative Work</h1>
      <p class="lead mt-3">A small Dribbble-style landing page clone built with Bootstrap.</p>
      <a href="#shots" class="btn btn-light btn-lg mt-3">Explore Shots</a>
    </div>
  </section>

  <!-- ✅ Shots Section -->
  <section id="shots">
    <div class="container">
      <h2 class="text-center mb-5">Recent Shots</h2>
      <div class="row g-4">
        <div class="col-md-4">
          <div class="card shot-card shadow-sm">
            <img src="image 1.jpg" class="card-img-top" alt="Shot 1">
            <div class="card-body">
              <h5 class="card-title">Creative Design 1</h5>
              <p class="card-text">A beautiful UI/UX shot showcasing modern design elements.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shot-card shadow-sm">
            <img src="image 2.jpg" class="card-img-top" alt="Shot 2">
            <div class="card-body">
              <h5 class="card-title">Creative Design 2</h5>
              <p class="card-text">A stylish mockup with clean and minimal aesthetics.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shot-card shadow-sm">
            <img src="image 3.jpg" class="card-img-top" alt="Shot 3">
            <div class="card-body">
              <h5 class="card-title">Creative Design 3</h5>
              <p class="card-text">Showcasing colorful illustrations and UI components.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ✅ About Section -->
  <section id="about" class="bg-light">
    <div class="container">
      <h2 class="text-center mb-4">About</h2>
      <p class="text-center">This is a simplified landing page clone inspired by Dribbble, built using Bootstrap. It demonstrates responsive design, cards, and navigation components.About project

Keckly is a platform that transforms collaboration into powerful investor presentations. The landing page focuses on clarity and teamwork, showing how simple it can be to prepare materials that resonate with investors.

Task

The task was to design a landing page with friendly illustrations and structured content that communicate trust, simplicity, and collaboration. The main goal was to make investor presentations feel accessible and engaging.

Process

We built the structure around bold headlines, minimal typography, and supportive illustration. A hero section introduces the value proposition with a strong tagline and a video CTA. Soft colors and vector characters emphasize teamwork and communication. Layout is kept clean with clear navigation, guiding users to templates, collaboration tools, and FAQ.

Result

The result is a welcoming landing page that blends business clarity with a human touch. Illustrations and layout balance professionalism and friendliness, helping users feel confident while preparing investor materials.</p>
    </div>
  </section>

  <!-- ✅ Contact Section -->
  <section id="contact">
    <div class="container">
      <h2 class="text-center mb-4">Contact</h2>
      <div class="row justify-content-center">
        <div class="col-md-6">
          <form>
            <div class="mb-3">
              <input type="text" class="form-control" placeholder="Your Name" required>
            </div>
            <div class="mb-3">
              <input type="email" class="form-control" placeholder="Your Email" required>
            </div>
            <div class="mb-3">
              <textarea class="form-control" rows="3" placeholder="Your Message" required></textarea>
            </div>
            <button type="submit" class="btn btn-pink w-100" style="background-color:#ea4c89; color:white;">Send Message</button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- ✅ Footer -->
  <footer class="text-center">
    <div class="container">
      <p>&copy; 2025 | Designed by Nivetha</p>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
# OUTPUT:

<img width="1366" height="712" alt="Screenshot 2025-10-05 222722" src="https://github.com/user-attachments/assets/9d2af279-ace0-4203-9d35-4d395cf8b081" />

<img width="1366" height="711" alt="Screenshot 2025-10-05 222931" src="https://github.com/user-attachments/assets/0e05ee16-4022-4a88-a773-5592341407c0" />


# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
