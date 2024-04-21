<template>
    <!-- <section>3</section> -->

    <div id="project" class="project section-3" data-scroll-index="2">
        <div class="container">
            <div class="row justify-content-between">
                <div class="col-lg-5">
                    <div class="work">
                        <h6><span>My Work</span></h6>
                        <h2 class="text-white" style="font-size: 40px;">RECENT PROJECT</h2>

                    </div>
                </div>
            </div>


            <div  class="d-flex gap-3 ">

                <div v-for="item in datas" :key="item" class="p-4 bg-white rounded">

                    <div>

                        <img class="rounded" :src="item.image" alt="" width="356px">
                    </div>


                    <h3 class="pt-2" style="font-size: 20px;">{{item.name}}</h3>
                    <div class="d-flex justify-content-between">
                        <h6 class="text-secondary">{{ item.title}}</h6>
                        <button type="button" class="arrar" data-bs-toggle="modal" data-bs-target="#mymodal"><span><i
                                    class="fa-solid fa-arrow-right "></i></span></button>
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
                        image: require('../assets/images/popup-project-1.jpg'),
                        name: 'Website design',
                        title: 'Web Design,App Design',
                       
                    }, 
                    {
                        image: require('../assets/images/popup-project-2.jpg'),
                        name: 'Website design',
                        title: 'Web Design,App Design',
                       
                    },
                     {
                        image: require('../assets/images/popup-project-3.jpg'),
                        name: 'Website design',
                        title: 'Web Design,App Design',
                      
                    },
                     {
                        image: require('../assets/images/popup-project-4.jpg'),
                        name: 'Website design',
                        title: 'Web Design,App Design',
                      
                    }, 
                    {
                        image: require('../assets/images/popup-project-5.jpg'),
                        name: 'Website design',
                        title: 'Web Design,App Design',
                       
                    },
                     {
                        image: require('../assets/images/popup-project-6.jpg'),
                        name: 'Website design',
                        title: 'Web Design,App Design',
                      
                        
                    },
                ]
            }
        },
    }
</script>

<style lang="scss" scoped>

</style>