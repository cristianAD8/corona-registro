
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">    
  </head>
  <body>

  <nav class="navbar navbar-expand-lg bg-body-tertiary " data-bs-theme="dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavDropdown">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Features</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Pricing</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Dropdown link
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
      </ul>
    </div>
  </div>
</nav>
<BR>
</BR>

<section class="formulario container">
  <form method="post" autocomplete="off">
    <h2>Agregar registro</h2>
<div class="input-group">

<div class="input-container">
  <input type="text" name="Nit" placeholder="NIT">
</div>

<div class="input-container">
  <input type="text" name="Nombre" placeholder="Nombre">
</div>

<div class="input-container">
  <input type="text" name="Codigo" placeholder="Codigo">
</div>

<div class="input-container">
  <input type="date" name="Fecha" placeholder="Fecha">
</div>

<div class="input-container">
  <input type="text" name="Cantidad" placeholder="Cantidad">
</div>

<div class="input-container">
  <input type="text" name="Base" placeholder="Base">
</div>

<div class="input-container">
  <input type="text" name="Linea" placeholder="Linea">
</div>

<div class="input-container">
  <input type="text" name="Maquina" placeholder="Maquina">
</div>

<div class="input-container">
  <textarea type="text" name="Detalles" placeholder="Detalles"></textarea>
</div>


<div class="d-grid gap-2 col-6 mx-auto">
  <input type="submit" class="btn" name="save" onclick="myFunction()" >
  </div>
</div>
</form>
</section>

<?php 
 include("save.php");
 ?>

 <script>
  function myFunction(){
    Window.location.href="localhost/paginaderegistros"

  }
 </script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
  </body>
</html>
