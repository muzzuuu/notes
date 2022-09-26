<template>

    <div class="container-fluid position-relative d-flex p-0">
        <sidebar />


        <!-- Content Start -->
        <div class="content">
            <app-header></app-header>
        </div>
        <!-- Content End -->


        <!-- Back to Top -->
        <!-- <a href="#" class="btn btn-lg btn-primary btn-lg-square back-to-top"><i class="bi bi-arrow-up"></i></a> -->
    </div>


</template>

<script>
import sidebar from './sidebar.vue';
import header from './header.vue';
export default {
    name: 'home-com',
    components: {
        sidebar,
        'app-header': header,
    },
}
</script>
