 <!-- My sad attempt at making a portfolio. It's a work in progress. -->

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    
    <title>Aja Black Portfolio|Not Up to my Perfectionist Standards</title>
    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">

    <!-- Bootstrap Icons -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.3.0/font/bootstrap-icons.css">

    <link href="../css/styles.css" rel="stylesheet" type="text/css" />

  </head>

  <body data-bs-spy="scroll" data-bs-target="#scrollSpy">
    
  <nav class="navbar sticky-top navbar-expand-lg navbar-dark">
    <div class="container-fluid" id="scrollSpy">
      <a class="navbar-brand" href="#home">
        <div class="brand-img"><!--DANCING WOLF-->
          <img src="img/wolf.jpg" width="75px" alt="Home">
        </div>
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto mb-2 mb-sm-0">
          <li class="nav-item">
            <a class="nav-link active" href="#mission">Meet Me</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#skills">Skills</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#inspiration">Inspiration</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  

  <div>
    <div class="fixed-bg">
      <div id="profile-img">
        <img src="https://i.imgur.com/DoUDvVx.jpeg" width="100%" alt="Mira the Cute Litte Doofus">
        <div class="middle">
          <h1>Aja Black</h1>
        </div>
      </div>
      <div class="tagline"><em>There's Method to Madness</em></div>
    </div>
  </div>


  <section class="container-fluid" id="mission-section">
    <div id="mission">
      <br>
      <h3>Meet Me</h3>
      <br>
      <div class="row">
        <div class="col-sm-4">
          <img id="auron" class="img-fluid" src="https://i.imgur.com/oTg9bLv.jpeg" alt="Auron the Moron">
        </div>
        <div class="col-sm-8" id="attempt">
          <p>A person with an insatiable thirst for knowledge, I am always searching for the next thing I can learn and master. Programming and development languages are some of the few casualties of my intents to learn.</p>
        </div>
      </div>
    </div>
    <hr>
  </section>

  <section class="container-fluid" id="skills-section">
    <div id="skills">
      <h3>Skills Section</h3>
      <br>
      <div class="skill-container row">
        <div class="col">
          <img src="img/html5.png" width="200px" alt="HTML5 logo" class="greyscale">
          <p><strong>Structuring pages with semantic HTML5</strong></p>
        </div>
        <div class="col">
          <img src="img/css.png" width="200px" alt="CSS3 logo" class="greyscale">
          <p><strong>Giving life to the HTML with CSS3</strong></p>
        </div>
        <div class="col">
          <img src="img/bootstrap.png" width="200px" height="200px" alt="Bootstrap logo" class="greyscale">
          <p><strong>Creating responsive websites with Bootstrap</strong></p>
        </div>
        <div class="col">
          <img src="img/python.png" width="200px" alt="Python logo" class="greyscale">
          <p><strong>Developing programmes with Python</strong></p>
        </div>
      </div>
    </div>
    <hr>
  </section>

  <section class="container-fluid" id="inspiration-section">
    <div id="inspiration">
      <h3>Inspiration</h3>
      <br>
      <div id="carouselCaptions" class="carousel slide carousel-fade" data-bs-ride="carousel">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <div class="overlay">
              <img src="img/albert.jpg" class="d-block w-100" alt="einstein" width="900px" height="600px">
            </div>
            <div class="carousel-caption d-md-block">
              <h5>The important thing is not to stop questioning. Curiosity has its own reason for existing.</h5>
              <p><small>Albert Einstein <br>Image by <a href="https://pixabay.com/users/parentrap-2161438/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1933340">Jackie Ramirez</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1933340">Pixabay</a></small></p>
            </div>
          </div>
          <div class="carousel-item">
            <div class="overlay">
              <img src="img/trees.jpg" class="d-block w-100" alt="lush forest" width="900px" height="600px">
            </div>
            <div class="carousel-caption d-md-block">
              <h5>Why give up, why give in?
                  It's not enough, it never is.
                  So I will go on until the end.</h5>
              <p><small>Breaking Benjamin: Until the End (2006) <br>Image by <a href="https://pixabay.com/users/12019-12019/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1587301">David Mark</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1587301">Pixabay</a></small></p>
            </div>
          </div>
          <div class="carousel-item">
            <div class="overlay">
              <img src="img/mountain.jpg" class="d-block w-100" alt="cloudy mountains" width="900px" height="600px">
            </div>
            <div class="carousel-caption d-md-block">
              <h5>The journey of a thousand miles begins with one step.</h5>
              <p><small>Lao Tzu <br>Photo by <a href="https://unsplash.com/@jirehfoo?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Jireh Foo</a> on <a href="https://unsplash.com/s/photos/lao-tzu?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a></small></p>
            </div>
          </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselCaptions" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselCaptions" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
    <hr>
  </section>

  <section class="container-fluid" id="contact-section">
    <div id="contact">
      <h3>Contact</h3> 
      <br>
      <div class="container-fluid">
        <div class="row">
          <div class="col">
            <a href="https://github.com/Johann2041" target="_blank"><span class="bi bi-github icon-white icon-lg icon"></span></a>
          </div>
          <div class="col">
            <a href="https://www.twitch.tv/johann2041" target="_blank"><span class="bi bi-twitch icon-purple icon-lg icon"></span></a>
          </div>
          <div class="col">
            <a href="https://www.linkedin.com/in/jasmine-black-b511b7200" target="_blank"><span class="bi bi-linkedin icon-blue-white icon-lg icon" id="linkedin"></span></a>
          </div>
          <div class="col">
            <a href="mailto: sentbyravens2012@gmail.com" target="_blank"><span class="bi bi-envelope-fill icon-grey icon-lg icon" id="email"></span></a>
          </div>
        </div>
      </div>
    </div>
    <br>
  </section>

  <footer>
    <h6>&copy; Aja Black 2022</h6>
  </footer>

    <!--Bootstrap JavaScript-->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-OERcA2EqjJCMA+/3y+gxIOqMEjwtxJY7qPCqsdltbNJuaOe923+mo//f6V8Qbsw3" crossorigin="anonymous"></script>
  </body>
</html>

 body {
    margin: auto;
    padding: 0;
    position: relative;
    background: rgb(2,0,36);
    font-size: 16px; 
}
  
.fixed-bg {
    background-image: url("background3.jpg");
    min-height: 700px;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}
  
#profile-img {
    display: flexbox;
    justify-content: center;
    margin: auto;
    width: 30%;
    padding-top: 8px;
    overflow: hidden;
    height: auto;
}
  
#profile-img img {
    border: 5px solid #00004c;
    border-radius: 100%;
    opacity: 1;
}

.middle {
    opacity: 1;
    position: relative;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    -ms-transform: translate(-50%, -50%);
    text-align: center;
}
  
h1 {
    color: #9dc09d;
    font-weight: 700;
    text-shadow: 2px 2px #000099;
}
  
.tagline {
    opacity: 1;
    position: relative;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    -ms-transform: translate(-50%, -50%);
    text-align: center;
    color: #bfbfbf;
}
  
.navbar {
    top: 0;
    position: sticky;
    background: #00004c;
    box-shadow: 0 8px 8px -8px #bfbfbf;
}
  
.brand-img {
    display: inline-block;
    clip-path: circle(20px at 50% 50%);
    border-radius: 50%;
    overflow: hidden;
    top: 10px;
}
  
.brand-img:hover {
    transform: rotateY(180deg);
    /* DANCING WOLF */
}
  
.navbar-nav li {
    padding: .75rem .50rem;
}
  
h3 {
    text-align: center;
    color: #fff;
}
  
#auron {
    border-radius: 50%;
    border: solid 2px #00004c;
}

#mission-section, #inspiration-section {
  color: #bfbfbf;
  <!-- background: linear-gradient(90deg, rgba(2,0,36,1) 0%, rgba(7,96,10,1) 49%); -->
  text-shadow: 2px 2px #000;
}

#skills-section, #contact-section {
  color: #bfbfbf;
  <!-- background: linear-gradient(90deg, rgba(2,0,36,1) 0%, rgba(7,96,10,1) 49%); -->
  text-shadow: 2px 2px #000;
}

#attempt {
  height: 10em;
  display: flex;
  align-items: center;
  justify-content: center;
}

#attempt p {
  margin: 0;
}

/* I think I did it? */

section {
  padding-bottom: 10px;
  padding-top: 10px;
  text-align: center;
  position: relative;
  font-size: clamp(1rem, 1.8vw, 2.5rem);
}

hr {
  margin: 25px 0;
  height: 5px;
  background: black;
  <!-- background: linear-gradient(to right, rgba(0,0,0,1) 0%, rgba(0,0,0,0.98) 2%, rgba(0, 0, 0, 1) 90%); -->
}

.greyscale {
  filter: grayscale(60%);
}

span {
  display: inline-block;
  padding: 10px 20px;
}

.carousel {
  display: inline-block;
  width: 75%;
  overflow: hidden;
  text-align: center;
}

.overlay {
  position: relative;
}

.overlay:after {
  content: " ";
  z-index: 10;
  display: block;
  position: absolute;
  height: 100%;
  top: 0;
  left: 0;
  right: 0;
  background: rgba(0, 0, 0, 0.5);
}

h5 {
  position: relative;
  color: #bfbfbf;
  z-index: 1000;
}

.carousel p a {
  text-shadow: 1px 1px #000;
  color: #bfbfbf;
}

.icon {
  transition-duration: 1s;
}

.icon-white {
  color: white;
}

.icon-purple {
  color: #5c16c5;
}

.icon-blue-white {
  color: #0073b1;
}

.icon-grey {
  color: darkgrey;
}

.icon-lg {
  font-size: 5vw;
}

.icon-white:hover {
  color: grey;
  transform: rotate(0.25turn);
}

.icon-purple:hover {
  color: purple;
  transform: rotate(0.5turn);
}

.icon-blue-white:hover {
  color: blue;
  transform: rotate(0.75turn);
}

.icon-grey:hover {
  color: rgba(49, 48, 29, 0.75);
  transform: rotate(1turn);
}

footer {
  color: #bfbfbf;
  vertical-align: center; 
  text-align: center;
}
  
