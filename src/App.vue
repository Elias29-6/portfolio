
<template>
  <header id="header" class="header dark-background d-flex flex-column">
    <i class="header-toggle d-xl-none bi bi-list"></i>

    <div class="profile-img">
      <img src="/src/assets/img/profile_icon.jpeg" alt="" class="img-fluid rounded-circle" >
    </div>

    <a href="/" class="logo d-flex align-items-center justify-content-center">

      <h1 class="sitename">Elías Arias Muñoz</h1>
    </a>

    <div class="social-links text-center">
      <a href="https://www.instagram.com/elias_arias16?igsh=MWFkbDZ5eXZoeWRxbg==" class="instagram"><i class="bi bi-instagram"></i></a>
      <a href="https://www.linkedin.com/in/el%C3%ADas-arias-mu%C3%B1oz-092ab9296" class="linkedin"><i class="bi bi-linkedin"></i></a>
    </div>

    <nav id="navmenu" class="navmenu">
      <ul>
        <li><a href="#hero" class="active"><i class="bi bi-house navicon"></i>Home</a></li>
        <li><a href="#about"><i class="bi bi-person navicon"></i> About</a></li>
        <li><a href="#resume"><i class="bi bi-file-earmark-text navicon"></i> Resume</a></li>
        <li><a href="#portfolio"><i class="bi bi-images navicon"></i> Portfolio</a></li>
        <li><a href="#contact"><i class="bi bi-envelope navicon"></i> Contact</a></li>
      </ul>
    </nav>

  </header>

  <main class="main">

    <!-- Hero Section -->
    <section id="hero" class="hero section dark-background">

      <img src="/src/assets/img/background5.png" alt="" data-aos="fade-in" class="">

      <div class="container" data-aos="fade-up" data-aos-delay="100">
        <h2>Elías Arias Muñoz</h2>
        <p>I'm <span class="typed" data-typed-items="Systems Engineer, Fullstack Developer">Designer</span><span class="typed-cursor typed-cursor--blink" aria-hidden="true"></span><span class="typed-cursor typed-cursor--blink" aria-hidden="true"></span></p>
      </div>

    </section><!-- /Hero Section -->

    <!-- About Section -->
    <section id="about" class="about section">

      <!-- Section Title -->
      <div class="container section-title" data-aos="fade-up">
        <h2>About me</h2>
        <p>I am deeply passionate about programming, development, and design, with a strong focus on continuous learning and the exploration of new languages and technologies. </p>
        <p>I embrace challenges as opportunities to apply and expand my expertise, consistently aiming for high-quality results. My dedication to excellence ensures the successful delivery of projects.</p>
        <p>Effective communication is a key aspect of my approach, keeping all stakeholders informed and aligned throughout the development process.</p>
      </div><!-- End Section Title -->

      <div class="container" data-aos="fade-up" data-aos-delay="100">

        <div class="row gy-4 justify-content-center">
          <div class="col-lg-4">
            <img src="/src/assets/img/profile_icon.jpeg" class="img-fluid rounded-image" alt="">
          </div>
          <div class="col-lg-8 content">
            <h2>Systems Engineer &amp; Full Stack Developer.</h2>
            <p class="fst-italic py-3">
            Let me tell you a little information about me
            </p>
            <div class="row">
              <div class="col-lg-6">
                <ul>
                  <li><i class="bi bi-chevron-right"></i> <strong>Birthday:</strong> <span>29 junio 2000</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>City:</strong> <span>Heredia</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>Age:</strong> <span>25</span></li>
                </ul>
              </div>
              <div class="col-lg-6">
                <ul>
                  <li><i class="bi bi-chevron-right"></i> <strong>Degree:</strong> <span>Bachelor in Information Systems Engineering</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>Email:</strong> <span>si.elias.arias@gmail.com</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>Status:</strong> <span>Available</span></li>
                </ul>
              </div>
            </div>
            <p class="py-3">
            I am always eager to collaborate on innovative projects that require problem-solving, technical expertise, and teamwork.
            I am particularly interested in contributing to dynamic environments where continuous improvement and learning are highly valued.
            </p>
          </div>
        </div>

      </div>

    </section><!-- /About Section -->

    <section id="skills" class="skills section light-background">
  <div class="container" data-aos="fade-up" data-aos-delay="100">

    <!-- Technical Skills -->
    <div class="row">
      <div class="col-lg-6 mb-4">
        <h3 class="text-center mb-4">Technical Skills</h3>
        <div class="card p-3">
          <h5 class="mb-3"><i class="bi bi-code-slash" style="color: #007bff;"></i> Programming Languages & Technologies</h5>
          <p>JAVA JavaScript, PHP, Kotlin, Python, HTML, CSS</p>

          <h5 class="mt-4 mb-3"><i class="bi bi-boxes" style="color: #17a2b8;"></i> Frameworks</h5>
          <p>Laravel (PHP), ASP.NET (C#), Bootstrap</p>

          <h5 class="mt-4 mb-3"><i class="bi bi-database" style="color: #6c757d;"></i> Databases</h5>
          <p>MySQL, Oracle, Firebase, SQLite</p>

          <h5 class="mt-4 mb-3"><i class="bi bi-tools" style="color: #f59e42;"></i> Tools</h5>
          <p>GitHub, Firebase (Crashlytics, Remote Config)</p>

          <h5 class="mt-4 mb-3"><i class="bi bi-diagram-3" style="color: #f11616;"></i> Methodologies</h5>
          <p>Waterfall, Agile Scrum (with Azure)</p>

          <h5 class="mt-4 mb-3"><i class="bi bi-windows" style="color: #28a745;"></i> Software</h5>
          <p>Basic knowledge of Microsoft Office 365</p>
        </div>
      </div>

      <!-- Soft Skills -->
      <div class="col-lg-6 mb-4">
        <h3 class="text-center mb-4">Soft Skills</h3>
        <div class="card p-3">
          <h5 class="mb-3"><i class="bi bi-award" style="color: #ffc107;"></i> Leadership</h5>
          <p>Demonstrated leadership and initiative in team settings.</p>

          <h5 class="mt-4 mb-3"><i class="bi bi-clock" style="color: #28a745;"></i> Time Management</h5>
          <p>Ability to work in an organized manner, managing time effectively and setting priorities.</p>

          <h5 class="mt-4 mb-3"><i class="bi bi-heart" style="color: #dc3545;"></i> Commitment</h5>
          <p>High dedication to work with top standards of effort, respect, and punctuality.</p>

          <h5 class="mt-4 mb-3"><i class="bi bi-arrow-repeat" style="color: #17a2b8;"></i> Adaptability</h5>
          <p>Strong desire for improvement and continuous learning.</p>

          <h5 class="mt-4 mb-3"><i class="bi bi-shield-lock" style="color: #6f42c1;"></i> Resilience</h5>
          <p>Proven ability to perform well under pressure.</p>

          <h5 class="mt-4 mb-3"><i class="bi bi-lightbulb" style="color: #f59e42;"></i> Problem Solving</h5>
          <p>Ability to adapt and find new solutions.</p>
        </div>
      </div>
    </div>
  </div>
</section>

        <!-- Resume Section -->
        <section id="resume" class="resume section">

        <!-- Section Title -->
        <div class="container section-title" data-aos="fade-up">
            <h2>Resume</h2>
            <p>I am passionate about programming and love to engage in continuous learning, constantly improving upon previously acquired skills.</p>
        </div><!-- End Section Title -->

        <div class="container">

            <div class="row">

            <div class="col-lg-6" data-aos="fade-up" data-aos-delay="100">

                <h3 class="resume-title">Education</h3>

                <div class="resume-item">
                  <h4>Licentiate Degree in Information Systems Engineering</h4>
                  <h5>2025 – Present </h5>
                  <p><em>Universidad Nacional de Costa Rica</em></p>
                </div>
                
                <div class="resume-item">
                <h4>Bachelor's Degree in Information Systems  Engineering</h4>
                <h5>2023 - 2024</h5>
                <p><em>Universidad Nacional de Costa Rica</em></p>
                </div><!-- Edn Resume Item -->

                <div class="resume-item">
                <h4>Diplomat in Information Systems Engineering</h4>
                <h5>2019 - 2023</h5>
                <p><em>Universidad Nacional de Costa Rica</em></p>
                </div><!-- Edn Resume Item -->


                <div class="resume-item">
                <h4>Middle Technician in Networking</h4>
                <h5>2018</h5>
                <p><em>CTP Jicaral</em></p>
                </div><!-- Edn Resume Item -->

                <div class="resume-item">
                <h4>Bachelor's Degree in Middle Education</h4>
                <h5>2018</h5>
                <p><em>CTP Jicaral</em></p>
                </div><!-- Edn Resume Item -->

            </div>

            

            <div class="col-lg-6" data-aos="fade-up" data-aos-delay="200">
                <h3 class="resume-title">Professional Experience</h3>


              <div class="resume-item">
                <h4>Mobile Developer </h4>
                <h5>August 2024 - January 2025</h5>
                <p><em>Freelance</em></p>
                <ul class="aligned-list">
                  <li>Designed, developed, and published a mobile application on the Play Store called PRO NOTES: Bloc Notas y Tareas, focused on task, note, and reminder management.</li>
                  <li>Implemented features such as scheduled alarms, custom folder creation, floating notes, and Firebase synchronization.</li>
                  <li>Applied modern design principles and user experience practices to enhance the app’s usability and visual appearance</li>
                </ul>
              </div><!-- Edn Resume Item -->

                <div class="resume-item">
                <h4>Fullstack Developer </h4>
                <h5>January 2024 - July 2024</h5>
                <p><em>CRNUBE</em></p>
                <ul class="aligned-list">
                    <li>Developed and implemented  a web project for the management of user authorizations to protected servers of its partners.</li>
                    <li>Authorizations control, user insertion of Excel files and movement control logs.</li>
                    <li>Teamwork under waterfall methodology.</li>
                </ul>
            </div><!-- Edn Resume Item -->

                <div class="resume-item">
                <h4>Fullstack Developer</h4>
                <h5>2022 - 2023</h5>
                <p><em>Santa Barbara Municipality</em></p>
                <ul class="aligned-list">
                    <li>Developed and implemented a web application for patent management.</li>
                    <li>Led the project's development using the Scrum methodology.</li>
                    <li>Migrated documents from Excel to a web system connected to a database.</li>
                </ul>
                </div><!-- Edn Resume Item -->

            </div>

            </div>

        </div>

    </section><!-- /Resume Section -->

 <!-- Certificates Section -->
<section id="certificates" class="certificates section light-background">
  <div class="container section-title" data-aos="fade-up">
    <h2>Certificates</h2>
    <p>Here are some of the certifications I've earned throughout my learning journey.</p>
  </div>

  <div class="container">
    <div class="row gy-4">

      <!-- Certificado 1 -->
      <div class="col-lg-4 col-md-6" data-aos="zoom-in" data-aos-delay="200">
        <div class="card shadow-sm h-100 p-3 d-flex flex-row align-items-start gap-3">
          <i class="bi bi-shield-check" style="font-size: 1.5rem; color: #0d6efd;"></i>
          <div>
            <h5 class="card-title mb-1">Endpoint Security</h5>
            <p class="card-text mb-0">INA</p>
          </div>
        </div>
      </div>

      <!-- Certificado 2 -->
      <div class="col-lg-4 col-md-6" data-aos="zoom-in" data-aos-delay="100">
        <div class="card shadow-sm h-100 p-3 d-flex flex-row align-items-start gap-3">
          <i class="bi bi-code-slash" style="font-size: 1.5rem; color: #198754;"></i>
          <div>
            <h5 class="card-title mb-1">Intermediate Python Course</h5>
            <p class="card-text mb-0">UDEMY</p>
          </div>
        </div>
      </div>

      <!-- Certificado 3 -->
      <div class="col-lg-4 col-md-6" data-aos="zoom-in" data-aos-delay="200">
        <div class="card shadow-sm h-100 p-3 d-flex flex-row align-items-start gap-3">
          <i class="bi bi-diagram-3" style="font-size: 1.5rem; color: #f59e42;"></i>
          <div>
            <h5 class="card-title mb-1">Scrum Fundamentals Certified</h5>
            <p class="card-text mb-0">Universidad Nacional</p>
          </div>
        </div>
      </div>

    </div>
  </div>
</section>



    <!-- Portfolio Section -->
    <section id="portfolio" class="portfolio section white-background">

      <!-- Section Title -->
      <div class="container section-title" data-aos="fade-up">
        <h2>Portfolio</h2>
        <p>
        Welcome to my portfolio! Here, you will find a collection of projects that showcase my skills and experience in software development, system design, and web applications.
        Each project represents a unique challenge I have tackled, demonstrating my commitment to delivering high-quality solutions through innovative thinking and technical expertise. I invite you to explore and discover how my work reflects my passion for technology and continuous learning.
       </p>
      </div><!-- End Section Title -->

      <div class="container">

        <div class="isotope-layout" data-default-filter="*" data-layout="masonry" data-sort="original-order">

          <ul class="portfolio-filters isotope-filters" data-aos="fade-up" data-aos-delay="100">
            <li data-filter="*" class="filter-active">All</li>
               <li data-filter=".filter-currently">In Progress</li>
            <li data-filter=".filter-app">App</li>
            <li data-filter=".filter-project">Projects</li>
          </ul><!-- End Portfolio Filters -->

          <div class="row gy-4 isotope-container" data-aos="fade-up" data-aos-delay="200">

              <div class="col-lg-4 col-md-6 portfolio-item isotope-item filter-currently filter-app">
              <div class="portfolio-content h-100">
                <img src="/src/assets/img/portfolio/riftmasters.png" class="img-fluid rounded-apps-section" alt="" >
                <div class="portfolio-info">
                  <h4>RIFT MASTERS</h4>
                  <p>Be a pro player</p>
                  <a href="/src/assets/img/portfolio/riftmasters.png" title="RIFT MASTERS" data-gallery="portfolio-gallery-app" class="glightbox preview-link"><i class="bi bi-zoom-in"></i></a>
                  <a href="#" target="_blank" title="More Details" class="details-link"><i class="bi bi-link-45deg"></i></a>
                </div>
                <p for="" class="project_titles">RIFT MASTERS | Kotlin | Google Play</p>
              </div>
            </div><!-- End Portfolio Item -->

            <div class="col-lg-4 col-md-6 portfolio-item isotope-item filter-app">
              <div class="portfolio-content h-100">
                <img src="/src/assets/img/portfolio/pronotes.png" class="img-fluid rounded-apps-section" alt="" >
                <div class="portfolio-info">
                  <h4>PRO NOTES</h4>
                  <p>Organize your notes and tasks</p>
                  <a href="/portfolio/src/assets/img/portfolio/pronotes.png" title="PRO NOTES" data-gallery="portfolio-gallery-app" class="glightbox preview-link"><i class="bi bi-zoom-in"></i></a>
                  <a href="#" target="_blank" title="More Details" class="details-link"><i class="bi bi-link-45deg"></i></a>
                </div>
                <p for="" class="project_titles">PRO NOTES | Kotlin | Google Play</p>
              </div>
            </div><!-- End Portfolio Item -->

             <div class="col-lg-4 col-md-6 portfolio-item isotope-item filter-project filter-currently ">
              <div class="portfolio-content h-100">
                <img src="/src/assets/img/portfolio/sisbot.png" class="img-fluid rounded-apps-section" alt="" >
                <div class="portfolio-info">
                  <h4>SISBOT</h4>
                  <p>volcanic and seismic information</p>
                  <a href="/portfolio/src/assets/img/portfolio/sisbot.png" title="SISBOT" data-gallery="portfolio-gallery-app" class="glightbox preview-link"><i class="bi bi-zoom-in"></i></a>
                  <a href="https://t.me/Ovsicori_SisBot" target="_blank" title="More Details" class="details-link"><i class="bi bi-link-45deg"></i></a>
                </div>
                <p for="" class="project_titles">SISBOT | Python + IA | OVSICORI </p>
              </div>
            </div><!-- End Portfolio Item -->

            <div class="col-lg-4 col-md-6 portfolio-item isotope-item filter-project filter-currently ">
              <div class="portfolio-content h-100">
                <img src="/src/assets/img/portfolio/kode.png" class="img-fluid rounded-apps-section" alt="" >
                <div class="portfolio-info">
                  <h4>KODE</h4>
                  <p>Your class assistance</p>
                  <a href="/portfolio/src/assets/img/portfolio/kode.png" title="KODE" data-gallery="portfolio-gallery-app" class="glightbox preview-link"><i class="bi bi-zoom-in"></i></a>
                  <a href="https://kode-frontend.netlify.app" target="_blank" title="More Details" class="details-link"><i class="bi bi-link-45deg"></i></a>
                </div>
                <p for="" class="project_titles">KODE | Springboot + React + Next.js + IA | Personal </p>
              </div>
            </div><!-- End Portfolio Item -->
          </div><!-- End Portfolio Container -->

        </div>

      </div>

    </section><!-- /Portfolio Section -->

    <!-- Contact Section -->
    <section id="contact" class="contact section light-background">

      <!-- Section Title -->
      <div class="container section-title" data-aos="fade-up">
        <h2>Contact</h2>
      </div><!-- End Section Title -->

      <div class="container" data-aos="fade-up" data-aos-delay="100">

        <div class="row gy-4">

          <div class="col-lg-6">

            <div class="info-wrap">
              <div class="info-item d-flex" data-aos="fade-up" data-aos-delay="200">
                <i class="bi bi-geo-alt flex-shrink-0"></i>
                <div>
                  <h3>Address</h3>
                  <p>Heredia, CR</p>
                </div>
              </div><!-- End Info Item -->

              <div class="info-item d-flex" data-aos="fade-up" data-aos-delay="200">
                <i class="bi bi-linkedin flex-shrink-0"></i>
                <div>
                  <h3>Chat with me</h3>
                  <a href="https://www.linkedin.com/in/el%C3%ADas-arias-mu%C3%B1oz-092ab9296/">Send a message</a>
                </div>
              </div>


              <div class="info-item d-flex" data-aos="fade-up" data-aos-delay="400">
                <i class="bi bi-envelope flex-shrink-0"></i>
                <div>
                  <h3>Email me</h3>
                  <p>si.elias.arias@gmail.com</p>
                </div>
              </div><!-- End Info Item -->
            </div>
          </div>

          <div class="col-lg-6">
            <div class="php-email-form" data-aos="fade-up" data-aos-delay="200">
            <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d15716.8957671913!2d-84.13219130856986!3d9.99835194170963!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8fa0faddaded66bd%3A0x2527e99d1a1e0bdf!2sHeredia!5e0!3m2!1ses-419!2scr!4v1732896412988!5m2!1ses-419!2scr"
                width="100%"
                height="250"
                style="border:0;"
                allowfullscreen=""
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade">
            </iframe>
                </div>
          </div><!-- End Contact Form -->

        </div>

      </div>

    </section><!-- /Contact Section -->

  </main>

  <footer id="footer" class="footer position-relative white-background">

    <div class="container">
      <div class="copyright text-center ">
        <p>© <span>Copyright</span> <strong class="px-1 sitename">Elías Arias Muñoz</strong> <span>All Rights Reserved</span></p>
      </div>
    </div>

  </footer>

  <!-- Scroll Top -->
  <a href="#" id="scroll-top" class="scroll-top d-flex align-items-center justify-content-center"><i class="bi bi-arrow-up-short"></i></a>

  <!-- Preloader -->
  <div id="preloader"></div>

  

</template>


<script setup>
import { onMounted } from 'vue'
import Isotope from 'isotope-layout'
import imagesLoaded from 'imagesloaded'

onMounted(() => {
  const container = document.querySelector('.isotope-container')
  const filterButtons = document.querySelectorAll('.portfolio-filters li')

  if (container) {
    // Espera a que las imágenes se carguen antes de inicializar
    imagesLoaded(container, () => {
      const iso = new Isotope(container, {
        itemSelector: '.portfolio-item',
        layoutMode: 'masonry',
      })

      filterButtons.forEach(btn => {
        btn.addEventListener('click', function () {
          // Quitar clase activa anterior
          document.querySelector('.portfolio-filters .filter-active')?.classList.remove('filter-active')
          this.classList.add('filter-active')

          const filterValue = this.getAttribute('data-filter')
          iso.arrange({ filter: filterValue })
        })
      })
    })
  }
})

import Typed from 'typed.js'

onMounted(() => {
  const el = document.querySelector('.typed')
  if (el) {
    const typedStrings = el.getAttribute('data-typed-items')?.split(',') || []
    new Typed('.typed', {
      strings: typedStrings,
      typeSpeed: 100,
      backSpeed: 50,
      loop: true,
      backDelay: 2000,
      smartBackspace: true
    })
  }
})
</script>


<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
