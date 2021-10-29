<template>
  <main class="col px-0 flex-grow-1">
          <div class="container py-3 d-md-flex align-items-center justify-content-center">
            <article class="welcome">
              <h1 class="fw-bolder fs-1 mb-3 ">Hello there!</h1>
              <h4 class="fw-bold fs-3 mb-3">
                I'm Ibukun.
              </h4>
              <p class="fw-bold fs-5 w-md-50 mb-sm-0">
                I am currently enrolled in the Enyata Academy program. I
                look forward to honing and harnessing my engineering skills
                in your establishment.
              </p>
              <p class="fw-bold fs-5 w-md-50 mb-sm-0">I am passionate about building and managing friendly & cutting edge web applications.</p>
              <p class="fw-bold fs-5 w-md-50 mb-sm-0">My core strengths are HTML, CSS and Bootstrap.</p>
            </article>
            <div class="image">
              <img src="/assets/Female-illustration.jpg" alt="female-designer-cartoon"/>
            </div>
          </div>

          <div>
            <router-link :to="{name:'about-Enyata'}">About Enyata</router-link>
          </div>
          <router-view/>
        </main>
</template>


<script>
export default {
  name: "About"
};
</script>


<style scoped>
img {
    max-width: 100%;
    padding-top: 4rem;
  }

  .image {
    flex-basis: 90%
  }

.welcome{
    margin-top: 4rem;
    margin-left: 3rem;
}
a {
    font-weight: 700;
    font-size: 25px;
    color: #185DB8;
}
</style>
