<template>
 <div class="header">
        <nav class="navbar navbar-expand-lg bg-dark fixed-top">
            <div class=" container ">
                <a href="" class=" navbar-brand"><img src="../assets/images/logo-light.svg" alt=""></a>
            <button type="button" class="navbar-toggler bg-white" data-bs-toggle="collapse" data-bs-target="#navbaraid">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse text-uppercase gap-5  justify-content-end" id="navbaraid">
                <ul class="navbar-nav text-start">
                    <li class="nav-item"><a class="nav-link text-white" href="#home">home</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#about">about</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#project">Project</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#service">service</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#contact">contact</a></li>
                </ul>
                <div>
                    <a class="px-btn d-none d-lg-inline-flex text-white" href="#">Lets'Talk</a>
                </div>
            </div>
    </div>
    </nav>
    </div>
</template>

<script>
  export default {
    name: 'navBar'
  }
</script>

<style lang="scss" scoped>

</style>