<template >
   <nav class="navbar navbar-expand-lg bg-light shadow-sm sticky-top">
  <div class="container-fluid  ">
    <a class="navbar-brand text-danger" href="#">My Portfolio</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse " id="navbarNav">
      <ul class="navbar-nav ">
        <li class="nav-item">
          <a href="#home" class="text-danger">Home</a>
        </li>
        <li class="nav-item">
          <a href="#about-me" class="text-danger">About Me</a>
        </li>
        <li class="nav-item">
          <a href="#can-do" class="text-danger"> Portfolio</a>
        </li>
        <li class="nav-item" >
          <a href="#projects" class="text-danger">My Project</a>
        </li>

        <li class="nav-item">
          <a href="#member" class="text-danger">Team Member</a>
        </li>

        <li class="nav-item">
          <a href="#contact-me" class="text-danger">Contact</a>
        </li>

        
      </ul>
    </div>
  </div>
</nav>


 <!-- home site -->
 <section  class="px-4 pb-5 mt-5" id="home">
    <div class="container-lg">
      <div class="row g-4 align-items-center align-content-center min-vh-75 mt-3">  <!--align-items-center & align-content-center is important also  min-vh-75-->
        <div class="col-md-6 text-center mt-5  mb-5 mb-sm-5">
          <img src="../assets/profile.jpg" class=" rounded-circle shadow-lg img-thumbnail bg-danger " style="width:300px;" alt="">
        </div>
        <div class="col-md-6 order-md-first">
          <div class="my-portfolio">
          <h4 class="text-muted">Hello! I'm</h4>
          <h1 class="text-danger">Web Developer</h1>
          <h5 >(Aung Thu Hein)</h5>
          <p class="mt-4 text-muted">Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus laboriosam ut porro at est nam nemo voluptatem quis aspernatur tenetur modi culpa cumque maiores dolorem cum aut quod, hic ea?</p>
          <a href="" class="btn btn-danger mt-3 px-3">My Work</a>
         
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- home end -->

  <!-- about me start -->
  <div class="about py-1 p-sm-4 p-3" id="about-me">
    <div class="about-container container-lg">
      <div class="row ">
        <div class="col-lg-12 text-center"><h2  class=" fw-bold  mb-4">About Me</h2></div>
      </div>

      <!-- skil -->
      <div class="skill-container py-2 ">
         <div class="row g-5">
          <div class="col-md-6">
            <div class="about-me">
              <h3 class="mb-3 ">FreeLancer</h3>
              <p class=" text-muted">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolore accusamus magnam possimus exercitationem doloremque hic eligendi expedita reprehenderit animi enim, quis veniam placeat architecto nesciunt earum, est eos itaque iure?lo
              </p>
            </div>
            <div class="row text-center" style="margin-top:50px">
              <div class="col-sm-4">
                 <div class="text-container">
                    <h4 class=" fw-bold fs-1">10+</h4>
                    <p class=" ml-5 text-muted ">Project Complete</p>
                 </div>
              </div>
              <div class="col-sm-4">
                <div class="text-container">
                    <h4 class=" fw-bold fs-1">5+</h4>
                    <p class=" ml-5 text-muted">Happy Clients</p>
                 </div>
              </div>
              <div class="col-sm-4 ">
                <div class="text-container">
                    <h4 class=" fw-bold fs-1">95+</h4>
                    <p class=" ml-5 text-muted">Positive Reviews</p>
                 </div>
              </div>
            </div>

            <div class="row mt-3">
              <div class="p-4 col-md-12 p-sm-4 d-flex align-items-center justify-content-sm-center justify-content-center">
                <a href="" class="btn btn-danger px-3 me-4">DownLoad CV</a>
                <div class="social-link ho">
                 <a href="https://www.facebook.com/profile.php?id=100038261822889"> <i class="fa-brands fs-2 fa-facebook me-4 text-decoration-none  overlay"></i></a>
                 <a href=""> <i class="fa-brands fs-2 fa-twitter  me-4 text-decoration-none"></i></a>
                 <a href="https://github.com/aHein007?tab=repositories"> <i class="fa-brands fa-github fs-2 me-4 text-decoration-none "></i></a>
                 <a href=""> <i class="fa-brands fa-viber fs-2 text-decoration-none "></i></a>
                </div>
              </div>
            </div>
          </div>

          

          <div class="col-md-6">
            <div class="container">
              <div class="text-container">
                <div class="mb-4">
                  <h3 class="fs-6 fw-bold">HTML</h3>
                  <div class="progress" style="height: 4px;">
                    <div class="progress-bar text-bg-danger" role="progressbar" aria-label="Example 1px high" style="width: 90%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">
                    </div>
                  </div>                 
                </div>

                <div class="mb-4">
                  <h3 class="fs-6 fw-bold">CSS</h3>
                  <div class="progress" style="height: 4px;">
                    <div class="progress-bar text-bg-danger" role="progressbar" aria-label="Example 1px high" style="width: 60%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">
                    </div>
                  </div>                 
                </div>

                <div class="mb-4">
                  <h3 class="fs-6 fw-bold">JAVASCRIPT</h3>
                  <div class="progress" style="height: 4px;">
                    <div class="progress-bar text-bg-danger" role="progressbar" aria-label="Example 1px high" style="width: 85%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">
                    </div>
                  </div>                 
                </div>

                <div class="mb-4">
                  <h3 class="fs-6 fw-bold">PHP</h3>
                  <div class="progress" style="height: 4px;">
                    <div class="progress-bar text-bg-danger" role="progressbar" aria-label="Example 1px high" style="width: 75%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">
                    </div>
                  </div>                 
                </div>

                <div class="mb-4">
                  <h3 class="fs-6 fw-bold">BootStrap</h3>
                  <div class="progress" style="height: 4px;">
                    <div class="progress-bar text-bg-danger" role="progressbar" aria-label="Example 1px high" style="width: 60%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">
                    </div>
                  </div>                 
                </div>


                <div class="mb-4">
                  <h3 class="fs-6 fw-bold">Vue.js</h3>
                  <div class="progress" style="height: 4px;">
                    <div class="progress-bar text-bg-danger" role="progressbar" aria-label="Example 1px high" style="width: 85%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">
                    </div>
                  </div>                 
                </div>


                <div class="mb-5">
                  <h3 class="fs-6 fw-bold">Laravel</h3>
                  <div class="progress" style="height: 4px;">
                    <div class="progress-bar text-bg-danger" role="progressbar" aria-label="Example 1px high" style="width: 75%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">
                    </div>
                  </div>                 
                </div>
              </div>
            </div>
          </div>
         </div>
      </div>
    </div>

  </div>
  <!-- about me end -->

  <!-- What can I do -->
  <div class="can-do text-center p-4 m-auto container-lg" id="can-do">
    <div class="row">
      <div class="col-lg-12 text-center"><h2  class=" fw-bold  mb-4">What can I do for you!</h2></div>
    </div>

    <div class="row">
      <div class="d-md-flex col-md-12">
        <div class="col-md-4 col-sm-12 bg-white shadow-lg p-4 rounded-3 me-3 mb-4">
            <i class="fa-solid fs-2  fa-code mb-4 text-danger"></i>
            <h3 class="fs-4">Web Developement</h3>
            <p class=" text-muted">Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur nam ad nisi cum ipsum dolor porro deserunt impedit, consequatur . </p>
        </div>
        <div class="col-md-4 col-sm-12 bg-white shadow-lg p-4 rounded-3 me-3 mb-4">
          <i class="fa-solid fa-lightbulb fs-2 mb-4 text-danger"></i>
            <h3 class="fs-4">Created Idea</h3>
            <p class=" text-muted">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Enim corrupti totam et amet sunt minus sequi beatae rem quasi. Optio earum i.</p>
        </div>
        <div class="col-md-4 col-sm-12  bg-white shadow-lg p-4 rounded-3 me-3 mb-4">
          <i class="fa-solid fs-2  fa-code mb-4 text-danger"></i>
            <h3 class="fs-4">Web Developement</h3>
            <p class=" text-muted">Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur nam ad nisi cum ipsum dolor porro deserunt impedit, consequatur .</p>
        </div>
      </div>
    </div>
  </div>
  <!-- what can I do End -->

  <!-- my project start -->
  <div class="project-container ps-lg-5 p-3 px-5 container-lg" id="projects">
    <div class="row">
      <div class="col-lg-12 text-center"><h2  class=" fw-bold  mb-5">My Lastest Projects</h2></div>
    </div>

    <div class="row col-lg-12 g-4 ">
      <div class="box col-lg-4  col-md-6 ">
        <div class=" m-auto w-100 h-100 " style="height:240px" >
            <img src="https://img.freepik.com/premium-vector/infographic-dashboard-template-simple-green-blue-design-interface-admin-panel-with-graphs-chart-diagrams-vector-infographics_53562-9185.jpg?w=2000" class="card-img-top h-75 img-thumbnail shadow-sm" alt="">
          <div class="">
            <h3 class="fs-5 my-2">Admin Dashboard</h3>
            <p>
              <a href="#" class=" text-decoration-none text-danger">Live Demo</a>
            </p>
          </div>
        </div>
      </div>
      <div class="box col-lg-4  col-md-6 ">
        <div class=" m-auto w-100 h-100 " style="height:240px" >
            <img src="https://coreui.io/images/templates/coreui_pro_light_v3_1440.webp" class="card-img-top h-75 img-thumbnail shadow-sm" alt="">
          <div class="">
            <h3 class="fs-5 my-2">Admin Dashboard</h3>
            <p>
              <a href="#" class=" text-decoration-none text-danger">Live Demo</a>
            </p>
          </div>
        </div>
      </div>
      <div class="box col-lg-4  col-md-6 ">
        <div class=" m-auto w-100 h-100" style="height:240px" >
            <img src="https://coreui.io/images/templates/coreui_free_1440.webp" class="card-img-top h-75 img-thumbnail shadow-sm" alt="">
          <div class="">
            <h3 class="fs-5 my-2">Admin Dashboard</h3>
            <p>
              <a href="#" class=" text-decoration-none text-danger">Live Demo</a>
            </p>
          </div>
        </div>
      </div>
      <div class="box col-lg-4  col-md-6 ">
        <div class=" m-auto w-100 h-100" style="height:240px" >
            <img src="https://assets.startbootstrap.com/img/screenshots/themes/sb-admin-2.png" class="card-img-top h-75 img-thumbnail shadow-sm" alt="">
          <div class="">
            <h3 class="fs-5 my-2">Admin Dashboard</h3>
            <p>
              <a href="#" class=" text-decoration-none text-danger">Live Demo</a>
            </p>
          </div>
        </div>
      </div>
      <div class="box col-lg-4  col-md-6 ">
        <div class=" m-auto w-100 h-100" style="height:240px" >
            <img src="https://themewagon.com/wp-content/uploads/2021/04/Mazer-1-1200x736.png" class="card-img-top h-75 img-thumbnail shadow-sm" alt="">
          <div class="">
            <h3 class="fs-5 my-2">Admin Dashboard</h3>
            <p>
              <a href="#" class=" text-decoration-none text-danger">Live Demo</a>
            </p>
          </div>
        </div>
      </div>
      <div class="box col-lg-4  col-md-6 ">
        <div class=" m-auto w-100 h-100" style="height:240px" >
            <img src="https://themewagon.com/wp-content/uploads/2021/12/corona-1.png" class="card-img-top h-75 img-thumbnail shadow-sm" alt="">
          <div class="">
            <h3 class="fs-5 my-2">Admin Dashboard</h3>
            <p>
              <a href="#" class=" text-decoration-none text-danger">Live Demo</a>
            </p>
          </div>
        </div>
      </div>
    </div>

    
  </div>

  <!-- my project end -->

  <!-- Contact me start-->
    <div class="bg-danger shadow-lg">
        <div class="row  text-center text-white" style="height:380px">
          <div class="col h-50" >
            <h4 class="pt-5 mt-5">Do you have any Project?</h4>
            <h1 class="mt-5 ">I'm Available for Freelancer Projects</h1>
            <a href="#"><button class=" btn btn-outline-light mt-5">Contact Me</button></a>
          </div>
        </div>
    </div>
  <!-- Contact me end -->

  <!-- member selector start -->

    <div class="member-section" id="member">
      <div class="about-container container-lg">
      <div class="row ">
        <div class="col-lg-12 text-center"><h2  class=" fw-bold  mt-4">Our Team Member</h2></div>
      </div>
    </div>
      <div class="row m-3  bg-light py-4 px-1">
        <div class="col-lg-8  m-auto  shadow-lg">
          <!-- carousel all request start -->
          <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
            <div class="carousel-indicators ">
              <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active bg-danger" aria-current="true" aria-label="Slide 1"></button>
              <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" class="bg-danger" aria-label="Slide 2"></button>
              <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" class="bg-danger" aria-label="Slide 3"></button>
            </div>
          <div class=" carousel-inner">
            <div class="card-container carousel-item active  px-3 py-5">
            <div class="d-flex  align-items-center ">
                <img src="../assets/boy.jpg" class="rounded-circle  img-thumbnail" style="width:150px;height:150px" alt="">
                <div class="text-container ms-3">
                  <h3 class=" fs-6 fw-bold mb-1">David John</h3>
                  <p class=" text-muted ">Senior Web Developer</p>
                </div>
                
            </div>
            <p class="text-muted mt-3"> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Molestias quod delectus ipsam blanditiis quisquam atque eius possimus incidunt veritatis provident obcaecati nam, quasi dolore itaque deserunt nulla magnam similique illo!
              
            </p>
            <div class="star-container text-danger">
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
            </div>
          </div>

          <div class="card-container px-3 py-5 carousel-item">
            <div class="d-flex  align-items-center ">
                <img src="../assets/girl3.png" class="rounded-circle  img-thumbnail" style="width:150px;height:150px" alt="">
                <div class="text-container ms-3">
                  <h3 class=" fs-6 fw-bold mb-1">David John</h3>
                  <p class=" text-muted ">Senior Web Developer</p>
                </div>
                
            </div>
            <p class="text-muted mt-3"> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Molestias quod delectus ipsam blanditiis quisquam atque eius possimus incidunt veritatis provident obcaecati nam, quasi dolore itaque deserunt nulla magnam similique illo!</p>
            <div class="star-container text-danger">
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              
            </div>
          </div>

          <div class="card-container px-3 py-5  carousel-item">
            <div class="d-flex  align-items-center ">
                <img src="../assets/girl1.jpg" class="rounded-circle  img-thumbnail" style="width:150px;height:150px" alt="">
                <div class="text-container ms-3">
                  <h3 class=" fs-6 fw-bold mb-1">David John</h3>
                  <p class=" text-muted ">Senior Web Developer</p>
                </div>
                
            </div>
            <p class="text-muted mt-3"> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Molestias quod delectus ipsam blanditiis quisquam atque eius possimus incidunt veritatis provident obcaecati nam, quasi dolore itaque deserunt nulla magnam similique illo!</p>
            <div class="star-container text-danger ">
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
              <i class="fa-solid fa-star"></i>
            </div>
          </div>
        </div>
      </div>
          <!-- carousel  all request is end -->
        </div>
      </div>
    </div>
  <!-- member selector end -->

    <!-- contact section start-->
      <div class="container-lg" id="contact-me">
        <div class="row ">
          <div class="col-lg-12 text-center"><h2  class="fw-bold mt-4">Contact me</h2></div>
        </div>

        <div class="row ">
          <div class="col-md-4 p-5 ">
             <div class="input-name mb-4 ">
                <div class="contact-item d-flex justify-content-center me-3">
                  <div class="icon text-danger"><i class="fa-solid fa-phone fs-4 mt-2"></i></div>
                  <div class="text ms-4">
                    <div class="phone fs-5">Phone</div>
                    <div class="text-muted">09962294805</div>
                  </div>
                </div>
             </div>
             <div class="input-name mb-4">
                <div class="contact-item d-flex justify-content-center ms-5 ">
                  <div class="icon text-danger"><i class="fa-solid fa-envelope fs-4 mt-2"></i></div>
                  <div class="text ms-4">
                    <div class="email fs-5">Email</div>
                    <div class="text-muted">ahein8604@gmail.com</div>
                  </div>
                </div>
             </div>
             <div class="input-name mb-4">
                <div class="contact-item d-flex justify-content-center me-5 ms-2">
                  <div class="icon text-danger"><i class="fa-solid fa-map-location-dot fs-4 mt-2"></i></div>
                  <div class="text ms-4">
                    <div class="phone fs-5">Address</div>
                    <div class="text-muted">Japan</div>
                  </div>
                </div>
             </div>
             
          </div>
          <div class="col-md-8 py-md-5 " >
              <div class="container-md">
                <form @submit.prevent="contact">
                  <div class="row">
                  <div class="col-md-6 mb-3">
                      <input type="text" class="form-control " placeholder="Enter your name"  v-model="name">
                     
                  </div>
                  <div class="col-md-6 mb-3">
                     <input type="email" name="" id="" class="form-control " placeholder="Enter your email" v-model="email">
                  </div>
                </div>
                <div class="row">
                  <div class="col-md-12 mb-3">
                    <input type="text" class="form-control " placeholder="Enter Subject" v-model="subject">
                  </div>
                </div>
                <div class="row">
                  <div class="col-md-12 mb-3">
                    <textarea placeholder="Your Message" class="form-control" cols="65" rows="10" v-model="message"></textarea>
                  </div>
                </div>


                <button class="btn btn-danger px-1 mb-5">Send Message <i class=" ms-2 fa-solid fa-paper-plane"></i></button>
                </form>
              </div>
          </div>
        </div>
      </div>
    <!-- contact section end -->


    <!-- footer start -->
    <div class="footer " >
      <div class="row h-75">
        <div class="col-md-12 border text-white border-top text-center p-5 bg-danger">
          <h5> This is all about my self.Thank for Watching!</h5>
          <p class="mt-4">Have a greate day!</p>
        </div>
      </div>
    </div>
    <!-- footer end  -->
</template>

<script>
import { ref } from '@vue/reactivity'


export default {
 setup(){
    let name =ref("");
    let email =ref("")
    let subject =ref("");
    let message=ref("")

    let contact =()=>{
      let data ={
        username:name.value,
        useremail:email.value,
        usersubject:subject.value,
        usermessage:message.value,
      }
      console.log(data)
      
    }



    return {name,email,subject,message,contact}
 }
}
</script>



<style >

.social-link > a{
  color:black;
  text-decoration: none;
}



.social-link > a:hover{
 color:rgb(255, 71, 108);
}
</style>
