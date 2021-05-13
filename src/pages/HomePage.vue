<template>
  <div class="home">
    <!-- Showcase Photo Section -->
    <div class="row" id="row1">
      <div class="col-12">
        <img src="https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/dls-1531337226.jpg" id="dls" alt="">
      </div>
    </div>
    <!-- Watch Photo Section -->
    <div class="row bg-dark">
      <div class="col-12">
        <img src="https://singervehicledesign.com/wp-content/uploads/2021/01/singer-watch-2018.jpg" id="watch" alt="">
      </div>
    </div>
    <!-- Video Section -->
    <div class="row bg-dark">
      <img src="C:\source\codeworks\siteclonewithvuerebuild\src\assets\img\VideoPic.PNG" id="dls" alt="">
    </div>
    <!-- Book Section -->
    <div class="row">
      <div class="col-6 text-center pb-5 pr-5">
        <img src="https://images.squarespace-cdn.com/content/v1/5506e74de4b030d1c8010865/1445628042654-NNPWYP4B72304Z17FLCT/ke17ZwdGBToddI8pDm48kJIk2KS3iEYhWPifsi4EcYp7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z4YTzHvnKhyp6Da-NYroOW3ZGjoBKy3azqku80C789l0luj0xCD0oh5KMc0gpox0u_rWkO288leZbg3FK17DaDikIfenswn8eFk7VDHVWzWwQ/SINGER_COVER.jpg?format=2500w" class="pl-5 ml-5" id="book" alt="">
      </div>
      <div class="col-6 pt-5">
        <h3>ONE MORE THAN 10</h3>
        <h3>SINGER AND THE PORSCHE 911</h3>
        <br>
        <h6>Singer Vehicle Design is driven by the singular vision of Rob</h6>
        <h6>Dickinson- an ex car designer who then became a rock musician</h6>
        <h6>who now stands as one of the worlds foremost distillers of the</h6>
        <h6>essence of air cooled Porsche.</h6>
        <br>
        <h6>Journalist Michael Harley and Dickinson tell the story, while an</h6>
        <h6>all-star cast of automotive writers, journalists, and personalities</h6>
        <h6> offer their perspectives on the Singer phenomenon.</h6>
        <button type="button" class="btn btn-outline-dark" id="button">
          Buy Now
        </button>
      </div>
    </div>
    <!-- News Section -->
    <div class="row bg-dark">
      <div class="col-6 text-center">
        <h6 id="text">
          RESTORED.
        </h6>
        <h6 id="text">
          REIMAGINED.
        </h6>
        <h6 id="text">
          REBORN.
        </h6>
      </div>
      <div class="col-6">
        <h6 class="text-white">
          RECENT NEWS
        </h6>
      </div>
    </div>
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

  user-select: none;
  > img{
    height: 200px;
    width: 200px;
  }
  #dls{
    height: 800px;
    width: 1400px;
  }
    #watch{
    height: 1100px;
    width: 1400px;
  }
  #book{
    height: 450px;
    width: 575px;
  }
  #button{
    height: 55px;
    width: 120px;
  }
  #row1{
    height: 700px;
  }
  #text{
    color: rgb(164, 227, 243);
  }
}

</style>
