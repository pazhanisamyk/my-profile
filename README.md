<!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <!--=============== FAVICON ===============-->
        <link class="profile__border" rel="shortcut icon" href="assets/img/pazhani.jpg" type="image/x-icon">
        
        <!--=============== REMIX ICONS ===============-->
        <link href="https://cdn.jsdelivr.net/npm/remixicon@2.5.0/fonts/remixicon.css" rel="stylesheet">

        <!--=============== CSS ===============-->
        <link rel="stylesheet" href="assets/css/styles.css">

        <title>Pazhanisamy.K ( Personal Profile)</title>
    </head>
    <body>
        <!--=============== HEADER ===============-->
        <header class="profile container">
            <!-- Theme button -->
            <i class="ri-moon-line change-theme" id="theme-button"></i>

            <div class="profile__container grid">
                <div class="profile__data">
                    <div class="profile__border">
                        <div class="profile__perfil">
                            <!-- Insert your image, according to the example size of the portfolio -->
                            <img src="assets/img/pazhani.jpg" alt="">
                        </div>
                    </div>

                    <h2 class="profile__name">Pazhani Samy.K</h2>
                    <h3 class="profile__profession">Mobile & Web developer</h3>

                    <ul class="profile__social">
                        <a href="https://www.linkedin.com/in/pazhani-samy-15a977178" target="" class="profile__social-link">
                            <i class="ri-linkedin-line"></i>
                        </a>
                        <a href="mailto:pazhanisamy3434@gmail.com?subject=feedback&body=Hai Pazhanisamy.k/" target="pazhanisamy3434@gmail.com" class="profile__social-link">
                            <i class="ri-google-line"></i>
                        </a>
                        <a href="" target="" class="profile__social-link">
                            <i class="ri-github-line"></i>
                        </a>
                    </ul>
                </div>

                <div class="profile__info grid">
                    <div class="profile__info-group">
                        <h3 class="profile__info-number">8+</h3>
                        <p class="profile__info-description">
                            months of <br> Work Experience
                        </p>
                    </div>
                    <div class="profile__info-group">
                        <h3 class="profile__info-number">4+</h3>
                        <p class="profile__info-description">
                            accademic <br> projects  completed
                        </p>
                    </div>
                    <div class="profile__info-group">
                        <h3 class="profile__info-number">2+</h3>
                        <p class="profile__info-description">realtime<br>projects (in progress)</p>
                    </div>
                </div>

                <div class="profile__buttons">
                    <!-- Insert your CV -->
                    <!--https://drive.google.com/file/d/11yVfPMFEv1tX6g1my_YjovHZllAEjcrS/view?usp=drivesdk-->
                    <a download="" href="assets/pdf/RESUME.pdf" class="button">
                        Download Resume <i class="ri-download-line"></i>
                    </a>

                    <div class="profile__buttons-small">
                        <!-- Insert a real number plus country code -->
                        <a href="https://api.whatsapp.com/send?phone=+916374657369&text=Hai Pazhanisamy.k" target="6374657369" class="button button__small button__gray">
                            <i class="ri-whatsapp-line"></i>
                        </a>
                        <!-- Insert your brand name or profile -->
                        <a href="tel:6374657369" target="6374657369" class="button button__small button__gray">
                            <i class="ri-phone-line"></i>
                        </a>
                    </div>
                </div>
            </div>
        </header>

        <!--=============== MAIN ===============-->
        <main class="main">
            <section class="filters container">
                <!--=============== FILTERS TABS ===============-->
                <ul class="filters__content">
                    <button class="filters__button filter-tab-active" data-target="#projects">
                        Projects
                    </button>
                    <button class="filters__button" data-target="#skills">
                        Skills
                    </button>
                </ul>

                <div class="filters__sections">
                    <!--=============== PROJECTS ===============-->
                    <div class="projects__content grid filters__active" data-content id="projects">
                        <article class="projects__card">
                            <!-- Insert your image in a rectangular format (Ex: 600 x 400, 1000 x 800, 1200 x 1000, etc) -->
                            <img src="assets/img/project1.png" alt="" class="projects__img">

                            <div class="projects__modal">
                                <div>
                                    <span class="projects__subtitle">Web</span>
                                    <h3 class="projects__title">Mobile Selling WebSite</h3>
                                    <a href="#" class="projects__button button button__small">
                                        <i class="ri-link"></i>
                                    </a>
                                </div>
                            </div>
                        </article>

                        <article class="projects__card">
                            <img src="assets/img/project2.png" alt="" class="projects__img">

                            <div class="projects__modal">
                                <div>
                                    <span class="projects__subtitle">Web</span>
                                    <h3 class="projects__title">Employee Management System</h3>
                                    <a href="#" class="projects__button button button__small">
                                        <i class="ri-link"></i>
                                    </a>
                                </div>
                            </div>
                        </article>

                        <article class="projects__card">
                            <img src="assets/img/project3.jpg" alt="" class="projects__img">

                            <div class="projects__modal">
                                <div>
                                    <span class="projects__subtitle">Android App (flutter)</span>
                                    <h3 class="projects__title">Organic Products Selling App</h3>
                                    <a href="#" class="projects__button button button__small">
                                        <i class="ri-link"></i>
                                    </a>
                                </div>
                            </div>
                        </article>

                        <article class="projects__card">
                            <img src="assets/img/project4.png" alt="" class="projects__img">

                            <div class="projects__modal">
                                <div>
                                    <span class="projects__subtitle">Android App (java)</span>
                                    <h3 class="projects__title">Offline Music Player</h3>
                                    <a href="#" class="projects__button button button__small">
                                        <i class="ri-link"></i>
                                    </a>
                                </div>
                            </div>
                        </article>

                       
                    </div>

                    <!--=============== SKILLS ===============-->
                    <div class="skills__content grid" data-content id="skills">
                        <div class="skills__area">
                            <h3 class="skills__title">Frontend Developer</h3>
    
                            <div class="skills__box">
                                <div class="skills__group">
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>
        
                                        <div>
                                            <h3 class="skills__name">HTML</h3>
                                            <span class="skills__level">Advanced</span>
                                        </div>
                                    </div>
        
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>
        
                                        <div>
                                            <h3 class="skills__name">CSS</h3>
                                            <span class="skills__level">Intermediate</span>
                                        </div>
                                    </div>
        
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>
        
                                        <div>
                                            <h3 class="skills__name">JavaScript</h3>
                                            <span class="skills__level">Intermediate</span>
                                        </div>
                                    </div>
                                </div>
                                
                                <div class="skills__group">
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>
        
                                        <div>
                                            <h3 class="skills__name">Flutter</h3>
                                            <span class="skills__level">Intermediate</span>
                                        </div>
                                    </div>
        
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>
        
                                        <div>
                                            <h3 class="skills__name">React</h3>
                                            <span class="skills__level">Intermediate</span>
                                        </div>
                                    </div>
        
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>
        
                                        <div>
                                            <h3 class="skills__name">React Native</h3>
                                            <span class="skills__level">Intermediate</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="skills__area">
                            <h3 class="skills__title">Backend Developer</h3>
    
                            <div class="skills__box">
                                <div class="skills__group">
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>
        
                                        <div>
                                            <h3 class="skills__name">PHP</h3>
                                            <span class="skills__level">Intermediate</span>
                                        </div>
                                    </div>
        
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>
        
                                        <div>
                                            <h3 class="skills__name">MySQL</h3>
                                            <span class="skills__level">Intermediate</span>
                                        </div>
                                    </div>
        
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>
        
                                        <div>
                                            <h3 class="skills__name">Firebase</h3>
                                            <span class="skills__level">Intermediate</span>
                                        </div>
                                    </div>
                                </div>
                                
                                <div class="skills__group">
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>
        
                                        <div>
                                            <h3 class="skills__name">C++</h3>
                                            <span class="skills__level">Basic</span>
                                        </div>
                                    </div>
        
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>
        
                                        <div>
                                            <h3 class="skills__name">Java</h3>
                                            <span class="skills__level">Basic</span>
                                        </div>
                                    </div>
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>
        
                                        <div>
                                            <h3 class="skills__name">node js</h3>
                                            <span class="skills__level">Basic</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </main>

        <!--=============== FOOTER ===============-->
        <footer class="footer container">
            <span class="footer__copy">Copyrights
                &#169;2023 Pazhanisamy.k , All rigths reserved
            </span>
        </footer>

        <!--=============== SCROLLREVEAL ===============-->
        <script src="assets/js/scrollreveal.min.js"></script>

        <!--=============== MAIN JS ===============-->
        <script src="assets/js/main.js"></script>
    </body>
</html>
