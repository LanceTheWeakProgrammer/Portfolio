  <template>
      <nav class="navbar navbar-expand-lg bg-body-tertiary sticky-top">
        <div class="container-fluid">
          <a class="navbar-brand me-4 text-dark stylish-font1 fs-3">LANCE</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link fs-5" aria-current="page" href="#home">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link fs-5" href="#skills">Skills</a>
              </li>
              <li class="nav-item">
                <a class="nav-link fs-5" href="#projects">Projects</a>
              </li>
              <li class="nav-item">
                <a class="nav-link fs-5" href="#contact">Contact</a>
              </li>
              <li class="nav-item">
                <a class="nav-link fs-5" href="#about">About</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
      <div id="home" class="container">
        <div class="row justify-content-center">
          <div>
            <h1 class="stylish-font1">
            Lance Javate
            </h1>
          </div>
          <div class="col-md-3" id="description1">
              <h5>
                Hello there! My name is Lance Javate. I am a college student from <a class="text-dark fw-bold text-decoration-none" href="https://www.facebook.com/cpcofficial2005"> Cordova Public College </a> that pursues computer studies.
              </h5>
          </div>
          <div class="col-md-6 position-relative">
            <img class="img-fluid rounded mb-5" alt="Portrait" src="/portrait.png">
          </div>
          <div class="col-md-3" id="description2">
              <h5>
                I am a skilled designer, adept at adapting to various challenges and proficient in multiple programming languages. Eager to expand my knowledge, I am committed to continuous learning and growth in the ever-evolving tech landscape.
              </h5>
          </div>
        </div>
      </div>

        <div id="skills"></div>

        <h2 class="pt-4 mb-4 text-center fw-bold stylish-font3">Skills</h2>

        <div class="container">
            <div class="row justify-content-evenly px-lg-0 px-md-3 px-5">
                <div class="col-lg-2 col-md-4 text-center py-4 my-3 mx-4">
                  <img src="laravel.png" width="80px" title="Laravel" class="zoom-in-effect" data-bs-toggle="tooltip" data-bs-placement="top">
                </div>
                <div class="col-lg-2 col-md-4 text-center py-4 my-3 mx-4">
                    <img src="bootstrap.png" width="80px" title="Bootstrap" class="zoom-in-effect">
                </div>
                <div class="col-lg-2 col-md-4 text-center py-4 my-3 mx-4">
                    <img src="css.png" width="80px" title="CSS" class="zoom-in-effect">
                </div>
                <div class="col-lg-2 col-md-4 text-center py-4 my-3 mx-4">
                    <img src="js.png" width="80px" title="JavaScript" class="zoom-in-effect">
                </div>
                <div class="col-lg-2 col-md-4 text-center py-4 my-3 mx-4">
                    <img src="php.png" width="140px" title="PHP" class="zoom-in-effect">
                </div>
                <div class="col-lg-2 col-md-4 text-center py-4 my-3 mx-4">
                    <img src="sql.png" width="130px" title="SQL" class="zoom-in-effect">
                </div>
                <div class="col-lg-2 col-md-4 text-center py-4 my-3 mx-4">
                    <img src="html.png" width="80px" title="HTML" class="zoom-in-effect">
                </div>
                <div class="col-lg-2 col-md-4 text-center py-4 my-3 mx-4">
                    <img src="vue.png" width="100px" title="Vue.js" class="zoom-in-effect">
                </div>
            </div>
        </div>

        <div id="projects"></div>

        <h2 class="mt-5 pt-4 mb-4 text-center fw-bold stylish-font3">Projects</h2>

        <div class="container">
          <div class="row">
            <div class="col-lg-6 offset-lg-0 col-md-8 offset-md-2 p-4">
                <div class="card border-0 round shadow" style="width: 100%; height: 100%;">
                    <div style="height: 300px; overflow: hidden;" class="border-4 round">
                        <img src="https://scontent.fceb2-2.fna.fbcdn.net/v/t39.30808-6/434261221_374586668881335_8014069547964949419_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeGRP5-VMZ4VX6MpTPtf9rwvRrYC0vkXXXdGtgLS-RdddxxWXSz3I4WYdPWRFmxwQFhCME-bBkwa2FaRSOJbYwNm&_nc_ohc=fV_LEK5ZJP4AX_UcZ-4&_nc_ht=scontent.fceb2-2.fna&oh=00_AfA5cDJoVlLse4scryl2onD_ydmkba-lXoHz31K7Lmj6Kw&oe=66095717" class="img-fluid" alt="Image" style="width: 100%; height: 400px; object-fit: cover;">
                    </div>
                    <div class="card-body">
                        <a href="https://github.com/LanceTheWeakProgrammer/Calculator" class="text-dark text-decoration-none">
                            <h5 class="zoom-in-effect">Replica of Microsoft's Standard Calculator</h5>
                        </a>
                    </div>
                </div>
            </div>
            <div class="col-lg-6 offset-lg-0 col-md-8 offset-md-2 p-4">
                <div class="card border-0 round shadow" style="width: 100%; height: 100%;">
                    <div style="height: 300px; overflow: hidden;" class="border-4 round">
                        <img src="https://scontent.fmnl25-3.fna.fbcdn.net/v/t39.30808-6/434139527_374587565547912_3114569687569442916_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeFgGS80V02dgjQcVmbpNx6HXEkt2stBkpdcSS3ay0GSl1igDHziBhdnnKBNzG-xiu3Pm_yPi8inJFXIBH1p6MIa&_nc_ohc=yrDkuaIrjx0AX-Wtjf7&_nc_ht=scontent.fmnl25-3.fna&oh=00_AfBH_rFaW7n54_U6WBJaE7Cm6uZdSayb5Qn5x-p9kugFwA&oe=6608E65A" class="img-fluid" alt="Image" style="width: 100%; height: 400px; object-fit: cover;">
                    </div>
                    <div class="card-body">
                      <a href="https://github.com/LanceTheWeakProgrammer/Booking" class="text-dark text-decoration-none">
                        <h5 class="zoom-in-effect">Automobile Services Booking System</h5>
                      </a>
                    </div>
                </div>
            </div>
            <div class="col-lg-6 offset-lg-0 col-md-8 offset-md-2 p-4">
                <div class="card border-0 round shadow" style="width: 100%; height: 100%;">
                    <div style="height: 300px; overflow: hidden;" class="border-4 round">
                        <img src="https://scontent.fceb6-1.fna.fbcdn.net/v/t39.30808-6/434359358_374587788881223_5329172037818751384_n.jpg?_nc_cat=100&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeHeEBQwb8SV2DiYPg45K1kiuPqj-6P8gAW4-qP7o_yABb6606_LTG0cB1hSEo80_kixHoNXBM125mAzMmrSzkF1&_nc_ohc=u1E4pTmVPw4AX8gAavu&_nc_ht=scontent.fceb6-1.fna&oh=00_AfDJKan6M_lTk82_mXiTxIUJFbrrVvjWpPjmwiCi1AxXNg&oe=6607B650" class="img-fluid" alt="Image" style="width: 100%; height: 400px; object-fit: cover;">
                    </div>
                    <div class="card-body">
                      <a href="https://github.com/LanceTheWeakProgrammer/Pokemon" class="text-decoration-none text-dark">
                        <h5 class="zoom-in-effect">Pokemon Info</h5>
                      </a>  
                    </div>
                </div>
            </div>
            <div class="col-lg-6 offset-lg-0 col-md-8 offset-md-2 p-4">
                <div class="card border-0 round shadow" style="width: 100%; height: 100%;">
                    <div style="height: 300px; overflow: hidden;" class="border-4 round">
                        <img src="https://scontent.fmnl25-4.fna.fbcdn.net/v/t39.30808-6/434359467_374589762214359_4963283663627951733_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeEtwREAcGME7XbnBuCpULtBJFhr-phFdKQkWGv6mEV0pFGQu9BR-GHzDYavh3F4nq2fiuagx5EjNCWQe7_tsKBQ&_nc_ohc=_Vf0-6da9VYAX_rYvyQ&_nc_ht=scontent.fmnl25-4.fna&oh=00_AfDn3sNXKVXnph0vH_Ya4_SQWvigA5ZiitmXogUolJEYMA&oe=6608443B" class="img-fluid" alt="Image" style="width: 100%; height: 400px; object-fit: cover;">
                    </div>
                    <div class="card-body">
                      <a href="https://github.com/LanceTheWeakProgrammer/Library" class="text-dark text-decoration-none">
                        <h5 class="zoom-in-effect">Student Library System</h5>
                      </a>
                    </div>
                </div>
            </div>
          </div>
        </div>

        <div id="contact"></div>
        
        <h2 class="pt-4 mb-4 text-center fw-bold stylish-font1">Reach me out...</h2>

        <div class="container">
            <div class="row justify-content-evenly px-lg-0 px-md-3 px-5">
                <div class="col-lg-2 col-md-4 text-center py-4 my-3 mx-3">
                    <a href="https://twitter.com/lanceeee_7">
                      <img src="x.png" width="80px" title="X/Twitter" class="zoom-in-effect">
                    </a>
                </div>
                <div class="col-lg-2 col-md-4 text-center py-4 my-3 mx-4">
                <a href="https://github.com/LanceTheWeakProgrammer">
                  <img src="github.png" width="80px" title="Github" class="zoom-in-effect">
                </a>
                </div>
                <div class="col-lg-2 col-md-4 text-center py-4 my-3 mx-3">
                  <a href="https://www.facebook.com/profile.php?id=100089900131835">
                    <img src="fb.png" width="80px" title="Facebook" class="zoom-in-effect">
                  </a>  
                </div>
                <div class="col-lg-2 col-md-4 text-center py-4 my-3 mx-3">
                  <a href="https://www.instagram.com/lansyoooo/">
                    <img src="ig.png" width="80px" title="Instagram" class="zoom-in-effect">
                  </a>  
                </div>
                <div class="col-lg-2 col-md-4 text-center py-4 my-3 mx-3">
                  <a href="https://www.reddit.com/user/gravityissue/">
                    <img src="reddit.png" width="80px" title="Reddit" class="zoom-in-effect">
                  </a>  
                </div>
                <div class="col-lg-4 col-md-4 text-center py-4 my-3 mx-3">
                  <a href="mailto:lancejavate2002@gmail.com" class="text-dark text-decoration-none">
                    <h5 class="zoom-in-effect fw-bold"><i class="fas fa-envelope"></i> Email: lancejavate2002@gmail.com</h5>
                  </a>  
                </div>
                <div class="col-lg-4 col-md-4 text-center py-4 my-3 mx-3">
                  <h5 class="zoom-in-effect fw-bold"><i class="fas fa-phone"></i> Contact Number: +639662554423</h5>
                </div>
            </div>
        </div>

        <div id="about">

          <h2 class="pt-4 mb-4 text-center fw-bold stylish-font1">About me...</h2>

          <div class="container">
            <h5>
              Allow me to introduce myself – I'm Lance Javate, a budding programmer with a passion for crafting captivating web experiences. I find joy in the art of web design and the meticulous planning that goes into each project. While I'm still honing my skills, I've discovered a knack for frontend development, where I excel at bringing designs to life. Yet, my backend skills are nothing to scoff at either.
            </h5>
          </div>
          <div class="container mt-3">
            <h5>
                What sets me apart isn't just my technical abilities; it's my knack for communication and strategic planning. I believe in crafting solutions that not only work flawlessly but also resonate with users on a deeper level.
            </h5>
          </div>      
          <div class="container mt-3">
            <h5>
                Through my portfolio, I aim to showcase not just the projects I've worked on, but the skills I've cultivated along the way. Each project is a testament to my dedication and creativity, inviting you to join me on my journey of growth and exploration in the world of programming.
            </h5>
          </div>      
        </div>

        <div class="container-fluid bg-white mt-5 footer">
            <div class="row">
                <div class="col-lg-4">
                    <h3 class="stylish-font1 fw-bold fs-3 mb-3">
                        LANCE
                    </h3>
                    <p> 
                      Allow me to introduce myself – I'm Lance Javate, a budding programmer with a passion for crafting captivating web experiences. I find joy in the art of web design and the meticulous planning that goes into each project. 
                    </p>
                </div>
                <div class="col-lg-4 p-4">
                    <h5 class="mb-3">Links</h5>
                    <a href="#home" class="d-inline-block mb-2 text-dark text-decoration-none">Home</a> <br>
                    <a href="#skills" class="d-inline-block mb-2 text-dark text-decoration-none">Skills</a> <br>
                    <a href="#projects" class="d-inline-block mb-2 text-dark text-decoration-none">Projects</a> <br>
                    <a href="#contact" class="d-inline-block mb-2 text-dark text-decoration-none">Contact</a> <br>
                    <a href="#about" class="d-inline-block mb-2 text-dark text-decoration-none">About</a>
                </div>
                <div class="col-lg-4 p-4">
                    <h5 class="mb-3">Contact me</h5>
                    <a href="" class="d-inline-block text-dark text-decoration-none mb-2">
                        <i class="fab fa-twitter me-1"></i> Twitter
                    </a><br>
                    <a href="" class="d-inline-block text-dark text-decoration-none mb-2">
                        <i class="fab fa-facebook me-1"></i> Facebook
                    </a><br>
                    <a href="" class="d-inline-block text-dark text-decoration-none mb-2">
                        <i class="fab fa-instagram me-1"></i> Instagram
                    </a><br>
                </div>
            </div>
        </div>
  </template>

  <script>

  </script>

  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  #description1 {
    margin-top: 280px;
  }

  #description2 {
    margin-top: 200px;
  }

  h1 {
    font-size: 150px;
  }

  @media (max-width: 767px) {
    #description1,
    #description2 {
      margin-top: 0; 
    }
    h1 {
    font-size: 50px;
  }
  }

  h3 {
    margin: 40px 0 0;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }
  a {
    color: #42b983;
  }
  .stylish-font1 {
    font-family: "Play", sans-serif;
    font-weight: 700;
    font-style: normal;
  }

  .stylish-font2 {
    font-family: "Dancing Script", cursive;
    font-optical-sizing: auto;
    font-weight: 700;
    font-style: normal;
    font-size: 27px; 
  }
  .stylish-font3 {
    font-family: "Bebas Neue", sans-serif;
    font-weight: 400;
    font-style: normal;
    font-size: 60px; 
  }
  .stylish-font4 {
    font-family: "Playfair Display", serif;
    font-optical-sizing: auto;
    font-weight: 700;
    font-style: normal;
    font-size: 22px; 
  }
  </style>
