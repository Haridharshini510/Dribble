# Project Responsive Web Design using Bootstrap
## Date:22/12/24

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
homepage.html

<html>
<head>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-light" style="margin: 0px;  padding-right: 10px;">
  <div>
    <div class="row align-items-center p-2 bg-dark" >
      
      <div class="col-6  d-flex align-items-center">
        <img src="dri-removebg-preview.png" class="top-left-image" style="width: 100px; height: auto;">
        
        <a href="1" class="m-0 ms-3 fs-5 text-white" style="text-decoration: none;">Home</a>
        <a href="2" class="m-0 ms-3 fs-5 text-white" style="text-decoration: none;">Designers</a>
        <a href="3" class="m-0 ms-3 fs-5 text-white" style="text-decoration: none;">Jobs</a>
        <a href="4" class="m-0 ms-3 fs-5 text-white" style="text-decoration: none;">Teams</a>
        <a href="5" class="m-0 ms-3 fs-5 text-white" style="text-decoration: none;">Collaboration</a>
      </div>
      <div class="col-6 d-flex fs-5">
        <button type="button" class=" col-2 btn btn-info text-white"  style="margin: 7px;">Sign up</button>
        <button type="button" class="col-2 btn btn-info text-white" style="margin: 7px;">Sign in</button>
        <input type="search" class=" form-control fs-5" style="margin: 7px; margin-right:7px ;" placeholder="Search">
      </div>

    </div>
  </div>
  <div class="row">
    <div class="col-sm-12 p-3 bg-secondary  text-white text-center fs-4">To see what's new     <button class="btn btn-dark">Learn more</button> <button class="btn btn-warning">Sign up</button></div>
  </div>
  <h5 style="padding: 10px;"><i>Designs and Designers</i></h5>
  <div class="row align-items-center  d-block mx-auto">
    <img class="col-sm-3 " style="width: 240px;" src="d6f518d1143e1de99a7e046fa276442c.jpg" alt="5">
    <img class="col-sm-3 " style="width: 240px;" src="517cd97c8bd7b212b8f75759da53293d.jpg" alt="1">
    <img class="col-sm-3" style="width: 240px;" src="2438b1d837c47f288f2724d429c56140.jpg" alt="2">
    <img class="col-sm-3" style="width: 240px;" src="363239ad815ea1bc2c059cfcd124437d.jpg" alt="3">
    <img class="col-sm-3" style="width: 240px;" src="bf5012111058ad397edbbe9e246b4382.jpg" alt="4">
  </div>
  <div class="row align-items-center  d-block mx-auto">
    <a href="1" class="col-sm-3 "  style="padding-right: 200px;">Jhon</a>
    <a href="2" class="col-sm-3 "  style="padding-right: 200px;">James</a>
    <a href="3" class="col-sm-3 "  style="padding-right: 200px;">Lily</a>
    <a href="4" class="col-sm-3 "  style="padding-right: 200px;">Rose</a>
    <a href="5" class="col-sm-3 "  style="padding-right: 200px;">Max</a>

  </div>
  <br>
  <div class="row align-items-center  d-block mx-auto">
    <img class="col-sm-3 " style="width: 240px;" src="a1a97a30472d0da0c5f209cd6a38004f.jpg" alt="5">
    <img class="col-sm-3 " style="width: 240px;" src="c3f2e4b74b2cc3edc40d84f797f8ef52.jpg" alt="1">
    <img class="col-sm-3" style="width: 240px;" src="6b52455a85f11b86bf9aa152adbde22a.jpg" alt="2">
    <img class="col-sm-3" style="width: 240px;" src="49722f6c6e454887d2095e6d4a958de5.jpg" alt="3">
    <img class="col-sm-3" style="width: 240px;" src="8ec2ee6c1167327bd1476b97b7e94eee.jpg" alt="4">
  </div>
  <div class="row align-items-center  d-block mx-auto">
    <a href="1" class="col-sm-3 "  style="padding-right: 200px;">Jackson</a>
    <a href="2" class="col-sm-3 "  style="padding-right: 200px;">Jennie</a>
    <a href="3" class="col-sm-3 "  style="padding-right: 200px;">Lara</a>
    <a href="4" class="col-sm-3 "  style="padding-right: 200px;">Joe</a>
    <a href="5" class="col-sm-3 "  style="padding-right: 200px;">Jack</a>

  </div>
</body>
</html>
```
## OUTPUT:
![alt text](<Screenshot (102).png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
