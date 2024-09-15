Thanks for downloading this template!

Template Name: Laura
Template URL: https://bootstrapmade.com/laura-free-creative-bootstrap-theme/
Author: BootstrapMade.com
License: https://bootstrapmade.com/license/




   <div class="row portfolio-container">
<div class="col-lg-4 col-md-6 portfolio-item filter-card">
              <div class="portfolio-img">
                <img
                  src="assets/img/portfolio/Screenshot 2024-09-14 133222.png"
                  class="img-fluid"
                  alt=""
                />
              </div>
              <div class="portfolio-info">
                <h4>Web 1</h4>
                <p>Web</p>
                <a
                  href="assets/img/portfolio/Screenshot 2024-09-14 133548.png"
                  data-gallery="portfolioGallery"
                  class="portfolio-lightbox preview-link"
                  title="Card 3"
                  ><i class="bx bx-plus"></i
                ></a>
                <a
                  href="portfolio-details.html"
                  class="details-link"
                  title="More Details"
                  ><i class="bx bx-link"></i
                ></a>
              </div>
            </div>
            <div class="col-lg-4 col-md-6 portfolio-item filter-card">
              <div class="portfolio-img">
                <img
                  src="assets/img/portfolio/Screenshot 2024-09-14 133900.png"
                  class="img-fluid"
                  alt=""
                />
              </div>
              <div class="portfolio-info">
                <h4>Web 2</h4>
                <p>Web</p>
                <a
                  href="assets/img/portfolio/Screenshot 2024-09-14 134024.png"
                  data-gallery="portfolioGallery"
                  class="portfolio-lightbox preview-link"
                  title="Card 3"
                  ><i class="bx bx-plus"></i
                ></a>
                <a
                  href="portfolio-details.html"
                  class="details-link"
                  title="More Details"
                  ><i class="bx bx-link"></i
                ></a>
              </div>
            </div>

            <div class="col-lg-4 col-md-6 portfolio-item filter-web">
              <div class="portfolio-img">
                <img
                  src="assets/img/portfolio/Screenshot 2024-09-14 140429.png"
                  class="img-fluid"
                  alt=""
                />
              </div>
              <div class="portfolio-info">
                <h4>Web 3</h4>
                <p>Web</p>
                <a
                  href="assets/img/portfolio/Screenshot 2024-09-14 140503.png"
                  data-gallery="portfolioGallery"
                  class="portfolio-lightbox preview-link"
                  title="Web 3"
                  ><i class="bx bx-plus"></i
                ></a>
                <a
                  href="portfolio-details.html"
                  class="details-link"
                  title="More Details"
                  ><i class="bx bx-link"></i
                ></a>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- End My Portfolio Section -->











      .portfolio #portfolio-flters {
  list-style: none;
  margin-bottom: 20px;
}

.portfolio #portfolio-flters li {
  cursor: pointer;
  display: inline-block;
  margin: 0 10px 10px 10px;
  font-size: 15px;
  font-weight: 600;
  line-height: 1;
  padding: 7px 10px;
  text-transform: uppercase;
  color: #444444;
  transition: all 0.3s ease-in-out;
  border: 2px solid #fff;
}

.portfolio #portfolio-flters li:hover,
.portfolio #portfolio-flters li.filter-active {
  color: #f3a200;
  border-color: #ffb727;
}

.portfolio .portfolio-item {
  margin-bottom: 30px;
}

.portfolio .portfolio-item .portfolio-img {
  overflow: hidden;
}

.portfolio .portfolio-item .portfolio-img img {
  transition: all 0.8s ease-in-out;
}

.portfolio .portfolio-item .portfolio-info {
  opacity: 0;
  position: absolute;
  left: 15px;
  bottom: 0;
  z-index: 3;
  right: 15px;
  transition: all ease-in-out 0.3s;
  background: rgba(0, 0, 0, 0.5);
  padding: 10px 15px;
}

.portfolio .portfolio-item .portfolio-info h4 {
  font-size: 18px;
  color: #fff;
  font-weight: 600;
  color: #fff;
  margin-bottom: 0px;
}

.portfolio .portfolio-item .portfolio-info p {
  color: rgba(255, 255, 255, 0.8);
  font-size: 14px;
  margin-bottom: 0;
}

.portfolio .portfolio-item .portfolio-info .preview-link,
.portfolio .portfolio-item .portfolio-info .details-link {
  position: absolute;
  right: 40px;
  font-size: 24px;
  top: calc(50% - 18px);
  color: #fff;
  transition: 0.3s;
}

.portfolio .portfolio-item .portfolio-info .preview-link:hover,
.portfolio .portfolio-item .portfolio-info .details-link:hover {
  color: #ffc041;
}

.portfolio .portfolio-item .portfolio-info .details-link {
  right: 10px;
}

.portfolio .portfolio-item:hover .portfolio-img img {
  transform: scale(1.2);
}

.portfolio .portfolio-item:hover .portfolio-info {
  opacity: 1;
}

/*--------------------------------------------------------------
# Portfolio Details
--------------------------------------------------------------*/
.portfolio-details {
  padding-top: 40px;
}

.portfolio-details .portfolio-details-slider img {
  width: 100%;
}

.portfolio-details .portfolio-details-slider .swiper-pagination {
  margin-top: 20px;
  position: relative;
}

.portfolio-details .portfolio-details-slider .swiper-pagination .swiper-pagination-bullet {
  width: 12px;
  height: 12px;
  background-color: #fff;
  opacity: 1;
  border: 1px solid #ffb727;
}

.portfolio-details .portfolio-details-slider .swiper-pagination .swiper-pagination-bullet-active {
  background-color: #ffb727;
}

.portfolio-details .portfolio-info {
  padding: 30px;
  box-shadow: 0px 0 30px rgba(59, 67, 74, 0.08);
}

.portfolio-details .portfolio-info h3 {
  font-size: 22px;
  font-weight: 700;
  margin-bottom: 20px;
  padding-bottom: 20px;
  border-bottom: 1px solid #eee;
}

.portfolio-details .portfolio-info ul {
  list-style: none;
  padding: 0;
  font-size: 15px;
}

.portfolio-details .portfolio-info ul li+li {
  margin-top: 10px;
}

.portfolio-details .portfolio-description {
  padding-top: 30px;
}

.portfolio-details .portfolio-description h2 {
  font-size: 26px;
  font-weight: 700;
  margin-bottom: 20px;
}

.portfolio-details .portfolio-description p {
  padding: 0;
}


my class



 <section id="portfolio" class="portfolio">
        <div class="container">
          <div class="section-title">
            <span>My Portfolio</span>
            <h2>My Portfolio</h2>
          </div class="image grid">
          <div id="three1">
          <a href="https://spontaneous-gumption-950146.netlify.app/">
            <img src="assets/img/portfolio/Screenshot 2024-09-14 133222.png" alt="responsive landpage">
          </a>
          </div>
          <div id="three2">
          <a href="https://starlit-cuchufli-6d8394.netlify.app/">
            <img src="assets/img/portfolio/Screenshot 2024-09-14 133548.png" alt="stopwatch">
          </a>
          </div>
          <div id="three4">
          <a href="https://transcendent-bunny-7fba66.netlify.app/">
            <img src="assets/img/portfolio/Screenshot 2024-09-14 133900.png" alt="Tic Tac Toe">
          </a>
          </div>
          <a href="https://neon-druid-f5d1fe.netlify.app/">
            <img src="assets/img/portfolio/Screenshot 2024-09-14 134024.png" alt="weather app">
          </a>
          <a href="https://resilient-cactus-a679c8.netlify.app">
            <img src="assets/img/portfolio/Screenshot 2024-09-14 140429.png" alt="Netflix clone">
          </a>
          <a href="https://melodic-tapioca-6ae3fa.netlify.app">
            <img src="assets/img/portfolio/Screenshot 2024-09-14 140503.png" alt="Amazon clone">
          </a>





          <section id="portfolio" class="portfolio">
        <div class="container">
          <div class="section-title">
            <span>My Portfolio</span>
            <h2>My Portfolio</h2>
          </div class="image grid">
          <div id="three1">
          <a href="https://spontaneous-gumption-950146.netlify.app/">
            <img src="assets/img/portfolio/Screenshot 2024-09-14 133222.png" alt="responsive landpage">
          </a>
          </div>
          <div id="three2">
          <a href="https://starlit-cuchufli-6d8394.netlify.app/">
            <img src="assets/img/portfolio/Screenshot 2024-09-14 133548.png" alt="stopwatch">
          </a>
          </div>
          <div id="three4">
          <a href="https://transcendent-bunny-7fba66.netlify.app/">
            <img src="assets/img/portfolio/Screenshot 2024-09-14 133900.png" alt="Tic Tac Toe">
          </a>
          </div>
          <a href="https://neon-druid-f5d1fe.netlify.app/">
            <img src="assets/img/portfolio/Screenshot 2024-09-14 134024.png" alt="weather app">
          </a>
          <a href="https://resilient-cactus-a679c8.netlify.app">
            <img src="assets/img/portfolio/Screenshot 2024-09-14 140429.png" alt="Netflix clone">
          </a>
          <a href="https://melodic-tapioca-6ae3fa.netlify.app">
            <img src="assets/img/portfolio/Screenshot 2024-09-14 140503.png" alt="Amazon clone">
          </a>









          <div class="skills-content ps-lg-4">
                <div class="progress">
                  <span class="skill">HTML <i class="val">100%</i></span>
                  <div class="progress-bar-wrap">
                    <div
                      class="progress-bar"
                      role="progressbar"
                      aria-valuenow="100"
                      aria-valuemin="0"
                      aria-valuemax="100"
                    ></div>
                  </div>
                </div>

                <div class="progress">
                  <span class="skill">CSS <i class="val">90%</i></span>
                  <div class="progress-bar-wrap">
                    <div
                      class="progress-bar"
                      role="progressbar"
                      aria-valuenow="90"
                      aria-valuemin="0"
                      aria-valuemax="100"
                    ></div>
                  </div>
                </div>

                <div class="progress">
                  <span class="skill">Bootstrap <i class="val">75%</i></span>
                  <div class="progress-bar-wrap">
                    <div
                      class="progress-bar"
                      role="progressbar"
                      aria-valuenow="75"
                      aria-valuemin="0"
                      aria-valuemax="100"
                    ></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>