# Project Responsive Web Design using Bootstrap
# Date:
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

# PROGRAM 
```
HOME PAGE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">Daraz</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="about.html">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="watch.html">products</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="contact.html">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class=" text-white text-center py-5" style="background-image: url(bc.jpg); width:100%;height: 200px; background-repeat: no-repeat;background-size: cover;" >
        <div class="container">
            <h1 style="font-family: 'Times New Roman'; font-size: xxx-large;color:rgb(2, 22, 53);">Welcome to Daraz</h1>
        </div>
    </header>
    <header class=" text-white text-center py-5" style="background-image: url('360_F_878511775_oodJ4DLLtkzhDBuD45UE7G0BYdhdmM7F.jpg'); background-repeat: no-repeat; background-size: cover; height: 600px;" ></header>

    <!-- Work Section -->
    <section id="work" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center">New Arrival</h2>
            <div class="row">
                <div class="col-md-3">
                    <div class="card">
                        <img src="C:\Users\admin\Desktop\Django\Figma\images (7).jpg" width="300px" height="300px" class="card-img-top" alt="Work Example">
                       
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <img src="C:\Users\admin\Desktop\Django\Figma\images (8).jpg" width="300px" height="300px" class="card-img-top" alt="Work Example">
                    
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <img src="C:\Users\admin\Desktop\Django\Figma\2644KM02_1.jpg" width="300px" height="300px"  class="card-img-top" alt="Work Example">
                        
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <img src="C:\Users\admin\Desktop\Django\Figma\product-jpeg.jpg" class="card-img-top" alt="Work Example">
                        
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <div class="container">
            <p>&copy; 2024 Daraz. All rights reserved.</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

PRODUCT PAGE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">Daraz</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="homw page.html">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="about.html">About</a>
                    </li>
                   
                    <li class="nav-item">
                        <a class="nav-link" href="contact.html">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Work Section -->
    <section id="work" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center">Women Watch</h2>
            <div class="row">
                <div class="col-md-3">
                    <div class="card">
                        <img src="C:\Users\admin\Desktop\Django\Figma\images (1).jpg" width="300px" height="300px"class="card-img-top" alt="Work Example">
                        <div class="card-body">
                            <p class="card-text"> Quartz Analog White Dial Watch</p>
                            <p>Rs.1499</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <img src="C:\Users\admin\Desktop\Django\Figma\SP80065WM01W_1 (1).jpg" width="300px" height="300px"class="card-img-top" alt="Work Example">
                        <div class="card-body">
                            <p class="card-text">Rose Gold Dial Mesh Strap Watch</p>
                            <p>Rs.1900</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <img src="C:\Users\admin\Desktop\Django\Figma\2-106-06-0052_d1.jpg" width="300px" height="300px"class="card-img-top" alt="Work Example">
                        <div class="card-body">
                            <p class="card-text">Thin store ladies watch</p>
                            <p>Rs.9999</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <img src="C:\Users\admin\Desktop\Django\Figma\images.jpg" width="300px" height="300px" class="card-img-top" alt="Work Example">
                        <div class="card-body">
                            <p class="card-text">Malibu Rose Women's Watch</p>
                            <p>Rs.1199</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section id="work" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center">Men Watches</h2>
            <div class="row">
                <div class="col-md-3">
                    <div class="card">
                        <img src="C:\Users\admin\Desktop\Django\Figma\71qJNo0Y2DL.AC_UY1000.jpg" width="300px" height="300x" class="card-img-top" alt="Work Example">
                        <div class="card-body">
                             
                            <p class="card-text"> Miami Faux Leather Strap</p>
                            <p>Rs.2899</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <img src="C:\Users\admin\Desktop\Django\Figma\download.jpg"width="300px" height="300px" class="card-img-top" alt="Work Example">
                        <div class="card-body">
                            <h5 class="card-title"> Analog Blue Dial Leather Strap</h5>
                            <p class="card-text">Rs.1499</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <img src="C:\Users\admin\Desktop\Django\Figma\images (3).jpg"  width="300px" height="300px"class="card-img-top" alt="Work Example">
                        <div class="card-body">
                            <h5 class="card-title"> Blue Dial Watches with Stunning Blue Faces </h5>
                            <p class="card-text">Rs.1749</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="card">
                        <img src="C:\Users\admin\Desktop\Django\Figma\images (2).jpg" width="300px" height="300px" class="card-img-top" alt="Work Example">
                        <div class="card-body">
                            <h5 class="card-title">Blue dial with Brown Leather </h5>
                            <p class="card-text">Rs.799.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <div class="container">
            <p>&copy; 2024 Daraz. All rights reserved.</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
ABOUT PAGE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">Daraz</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="homw page.html">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active" href="about.html">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="contact.html">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- About Section -->
    <section class="py-5">
        <div class="container">
            <h2 class="text-center">About Us</h2>
            <p class="text-center">Discover the story behind Daraz and our passion for exceptional timepieces.</p>

            <div class="row">
                <div class="col-md-6">
                    <h4>Our Mission</h4>
                    <p>At Daraz, our mission is to bring timeless elegance and precision to your wrist. We are committed to offering a curated selection of watches that blend style, functionality, and craftsmanship, catering to watch enthusiasts and everyday wearers alike.</p>
                </div>
                <div class="col-md-6">
                    <h4>Our Story</h4>
                    <p>Founded by a group of watch aficionados, Daraz started with a vision to make quality timepieces accessible to everyone. From classic designs to modern innovations, we have grown into a trusted destination for watch lovers seeking authenticity and style.</p>
                </div>
            </div>

            <div class="text-center mt-4">
                <img src="C:\Users\admin\Desktop\Django\Figma\team.jpg" alt="Our Team" class="img-fluid rounded">
                <p class="mt-2">Our dedicated team works tirelessly to bring you the finest collection of watches from around the globe.</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <div class="container">
            <p>&copy; 2024 Daraz. All rights reserved.</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
CONTACT US PAGE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">Daraz</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="homw page.html">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="about.html">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active" href="contact.html">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Contact Section -->
    <section class="py-5">
        <div class="container">
            <h2 class="text-center">Contact Us</h2>
            <p class="text-center">We would love to hear from you! Feel free to reach out for collaborations, inquiries, or just to say hi.</p>

            <div class="row">
                <!-- Contact Form -->
                <div class="col-md-6">
                    <h4>Send Us a Message</h4>
                    <form>
                        <div class="mb-3">
                            <label for="name" class="form-label">Name</label>
                            <input type="text" class="form-control" id="name" placeholder="Your Name">
                        </div>
                        <div class="mb-3">
                            <label for="email" class="form-label">Email</label>
                            <input type="email" class="form-control" id="email" placeholder="Your Email">
                        </div>
                        <div class="mb-3">
                            <label for="message" class="form-label">Message</label>
                            <textarea class="form-control" id="message" rows="3" placeholder="Your Message"></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">Submit</button>
                    </form>
                </div>

                <!-- Contact Details -->
                <div class="col-md-6">
                    <h4>Contact Details</h4>
                    <ul class="list-unstyled">
                        <li><strong>Email:</strong> contact@dribbbleclone.com</li>
                        <li><strong>Phone:</strong> +1 (123) 456-7890</li>
                        <li><strong>Address:</strong> 123 Creative Lane, Design City, DC 45678</li>
                    </ul>

                    <h4>Follow Us</h4>
                    <ul class="list-inline">
                        <li class="list-inline-item">
                            <a href="#" class="text-decoration-none">Facebook</a>
                        </li>
                        <li class="list-inline-item">
                            <a href="#" class="text-decoration-none">Twitter</a>
                        </li>
                        <li class="list-inline-item">
                            <a href="#" class="text-decoration-none">Instagram</a>
                        </li>
                        <li class="list-inline-item">
                            <a href="#" class="text-decoration-none">LinkedIn</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <div class="container">
            <p>&copy; 2024 Daraz. All rights reserved.</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
# OUTPUT:
![Screenshot (108)](https://github.com/user-attachments/assets/0d5afbcc-6b5f-4f0f-9882-f686be8e696b)
![Screenshot (109)](https://github.com/user-attachments/assets/e6690f42-5267-4cb1-9924-e51fed0fbf14)
![Screenshot (110)](https://github.com/user-attachments/assets/6b5bcb3b-a12b-4f6c-80c7-628968dcdf70)
![Screenshot (111)](https://github.com/user-attachments/assets/e6da87d1-e17f-47ec-9616-25936344f5f5)
![Screenshot (112)](https://github.com/user-attachments/assets/e06eef76-6a1a-4973-8e58-26f1a2ca04a6)
![Screenshot (113)](https://github.com/user-attachments/assets/1133f4ba-b6d6-4b14-a4de-fdc2648a556b)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
