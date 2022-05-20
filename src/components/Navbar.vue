<template>
  <div class="navbar">
    <nav class="navbar navbar-expand-md fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#"><img src="../assets/images/getajob_logo-removebg-preview(1).png" alt=""></a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse d-flex justify-content-around align-center" id="navbarCollapse">
        <ul class="navbar-nav me-auto mb-2 mb-md-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Companies</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Candidates</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Assessment</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Post a Job</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Career Advice</a>
            </li>
        </ul>
        <div class="btn-links">
            <a href="">Sign Up</a>
            <button class="btn-header">Log In</button>
        </div>
      </div>
    </div>
  </nav>
    
  </div>
</template>

<script>
export default {
  name: 'Navbar',
 
}
</script>


<style scoped>
  .navbar-nav > li{
    padding-left: 20px;
  }
  nav .btn-header{
    border: none;
    padding: 5px 25px;
    background-color: rgba(6, 148, 42, 0.2);
    color:rgba(6, 148, 42, 1);
    border-radius: 50px;
    font-weight: bold;
}
  .btn-links a{
    padding-right: 20px;
    color: #000;
  }
</style>
