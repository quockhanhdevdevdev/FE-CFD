<template>
    <layouts-instructorborder></layouts-instructorborder>

    <student-breadcrumb :title="title" :text="text" :text1="text1" />

    <!-- Page Content -->
    <div class="page-content">
        <div class="container">
            <div class="row">

                <!-- sidebar -->
                <instructor-sidebar></instructor-sidebar>
                <!-- /Sidebar -->

                <!-- Student Dashboard -->
                <div class="col-xl-9 col-lg-9">

                    <!-- Dashboard Grid -->
                    <div class="row justify-content-center">
                        <div class="col-lg-4 col-md-6 d-flex">
                            <div class="card dash-info flex-fill">
                                <div class="card-body">
                                    <h5>Enrolled Courses</h5>
                                    <h2>13</h2>
                                </div>
                            </div>
                        </div>
                        <div class="col-lg-4 col-md-6 d-flex">
                            <div class="card dash-info flex-fill">
                                <div class="card-body">
                                    <h5>Active Courses</h5>
                                    <h2>08</h2>
                                </div>
                            </div>
                        </div>
                        <div class="col-lg-4 col-md-6 d-flex">
                            <div class="card dash-info flex-fill">
                                <div class="card-body">
                                    <h5>Completed Courses</h5>
                                    <h2>06</h2>
                                </div>
                            </div>
                        </div>
                        <div class="col-lg-4 col-md-6 d-flex">
                            <div class="card dash-info flex-fill">
                                <div class="card-body">
                                    <h5>Total Students</h5>
                                    <h2>5</h2>
                                </div>
                            </div>
                        </div>
                        <div class="col-lg-4 col-md-6 d-flex">
                            <div class="card dash-info flex-fill">
                                <div class="card-body">
                                    <h5>Total Courses</h5>
                                    <h2>11</h2>
                                </div>
                            </div>
                        </div>
                        <div class="col-lg-4 col-md-6 d-flex">
                            <div class="card dash-info flex-fill">
                                <div class="card-body">
                                    <h5>Total Earnings</h5>
                                    <h2>$486</h2>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- /Dashboard Grid -->

                    <div class="instructor-course-table">
                        <div class="dashboard-title">
                            <h4>Recently Created Courses</h4>
                        </div>
                        <div class="table-responsive custom-table">

                            <!-- Referred Users-->
                            <table class="table table-nowrap mb-0">
                                <thead>
                                    <tr>
                                        <th>Courses</th>
                                        <th>Enrolled</th>
                                        <th>Status</th>
                                    </tr>
                                </thead>
                                <tbody>
                                    <tr>
                                        <td>
                                            <div class="table-course-detail">
                                                <router-link to="/course/course-details" class="course-table-img">
                                                    <span><img src="@/assets/img/instructor/instructor-table-01.jpg"
                                                            alt="Img"></span>
                                                    Complete HTML, CSS and Javascript Course
                                                </router-link>
                                            </div>
                                        </td>
                                        <td>0</td>
                                        <td>Published</td>
                                    </tr>
                                    <tr>
                                        <td>
                                            <div class="table-course-detail">
                                                <router-link to="/course/course-details" class="course-table-img">
                                                    <span><img src="@/assets/img/instructor/instructor-table-05.jpg"
                                                            alt="Img"></span>
                                                    Complete Course on Fullstack Web Developer
                                                    </router-link>
                                            </div>
                                        </td>
                                        <td>2</td>
                                        <td>Published</td>
                                    </tr>
                                    <tr>
                                        <td>
                                            <div class="table-course-detail">
                                                <router-link to="/course/course-details" class="course-table-img">
                                                    <span><img src="@/assets/img/instructor/instructor-table-02.jpg"
                                                            alt="Img"></span>
                                                    Data Science Fundamentals and Advanced Bootcamp
                                                    </router-link>
                                            </div>
                                        </td>
                                        <td>2</td>
                                        <td>Published</td>
                                    </tr>
                                    <tr>
                                        <td>
                                            <div class="table-course-detail">
                                                <router-link to="/course/course-details" class="course-table-img">
                                                    <span><img src="@/assets/img/instructor/instructor-table-03.jpg"
                                                            alt="Img"></span>
                                                    Master Microservices with Spring Boot and Spring Cloud
                                                    </router-link>
                                            </div>
                                        </td>
                                        <td>1</td>
                                        <td>Published</td>
                                    </tr>
                                    <tr>
                                        <td>
                                            <div class="table-course-detail">
                                                <router-link to="/course/course-details" class="course-table-img">
                                                    <span><img src="@/assets/img/instructor/instructor-table-04.jpg"
                                                            alt="Img"></span>
                                                    Information About UI/UX Design Degree
                                                    </router-link>
                                            </div>
                                        </td>
                                        <td>3</td>
                                        <td>Published</td>
                                    </tr>
                                </tbody>
                            </table>
                        </div>
                    </div>


                    <div class="dashboard-title">
                        <h4>Recently Enrolled Courses</h4>
                    </div>
                    <div class="row">

                        <!-- Course Grid -->
                        <div class="col-xxl-4 col-md-6 d-flex">
                            <div class="course-box flex-fill">
                                <div class="product">
                                    <div class="product-img">
                                        <router-link to="/course/course-details">
                                            <img class="img-fluid" alt="Img" src="@/assets/img/course/course-02.jpg">
                                        </router-link>
                                        <div class="price">
                                            <h3>$80 <span>$99.00</span></h3>
                                        </div>
                                    </div>
                                    <div class="product-content">
                                        <div class="course-group d-flex">
                                            <div class="course-group-img d-flex">
                                                <router-link to="/instructor/instructor-profile"><img src="@/assets/img/user/user2.jpg"
                                                        alt="Img" class="img-fluid"></router-link>
                                                <div class="course-name">
                                                    <h4><router-link to="/instructor/instructor-profile">Cooper</router-link></h4>
                                                    <p>Instructor</p>
                                                </div>
                                            </div>
                                            <div class="course-share d-flex align-items-center justify-content-center">
                                                <a href="#"><i class="fa-regular fa-heart"></i></a>
                                            </div>
                                        </div>
                                        <h3 class="title instructor-text"><router-link to="/course/course-details">Wordpress for
                                                Beginners - Master Wordpress Quickly</router-link></h3>
                                        <div class="course-info d-flex align-items-center">
                                            <div class="rating-img d-flex align-items-center">
                                                <img src="@/assets/img/icon/icon-01.svg" alt="Img">
                                                <p>12+ Lesson</p>
                                            </div>
                                            <div class="course-view d-flex align-items-center">
                                                <img src="@/assets/img/icon/icon-02.svg" alt="Img">
                                                <p>70hr 30min</p>
                                            </div>
                                        </div>
                                        <div class="rating mb-0">
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star filled me-1"></i>
                                            <span class="d-inline-block average-rating"><span>5.0</span> (20)</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <!-- /Course Grid -->

                        <!-- Course Grid -->
                        <div class="col-xxl-4 col-md-6 d-flex">
                            <div class="course-box flex-fill">
                                <div class="product">
                                    <div class="product-img">
                                        <router-link to="/course/course-details">
                                            <img class="img-fluid" alt="Img" src="@/assets/img/course/course-03.jpg">
                                        </router-link>
                                        <div class="price combo">
                                            <h3>FREE</h3>
                                        </div>
                                    </div>
                                    <div class="product-content">
                                        <div class="course-group d-flex">
                                            <div class="course-group-img d-flex">
                                                <router-link to="/instructor/instructor-profile"><img src="@/assets/img/user/user5.jpg"
                                                        alt="Img" class="img-fluid"></router-link>
                                                <div class="course-name">
                                                    <h4><router-link to="/instructor/instructor-profile">Jenny</router-link></h4>
                                                    <p>Instructor</p>
                                                </div>
                                            </div>
                                            <div class="course-share d-flex align-items-center justify-content-center">
                                                <a href="#"><i class="fa-regular fa-heart"></i></a>
                                            </div>
                                        </div>
                                        <h3 class="title instructor-text"><router-link to="/course/course-details">Sketch from A to
                                                Z (2022): Become an app designer</router-link></h3>
                                        <div class="course-info d-flex align-items-center">
                                            <div class="rating-img d-flex align-items-center">
                                                <img src="@/assets/img/icon/icon-01.svg" alt="Img">
                                                <p>10+ Lesson</p>
                                            </div>
                                            <div class="course-view d-flex align-items-center">
                                                <img src="@/assets/img/icon/icon-02.svg" alt="Img">
                                                <p>40hr 10min</p>
                                            </div>
                                        </div>
                                        <div class="rating mb-0">
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star me-1"></i>
                                            <i class="fas fa-star me-1"></i>
                                            <span class="d-inline-block average-rating"><span>3.0</span> (18)</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <!-- /Course Grid -->

                        <!-- Course Grid -->
                        <div class="col-xxl-4 col-md-6 d-flex">
                            <div class="course-box flex-fill">
                                <div class="product">
                                    <div class="product-img">
                                        <router-link to="/course/course-details">
                                            <img class="img-fluid" alt="Img" src="@/assets/img/course/course-04.jpg">
                                        </router-link>
                                        <div class="price">
                                            <h3>$65 <span>$70.00</span></h3>
                                        </div>
                                    </div>
                                    <div class="product-content">
                                        <div class="course-group d-flex">
                                            <div class="course-group-img d-flex">
                                                <router-link to="/instructor/instructor-profile"><img src="@/assets/img/user/user4.jpg"
                                                        alt="Img" class="img-fluid"></router-link>
                                                <div class="course-name">
                                                    <h4><router-link to="/instructor/instructor-profile">Nicole Brown</router-link></h4>
                                                    <p>Instructor</p>
                                                </div>
                                            </div>
                                            <div class="course-share d-flex align-items-center justify-content-center">
                                                <a href="#"><i class="fa-regular fa-heart"></i></a>
                                            </div>
                                        </div>
                                        <h3 class="title instructor-text"><router-link to="/course/course-details">Learn Angular
                                                Fundamentals From beginning to advance lavel</router-link></h3>
                                        <div class="course-info d-flex align-items-center">
                                            <div class="rating-img d-flex align-items-center">
                                                <img src="@/assets/img/icon/icon-01.svg" alt="Img">
                                                <p>15+ Lesson</p>
                                            </div>
                                            <div class="course-view d-flex align-items-center">
                                                <img src="@/assets/img/icon/icon-02.svg" alt="Img">
                                                <p>80hr 40min</p>
                                            </div>
                                        </div>
                                        <div class="rating mb-0">
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star me-1"></i>
                                            <span class="d-inline-block average-rating"><span>4.0</span> (10)</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <!-- /Course Grid -->

                        <!-- Course Grid -->
                        <div class="col-xxl-4 col-md-6 d-flex">
                            <div class="course-box flex-fill">
                                <div class="product">
                                    <div class="product-img">
                                        <router-link to="/course/course-details">
                                            <img class="img-fluid" alt="Img" src="@/assets/img/course/course-05.jpg">
                                        </router-link>
                                        <div class="price combo">
                                            <h3>FREE</h3>
                                        </div>
                                    </div>
                                    <div class="product-content">
                                        <div class="course-group d-flex">
                                            <div class="course-group-img d-flex">
                                                <router-link to="/instructor/instructor-profile"><img src="@/assets/img/user/user3.jpg"
                                                        alt="Img" class="img-fluid"></router-link>
                                                <div class="course-name">
                                                    <h4><router-link to="/instructor/instructor-profile">John Smith</router-link></h4>
                                                    <p>Instructor</p>
                                                </div>
                                            </div>
                                            <div class="course-share d-flex align-items-center justify-content-center">
                                                <a href="#"><i class="fa-regular fa-heart"></i></a>
                                            </div>
                                        </div>
                                        <h3 class="title instructor-text"><router-link to="/course/course-details">Build Responsive
                                                Real World Websites with Crash Course</router-link></h3>
                                        <div class="course-info d-flex align-items-center">
                                            <div class="rating-img d-flex align-items-center">
                                                <img src="@/assets/img/icon/icon-01.svg" alt="Img">
                                                <p>12+ Lesson</p>
                                            </div>
                                            <div class="course-view d-flex align-items-center">
                                                <img src="@/assets/img/icon/icon-02.svg" alt="Img">
                                                <p>70hr 30min</p>
                                            </div>
                                        </div>
                                        <div class="rating mb-0">
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star me-1"></i>
                                            <span class="d-inline-block average-rating"><span>4.0</span> (15)</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <!-- /Course Grid -->

                        <!-- Course Grid -->
                        <div class="col-xxl-4 col-md-6 d-flex">
                            <div class="course-box flex-fill">
                                <div class="product">
                                    <div class="product-img">
                                        <router-link to="/course/course-details">
                                            <img class="img-fluid" alt="Img" src="@/assets/img/course/course-07.jpg">
                                        </router-link>
                                        <div class="price">
                                            <h3>$70 <span>$80.00</span></h3>
                                        </div>
                                    </div>
                                    <div class="product-content">
                                        <div class="course-group d-flex">
                                            <div class="course-group-img d-flex">
                                                <router-link to="/instructor/instructor-profile"><img src="@/assets/img/user/user6.jpg"
                                                        alt="Img" class="img-fluid"></router-link>
                                                <div class="course-name">
                                                    <h4><router-link to="/instructor/instructor-profile">Stella Johnson</router-link></h4>
                                                    <p>Instructor</p>
                                                </div>
                                            </div>
                                            <div class="course-share d-flex align-items-center justify-content-center">
                                                <a href="#"><i class="fa-regular fa-heart"></i></a>
                                            </div>
                                        </div>
                                        <h3 class="title instructor-text"><router-link to="/course/course-details">Learn JavaScript
                                                and Express to become a Expert</router-link></h3>
                                        <div class="course-info d-flex align-items-center">
                                            <div class="rating-img d-flex align-items-center">
                                                <img src="@/assets/img/icon/icon-01.svg" alt="Img">
                                                <p>15+ Lesson</p>
                                            </div>
                                            <div class="course-view d-flex align-items-center">
                                                <img src="@/assets/img/icon/icon-02.svg" alt="Img">
                                                <p>70hr 30min</p>
                                            </div>
                                        </div>
                                        <div class="rating mb-0">
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star me-1"></i>
                                            <span class="d-inline-block average-rating"><span>4.6</span> (15)</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <!-- /Course Grid -->

                        <!-- Course Grid -->
                        <div class="col-xxl-4 col-md-6 d-flex">
                            <div class="course-box flex-fill">
                                <div class="product">
                                    <div class="product-img">
                                        <router-link to="/course/course-details">
                                            <img class="img-fluid" alt="Img" src="@/assets/img/course/course-08.jpg">
                                        </router-link>
                                        <div class="price combo">
                                            <h3>FREE</h3>
                                        </div>
                                    </div>
                                    <div class="product-content">
                                        <div class="course-group d-flex">
                                            <div class="course-group-img d-flex">
                                                <router-link to="/instructor/instructor-profile"><img src="@/assets/img/user/user1.jpg"
                                                        alt="Img" class="img-fluid"></router-link>
                                                <div class="course-name">
                                                    <h4><router-link to="/instructor/instructor-profile">Nicole Brown</router-link></h4>
                                                    <p>Instructor</p>
                                                </div>
                                            </div>
                                            <div class="course-share d-flex align-items-center justify-content-center">
                                                <a href="#"><i class="fa-regular fa-heart"></i></a>
                                            </div>
                                        </div>
                                        <h3 class="title instructor-text"><router-link to="/course/course-details">Introduction to
                                                Programming- Python & Java</router-link></h3>
                                        <div class="course-info d-flex align-items-center">
                                            <div class="rating-img d-flex align-items-center">
                                                <img src="@/assets/img/icon/icon-01.svg" alt="Img">
                                                <p>10+ Lesson</p>
                                            </div>
                                            <div class="course-view d-flex align-items-center">
                                                <img src="@/assets/img/icon/icon-02.svg" alt="Img">
                                                <p>70hr 30min</p>
                                            </div>
                                        </div>
                                        <div class="rating mb-0">
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star filled me-1"></i>
                                            <i class="fas fa-star filled me-1"></i>
                                            <span class="d-inline-block average-rating"><span>5.0</span> (13)</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <!-- /Course Grid -->

                    </div>
                    <div class="dash-pagination">
                        <div class="row align-items-center">
                            <div class="col-6">
                                <p>Page 1 of 2</p>
                            </div>
                            <div class="col-6">
                                <ul class="pagination">
                                    <li class="active">
                                        <a href="#">1</a>
                                    </li>
                                    <li>
                                        <a href="#">2</a>
                                    </li>
                                    <li>
                                        <a href="#"><i class="bx bx-chevron-right"></i></a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- Student Dashboard -->

            </div>
        </div>
    </div>
    <!-- /Page Content -->

    <layouts1></layouts1>
</template>

<script>
export default {
    data() {
        return {
            title: "Dashboard",
            text: "Home",
            text1: "Dashboard",
        }
    },
}
</script>