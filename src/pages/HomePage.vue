<template>
  <div class="home flex-grow-1 d-flex flex-column align-items-center justify-content-center">
    <!-- Showcase Photo Section -->
    <div class="row" id="">
      <div class="col-12">
        <img src="https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/dls-1531337226.jpg" id="dls" alt="">
      </div>
    </div>
    <!-- Watch Photo Section -->
    <div class="row"></div>
    <!-- Video Section -->
    <div class="row"></div>
    <!-- Book Section -->
    <div class="row"></div>
    <!-- News Section -->
    <div class="row"></div>
    <!-- Footer Area -->
    <div class="row"></div>
  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<style scoped lang="scss">
.home{
  text-align: center;
  user-select: none;
  > img{
    height: 200px;
    width: 200px;
  }
  #dls{
    height: 800px;
    width: 1400px;
  }
}

</style>
