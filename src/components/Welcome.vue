<template>
   <main class="col px-0 flex-grow-1">
          <div class="container py-3 d-md-flex align-items-center justify-content-center">
            <article class="welcome">
              <h1 class="fw-bolder fs-1 mb-3 ">Welcome!</h1>
              <h4 class="fw-bold fs-3 mb-3">
                I'm a Software Developer based in Nigeria.
              </h4>
              <p class="fw-bold fs-5 w-md-50 mb-sm-0">
                I am currently enrolled in the Enyata Academy program. I
                look forward to honing and harnessing my engineering skills
                in your establishment.
              </p>
            </article>
            <div class="image">
              <img src="/assets/4207.jpg" alt="welcome-animation">
            </div>
          </div>
        </main>
</template>

<script>
export default {
  name: "Welcome"
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
img {
    max-width: 100%;
    padding-top: 2rem;
  }

  .image {
    flex-basis: 90%
  }

.welcome{
    margin-top: 2rem;
    margin-left: 3rem;
}

</style>
