# Ex01 Portfolio
## Date: 23.05.2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM

Index.html

```
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Portfolio</title>
    <link rel="stylesheet" href="swiper-bundle.min.css" />
    <link rel="stylesheet" href="style.css" />
    <link
      rel="stylesheet"
      href="https://unicons.iconscout.com/release/v4.0.8/css/line.css"
    />
  </head>

  <body oncontextmenu="return false">
    <header class="header" id="header">
      <nav class="nav container">
        <a href="#" class="nav__logo">Prema Latha S</a>
        <div class="nav__menu" id="nav-menu">
          <ul class="nav__list grid">
            <li class="nav__item">
              <a href="#home" class="nav__link active-link">
                <i class="uil uil-estate nav__icon"></i>Home
              </a>
            </li>
            <li class="nav__item">
              <a href="#about" class="nav__link">
                <i class="uil uil-user nav__icon"></i>About
              </a>
            </li>
            <li class="nav__item">
              <a href="#skills" class="nav__link">
                <i class="uil uil-file-alt nav__icon"></i>Skills
              </a>
            </li>
            <li class="nav__item">
              <a href="#qualification" class="nav__link">
                <i class="uil uil-briefcase-alt nav__icon"></i>Qualification
              </a>
            </li>
            <li class="nav__item">
              <a href="#portfolio" class="nav__link">
                <i class="uil uil-scenery nav__icon"></i>Projects
              </a>
            </li>
            <li class="nav__item">
              <a href="#contact" class="nav__link">
                <i class="uil uil-message nav__icon"></i>Contact-Me
              </a>
            </li>
          </ul>
          <i class="uil uil-times nav__close" id="nav-close"></i>
        </div>
        <div class="nav__btns">
          <!-- Theme change button -->
          <i class="uil uil-moon change-theme" id="theme-button"></i>

          <div class="nav__toggle" id="nav-toggle">
            <i class="uil uil-apps"></i>
          </div>
        </div>
      </nav>
    </header>
    <!-- main-->

    <main class="main">
      <!--========================= Home =====================-->

      <section class="home section" id="home">
        <div class="home__container container grid">
          <div class="home__content grid">
            <div class="home__social">
              <a
                href="https://www.linkedin.com/in/prema-latha-sureshbabu/"
                target="_blank"
                class="home__social-icon"
              >
                <i class="uil uil-linkedin-alt home__icon"></i>
              </a>

              <a
                href="https://github.com/premalatha-sureshbabu"
                target="_blank"
                class="home__social-icon"
              >
                <i class="uil uil-github-alt home__icon"></i>
              </a>
            </div>
            <div class="home__img">
              <svg
                class="home__blob"
                viewBox="0 0 200 187"
                xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink"
              >
                <mask id="mask0" mask-type="alpha">
                  <path
                    d="M190.312 36.4879C206.582 62.1187 201.309 102.826 182.328 134.186C163.346 165.547 
                      130.807 187.559 100.226 186.353C69.6454 185.297 41.0228 161.023 21.7403 129.362C2.45775 
                      97.8511 -7.48481 59.1033 6.67581 34.5279C20.9871 10.1032 59.7028 -0.149132 97.9666 
                      0.00163737C136.23 0.303176 174.193 10.857 190.312 36.4879Z"
                  />
                </mask>
                <g mask="url(#mask0)">
                  <path
                    d="M190.312 36.4879C206.582 62.1187 201.309 102.826 182.328 134.186C163.346 
                      165.547 130.807 187.559 100.226 186.353C69.6454 185.297 41.0228 161.023 21.7403 
                      129.362C2.45775 97.8511 -7.48481 59.1033 6.67581 34.5279C20.9871 10.1032 59.7028 
                     -0.149132 97.9666 0.00163737C136.23 0.303176 174.193 10.857 190.312 36.4879Z"
                  />
                  <image
                    class="home__blob-img"
                    x="-79"
                    y="-46"
                    xlink:href="prema.jpeg"
                  />
                </g>
              </svg>
            </div>
            <div class="home__data">
              <h1 class="home__title">Hi, I'm Prema Latha</h1>
              <h3 class="home__subtitle">
                Artificial Intelligence & Data Science Engineering Student
              </h3>
              <p class="home__description">
                A third-year undergraduate engineering student at
                <strong>Saveetha Engineering College </strong>, Chennai.
              </p>
              <a href="#contact" class="button button--flex">
                Contact me<i class="uil uil-message button__icon"></i>
              </a>
            </div>
          </div>

          <div class="home__scroll">
            <a href="#about" class="home__scroll-button button--flex">
              <i class="uil uil-mouse-alt home__scroll-mouse"></i>
              <span class="home__scroll-name">Scroll down</span>
              <i class="uil uil-arrow-down home__scroll-arrow"></i>
            </a>
          </div>
        </div>
      </section>

      <!--======================= About========================-->

      <section class="about section" id="about">
        <h2 class="section__title">About Me</h2>
        <span class="section__subtitle">My introduction</span>

        <div class="about__container container grid">
          <img src="assets\img\about.jpg" alt="" class="about__img" />

          <div class="about__data">
            <p class="about__description">
              I'm a third-year AIDS undergraduate, passionate about technology and an avid reader. I have a self-motivated and can-do attitude, thriving in challenging and dynamic environments. Seeking a competitive position to enhance my skills and contribute to a professional organization. I'm very much passionate to learn new stuff that interests me and can help me to get better.
            </p>

            <div class="about__info">
              <div>
                <span class="about__info-title">08.60+</span>
                <span class="about__info-name">Aggregate <br />CGPA</span>
              </div>

              <div>
                <span class="about__info-title">04+</span>
                <span class="about__info-name"
                  >
                  Projects</span
                >
              </div>

              <div>
                <span class="about__info-title">01+</span>
                <span class="about__info-name">Months <br />experience</span>
              </div>
            </div>

            <div class="about__buttons">
              <a download="" href="Resume-Prema.pdf" class="button button--flex">
                Download CV<i class="fas fa-download button__icon"></i>
              </a>
            </div>
          </div>
        </div>
      </section>

      <!--===================== SKILLS =====================-->

      <section class="skills section" id="skills">
        <h2 class="section__title">Skills</h2>
        <span class="section__subtitle">My technical level</span>

        <div class="skills__container container grid">
          <div>
            <!--==================== Skill 1 =================-->
            <div class="skills__content skills__open">
              <div class="skills__header">
                <i class="fas fa-pencil-ruler skills__icon"></i>

                <div>
                  <h1 class="skills__title">Programming Languages</h1>
                </div>

                <i class="uil uil-angle-down skills__arrow"></i>
              </div>
              

              <div class="skills__list grid">
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">C</h3>
                  </div>
                  
                </div>
                
                  <div class="skills__data">
                    <div class="skills__titles">
                      <h3 class="skills__name">Java</h3>
                    </div>
                    
                  </div>
                  <div class="skills__data">
                    <div class="skills__titles">
                      <h3 class="skills__name">JavaScript</h3>
                    </div>
                    
                  </div>
                  <div class="skills__data">
                    <div class="skills__titles">
                      <h3 class="skills__name">Python</h3>
                    </div>
                   
                  </div>
                  <div class="skills__data">
                    <div class="skills__titles">
                      <h3 class="skills__name">Full Stack</h3>
                    </div>
                </div>
                
                
              </div>
            </div>

            <!--==================== Skill 2 =================-->
            <div class="skills__content skills__close">
              <div class="skills__header">
                <i class="fas fa-code skills__icon"></i>

                <div>
                  <h1 class="skills__title">Technical Constructs</h1>
                </div>

                <i class="uil uil-angle-down skills__arrow"></i>
              </div>

              <div class="skills__list grid">
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">Machine Learning</h3>
                  </div>
                  
                </div>
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">DS & Algorithms</h3>
                  </div>
                  
                </div>
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">OOP</h3>
                  </div>
                  
                </div>
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">Deep Learning</h3>
                  </div>
                  
                </div>
                <div class="skills__data">
                    <div class="skills__titles">
                      <h3 class="skills__name">NLP</h3>
                    </div>
                    
                  </div>
                  <div class="skills__data">
                    <div class="skills__titles">
                      <h3 class="skills__name">Computer Vision</h3>
                    </div>
                    
                  </div>
              </div>
            </div>
          </div>

          <div>
            <!--==================== Skill 3 =================-->
            <div class="skills__content skills__close">
              <div class="skills__header">
                <i class="fas fa-swatchbook skills__icon"></i>
                <div>
                  <h1 class="skills__title">Tools</h1>
                </div>

                <i class="uil uil-angle-down skills__arrow"></i>
              </div>

              <div class="skills__list grid">
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">Version Control</h3>
                  </div>
                  
                </div>
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">MongoDB</h3>
                  </div>
                  
                </div>
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">Web Development</h3>
                  </div>
                  
                </div>
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">VS Code</h3>
                  </div>
                  
                </div>
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">React.js</h3>
                  </div>
                  
                </div>
                
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">UI/UX</h3>
                  </div>
                  
                </div>
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">Open CV</h3>
                  </div>
                  
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!--==================== Qualifications ==================-->

      <section
        class="qualification__section service__section"
        id="qualification"
      >
        <h2 class="section__title">Qualification</h2>
        <span class="section__subtitle">My personal journey</span>

        <div
          class="qualification__container container grid services__container"
        >
          <div class="qualification__tabs">
            <div
              class="qualification__button button--flex qualification__active"
              data-target="#education"
            >
              <i class="uil uil-graduation-cap qualification__icon"></i>
              Education
            </div>
          </div>

          <div class="qualification__sections">
            <!--====== Qualification Content 1 ======-->
            <div
              class="qualification__content qualifiation__active services__content"
              data-content
              id="education"
            >
              <!--====== Qualification 1 ======-->
              <div class="qualification__data">
                <div>
                  <h3 class="qualification__title">SSLC</h3>
                  <span class="qualification__subtitle"
                    >St.Paul's Matriculation Higher Secondary School<br />High School</span
                  >
                  <div class="qualification__calender">
                    <i class="uil uil-calendar-alt"></i>
                    - 2020
                  </div>
                  <span
                    class="button button--flex button--small button--link services__button"
                  >
                    View More
                    <i class="uil uil-arrow-right button__icon"></i>
                  </span>
                  <div class="services__modal">
                    <div class="services__modal-content">
                      <h4 class="services__modal-title">
                        Class 10th Summary :
                      </h4>
                      <i class="uil uil-times services__modal-close"></i>
                      <ul class="services__modal-services grid">
                        <li class="services__modal-service">
                          <i
                            class="uil uil-check-circle services__moda-icon"
                          ></i>
                          <p>
                            Subjects studied: Science, Maths, English,
                            Social Studies,Tamil,
                          </p>
                        </li>
                        <li class="services__modal-service">
                          <i
                            class="uil uil-check-circle services__moda-icon"
                          ></i>
                          <p>Scored 84.8%</p>
                        </li>
                        <li class="services__modal-service">
                          <i
                            class="uil uil-check-circle services__moda-icon"
                          ></i>
                          <p>Came runners up in inter-school Running Competition</p>
                        </li>
                      </ul>
                    </div>
                  </div>
                </div>

                <div>
                  <span class="qualification__rounder"></span>
                  <span class="qualification__line"></span>
                </div>
              </div>

              <!--====== Qualification 2 ======-->
              <div class="qualification__data">
                <div></div>

                <div>
                  <span class="qualification__rounder"></span>
                  <span class="qualification__line"></span>
                </div>
                <div>
                  <h3 class="qualification__title">HSC</h3>
                  <span class="qualification__subtitle"
                    >St.Paul's Matriculation Higher Secondary School <br />High School</span
                  >
                  <div class="qualification__calender">
                    <i class="uil uil-calendar-alt"></i>
                    - 2022
                  </div>
                  <span
                    class="button button--flex button--small button--link services__button"
                  >
                    View More
                    <i class="uil uil-arrow-right button__icon"></i>
                  </span>
                  <div class="services__modal">
                    <div class="services__modal-content">
                      <h4 class="services__modal-title">
                        Class 12th Summary :
                      </h4>
                      <i class="uil uil-times services__modal-close"></i>
                      <ul class="services__modal-services grid">
                        <li class="services__modal-service">
                          <i
                            class="uil uil-check-circle services__moda-icon"
                          ></i>
                          <p>
                            Subjects studied: Physics, Chemistry, Maths,
                            English, Biology,Tamil.
                          </p>
                        </li>
                        <li class="services__modal-service">
                          <i
                            class="uil uil-check-circle services__moda-icon"
                          ></i>
                          <p>Scored 93.3%</p>
                        </li>
                      </ul>
                    </div>
                  </div>
                </div>
              </div>

              <!--====== Qualification 3 ======-->
              <div class="qualification__data">
                <div>
                  <h3 class="qualification__title">College</h3>
                  <span class="qualification__subtitle"
                    >Saveetha Engineering College ,Chennai</span
                  >
                  <div class="qualification__calender">
                    <i class="uil uil-calendar-alt"></i>
                    2022 - 2026
                  </div>
                  <span
                    class="button button--flex button--small button--link services__button"
                  >
                    View More
                    <i class="uil uil-arrow-right button__icon"></i>
                  </span>
                  <div class="services__modal">
                    <div class="services__modal-content">
                      <h4 class="services__modal-title">College Summary :</h4>
                      <i class="uil uil-times services__modal-close"></i>
                      <ul class="services__modal-services grid">
                        <li class="services__modal-service">
                          <i
                            class="uil uil-check-circle services__modal-icon"
                          ></i>
                          <p>
                            Studying core subjects of AIDS including DSA, Java, Web Development, OOPs, Operating
                            systems, and Computer architecture .
                          </p>
                        </li>
                        <li class="services__modal-service">
                          <i
                            class="uil uil-check-circle services__modal-icon"
                          ></i>
                          <p>Scored an aggregate of 8.60 CGPA till now.</p>
                        </li>
                        <li class="services__modal-service">
                          <i
                            class="uil uil-check-circle services__modal-icon"
                          ></i>
                          <p>
                            Student coordinator in Events
                          </p>
                        </li>
                        <li class="services__modal-service">
                          <i
                            class="uil uil-check-circle services__modal-icon"
                          ></i>
                          <p>
                            Coordinator in Badminton
                          </p>
                        </li>
                       
                      </ul>
                    </div>
                  </div>
                </div>

                <div>
                  <span class="qualification__rounder"></span>
                  <!--<span class="qualification__line"></span>-->
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!--=================== Portfolio ===================-->
      <section class="portfolio section" id="portfolio">
        <h2 class="section__title">Projects</h2>
        <span class="section__subtitle">Most recent work</span>

        <div class="portfolio__container container swiper-container">
          <div class="swiper-wrapper">
            <!-- ------------------------portfollio 1-------------------- -->
            <div class="portfolio__content grid swiper-slide">
              <img src="portfolio5.png" class="portfolio__img" />

              <div class="portfolio__data">
                <h3 class="portfolio__title">
                  Movie-App
                </h3>
                <p class="portfolio__description">
                    The Movie App is a dynamic web application that enables users to explore movies, view details, and search for their favorite films. Built using modern web technologies like React, JavaScript, and API integration, the app provides an intuitive and user-friendly interface. It efficiently fetches and displays movie data, offering users real-time access to trending and popular films. The project showcases strong frontend development skills, making it a valuable addition to a portfolio.
                </p>
                <a
                  href="https://github.com/premalatha-sureshbabu/movie-app"
                  class="button button--flex button--small portfolio__button"
                >
                  GitHub Repository
                  <i class="uil uil-external-link-alt button__icon"></i>
                </a>
                <a
                  href="https://codepen.io/Prema-Latha/pen/RNwVKpg"
                  class="button button--flex button--small portfolio__button"
                >
                  See Live
                  <i class="uil uil-external-link-alt button__icon"></i>
                </a>
              </div>
            </div>
            <!-- ------------------------portfollio 2-------------------- -->

            <div class="portfolio__content grid swiper-slide">
              <img src="portfolio1.png" class="portfolio__img" />

              <div class="portfolio__data">
                <h3 class="portfolio__title">
                  Hidden-Camera-Detection
                </h3>
                <p class="portfolio__description">
                    This project focuses on real-time detection of hidden spy cameras using the COCO SSD (Single Shot MultiBox Detector) model. It aims to enhance privacy and security by identifying concealed cameras in various environments, such as hotels, public restrooms, and changing rooms.
                </p>
                <a
                  href="https://github.com/premalatha-sureshbabu/spy-cam"
                  class="button button--flex button--small portfolio__button"
                >
                  GitHub Repository
                  <i class="uil uil-external-link-alt button__icon"></i>
                </a>
                <a
                  href="https://codepen.io/Prema-Latha/pen/GgRGyqY"
                  class="button button--flex button--small portfolio__button"
                >
                  See Live
                  <i class="uil uil-external-link-alt button__icon"></i>
                </a>
              </div>
            </div>

            <!-- ------------------------portfollio 3-------------------- -->
            <div class="portfolio__content grid swiper-slide">
              <img src="portfolio2.png" class="portfolio__img" />

              <div class="portfolio__data">
                <h3 class="portfolio__title">Spotify-Clone</h3>
                <p class="portfolio__description">
                  Spotify Clone is a web app developed using HTML, CSS, and
                  JavaScript. It recreates Spotify's interface and features,
                  allowing users to browse, search, and play songs, create
                  playlists, and discover new music. Responsive design ensures a
                  seamless experience on any device. Contributions are welcome!
                </p>
                <a
                  href="https://github.com/premalatha-sureshbabu/music-player"
                  class="button button--flex button--small portfolio__button"
                >
                  GitHub Repository
                  <i class="uil uil-external-link-alt button__icon"></i>
                </a>
                <a
                  href="https://codepen.io/Prema-Latha/pen/qEBKppx"
                  class="button button--flex button--small portfolio__button"
                >
                  See Live
                  <i class="uil uil-external-link-alt button__icon"></i>
                </a>
              </div>
            </div>
            <!-- ------------------------portfollio 4-------------------- -->
            <div class="portfolio__content grid swiper-slide">
              <img src="portfolio3.png" class="portfolio__img" />

              <div class="portfolio__data">
                <h3 class="portfolio__title">Shoplifting Detection</h3>
                <p class="portfolio__description">
                    The shoplifting detection system utilizes the YOLO (You Only Look Once) model, a real-time object detection algorithm, to identify suspicious activities in retail environments. The model is trained on surveillance footage, analyzing video frames to detect potential shoplifting behavior based on predefined patterns. YOLO’s ability to process images in a single pass allows for fast and accurate detection, making it suitable for real-time monitoring. 
                </p>
                <a
                  href="https://github.com/premalatha-sureshbabu/Shoplifting-Detection-"
                  class="button button--flex button--small portfolio__button"
                >
                  GitHub Repository
                  <i class="uil uil-external-link-alt button__icon"></i>
                </a>
                <a
                  href="https://colab.research.google.com/drive/1_BIGPOTs6_l8CEGgIXrlrzJVbeFSlk63?usp=sharing"
                  class="button button--flex button--small portfolio__button"
                >
                  See Live
                  <i class="uil uil-external-link-alt button__icon"></i>
                </a>
              </div>
            </div>

            <!-- ------------------------portfollio 5-------------------- -->
            <div class="portfolio__content grid swiper-slide">
              <img src="portfolio4.png" class="portfolio__img" />

              <div class="portfolio__data">
                <h3 class="portfolio__title">Toxic and Non-Toxic Plant classification</h3>
                <p class="portfolio__description">
                  Developed a deep learning-based image classification model using Convolutional Neural Networks (CNNs) to accurately distinguish between toxic and non-toxic plants. The model was trained and evaluated on a Kaggle dataset, achieving high accuracy through advanced techniques like data augmentation, transfer learning, and fine-tuning. This project showcases my ability to apply computer vision and deep learning to real-world safety and environmental applications.
                </p>
                <a
                  href="https://github.com/premalatha-sureshbabu/toxic-and-non-toxic-plant-classification"
                  class="button button--flex button--small portfolio__button"
                >
                  GitHub Repository
                  <i class="uil uil-external-link-alt button__icon"></i>
                </a>
                <a
                  href="https://colab.research.google.com/drive/1SPoZD3JDMttGh7XQt7yyAuPnWp0oPagP?usp=sharing"
                  class="button button--flex button--small portfolio__button"
                >
                  See Live
                  <i class="uil uil-external-link-alt button__icon"></i>
                </a>
              </div>
            </div>
          </div>

          <!-- add arrows -->
          <div class="swiper-button-next">
            <i class="uil uil-angle-right-b swiper-portfolio-icon"></i>
          </div>
          <div class="swiper-button-prev">
            <i class="uil uil-angle-left-b swiper-portfolio-icon"></i>
          </div>
          <!-- add pagination -->
          <div class="swiper-pagination"></div>
        </div>
      </section>

      <!--===================== Contact Me =====================-->
      <section class="contact section" id="contact">
        <h2 class="section__title">Contact Me</h2>
        <span class="section__subtitle">Get in touch</span>

        <div class="contact__container container grid">
          <div>
            <div class="contact__information">
              <i class="uil uil-calling contact__icon"></i>

              <div>
                <h3 class="contact__title">Contact Me</h3>
                <span class="contact__subtitle"
                  ><a href="tel:8124694321"></a>8124694321</span
                >
              </div>
            </div>

            <div class="contact__information">
              <i class="uil uil-envelope-minus contact__icon"></i>

              <div>
                <h3 class="contact__title">Email</h3>
                <span class="contact__subtitle"
                  >s.premalatha260804@gmail.com</span
                >
              </div>
            </div>

            <div class="contact__information">
              <i class="uil uil-map-marker contact__icon"></i>

              <div>
                <h3 class="contact__title">Location</h3>
                <span class="contact__subtitle"
                  >Chennai, Tamilnadu, India</span
                >
              </div>
            </div>
          </div>

          <form action="" class="contact__form grid">
            <div class="contact__inputs grid">
              <div class="contact__content">
                <label for="" class="content__label">Name</label>
                <input type="text" class="contact__input" />
              </div>

              <div class="contact__content">
                <label for="" class="content__label">Email</label>
                <input type="Email" class="contact__input" />
              </div>
            </div>

            <div class="contact__content">
              <label for="" class="content__label">Message</label>
              <textarea
                name=""
                id=""
                cols="0"
                rows="7"
                class="contact__input"
              ></textarea>
            </div>

            <div>
              <a
                href=" mailto: rkamathvenkatesh@gmail.com?subject=Testing out mailto! &body=This is only a test!"
                class="button button--flex"
              >
                Send Message
                <i class="uil uil-message button__icon"></i>
              </a>
            </div>
          </form>
        </div>
      </section>
    </main>

    <!--================== Footer ===============-->
    <footer class="footer">
      <div class="footer__bg">
        <div class="footer__container container grid">
          <div>
            <h1 class="footer__title">Prema Latha S</h1>
            <span class="footer__subtitle"
              >Artificial Intelligence & Data Science Engineering Student</span
            >
          </div>

          <ul class="footer__links">
            <li>
              <a href="#qualification" class="footer__link">Qualification</a>
            </li>
            <li>
              <a href="#portfolio" class="footer__link">Portfolio</a>
            </li>
            <li>
              <a href="#contact" class="footer__link">Contact-Me</a>
            </li>
          </ul>

          <div class="footer__socials">
            <a
              href="https://www.instagram.com/venkateeshh/"
              class="footer__social"
              target="__blank"
            >
            <i class="fa-brands fa-instagram"></i>
            </a>

            <a
              href="https://twitter.com/Venkateeshhh"
              target="__blank"
              class="footer__social"
            >
            <i class="fa-brands fa-x-twitter"></i>
            </a>
          </div>
        </div>

        <p class="footer__copy">&#169; Prema Latha. All right reserved</p>
      </div>
    </footer>

    <!--================== SCROLL TOP ==================-->
    <a href="#" class="scrollup" id="scroll-up">
      <i class="uil uil-arrow-up scrollup__icon"></i>
    </a>

    <script type="text/javascript" src="swiper-bundle.min.js"></script>
    <script src="https://kit.fontawesome.com/2205d59d52.js" crossorigin="anonymous"></script>
    <script src="ptj.js"></script>
  </body>
</html>

```
Style.css

```
/* General Styling */
body {
  font-family: 'Helvetica Neue', Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f9f9f9;
  color: #333;
  line-height: 1.6;
}

header {
  background-color: #1e1e2f;
  color: white;
  padding: 20px 0;
  text-align: center;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

header h1 {
  margin: 0;
  font-size: 2.5rem;
  letter-spacing: 1px;
  font-weight: 600;
}

nav ul {
  list-style-type: none;
  padding: 0;
  margin: 20px 0 0;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
  font-size: 1rem;
  text-transform: uppercase;
  font-weight: 500;
}

nav ul li a:hover {
  color: #ff6600;
}

/* Section Styling */
section {
  padding: 60px 20px;
  margin: 0 auto;
  max-width: 1000px;
}

/* About Section */
#about {
  background-color: #ffffff;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  text-align: center;
}

#about .profile-pic {
  border-radius: 50%;
  width: 160px;
  height: 160px;
  object-fit: cover;
  margin-top: 20px;
}

#about h2 {
  font-size: 2rem;
  margin-bottom: 20px;
  font-weight: 600;
  color: #333;
}

#about p {
  font-size: 1.1rem;
  color: #555;
  margin: 20px 0;
}

#about a {
  color: #1e1e2f;
  font-weight: 600;
}

#about a:hover {
  color: #ff6600;
}

/* Education Section */
#education {
  background-color: #ffffff;
  margin-top: 30px;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

#education p {
  font-size: 1.1rem;
  color: #555;
  margin: 10px 0;
}

/* Skills Section */
#skills {
  background-color: #ffffff;
  margin-top: 30px;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

#skills p {
  font-size: 1.1rem;
  color: #555;
  margin: 10px 0;
}

/* Projects Section */
#projects {
  background-color: #ffffff;
  margin-top: 30px;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.project {
  background-color: #f9f9f9;
  padding: 20px;
  margin-bottom: 20px;
  border-radius: 6px;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
}

.project h3 {
  font-size: 1.6rem;
  color: #333;
  margin-bottom: 10px;
  font-weight: 600;
}

.project p {
  font-size: 1rem;
  color: #666;
}

/* Internships Section */
#internships {
  background-color: #ffffff;
  margin-top: 30px;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.internship {
  background-color: #f9f9f9;
  padding: 20px;
  margin-bottom: 20px;
  border-radius: 6px;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
}

.internship h3 {
  font-size: 1.6rem;
  color: #333;
  margin-bottom: 10px;
  font-weight: 600;
}

.internship p {
  font-size: 1rem;
  color: #666;
}

/* Achievements Section */
#achievements {
  background-color: #ffffff;
  margin-top: 30px;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

#achievements p {
  font-size: 1.1rem;
  color: #555;
  margin: 10px 0;
}

#achievements ul {
  list-style-type: none;
  padding: 0;
}

#achievements ul p {
  margin: 10px 0;
  font-size: 1.1rem;
  color: #555;
}

/* Contact Section */
#contact {
  background-color: #ffffff;
  margin-top: 30px;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

#contact p {
  font-size: 1.1rem;
  color: #555;
  margin: 10px 0;
}

#contact a {
  color: #ff6600;
  font-weight: 600;
}

#contact a:hover {
  color: #1e1e2f;
}

/* Footer */
footer {
  background-color: #1e1e2f;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 40px;
}

footer p {
  margin: 0;
  font-size: 1rem;
}

/* Responsive Design */
@media screen and (max-width: 768px) {
  header h1 {
      font-size: 2rem;
  }

  nav ul li {
      display: block;
      margin: 10px 0;
  }

  nav ul li a {
      font-size: 1rem;
  }

  section {
      padding: 40px 20px;
  }
}
```

## OUTPUT

![image](https://github.com/user-attachments/assets/28f21104-37a3-4d83-a460-52fb1a7ec850)
![image](https://github.com/user-attachments/assets/a3ff8af5-fe97-4b44-8c3f-e0bf4e6a1b6e)
![image](https://github.com/user-attachments/assets/7cb27df8-9f83-4e8f-996d-fcdb1d58c326)
![image](https://github.com/user-attachments/assets/9f4fa90b-8362-49bb-90b5-bc429201caa9)
![image](https://github.com/user-attachments/assets/3772f499-3b30-4c51-a306-2a7057853139)
![image](https://github.com/user-attachments/assets/057b94bc-11cc-40b7-a5cc-0962d2bba1e4)


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
