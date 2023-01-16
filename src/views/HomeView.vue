<template>
  <div class="home">
    <div class="feature-card">
      <router-link to="/movie/tt0409519">
        <img class="feature-img" src="@/ti/thumbbig-975294.webp" alt="Avenger Endgame">
        <div class="detail">
          <h3>Avengers Endgame</h3>
          <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Repudiandae, minima? Saepe, corporis nobis! Tempore illum est architecto voluptates ipsa quaerat sint, laudantium amet dignissimos! Illo!</p>
        </div>
      </router-link>
    </div>
  </div>
</template>

<script>

export default {
  name: 'HomeView',
  components: {
  }
}
</script>

<style>
.home .feature-card {
  position: relative;
}
.home .feature-card .feature-img {
  display: block;
  width: 100%;
  height: auto;
  object-fit: cover;
  position: relative;
  z-index: 0;
}
.detail {
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  background-image: linear-gradient(to top, rgba(0, 0, 0, 1), rgba(0, 0, 0, 0));
  padding: 16px;
  z-index: 1;
}
.detail {
  color: #ffffff;
  /* margin-bottom: 16px; */
}

</style>
