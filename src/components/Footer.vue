<script>
import {
  FacebookIcon,
  InstagramIcon,
  TwitterIcon,
  LinkedinIcon,
  MailIcon,
} from 'vue-feather-icons';
export default {
  data() {
    return {};
  },
  components: {
    FacebookIcon,
    InstagramIcon,
    TwitterIcon,
    LinkedinIcon,
    MailIcon,
  },
};
</script>

<template>
  <div>
    <!-- Footer Start -->
    <footer class="footer">
      <div class="container">
        <div class="row">
          <div class="col-md-4 col-12 text-center">
            <a href="#" class="logo-footer">
              <img src="images/logo-light.png" height="24" alt="" />
            </a>
            <p class="mt-4 footerlogo">
              <img src="../assets/img/logo-tebanko.png" height="70" alt="" />
            </p>
            <ul class="list-unstyled social-icon social mb-0 mt-4">
              <li class="list-inline-item">
                <a href="javascript:void(0)" class="rounded">
                  <facebook-icon class="fea icon-sm fea-social"></facebook-icon>
                </a>
              </li>
              <li class="list-inline-item ml-1">
                <a href="javascript:void(0)" class="rounded">
                  <instagram-icon
                    class="fea icon-sm fea-social"
                  ></instagram-icon>
                </a>
              </li>
              <li class="list-inline-item ml-1">
                <a href="javascript:void(0)" class="rounded">
                  <twitter-icon class="fea icon-sm fea-social"></twitter-icon>
                </a>
              </li>
              <li class="list-inline-item ml-1">
                <a href="javascript:void(0)" class="rounded">
                  <linkedin-icon class="fea icon-sm fea-social"></linkedin-icon>
                </a>
              </li>
            </ul>
            <!--end icon-->
          </div>
          <!--end col-->

          <div class="col-md-4 col-12">
            <h4 class="text-light footer-head">Ubicación y Contacto</h4>

            <p class="mt-4">
              <img class="smalllogos" src="../assets/img/iconos/location.svg" />
              Radial 27 entre 3er y 4to anillo. Entre calle Valdivia y calle N4
            </p>

            <p class="mt-4">
              <img class="smalllogos" src="../assets/img/iconos/call.svg" />
              +(00591) 767 - 85558
            </p>

            <p class="mt-4">
              <img class="smalllogos" src="../assets/img/iconos/mail.svg" />
              info@tebanko.com
            </p>
          </div>
          <!--end col-->

          <div class="col-md-4 col-12">
            <h4 class="text-light footer-head">Información</h4>
            <p class="mt-4">
              Déjanos tu correo electrónico para enterarte de las ofertas y
              productos que te ofrece TeBanko.
            </p>
            <form>
              <div class="row">
                <div class="col-lg-12">
                  <div class="foot-subscribe form-group position-relative">
                    <label
                      >Ingresa tu correo electrónico
                      <span class="text-danger">*</span></label
                    >
                    <mail-icon class="fea icon-sm icons"></mail-icon>
                    <input
                      type="email"
                      name="email"
                      id="emailsubscribe"
                      class="form-control pl-5 rounded"
                      placeholder="Correo: "
                      required
                    />
                  </div>
                </div>
                <div class="col-lg-12">
                  <input
                    type="submit"
                    id="submitsubscribe"
                    name="send"
                    class="btn btn-soft-primary btn-block"
                    value="Ingresar"
                  />
                </div>
              </div>
            </form>
          </div>
          <!--end col-->
        </div>
        <!--end row-->
      </div>
      <!--end container-->
    </footer>
    <!--end footer-->
    <footer class="footer footer-bar">
      <div class="container text-center">
        <div class="row align-items-center">
          <div class="col-sm-6">
            <div class="text-sm-left">
              <p class="mb-0">
                © 2021 TeBanko. Website designed by @Mfleig
              </p>
            </div>
          </div>
          <!--end col-->

          <!--end col-->
        </div>
        <!--end row-->
      </div>
      <!--end container-->
    </footer>
    <!--end footer-->
  </div>
</template>
