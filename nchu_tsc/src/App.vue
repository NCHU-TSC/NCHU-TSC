<template>
  <div class="d-flex flex-column h-100">
    <header id="header-home" class="position-sticky top-0">
      <!-- 加载 header 组件 -->
      <HeaderHome />
    </header>

    <main class="flex-grow-1">
      <div class="p-5" id="content">
        <div class="container-xxl bd-gutter">
          <div class="col-md-8 mx-auto text-center">
            <img
              src="/favicon.ico"
              width="200"
              height="200"
              alt="家教服務社"
              class="d-none d-sm-block mx-auto mb-3"
            />
            <h1 class="mb-3 fw-semibold lh-1">國立中興大學 家教服務社</h1>
            <p class="lead mb-4">
              本社為校內有志於半工半讀，自食其力的同學尋找工作的機會，以培養其自立自強的精神。亦致力於培養新教學人才，使台中地區於課業上有困難者，或欲進修者，介紹適當對象予以適當之輔導
            </p>
          </div>
        </div>
      </div>

      <hr class="mt-5 mb-5 border-0" />

      <article class="container-xxl bd-gutter masthead-followup text-center">
        <section class="row g-3 g-md-5 mb-5 pb-5 justify-content-center">
          <div class="col-lg-6 py-lg-4 pe-lg-5">
            <!-- <svg class="bi m-4" width="72" height="72" fill="currentColor">
              <use xlink:href="/bootstrap/font/bootstrap-icons.svg#mortarboard"></use>
            </svg> -->
            <h3 class="fw-semibold">我是學生</h3>
            <p>我想申請接案！</p>
            <p>
              <button type="button" class="btn btn-primary">尋找案件</button>
              <button type="button" class="btn btn-secondary">我要入社</button>
            </p>
          </div>
          <div class="col-lg-6 py-lg-4 ps-lg-5 border-lg-start">
            <!-- <svg class="bi m-4" width="72" height="72" fill="currentColor">
              <use xlink:href="/bootstrap/font/bootstrap-icons.svg#people"></use>
            </svg> -->
            <h3 class="fw-semibold">我是家長</h3>
            <p>我想 Po 新案件！</p>
            <p>
              <button type="button" class="btn btn-primary">新增案件</button>
            </p>
          </div>

          <hr class="mt-5 mb-5 border-0" />

          <div class="col-md-8 mx-auto text-center">
            <h4 class="fw-semibold">還想了解更多嗎？</h4>
            <p>Get a jump on including Bootstrap's source files in a new project with our official guides.</p>
            <div class="d-flex flex-wrap align-items-center justify-content-center gap-4 mt-4">
              <a
                class="d-flex flex-column align-items-center text-decoration-none animate-img"
              >
                <img
                  class="d-block mb-2"
                  alt=""
                  width="72"
                  height="72"
                  loading="lazy"
                />
                <span class="text-body-secondary">Webpack</span>
              </a>
              <a
                class="d-flex flex-column align-items-center text-decoration-none animate-img"
              >
                <img
                  class="d-block mb-2"
                  alt=""
                  width="72"
                  height="72"
                  loading="lazy"
                />
                <span class="text-body-secondary">Parcel</span>
              </a>
              <a
                class="d-flex flex-column align-items-center text-decoration-none animate-img"
              >
                <img
                  class="d-block mb-2"
                  alt=""
                  width="72"
                  height="72"
                  loading="lazy"
                />
                <span class="text-body-secondary">Vite</span>
              </a>
            </div>
          </div>
        </section>
      </article>
    </main>

    <footer id="footer-home">
      <!-- 加载 footer 组件 -->
      <FooterHome />
    </footer>
  </div>
</template>

<script>
import HeaderHome from './components/HeaderHome.vue';
import FooterHome from './components/FooterHome.vue';

export default {
  name: 'HomePage',
  components: {
    HeaderHome,
    FooterHome,
  },
};
</script>

<style scoped>
#content {
  background-image: linear-gradient(
      to top,
      var(--bs-body-bg),
      rgba(var(--bs-body-bg-rgb), 0.25)
    ),
    url('/pexels/olia-danilevich-5088008.jpg');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
</style>

