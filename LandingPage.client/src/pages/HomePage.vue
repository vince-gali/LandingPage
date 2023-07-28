<template>
  <!-- <div class="home flex-grow-1 d-flex flex-column align-items-center justify-content-center">
    <div class="home-card p-5 bg-white rounded elevation-3">
      <img src="https://bcw.blob.core.windows.net/public/img/8600856373152463" alt="CodeWorks Logo"
        class="rounded-circle">
      <h1 class="my-5 bg-dark text-white p-3 rounded text-center">
        Vue 3 Starter
      </h1>
    </div>
  </div> -->
  <section class="row">
    <div class="text-center py-4 text-white">
      <h5><em>Some kind of image here</em></h5>
    </div>
  </section>


  <section class="row">
    <div class="text-center py-4 text-white">
      <h5><em>Project Highlights</em></h5>
      <div class="card elevation-4  col-3 bg-white">
        <img class="img-fluid" src="https://th.bing.com/th/id/R.49b026ec2df78cf2c7e584f083ce2042?rik=hoB8ydaEWq2T6Q&pid=ImgRaw&r=0" alt="">
        <div class="display-flex align-items-center">
          <p>project</p>
        </div>
      </div>
    </div>
  </section>



</template>

<script>
export default {
  setup() {
    return {}
  }
}
</script>

<style scoped lang="scss">
.home {
  display: grid;
  height: 80vh;
  place-content: center;
  text-align: center;
  user-select: none;

  .home-card {
    width: 50vw;

    >img {
      height: 200px;
      max-width: 200px;
      width: 100%;
      object-fit: contain;
      object-position: center;
    }
  }
}
</style>
