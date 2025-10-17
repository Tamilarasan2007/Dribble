# Project Responsive Web Design using Bootstrap
## Date:16/10/2025

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
tamil.html
<html>
<head>
<title>Tamilarasan R - 25009942</title>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css" rel="stylesheet">
</head>
<body class="bg-light">
<nav class="navbar navbar-expand-lg navbar-dark bg-dark py-2 shadow-sm">
  <div class="container-fluid">
    <a class="navbar-brand fw-bold" href="#" style="color:#ea4c89!important;">dribbble</a>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav me-auto">
        <li class="nav-item"><a class="nav-link text-white fw-bold active" href="#" style="color:#ea4c89!important;">Shots</a></li>
        <li class="nav-item"><a class="nav-link text-white fw-bold" href="#">Designers</a></li>
        <li class="nav-item"><a class="nav-link text-white fw-bold" href="#">Jobs</a></li>
      </ul>
      <ul class="navbar-nav">
        <li class="nav-item me-2"><a class="btn btn-outline-light btn-sm" href="#">Sign In</a></li>
        <li class="nav-item"><a class="btn btn-sm text-white" href="#" style="background-color:#ea4c89; border-color:#ea4c89;">Sign Up</a></li>
      </ul>
    </div>
  </div>
</nav>

<section class="text-center bg-white border-bottom p-3 shadow-sm" style="margin-top:0; border-top:1px solid #e0e0e0;">
    <h1 class="display-6 fw-bold mb-1" style="color:#343a40;">Discover the World's Top Designers & Creative Professionals.</h1>
    <p class="lead text-muted mb-0">Explore portfolios, find inspiration, or hire design talent.</p>
</section>

<section class="bg-white border-bottom p-2">
  <div class="container-fluid d-flex align-items-center">
    <a href="#" class="text-dark fw-bold ms-3 text-decoration-none small">Popular</a>
    <a href="#" class="text-dark fw-bold ms-3 text-decoration-none small">New</a>
    <a href="#" class="text-dark fw-bold ms-3 text-decoration-none small">Following</a>
    <div class="ms-auto me-3 d-flex align-items-center">
      <a href="#" class="text-muted me-3 text-decoration-none small">Filters <i class="bi bi-funnel"></i></a>
      <div class="btn-group">
        <select class="form-select form-select-sm shadow-sm" aria-label="Sort by">
          <option selected>Now</option>
          <option value="1">All Time</option>
        </select>
      </div>
    </div>
  </div>
</section>

<section class="py-3">
  <div class="container-fluid">
    <div class="row g-2 justify-content-center">
      
      <div class="col-lg-2 col-md-4 col-sm-6"><div class="card shadow-sm border-0 rounded-3"><img src="https://picsum.photos/seed/d1/300/200" class="card-img-top rounded-top" alt="Shot 1" style="height:160px; object-fit:cover;"><div class="card-body p-2"><h6 class="card-title m-0 small fw-bold">UI Kit Concept</h6><p class="card-text text-muted m-0" style="font-size:.75rem;">by arun</p></div></div></div>
      <div class="col-lg-2 col-md-4 col-sm-6"><div class="card shadow-sm border-0 rounded-3"><img src="https://picsum.photos/seed/d2/300/200" class="card-img-top rounded-top" alt="Shot 2" style="height:160px; object-fit:cover;"><div class="card-body p-2"><h6 class="card-title m-0 small fw-bold">Branding Mockup</h6><p class="card-text text-muted m-0" style="font-size:.75rem;">by tamilarasan</p></div></div></div>
      <div class="col-lg-2 col-md-4 col-sm-6"><div class="card shadow-sm border-0 rounded-3"><img src="https://picsum.photos/seed/d3/300/200" class="card-img-top rounded-top" alt="Shot 3" style="height:160px; object-fit:cover;"><div class="card-body p-2"><h6 class="card-title m-0 small fw-bold">Mobile App UI</h6><p class="card-text text-muted m-0" style="font-size:.75rem;">by rakesh</p></div></div></div>
      <div class="col-lg-2 col-md-4 col-sm-6"><div class="card shadow-sm border-0 rounded-3"><img src="https://picsum.photos/seed/d4/300/200" class="card-img-top rounded-top" alt="Shot 4" style="height:160px; object-fit:cover;"><div class="card-body p-2"><h6 class="card-title m-0 small fw-bold">Dashboard Design</h6><p class="card-text text-muted m-0" style="font-size:.75rem;">by manoj</p></div></div></div>
      <div class="col-lg-2 col-md-4 col-sm-6"><div class="card shadow-sm border-0 rounded-3"><img src="https://picsum.photos/seed/d5/300/200" class="card-img-top rounded-top" alt="Shot 5" style="height:160px; object-fit:cover;"><div class="card-body p-2"><h6 class="card-title m-0 small fw-bold">Website Layout</h6><p class="card-text text-muted m-0" style="font-size:.75rem;">by iyyappan</p></div></div></div>
      <div class="col-lg-2 col-md-4 col-sm-6"><div class="card shadow-sm border-0 rounded-3"><img src="https://picsum.photos/seed/d6/300/200" class="card-img-top rounded-top" alt="Shot 6" style="height:160px; object-fit:cover;"><div class="card-body p-2"><h6 class="card-title m-0 small fw-bold">Illustration Art</h6><p class="card-text text-muted m-0" style="font-size:.75rem;">by sachin</p></div></div></div>
      
      <div class="col-lg-2 col-md-4 col-sm-6"><div class="card shadow-sm border-0 rounded-3"><img src="https://picsum.photos/seed/d7/300/200" class="card-img-top rounded-top" alt="Shot 7" style="height:160px; object-fit:cover;"><div class="card-body p-2"><h6 class="card-title m-0 small fw-bold">Product Page</h6><p class="card-text text-muted m-0" style="font-size:.75rem;">by tharun</p></div></div></div>
      <div class="col-lg-2 col-md-4 col-sm-6"><div class="card shadow-sm border-0 rounded-3"><img src="https://picsum.photos/seed/d8/300/200" class="card-img-top rounded-top" alt="Shot 8" style="height:160px; object-fit:cover;"><div class="card-body p-2"><h6 class="card-title m-0 small fw-bold">Login Screen</h6><p class="card-text text-muted m-0" style="font-size:.75rem;">by mohan</p></div></div></div>
      <div class="col-lg-2 col-md-4 col-sm-6"><div class="card shadow-sm border-0 rounded-3"><img src="https://picsum.photos/seed/d9/300/200" class="card-img-top rounded-top" alt="Shot 9" style="height:160px; object-fit:cover;"><div class="card-body p-2"><h6 class="card-title m-0 small fw-bold">Checkout Flow</h6><p class="card-text text-muted m-0" style="font-size:.75rem;">by sabari</p></div></div></div>
      <div class="col-lg-2 col-md-4 col-sm-6"><div class="card shadow-sm border-0 rounded-3"><img src="https://picsum.photos/seed/d10/300/200" class="card-img-top rounded-top" alt="Shot 10" style="height:160px; object-fit:cover;"><div class="card-body p-2"><h6 class="card-title m-0 small fw-bold">Admin Panel</h6><p class="card-text text-muted m-0" style="font-size:.75rem;">by virat</p></div></div></div>
      <div class="col-lg-2 col-md-4 col-sm-6"><div class="card shadow-sm border-0 rounded-3"><img src="https://picsum.photos/seed/d11/300/200" class="card-img-top rounded-top" alt="Shot 11" style="height:160px; object-fit:cover;"><div class="card-body p-2"><h6 class="card-title m-0 small fw-bold">Blog Card</h6><p class="card-text text-muted m-0" style="font-size:.75rem;">by hiresh</p></div></div></div>
      <div class="col-lg-2 col-md-4 col-sm-6"><div class="card shadow-sm border-0 rounded-3"><img src="https://picsum.photos/seed/d12/300/200" class="card-img-top rounded-top" alt="Shot 12" style="height:160px; object-fit:cover;"><div class="card-body p-2"><h6 class="card-title m-0 small fw-bold">Landing Hero</h6><p class="card-text text-muted m-0" style="font-size:.75rem;">by prethish</p></div></div></div>

      <div class="col-lg-2 col-md-4 col-sm-6"><div class="card shadow-sm border-0 rounded-3"><img src="https://picsum.photos/seed/d13/300/200" class="card-img-top rounded-top" alt="Shot 13" style="height:160px; object-fit:cover;"><div class="card-body p-2"><h6 class="card-title m-0 small fw-bold">E-commerce Checkout</h6><p class="card-text text-muted m-0" style="font-size:.75rem;">by Raj</p></div></div></div>
      <div class="col-lg-2 col-md-4 col-sm-6"><div class="card shadow-sm border-0 rounded-3"><img src="https://picsum.photos/seed/d14/300/200" class="card-img-top rounded-top" alt="Shot 14" style="height:160px; object-fit:cover;"><div class="card-body p-2"><h6 class="card-title m-0 small fw-bold">Dark Mode UI</h6><p class="card-text text-muted m-0" style="font-size:.75rem;">by Sheela</p></div></div></div>
      <div class="col-lg-2 col-md-4 col-sm-6"><div class="card shadow-sm border-0 rounded-3"><img src="https://picsum.photos/seed/d15/300/200" class="card-img-top rounded-top" alt="Shot 15" style="height:160px; object-fit:cover;"><div class="card-body p-2"><h6 class="card-title m-0 small fw-bold">Vector Icon Set</h6><p class="card-text text-muted m-0" style="font-size:.75rem;">by John</p></div></div></div>
      <div class="col-lg-2 col-md-4 col-sm-6"><div class="card shadow-sm border-0 rounded-3"><img src="https://picsum.photos/seed/d16/300/200" class="card-img-top rounded-top" alt="Shot 16" style="height:160px; object-fit:cover;"><div class="card-body p-2"><h6 class="card-title m-0 small fw-bold">404 Error Page</h6><p class="card-text text-muted m-0" style="font-size:.75rem;">by Sam</p></div></div></div>
      <div class="col-lg-2 col-md-4 col-sm-6"><div class="card shadow-sm border-0 rounded-3"><img src="https://picsum.photos/seed/d17/300/200" class="card-img-top rounded-top" alt="Shot 17" style="height:160px; object-fit:cover;"><div class="card-body p-2"><h6 class="card-title m-0 small fw-bold">Mobile Game Art</h6><p class="card-text text-muted m-0" style="font-size:.75rem;">by Alex</p></div></div></div>
      <div class="col-lg-2 col-md-4 col-sm-6"><div class="card shadow-sm border-0 rounded-3"><img src="https://picsum.photos/300/200" class="card-img-top rounded-top" alt="Shot 18" style="height:160px; object-fit:cover;"><div class="card-body p-2"><h6 class="card-title m-0 small fw-bold">Crypto Dashboard</h6><p class="card-text text-muted m-0" style="font-size:.75rem;">by Bob</p></div></div></div>

    </div>
  </div>
</section>      
<footer class="text-white text-center" style="background-color:#212529; padding:15px 0; margin-top:20px; font-size:.85rem;">
  <p class="m-0">&copy; 2025 <span style="color:#ea4c89; font-weight:600;">Developed By TAMILARASAN R (25009942)</span> | Inspired by Dribble</p>
</footer>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (92).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
