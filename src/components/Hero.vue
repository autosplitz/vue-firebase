<template>
  <div class="hero">
    <div class="container h-100">
      <div class="row justify-content-center align-items-center h-100">
        <div class="col-md-5">
          <div class="hero-content">
            <h1 class="hero-title">Vue Shop for Developers</h1>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Incidunt, deleniti?</p>
            <div class="hero-btn mt-5">
              <button class="btn custom-btn btn-info mr-4">Explore</button>
              <button class="btn custom-btn btn-outline-secondary">Products</button>
            </div>
          </div>
        </div>
        <div class="col-md-7">
          <div class="graphic">
            <img src="/img/hero.png" alt="Hero" class="img-fluid" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.hero {
  margin-top: 3rem;
}
</style>
