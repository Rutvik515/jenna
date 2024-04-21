<template>
    <!-- <section>5</section> -->

    <div class="project section-3" data-scroll-index="2">
        <div class="container">
            <div class="work">
                <h6><span> EXPERIENCE</span></h6>
                <h2 class="text-white" style="font-size: 40px;">MY WORK<span class="text-primary"> EXPERIENCE</span>
                </h2>
            </div>

            <div v-for="item in datas" :key="item" class="box-1 rounded">

                <div class="row gy-4">
                    <div class="col-md-4 col-lg-3 box-sec mt-4 ">
                        <h4 class="text-white">{{ item.name}}</h4>
                        <span class="text-white" style="font-size: 14px;">WELAB | REMOTE</span>
                        <p class="text-white">{{item.time}} </p>
                        <label for="" class="bg-white rounded-5 justify-content-center align-items-center text-center"
                            style="width: 100px;">{{item.title}}</label>

                    </div>
                    <div class="col-md-8 col-lg-9 text-white">
                        <h1 style="font-size: 32px;">{{item.name2}}</h1>
                        <p>{{ item.desc}}</p>
                    </div>

                </div>
            </div>

            <div class="box-1 mt-4 rounded">

                <div class="row gy-4">
                    <div class="col-md-4 col-lg-3 box-sec mt-4">
                        <h4 class="text-white">Front-end Developer</h4>
                        <span class="text-white" style="font-size: 14px;">WELAB | REMOTE</span>
                        <p class="text-white">JAN 2019 - PRESENT </p>
                        <label for="" class="bg-white rounded-5 justify-content-center align-items-center text-center"
                            style="width: 100px;">FULL TIME</label>

                    </div>
                    <div class="col-md-8 col-lg-9 text-white">
                        <h1 style="font-size: 32px;">About Company</h1>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut
                            labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco
                            laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor.Lorem ipsum dolor sit
                            amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore
                            magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation .</p>
                    </div>

                </div>
            </div>

            <div class="box-1 mt-4 rounded">

                <div  class="row gy-4">
                    <div class="col-md-4 col-lg-3 box-sec mt-4">
                        <h4 class="text-white">Front-end Developer</h4>
                        <span class="text-white" style="font-size: 14px;">WELAB | REMOTE</span>
                        <p class="text-white">JAN 2019 - PRESENT </p>
                        <label for="" class="bg-white rounded-5 justify-content-center align-items-center text-center"
                            style="width: 100px;">FULL TIME</label>

                    </div>
                    <div class="col-md-8 col-lg-9 text-white">
                        <h1 style="font-size: 32px;">About Company</h1>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut
                            labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco
                            laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor.Lorem ipsum dolor sit
                            amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore
                            magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation .</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                datas:[
                    {
                        name: 'Front-end Developer',
                        title: 'FULL TIME',
                        date: 'JAN 2019 - PRESENT',
                        name2: 'About Company',
                        desc: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt utlabore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor.Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation .'
                    }
                ]
            }
        },
    }
</script>

<style lang="scss" scoped>

</style>