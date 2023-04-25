<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <meta name="viewport" content="initial-scale=1, maximum-scale=1">
        <title>my page</title>
        <link  rel="stylesheet" href="css/bootstrap.min.css">
        <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.7/dist/umd/popper.min.js" integrity="sha384-zYPOMqeu1DAVkHiLqWBUTcbYfZ8osu1Nd6Z89ify25QV9guujx43ITvfi12/QExE" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.min.js" integrity="sha384-Y4oOpwW3duJdCWv5ly8SCFYWqFDsfob/3GkgExXKV4idmbt98QcxXYs9UoXAB7BZ" crossorigin="anonymous"></script>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="container-fluid">
            <nav class="navbar navbar-expand-lg bg-body-tertiary">
                <div class="container-fluid">
                  <a class="navbar-brand" href="https://www.uj.edu.sa/"><img class="menu" src="images/logo.png" alt="uj logo" ></a>
                  <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav">
                      <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Home</a>
                      </li>
                      <li class="nav-item">
                        <a class="nav-link" href="#info">personal information</a>
                      </li>
                      <li class="nav-item">
                        <a class="nav-link" href="#edu">education</a>
                      </li>
                      <li class="nav-item">
                        <a class="nav-link" href="#projects">projects</a>
                      </li>
                      <li class="nav-item">
                        <a class="nav-link" href="#more">more about me</a>
                      </li>
                      <li class="nav-item">
                        <a class="nav-link" href="#contact">contact me</a>
                      </li>
                    </ul>
                  </div>
                  <div class="dropdown">
                    <button class="btn" type="button" data-bs-toggle="dropdown" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <ul class="dropdown-menu">
                        <li><a class="dropdown-item" href="#">home</a></li>
                        <li><a class="dropdown-item" href="#info">personal information</a></li>
                        <li><a class="dropdown-item" href="#edu">education</a></li>
                        <li><a class="dropdown-item" href="#projects">projects</a></li>
                        <li><a class="dropdown-item" href="#more">more about me</a></li>
                        <li><a class="dropdown-item" href="#contact">contact me</a></li>
                    </ul>
                  </div>
                </div>
              </nav>
        </div>

        <div id="carousel" class="carousel slide">
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img src="images/w.gif" class="d-block w-100" alt="...">
              </div>
              <div class="carousel-item">
                <img src="images/w1.gif" class="d-block w-100" alt="...">
              </div>
              <div class="carousel-item">
                <img src="images/w2.gif" class="d-block w-100" alt="...">
              </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carousel" data-bs-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carousel" data-bs-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Next</span>
            </button>
          </div>

        <section id="info">
            <h1 class="c1">personal information</h1>
            <p>my name is maram omar</p>
            <p>I am 21 years old, a cyber security student at the University of Jeddah and a home barista
                I have many hobbies, including drawing, pottery, and art in general, in addition to baking cookies, and a lot more<br>
                As a student in the field of cybersecurity, I always aim to develop my skills and knowledge in the field of electronic protection and technology, 
                and to learn about the tools and techniques used in cybersecurity. I also seek to understand the cybersecurity threats and challenges 
                facing organizations and individuals, and learn how to protect sensitive systems, data and information from cyberattacks.  Ultimately,
                I seek to develop my skills in the field of cybersecurity to become an expert in this field and contribute to protecting my community 
                and the institutions in which I will work.
            </p>
            <br>
        </section>
    
        <section id="edu">
            <h1 class="c2">education</h1>
            <p>I was always the distinguished student who participated in all events and was the presenter for most of the celebrations in the school.
                I was on the scout's team in elementary school, and in middle school, I was on the school organization team. As for secondary school, I was responsible for projectors, and from here my love and passion began in the computer, and I always dreamed of entering the world of cybersecurity
                Then, with Allah's grace and success, I was accepted into it, with a GPA of 4.88
                <br><i>You can view some school certificates <a href="files/certifications.pdf">"here"</a></i>
                <br><i><a href="files/010_SecurityZines_XSS-certificate.pdf">xss course certificate</a></i>
            </p>
            <br>
        </section>
        
        <section id="projects">
            <h1 class="c1">projects</h1>
            <p>
                <b><i>press the image to download the file</i></b>
                - <a href="files/MRcafe&roastry.zip">java1 project code</a><br><br>

                - java2 project<br>
                <a href="files/project.zip"><img src="images/java2proj.png" alt="java project" class="proj"></a><br><br>
                
                - data structure project<br>
                <a href="files/DSproject.zip"><img src="images/DSproj.png" alt="DS project" class="proj"></a><br><br>

                - Principle of Software Engineering project<br>
                <a href="files/MyFuture+App_YAL.pdf"><img src="images/myfuture.png" alt="Software project" class="proj"></a><br><br>

                - you can find this page on github<br>
                <a href="https://github.com/xmeowmeow/web-dev-assignment1.git"><img src="images/mypage.png" alt="page" class="proj"></a><br><br>
                

            </p>
            <br>
        </section>

        <section id="more">
            <h1 class="c2">more about me</h1>
            <p>
                As I mentioned that I am a home barista, I love coffee so much and consider it an essential part of my day
                 because it is as they say, "معشوقتي السمراء". Here are some pictures and 
                 you can find other videos on my <a href="https://www.tiktok.com/@xmem.n?item_id=7157798851884240133">TikTok</a> account
                <p class="photoo">
                    <img class="photo" src="images/1.jpg" alt="#">
                    <img class="photo" src="images/2.jpg" alt="#">
                    <img class="photo" src="images/3.jpg" alt="#">
                    <img class="photo" src="images/4.jpg" alt="#">
                    <img class="photo" src="images/5.jpg" alt="#">
                    <img class="photo" src="images/6.jpg" alt="#">
                    <img class="photo" src="images/7.jpg" alt="#">
                    <img class="photo" src="images/8.jpg" alt="#">
                </p>
                <br>
                and here are some of my drawings
                <p class="photoo">
                    <img class="photo" src="images/9.jpg" alt="#">
                    <img class="photo" src="images/10.jpg" alt="#">
                    <img class="photo" src="images/11.jpg" alt="#">
                    <img class="photo" src="images/12.jpg" alt="#">
                    <img class="photo" src="images/13.jpg" alt="#">
                    <img class="photo" src="images/14.jpg" alt="#">
                    <img class="photo" src="images/15.jpg" alt="#">
                    <img class="photo" src="images/16.jpg" alt="#">
                    <img class="photo" src="images/17.jpg" alt="#">
                    <img class="photo" src="images/18.jpg" alt="#">
                    <img class="photo" src="images/19.jpg" alt="#">
                    <img class="photo" src="images/20.jpg" alt="#">
                    <img class="photo" src="images/21.jpg" alt="#">
                    <img class="photo" src="images/22.jpg" alt="#">
                </p>
            </p>
        </section>

        <footer id="contact">
            <p>
                <img src="images/contact.png" alt="##">

                <a href="https://wa.me/0532975171"><img src="images/phone.png" alt="phone" class="con"></a> 
                <a href="mailto:xmem.n@hotmail.com"><img src="images/email.png" alt="email" class="con"></a> 
                <a href="https://instagram.com/xmeow.n?igshid=YmMyMTA2M2Y="><img src="images/insta.png" alt="insta" class="con"></a>
                <a href="https://www.tiktok.com/@xmem.n?item_id=7157798851884240133"><img src="images/tiktok.png" alt="tiktok" class="con"></a> 
                <a href="https://twitter.com/xmem_o?s=21&t=2VKp-3Mr4xLbDLSR-3uokQ"><img src="images/twitter.png" alt="twitter" class="con"></a>
                <a href="https://github.com/xmeowmeow"><img src="images/github.png" alt="github" class="con"></a>

            </p>
        </footer>
    </body>
</html>
