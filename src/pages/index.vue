<template>
    <navbar />
    <section>
    <!-- Section home -->
    <div class="home-section">
        <div class="container">
            <div id="home" class="row align-items-center">
                <div class="col-lg-6">
                    <h6 class="letter"><span class="text-white">JENNA ORTEGA</span></h6>
                    <h1 class="text-white" style="font-size: 70px;">HEY! I’M JENNA</h1>
                    <h2 class="desig">I'M A <span>DESIGNER</span></h2>
                    <p class="text-white text">Yet bed any for travelling assistance indulgence unpleasing. Not
                        thoughts all exercise blessing. Indulgence way everything joy alteration boisterous the
                        attachment.</p>

                    <div class="btn-bar d-flex align-items-center flex-column flex-sm-row">
                        <a class="px-btn1 btn-primary rounded-pill text-white" href="#">Get in touch <i
                                class="fas fa-arrow-right"></i></a>

                        <div class="social-icon ps-sm-4 pt-4 pt-sm-0 d-flex justify-content-center justify-content-sm-start">
                            <a class="facebook text-white" href="#"><i class="fab fa-facebook-f"></i></a>
                            <a class="dribbble text-white" href="#"><i class="fab fa-dribbble"></i></a>
                            <a class="linkedin m-0 text-white" href="#"><i class="fab fa-linkedin-in"></i></a>
                        </div>
                    </div>
                </div>
                <!-- Home image -->
                <div class="col-lg-6">
                    <img class="img-fluid" src="../assets/images/home-banner.png" alt="Jenna Ortega" width="700px">
                </div>
            </div>
        </div>
    </div>
</section>

<div class="container-fluid gray-bg ">
        <div class="container d-flex gap-5">
            <img class="img-fluid " src="../assets/images/brand-1.svg" alt="" width="215px">
            <img class="img-fluid" src="../assets/images/brand-2.svg" alt="" width="215px">
            <img class="img-fluid" src="../assets/images/brand-1.svg" alt="" width="215px">
            <img class="img-fluid" src="../assets/images/brand-2.svg" alt="" width="215px">
            <img class="img-fluid" src="../assets/images/brand-1.svg" alt="" width="215px">
        </div>
    </div>

    <aboutus />

    <project />


  <services />


<experience />

    <!-- <section>6</section> -->

<users />


  <footers />

</template>

<script>
import navbar from '@/components/navbar.vue';
import aboutus from '@/components/aboutus.vue';
import project from '@/components/recent-project.vue';
import experience from '@/components/work-experience.vue';
import services from '@/components/services.vue';
import users from '@/components/users.vue';
import footers from '@/components/footer.vue'
export default {
    name: 'indexOne',
    data() {
        return {
        }
    },
    components: {
        navbar,
        aboutus,
        project,
        experience,
        services,
        users,
        footers
    }
}
</script>

<style lang="scss" scoped></style>