<script>
/**
 * Index-personal component
 */
import { ArrowUpIcon } from 'vue-feather-icons';

export default {
  data() {
    return {};
  },
  components: { ArrowUpIcon },
};
</script>

<template>
  <div>
    <!-- Hero Start -->
    <section
      class="bg-home rtl-personal-hero bg-light d-flex align-items-center"
      style="background:url('../assets/img/tebankocover.jpg') center center"
      id="home"
    >
      <div class="container">
        <div class="row aligntoleft">
          <div class="col-lg-8 col-md-9">
            <div class="title-heading mt-4">
              <h1 class="display-3 font-weight-bold mb-3">
                Estamos contigo para alcanzar tus sueños.
              </h1>
              <p class="para-desc text-muted">
                Solicita tu préstamo personal de manera rápida y segura, desde
                la comodidad de tu hogar.
              </p>
              <div class="mt-4 pt-2">
                <a class="btn btn-primary mt-2 mr-2 mouse-down"
                  ><i class="mdi mdi-camera"></i> Solicítalo Aquí!</a
                >
                <br />
              </div>
            </div>
          </div>
          <!--end col-->
        </div>
        <!--end row-->
      </div>
      <!--end container-->
    </section>
    <!--end section-->
    <!-- Hero End -->

    <!--end section-->

    <!-- Back to top -->
    <a
      href="javascript: void(0);"
      class="btn btn-icon btn-soft-primary back-to-top"
      id="back-to-top"
      v-scroll-to="'#topnav'"
    >
      <arrow-up-icon class="icons"></arrow-up-icon>
    </a>
    <!-- Back to top -->
  </div>
</template>
