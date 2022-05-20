<template>
  <div class="body">
    <header>
      <Navbar />
    </header>
    <section class="jobs">
      <div class="container">
        <div class="row d-flex justify-content-between align-items-center">
            <div class="col-md-5 content">
              <h1 class="jobs_header">Find a <span style="color:rgba(6, 148, 42, 1);">job</span> easily</h1>
              <p>With verified, up-to-date job listings directly from employer websites, we create a premium experience for job seekers, employers, and data seekers alike.</p>
              <searchBar />
              <div class="trustees">
                <h6>Trusted by:</h6>
                <img src="./assets/images/paystack-removebg-preview.png" alt="" class="trustee_img">
                <img src="./assets/images/google-removebg-preview.png" alt="" class="trustee_img">
                <img src="./assets/images/kpmg-removebg-preview.png" alt="" class="trustee_img">
              </div>
            </div>
            <div class="col-md-6 hero">
              <img src="./assets/images/image(2).png" alt="" class="hero_image">
            </div>
        </div>
        
      </div>
    </section>
    <section class="container recommended">
      <h2 class="fw-bold fs-2 py-5">Recommended Jobs</h2>
      <div class="recommended_slides">
        
        <div class="card">
          <a href="" class="text-end"><button class="btn_card">Full Time</button></a>
          <div class="card-body text-center my-3">
            <img src="./assets/images/paystack.png" alt="paystack" class="img_card text-center">
            <h5 class="fs-5 py-4 fw-bold text-center">QA Engineer</h5>
          </div>
          <div class="card_footer">
              <p class="fw-bold my-3">Paystack</p>
              <div class="d-flex justify-content-between">
                <p><i class="fas fa-map-marker-alt me-2"></i>Lagos, Nigeria</p> 
                <a href="#"><button class="btn_card_footer">Apply Here</button></a>
              </div> 
          </div>
        </div> 
        <div class="card ">
          <a href="" class="text-end"><button class="btn_card">Part Time</button></a>
          <div class="card-body text-center my-3">
            <img src="./assets/images/google.png" alt="google" class="img_card text-center">
            <h5 class="fs-5 py-4 fw-bold text-center">Product Analyst</h5>
          </div>
          <div class="card_footer">
              <p class="fw-bold my-3">Google</p>
              <div class="d-flex justify-content-between">
                <p><i class="fas fa-map-marker-alt me-2"></i>Lagos, Nigeria</p> 
                <a href="#"><button class="btn_card_footer">Apply Here</button></a>
              </div> 
          </div>
        </div> 
        <div class="card">
          <a href="" class="text-end"><button class="btn_card">Full Time</button></a>
          <div class="card-body text-center my-3">
            <img src="./assets/images/flutterwave.png" alt="flutterwave" class="img_card text-center">
            <h5 class="fs-5 py-4 fw-bold text-center">HR Manager</h5>
          </div>
          <div class="card_footer">
              <p class="fw-bold my-3">Flutterwave</p>
              <div class="d-flex justify-content-between">
                <p><i class="fas fa-map-marker-alt me-2"></i>Abuja, Nigeria</p> 
                <a href="#"><button class="btn_card_footer">Apply Here</button></a>
              </div> 
          </div>
        </div> 
        <div class="card">
          <a href="" class="text-end"><button class="btn_card">Full Time</button></a>
          <div class="card-body text-center my-3">
            <img src="./assets/images/access.png" alt="access" class="img_card text-center">
            <h5 class="fs-5 py-4 fw-bold text-center">QA Engineer</h5>
          </div>
          <div class="card_footer">
              <p class="fw-bold my-3">Access</p>
              <div class="d-flex justify-content-between">
                <p><i class="fas fa-map-marker-alt me-2"></i>Lagos, Nigeria</p> 
                <a href="#"><button class="btn_card_footer">Apply Here</button></a>
              </div> 
          </div>
        </div> 
        
      </div>
    </section>
    <section class="works">
      <div class="container ">
        <div class="row">
          <div class="col-md-7 work_images">
            <div class="box">
              <img src="./assets/images/groupImage.svg" alt="" class="img-fluid" >
            </div>
          </div>
          <div class="col-md-5 work_content">
            <h2 class="fw-bold">How It works</h2>
            <p>Getajob helps you find the right job easily. Getajob helps you find the right job easily. Getajob helps you find the right job easily.</p>
            <div>
              <ul>
                <li class="py-2">
                  <h5><img src="./assets/images/group.png" alt="" class="pe-2"> Search Jobs</h5>
                  <p>We have jobs in the most popular industries and with top companies. Plus, you can create alerts so you never miss a job opportunity.</p>
                </li>
                <li class="py-2">
                  <h5><img src="./assets/images/group.png" alt="" class="pe-2">Create a Profile and Get Noticed</h5>
                  <p>Create a profile to showcase your skills and experience so recruiters can find you. Upload your CV so you can apply for jobs quickly and easily.</p>
                </li>
                <li class="py-2">
                  <h5><img src="./assets/images/group.png" alt="" class="pe-2">Apply for jobs</h5>
                  <p>Find the training you need to improve your skills, or visit our Career Center for tips and advice to build your career.</p>
                </li>
              </ul>
            </div>
          </div>
        </div>
        
      </div>
      
    </section>
    <section class="categories">
      <div class="container container_catgeories">
        <div class="box_group">
          <div>
              <img src="./assets/images/oil.svg" alt="">
          <h6 class="fw-bold py-2">Oil and Gas</h6>
              <p>(20 new jobs)</p>
          </div>
          
        </div>
        <div class="box_group">
          <div>
            <img src="./assets/images/healthcare.svg" alt="">
            <h6 class="fw-bold py-2">Healthcare</h6>
            <p>(10 new jobs)</p>
          </div>
          
        </div>
        <div class="box_group">
          <div>
            <img src="./assets/images/education.svg" alt="">
            <h6 class="fw-bold py-2">Education</h6>
            <p>(10 new jobs)</p>
          </div>
          
        </div>
        <div class="box_group">
          <div>
            <img src="./assets/images/accounting.svg" alt="">
            <h6 class="fw-bold py-2">Accounting</h6>
            <p>(10 new jobs)</p>
          </div>
          
        </div>
        <div class="box_group">
          <div>
            <img src="./assets/images/design.svg" alt="">
            <h6 class="fw-bold py-2">Design, Art and Multimedia</h6>
            <p>(20 new jobs)</p>
          </div>
          
        </div>
        <div class="box_group">
          <div>
            <img src="./assets/images/Laptop.svg" alt="">
              <h6 class="fw-bold py-2">Technology</h6>
            <p>(10 new jobs)</p>
          </div>
          
        </div>
        <div class="box_group">
          <div>
            <img src="./assets/images/security.svg" alt="">
            <h6 class="fw-bold py-2">Security</h6>
            <p>(10 new jobs)</p>
          </div>
          
        </div>
        <div class="box_group">
          <div>
            <img src="./assets/images/analyst.svg" alt="">
            <h6 class="fw-bold py-2">Data Analyst</h6>
            <p>(10 new jobs)</p>
          </div>
          
        </div>
      </div>
    </section>
    <section class="companies">
      <div class="container">
        <div class="row company_section">
          <div class="col-md-6 companies_content">
            <h2>Over  1000+  jobs from top companies in our network</h2>
            <p>Every day we index millions of jobs directly from employer websites. We’re committed to accurate, high-quality jobs so you won’t find old, duplicated, or spammy listings here.</p>
            <p>Organize and automate your job search while at home or on the go. We’ll deliver new, relevant jobs of interest straight to your inbox.</p>
            <a href="" class="companies_link">Learn more <i class="fas fa-arrow-right"></i></a>
          </div>
          <div class="col-md-6 companies_image">
            <img src="./assets/images/Logos.svg" alt="Companies Logos" class="img-fluid">
          </div>
        </div>
        
      </div>
    </section>
    <section class="customers">
      <div class="container">
        <div class="row customer_box">
           <h2 class="fw-bold py-5">What are our customers <br> saying</h2>
          <div class="col-md-5 box-image">
            <img src="./assets/images/customer_image.png" alt="customer" classs="customer_image">
          </div>
          <div class="col-md-7 box-content">
            <img src="./assets/images/cust.png" alt="" class="box-content_image">
            <p>The platform is really convenient to reach out to companies & I have managed to secure 2 interviews already! I can also track my application status instead of wondering whether the company has seen or shortlisted me</p>
            <h5>Irma Black</h5>
            <p style="color:rgba(155, 155, 155, 1);">HR Manager at MasterCard</p>
          </div>
        </div>
      </div>
    </section>
    <section class="get-started">
      <div class="container">
        <div class="container_started d-flex justify-content-end align-items-center">
          <div class="content-started">
            <h3 class="fw-bold">Get a Job you actually like</h3>
          <p>Create an account and start applying</p>
          <a href="" class="btn-get_started">Get Started</a>
          </div>
          
        </div>
      </div>
    </section>
    <footer class="footer">
      <div class="container">
        <div class="row">
          <div class="col-md-3 footer_box">
            <img src="./assets/images/footer_logo.svg" alt="" class="footer_logo">
            <p>Getajobng provides a full online service for anyone looking for a new job. We're not a recruitment agency, we're a job site.</p>
          </div>
          <div class="col-md-2 footer_box">
            <h5>Information</h5>
             <ul>
              <li><a href="">About Us</a></li>
              <li><a href="">Contact Us</a></li>
              <li><a href="">Terms & Condition</a></li>
            </ul>
          </div>
          <div class="col-md-2 footer_box">
            <h5>Job Seekers</h5>
             <ul>
              <li><a href="">Create Account</a></li>
              <li><a href="">Job List</a></li>
              <li><a href="">FAQ</a></li>
            </ul>
 
          </div>
          <div class="col-md-2 footer_box">
            <h5>Employers</h5>
            <ul>
              <li><a href="">Create Account</a></li>
              <li><a href="">Post a Job</a></li>
              <li><a href="">FAQ</a></li>
            </ul>  
          </div>
          <div class="col-md-3 footer_box">
            <h5>Social Media</h5>
            <ul class="d-flex">
              <li><a href=""><img src="./assets/images/Instagram.svg" alt=""></a></li>
              <li> <a href=""><img src="./assets/images/Twitter.svg" alt=""></a></li>
              <li><a href=""><img src="./assets/images/Facebook.svg" alt=""></a></li>
              <li><a href=""><img src="./assets/images/LinkedIn.svg" alt=""></a></li>
            </ul>     
          </div>
        </div> 
      </div>
    </footer>
    
  </div>
</template>

 <script>

import Navbar from './components/Navbar.vue'
import SearchBar from './components/SearchBar.vue'
export default {
  name: 'App',
  components: {
   Navbar, SearchBar
  }
}
</script>

<style scoped>
.body{
  background: url('./assets/images/Rectangle.svg') no-repeat;
  /* background-position:/; */
  background-size: 800px;
  background-position-y: 100%;
  height: 100vh;
  width: 100%;
  padding: 1rem 9%;
  
}
section{
  padding: 4rem 0;
}
/* .content{
  width: 45%;
} */
.jobs_header{
  font-weight: bold;
  font-size: 3rem;
}
.trustees h6{
  font-weight: bold;
}
.trustees img{
    margin-left: 10px;
}
.hero{
  position: relative;
   /* width: 50%; */
}
.hero_image{
  width: 450px;
  border-radius: 10px;
 
}
.hero::after{
  content: '';
  position: absolute;
  left: 70px;
  bottom: -15px;
  height: 500px;
  width: 400px;
  border-radius: 10px;
  border: 2px solid rgba(6, 148, 42, 1);
  z-index: -100;

}

.recommended_slides{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(15rem, 1fr));
    gap: 1.3rem;
    
}
.card{
  border: none !important;
  box-shadow: 5px 5px 5px 5px rgba(6, 148, 42, 0.05);
  padding:  10px;
  background: #fff;
}
.btn_card{
  border: none;
  padding: 5px 15px;
  background-color: var(--btn-mini);
  color:rgba(155, 155, 155, 1);
  border-radius: 50px;
  font-weight: bold;

}
.card .card_footer{
  border-top:1px solid rgba(155, 155, 155, 1);
  background-color: none !important;
}
.btn_card_footer{
   border: none;
  padding: 5px 10px;
  background-color: rgba(6, 148, 42, 0.2);
  color:rgba(6, 148, 42, 1);
  border-radius: 50px;
  font-weight: 600;
  font-size: 14px;
}
.works ul{
  list-style: none;
  padding-left: 0;
}
.container_catgeories{
     display: grid;
    grid-template-columns: repeat(auto-fit, minmax(12rem, 1fr));
    gap: 2rem;
}
.box_group{
  border: 1px solid rgba(229, 229, 229, 1);
  border-radius: 5px;
  padding: 25px 10px;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
  
}
.company_section{
  padding: 0 15px;
  display: flex;
  align-items: center;
  background-color: rgba(6, 148, 42, 0.1);
}
.companies_link, .companies_link i{
  color: rgba(6, 148, 42, 1);
  
}
.companies_link{
  font-weight: bold;
  text-transform: capitalize;
  border-bottom: 1px solid rgba(6, 148, 42, 0.14);
  
}
/* Customer Styles */
.box-image{
  position: relative;
  display: flex;
  align-items: center;
}
.box-image::after{
  content: '';
  position: absolute;
  left: 70px;
  bottom: -15px;
  height: 350px;
  width: 280px;
  border-radius: 25px;
  border: 2px solid rgba(6, 148, 42, 1);
  z-index: -100;
}
.box-content_image{
  position: relative;
  bottom: -20px;
  left: -7px;
}
.container_started{
  /* background: url('./assets/images/getStarted.png') no-repeat; */
   background: linear-gradient(to right, rgba(43, 48, 58, 0.6), rgba(43, 48, 58, 0.7)), url("./assets/images/getStarted.png") no-repeat;
  background-size: cover;
  height: 300px;
  width: 100%;
  border-radius: 30px;
}
.content-started{
  color: #fff;
  padding-right: 20px;
}
.content-started h3{
  font-size: 2.8rem;
}
.btn-get_started{
  padding: 8px 30px;
  color: #fff;
  font-size: 15px;
  background-color: rgba(6, 148, 42, 1);
  border-radius: 20px;
}
footer{
  border-top: 1px solid rgba(155, 155, 155, 1);
  padding: 20px 0 5rem;
}
.footer_logo{
  border-left: 1px solid #E5E5E5;
  margin-bottom: 10px;
}
.footer_box h5{
  padding: 20px 0;
}
.footer_box ul {
  list-style: none;
  padding: 0;
}

.footer_box li{
 
  padding-top: 15px;
}
.footer_box li a{
   color: #000;
}
</style>
