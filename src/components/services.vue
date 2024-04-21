<template>
    <div id="service" class="container pt-lg-5 pb-lg-5" data-scroll-index="3">
        <div>
            <h1 class="d-lg-inline-block text-white rounded-1 spacing" style="font-size: 20px;">SERVICE</h1>
            <h2 class="text-white" style="font-size: 40px;">DESIGN <span class="text-primary"> SERVICES</span> I AM
                PROVIDING</h2>
        </div>

        <div class="row gy-5">
            <div v-for="item in datas" :key="item.image" class="col-sm-6 col-xl-3">
                <div class="box d-flex justify-content-end align-items-start rounded img-fluid"
                    :style="'background-image: linear-gradient(to bottom, rgba(245, 246, 252, 0.084), rgba(6, 6, 6, 0.73)), url(' + item.image + '); width: 306px; height: 402px;'">
                    <div>
                        <a href="" class="icon"> <i class="fa-solid fa-paintbrush"></i></a>
                        <h5 class="text-white pt-2">{{ item.name }}</h5>
                        <p class="text-white" style="font-size: 14px;">{{ item.title }}</p>
                    </div>
                    <div style="border-top: 1px solid black;width: 100%;padding-top: 10px;">
                        <i class="fa-solid fa-star" style="color: #e2d43c;"></i>
                        <i class="fa-solid fa-star" style="color: #e2d43c;"></i>
                        <i class="fa-solid fa-star" style="color: #e2d43c;"></i>
                        <i class="fa-solid fa-star" style="color: #e2d43c;"></i>
                        <i class="fa-solid fa-star-half-stroke" style="color: #aed61f;"></i>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'serviceS',
    data() {
        return {
            datas: [
                {
                    image: 'https://shtheme.com/demosd/jenna/wp-content/uploads/2023/07/service-01.jpg',
                    name: 'Website Design',
                    title: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore.'
                },
                {
                    image: 'https://shtheme.com/demosd/jenna/wp-content/uploads/2023/07/service-02.jpg',
                    name: 'Website Design',
                    title: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore.'
                },
                {
                    image: 'https://shtheme.com/demosd/jenna/wp-content/uploads/2023/07/service-03.jpg',
                    name: 'Website Design',
                    title: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore.'
                },
                {
                    image: 'https://shtheme.com/demosd/jenna/wp-content/uploads/2023/07/service-04.jpg',
                    name: 'Website Design',
                    title: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore.'
                },
            ]
        }
    },
}
</script>

<style lang="scss" scoped>
</style>
