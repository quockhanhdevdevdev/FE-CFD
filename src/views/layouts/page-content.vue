<template>
  <ul class="nav header-navbar-rht">
    <li class="nav-item">
      <div>
        <a
          href="#"
          id="dark-mode-toggle"
          ref="darkModeToggle"
          class="dark-mode-toggle"
          @click="enableDarkMode"
        >
          <i class="fa-solid fa-moon"></i>
        </a>
        <a
          href="#"
          id="light-mode-toggle"
          class="dark-mode-toggle"
          ref="lightModeToggle"
          @click="disableDarkMode"
        >
          <i class="fa-solid fa-sun"></i>
        </a>
      </div>
    </li>
    <li class="nav-item">
      <router-link to="/student/student-messages"
        ><img src="@/assets/img/icon/messages.svg" alt="img"
      /></router-link>
    </li>
    <li class="nav-item cart-nav">
      <a href="#" class="dropdown-toggle" data-bs-toggle="dropdown">
        <img src="@/assets/img/icon/cart.svg" alt="img" />
      </a>
      <div class="wishes-list dropdown-menu dropdown-menu-right">
        <div class="wish-header">
          <a href="javascript:void(0)">View Cart</a>
          <a href="javascript:void(0)" class="float-end">Checkout</a>
        </div>
        <div class="wish-content">
          <ul>
            <li>
              <div class="media">
                <div class="d-flex media-wide">
                  <div class="avatar">
                    <router-link to="/pages/course-details">
                      <img alt="Img" src="@/assets/img/course/course-04.jpg" />
                    </router-link>
                  </div>
                  <div class="media-body">
                    <h6>
                      <router-link to="/pages/course-details"
                        >Learn Angular...</router-link
                      >
                    </h6>
                    <p>By Dave Franco</p>
                    <h5>$200 <span>$99.00</span></h5>
                  </div>
                </div>
                <div class="remove-btn">
                  <a href="#" class="btn">Remove</a>
                </div>
              </div>
            </li>
            <li>
              <div class="media">
                <div class="d-flex media-wide">
                  <div class="avatar">
                    <router-link to="/pages/course-details">
                      <img alt="Img" src="@/assets/img/course/course-14.jpg" />
                    </router-link>
                  </div>
                  <div class="media-body">
                    <h6>
                      <router-link to="/pages/course-details"
                        >Build Responsive Real...</router-link
                      >
                    </h6>
                    <p>Jenis R.</p>
                    <h5>$200 <span>$99.00</span></h5>
                  </div>
                </div>
                <div class="remove-btn">
                  <a href="#" class="btn">Remove</a>
                </div>
              </div>
            </li>
            <li>
              <div class="media">
                <div class="d-flex media-wide">
                  <div class="avatar">
                    <router-link to="/pages/course-details">
                      <img alt="Img" src="@/assets/img/course/course-15.jpg" />
                    </router-link>
                  </div>
                  <div class="media-body">
                    <h6>
                      <router-link to="/pages/course-details"
                        >C# Developers Double ...</router-link
                      >
                    </h6>
                    <p>Jesse Stevens</p>
                    <h5>$200 <span>$99.00</span></h5>
                  </div>
                </div>
                <div class="remove-btn">
                  <a href="#" class="btn">Remove</a>
                </div>
              </div>
            </li>
          </ul>
          <div class="total-item">
            <h6>Subtotal : $ 600</h6>
            <h5>Total : $ 600</h5>
          </div>
        </div>
      </div>
    </li>
    <li class="nav-item wish-nav">
      <a href="#" class="dropdown-toggle" data-bs-toggle="dropdown">
        <img src="@/assets/img/icon/wish.svg" alt="img" />
      </a>
      <div class="wishes-list dropdown-menu dropdown-menu-right">
        <div class="wish-content">
          <ul>
            <li>
              <div class="media">
                <div class="d-flex media-wide">
                  <div class="avatar">
                    <router-link to="/pages/course-details">
                      <img alt="Img" src="@/assets/img/course/course-04.jpg" />
                    </router-link>
                  </div>
                  <div class="media-body">
                    <h6>
                      <router-link to="/pages/course-details"
                        >Learn Angular...</router-link
                      >
                    </h6>
                    <p>By Dave Franco</p>
                    <h5>$200 <span>$99.00</span></h5>
                    <div class="remove-btn">
                      <a href="#" class="btn">Add to cart</a>
                    </div>
                  </div>
                </div>
              </div>
            </li>
            <li>
              <div class="media">
                <div class="d-flex media-wide">
                  <div class="avatar">
                    <router-link to="/pages/course-details">
                      <img alt="Img" src="@/assets/img/course/course-14.jpg" />
                    </router-link>
                  </div>
                  <div class="media-body">
                    <h6>
                      <router-link to="/pages/course-details"
                        >Build Responsive Real...</router-link
                      >
                    </h6>
                    <p>Jenis R.</p>
                    <h5>$200 <span>$99.00</span></h5>
                    <div class="remove-btn">
                      <a href="#" class="btn">Add to cart</a>
                    </div>
                  </div>
                </div>
              </div>
            </li>
            <li>
              <div class="media">
                <div class="d-flex media-wide">
                  <div class="avatar">
                    <router-link to="/pages/course-details">
                      <img alt="Img" src="@/assets/img/course/course-15.jpg" />
                    </router-link>
                  </div>
                  <div class="media-body">
                    <h6>
                      <router-link to="/pages/course-details"
                        >C# Developers Double ...</router-link
                      >
                    </h6>
                    <p>Jesse Stevens</p>
                    <h5>$200 <span>$99.00</span></h5>
                    <div class="remove-btn">
                      <a href="#" class="btn">Remove</a>
                    </div>
                  </div>
                </div>
              </div>
            </li>
          </ul>
        </div>
      </div>
    </li>
    <li class="nav-item noti-nav">
      <a href="#" class="dropdown-toggle" data-bs-toggle="dropdown">
        <img src="@/assets/img/icon/notification.svg" alt="img" />
      </a>
      <div class="notifications dropdown-menu dropdown-menu-right">
        <div class="topnav-dropdown-header">
          <span class="notification-title"
            >Notifications
            <select>
              <option>All</option>
              <option>Unread</option>
            </select>
          </span>
          <a href="javascript:void(0)" class="clear-noti"
            >Mark all as read <i class="fa-solid fa-circle-check"></i
          ></a>
        </div>
        <div class="noti-content">
          <ul class="notification-list">
            <li class="notification-message">
              <div class="media d-flex">
                <div>
                  <router-link to="/pages/notifications" class="avatar">
                    <img
                      class="avatar-img"
                      alt="Img"
                      src="@/assets/img/user/user1.jpg"
                    />
                  </router-link>
                </div>
                <div class="media-body">
                  <h6>
                    <router-link to="/pages/notifications"
                      >Lex Murphy requested <span>access to</span> UNIX
                      directory tree hierarchy
                    </router-link>
                  </h6>
                  <button class="btn btn-accept">Accept</button>
                  <button class="btn btn-reject">Reject</button>
                  <p>Today at 9:42 AM</p>
                </div>
              </div>
            </li>
            <li class="notification-message">
              <div class="media d-flex">
                <div>
                  <router-link to="/pages/notifications" class="avatar">
                    <img
                      class="avatar-img"
                      alt="Img"
                      src="@/assets/img/user/user2.jpg"
                    />
                  </router-link>
                </div>
                <div class="media-body">
                  <h6>
                    <router-link to="/pages/notifications"
                      >Ray Arnold left 6 <span>comments on</span> Isla Nublar
                      SOC2 compliance report</router-link
                    >
                  </h6>
                  <p>Yesterday at 11:42 PM</p>
                </div>
              </div>
            </li>
            <li class="notification-message">
              <div class="media d-flex">
                <div>
                  <router-link to="/pages/notifications" class="avatar">
                    <img
                      class="avatar-img"
                      alt="Img"
                      src="@/assets/img/user/user3.jpg"
                    />
                  </router-link>
                </div>
                <div class="media-body">
                  <h6>
                    <router-link to="/pages/notifications"
                      >Dennis Nedry <span>commented on</span> Isla Nublar SOC2
                      compliance report</router-link
                    >
                  </h6>
                  <p class="noti-details">
                    “Oh, I finished de-bugging the phones, but the system's
                    compiling for eighteen minutes, or twenty. So, some minor
                    systems may go on and off for a while.”
                  </p>
                  <p>Yesterday at 5:42 PM</p>
                </div>
              </div>
            </li>
            <li class="notification-message">
              <div class="media d-flex">
                <div>
                  <router-link to="/pages/notifications" class="avatar">
                    <img
                      class="avatar-img"
                      alt="Img"
                      src="@/assets/img/user/user1.jpg"
                    />
                  </router-link>
                </div>
                <div class="media-body">
                  <h6>
                    <router-link to="/pages/notifications"
                      >John Hammond <span>created</span> Isla Nublar SOC2
                      compliance report
                    </router-link>
                  </h6>
                  <p>Last Wednesday at 11:15 AM</p>
                </div>
              </div>
            </li>
          </ul>
        </div>
      </div>
    </li>
    <li class="nav-item user-nav">
      <a href="#" class="dropdown-toggle" data-bs-toggle="dropdown">
        <span class="user-img">
          <img src="@/assets/img/user/user11.jpg" alt="Img" />
          <span class="status online"></span>
        </span>
      </a>
      <div
        class="users dropdown-menu dropdown-menu-right"
        data-popper-placement="bottom-end"
      >
        <div class="user-header">
          <div class="avatar avatar-sm">
            <img
              src="@/assets/img/user/user11.jpg"
              alt="User Image"
              class="avatar-img rounded-circle"
            />
          </div>
          <div class="user-text">
            <h6>Rolands R</h6>
            <p class="text-muted mb-0">Student</p>
          </div>
        </div>
        <router-link class="dropdown-item" to="/student/setting-edit-profile"
          ><i class="feather-user me-1"></i> Profile</router-link
        >
        <router-link
          class="dropdown-item"
          to="/student/setting-student-subscription"
          ><i class="feather-star me-1"></i> Subscription</router-link
        >
        <div class="dropdown-item night-mode">
          <span><i class="feather-moon me-1"></i> Night Mode </span>
          <div class="form-check form-switch check-on m-0">
            <input class="form-check-input" type="checkbox" id="night-mode" />
          </div>
        </div>
        <router-link class="dropdown-item" to="/"
          ><i class="feather-log-out me-1"></i> Logout</router-link
        >
      </div>
    </li>
  </ul>
</template>
<script>
import { ref, onMounted } from "vue";
export default {
  setup() {
    const darkModeToggle = ref(null);
    const lightModeToggle = ref(null);

    // Function to enable dark mode
    function enableDarkMode() {
      document.documentElement.setAttribute("class", "light dark");
      darkModeToggle.value.classList.remove("activate");
      lightModeToggle.value.classList.add("activate");
      localStorage.setItem("darkMode", "enabled");
    }

    // Function to disable dark mode
    function disableDarkMode() {
      document.documentElement.setAttribute("class", "light");
      lightModeToggle.value.classList.remove("activate");
      darkModeToggle.value.classList.add("activate");
      localStorage.removeItem("darkMode");
    }

    // Check the current mode on page load
    onMounted(() => {
      const darkMode = localStorage.getItem("darkMode");
      if (darkMode === "enabled") {
        enableDarkMode();
      } else {
        disableDarkMode();
      }
    });

    return {
      darkModeToggle,
      lightModeToggle,
      enableDarkMode,
      disableDarkMode,
    };
  },
};
</script>
