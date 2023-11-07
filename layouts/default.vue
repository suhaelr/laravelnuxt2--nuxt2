<template>
  <div>

    <div>
      <b-navbar toggleable="lg" type="light" variant="light" class="shadow-md" fixed="top">
        <b-navbar-brand to="/">Selamat Datang</b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <b-nav-item to="/post">Input Data</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>

    <Nuxt />
  </div>
</template>

<style>
body{
  background-color: lightgray;
}
.mt-5 {
  margin-top: 100px!important;
}
</style>
