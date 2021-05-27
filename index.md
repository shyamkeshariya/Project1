<!DOCTYPE html>
<html>

<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width">
	<title>repl.it</title>
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x"
	 crossorigin="anonymous">
  <script src="https://kit.fontawesome.com/bc43582ce1.js" crossorigin="anonymous"></script>
</head>

<body class="bg-dark">

	<nav class="navbar sticky-top navbar-expand-lg navbar-dark bg-dark border-bottom border-2">
		<div class="container-fluid">
			<a class="navbar-brand" href="#">Bhavik Keshariya</a>
			<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse me-2" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#hero">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#skills">My Skills</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#work">My Work</a>
        <li class="nav-item">
          <a class="nav-link" href="#contact">Contact me</a>
        </li>
        </li>
      </ul>
    </div>
  </div>
</nav>

<main class="container mt-3">
  <section id="hero" class="d-flex justify-content-sm-center justify-content-md-evenly align-items-sm-center flex-column-reverse gap-2 flex-md-row p-4 border border-4 rounded">
    <div class="d-flex justify-content-sm-center align-items-sm-center flex-column justify-content-md-start align-items-md-start bg-dark">
      <h5 class="text-white">Hi!👋</h5>
      <h1 class="text-white">I'm Bhavik Keshariya</h1>
      <p class="text-white">Currently, I'm studying IT Engineering</p>
      <button class="btn btn-light btn-sm fw-bold">My Cool Resume🥳</button>
    </div>
    <div class="d-md-none w-50 w-50">
      <img src="https://pbs.twimg.com/profile_images/1291998248924635137/CxLrSl_o.jpg" alt="Bhavik" class="w-100 h-100 rounded-circle shadow p-2 bg-light rounded"> 
    </div>
    <div class="d-none d-md-block w-25 w-25">
      <img src="https://pbs.twimg.com/profile_images/1291998248924635137/CxLrSl_o.jpg" alt="Bhavik" class="w-100 h-100 rounded-circle shadow p-2 bg-light rounded"> 
    </div>
  </section>

  <section id="skills" class="bg-dark p-4 mt-4 rounded border border-4">
  <h1 class="text-white text-center">My Skill Set</h1>
  <div class="d-flex justify-content-evenly">
    <i class="fab fa-html5 p-1 fa-5x" style="color:#f06529"></i>
    <i class="fab fa-css3-alt p-1 fa-5x" style="color:#264de4"></i>
    <i class="fab fa-bootstrap p-1 fa-5x" style="color:#563d7c "></i>
  </div>
  </section>

  <section id="work" class="bg-dark p-4 mt-4 rounded border border-4">
    <h1 class="text-white text-center">My Work</h1>
  <div class="d-flex flex-column flex-md-row justify-content-md-evenly gap-3"> 
    <div class="card p-1 mt-1">
     <img src="https://images.unsplash.com/photo-1488590528505-98d2b5aba04b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80" class="card-img-top" alt="...">
      <div class="card-body">
      <h5 class="card-title">Portfolio Website</h5>
      <p class="card-text">Build an amazing responsive website using Bootstrap</p>
      <a href="#" class="btn btn-primary">View Source <i class="fab fa-github"></i></a>
      </div>
   </div>
   <div class="card p-1 mt-1">
     <img src="https://images.unsplash.com/photo-1488590528505-98d2b5aba04b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80" class="card-img-top" alt="...">
      <div class="card-body">
      <h5 class="card-title">Portfolio Website</h5>
      <p class="card-text">Build an amazing responsive website using Bootstrap</p>
      <a href="#" class="btn btn-primary">View Source <i class="fab fa-github"></i></a>
      </div>
   </div>
   <div class="card p-1 mt-1">
     <img src="https://images.unsplash.com/photo-1488590528505-98d2b5aba04b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80" class="card-img-top" alt="...">
      <div class="card-body">
      <h5 class="card-title">Portfolio Website</h5>
      <p class="card-text">Build an amazing responsive website using Bootstrap</p>
      <a href="#" class="btn btn-primary">View Source <i class="fab fa-github"></i></a>
      </div>
   </div>
  </div>
  </section>

  <section id="contact" class="bg-dark p-4 mt-4 rounded border border-4">
    <h1 class="text-white text-center">Contact me</h1>
<div class="row">
  <div class="col-md-8">
    <form>
      <div class="mb-3 text-white">
  <label for="exampleFormControlInput1" class="form-label">Email address</label>
  <input type="email" required class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
</div>
<div class="mb-3 text-white">
  <label for="exampleFormControlTextarea1" class="form-label">Your Message</label>
  <textarea class="form-control" required placeholder="Enter your Amazing message..." id="exampleFormControlTextarea1" rows="3"></textarea>
</div>
<input class="btn btn-primary" type="submit" value="Submit">
    </form>
  </div>
  <div class="col-md-4">
    <div>
      <p class="text-white"><i class="fas fa-envelope m-2" style="color:#FFFFFF"></i>bhavik.keshariya17303@marwadieducation.edu.in</p>
      <button type="button" class="btn btn-outline-light">

        <a href="https://github.com/shyamkeshariya"><i class="fab fa-github" style="color:#ffffff"></i></a>
      </button>
    </div>
</div>
  </section>
</main>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4" crossorigin="anonymous"></script>
</body>
</html>
