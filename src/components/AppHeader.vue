<script>

export default {
    name: 'AppHeader',

}


</script>

<template>
    <header>
        <div class="container d-flex space_between align-center">
            <div class="header_logo">

                <img src="../assets/img/MasterStudy-1.svg" alt="">
            </div>
            <ul class="d-flex">
                <li><a href="#">Courses</a></li>
                <li><a href="#">Course Formats</a></li>
                <li><a href="#">Add Course</a></li>
                <li><a href="#">Pages</a></li>
                <li><a class="active" href="#">Demos</a></li>
            </ul>
            <div class="social_media">
                <i class="fa-brands fa-linkedin"></i>
                <i class="fa-brands fa-instagram"></i>
                <i class="fa-brands fa-facebook"></i>
                <i class="fa-brands fa-twitter"></i>

            </div>







        </div>


    </header>


</template>

<style lang="scss" scoped>
header {


    .header_logo {
        img {
            max-width: 100%;
        }
    }

    ul {
        list-style: none;
        margin-left: 2rem;

        a {
            text-decoration: none;
            margin-left: 1rem;
            color: #333333;
        }
    }

    .fa-brands {
        margin-left: 1rem;
        color: #333333;
    }

    .active {
        border-bottom: 2px solid #F3C035;
        position: relative;

    }



}

.header_logo,
ul,
.social_media {
    padding: 2rem;
}
</style>