<template>
  <!-- Footer -->
  <footer class="footer footer-five">
    <!-- Footer Top -->
    <div class="footer-top-five">
      <div class="container">
        <div class="footer-five-left">
          <img src="@/assets/img/bg/footer-left.svg" alt="" />
        </div>

        <div class="row">
          <div class="col-xl-4 col-lg-6 col-md-6 col-sm-12">
            <!-- Footer Widget -->
            <div class="footer-contact footer-menu-five">
              <h2 class="footer-title footer-title-five">Get in touch</h2>
              <div class="footer-contact-info">
                <div class="footer-address">
                  <span><i class="feather-map-pin"></i></span>
                  <p>
                    3556 Beech Street, San Francisco,<br />
                    California, CA 94108
                  </p>
                </div>
                <p class="mb-0">
                  <span class="phone-icon"><i class="fa-solid fa-phone-volume"></i></span>
                  +19 123-456-7890
                </p>
              </div>
            </div>
            <!-- /Footer Widget -->
          </div>

          <div class="col-lg-2 col-md-3 col-sm-12">
            <!-- Footer Widget -->
            <div class="footer-menu footer-menu-five">
              <h2 class="footer-title footer-title-five">
                <i class="fa-sharp fa-solid fa-dash"></i>For Instructor
              </h2>
              <ul>
                <li><router-link to="/instructor/instructor-profile">Profile</router-link></li>
                <li><router-link to="/">Login</router-link></li>
                <li><router-link to="/register">Register</router-link></li>
                <li><router-link to="/instructor/instructor-list">Instructor</router-link></li>
                <li>
                  <router-link to="/instructor/instructor-dashboard"> Dashboard</router-link>
                </li>
              </ul>
            </div>
            <!-- /Footer Widget -->
          </div>

          <div class="col-lg-2 col-md-3 col-sm-12">
            <!-- Footer Widget -->
            <div class="footer-menu footer-menu-five">
              <h2 class="footer-title footer-title-five">For Student</h2>
              <ul>
                <li><router-link to="/student/student-profile">Profile</router-link></li>
                <li><router-link to="/">Login</router-link></li>
                <li><router-link to="/register">Register</router-link></li>
                <li><router-link to="/student/students-list">Student</router-link></li>
                <li>
                  <router-link to="/student/student-dashboard"> Dashboard</router-link>
                </li>
              </ul>
            </div>
            <!-- /Footer Widget -->
          </div>

          <div class="col-lg-4 col-md-6 col-sm-6 col-12">
            <h2 class="footer-title footer-title-five">Get More Updates</h2>
            <!-- Footer Widget -->
            <div class="footer-widget-five">
              <div class="footer-news-five">
                <form>
                  <div class="input-block mb-0">
                    <input
                      type="text"
                      class="form-control"
                      placeholder="Enter Your Email Address"
                    />
                    <button type="submit" class="btn btn-one">Subscribe</button>
                  </div>
                </form>
              </div>
              <div class="footer-about-five">
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut consequat
                  mauris Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut
                  consequat mauris
                </p>
              </div>
            </div>
            <!-- /Footer Widget -->
          </div>
        </div>

        <div class="footer-five-right">
          <img src="@/assets/img/bg/footer-right.svg" alt="" />
        </div>
      </div>
    </div>
    <!-- /Footer Top -->

    <!-- Footer Bottom -->
    <div class="footer-bottom footer-bottom-five">
      <div class="container">
        <!-- Copyright -->
        <div class="copyright-five">
          <div class="row align-items-center">
            <div class="col-md-4">
              <div class="footer-logo-five">
                <router-link to="/home/">
                  <img
                    src="@/assets/img/logo/logo-five.svg"
                    class="img-fluid"
                    alt="Footer Logo"
                  />
                </router-link>
              </div>
            </div>
            <div class="col-md-4">
              <div class="copyright-text">
                <p>&copy; 2023 DreamsLMS. All rights reserved.</p>
              </div>
            </div>
            <div class="col-md-4">
              <div class="social-icon-five">
                <ul class="nav">
                  <li>
                    <a href="javascript:;" target="_blank" class="twitter-icon">
                      <i class="fab fa-twitter"></i>
                    </a>
                  </li>
                  <li>
                    <a href="javascript:;" target="_blank" class="linked-icon">
                      <i class="fab fa-linkedin-in"></i>
                    </a>
                  </li>
                  <li>
                    <a href="javascript:;" target="_blank" class="facebook-icon">
                      <i class="fab fa-facebook-f"></i>
                    </a>
                  </li>
                  <li>
                    <a href="javascript:;" target="_blank" class="youtube-icon">
                      <i class="fab fa-youtube"></i>
                    </a>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
        <!-- /Copyright -->
      </div>
    </div>
    <!-- /Footer Bottom -->
  </footer>
  <!-- /Footer -->
</template>
