<template>
  <div>
    <TopHeader />
    <Menubar />
    <div class="page-title-area">
      <div class="container">
        <ul>
          <li><nuxt-link to="/">Home</nuxt-link></li>
          <li>Signup</li>
        </ul>
      </div>
    </div>

    <div class="signup-area ptb-60">
      <div class="container">
        <div class="signup-content">
          <div class="section-title">
            <h2><span class="dot"></span> Create an Account</h2>
          </div>

          <form class="signup-form">
            <div class="form-group">
              <label>First Name</label>
              <input
                type="text"
                class="form-control"
                placeholder="Enter your name"
                id="fname"
                name="fname"
              />
            </div>

            <div class="form-group">
              <label>Last Name</label>
              <input
                type="text"
                class="form-control"
                placeholder="Enter your name"
                id="lname"
                name="lname"
              />
            </div>

            <div class="form-group">
              <label>Email</label>
              <input
                type="email"
                class="form-control"
                placeholder="Enter your name"
                id="name"
                name="name"
              />
            </div>

            <div class="form-group">
              <label>Password</label>
              <input
                type="password"
                class="form-control"
                placeholder="Enter your password"
                id="password"
                name="password"
              />
            </div>

            <button type="submit" class="btn btn-primary">Signup</button>

            <nuxt-link to="/" class="return-store"
              >or Return to Store</nuxt-link
            >
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import TopHeader from '../layouts/TopHeader'
import Menubar from '../layouts/Menubar'

export default {
  components: {
    TopHeader,
    Menubar,
  }
}
</script>