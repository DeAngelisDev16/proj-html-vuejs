<script>

export default {
    name: 'AppMain'
}


</script>

<template>
    <section class="jumbo d-flex align-center">
        <div class="col-6"></div>
        <div class="col-6">
            <h1>Start your Human <br> <span>Revolution</span> today</h1>
        </div>

    </section>


    <section class="founder_info">
        <div class="container">
            <h2>founder info section</h2>
        </div>
    </section>

    <section class="new_courses">
        <div class="courses_container d-flex flex-wrap">
            <div class="course_card">
                <h3>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repellat quidem nisi cupiditate veniam?
                    Vitae, maxime quod repudiandae ut possimus numquam iusto, distinctio perspiciatis provident
                    accusamus inventore reiciendis iure, hic culpa.</h3>
            </div>
            <div class="course_card">
                <h3>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repellat quidem nisi cupiditate veniam?
                    Vitae, maxime quod repudiandae ut possimus numquam iusto, distinctio perspiciatis provident
                    accusamus inventore reiciendis iure, hic culpa.</h3>
            </div>
            <div class="course_card">
                <h3>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repellat quidem nisi cupiditate veniam?
                    Vitae, maxime quod repudiandae ut possimus numquam iusto, distinctio perspiciatis provident
                    accusamus inventore reiciendis iure, hic culpa.</h3>
            </div>
            <div class="course_card">
                <h3>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repellat quidem nisi cupiditate veniam?
                    Vitae, maxime quod repudiandae ut possimus numquam iusto, distinctio perspiciatis provident
                    accusamus inventore reiciendis iure, hic culpa.</h3>
            </div>
            <div class="course_card">
                <h3>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repellat quidem nisi cupiditate veniam?
                    Vitae, maxime quod repudiandae ut possimus numquam iusto, distinctio perspiciatis provident
                    accusamus inventore reiciendis iure, hic culpa.</h3>
            </div>
            <div class="course_card">
                <h3>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repellat quidem nisi cupiditate veniam?
                    Vitae, maxime quod repudiandae ut possimus numquam iusto, distinctio perspiciatis provident
                    accusamus inventore reiciendis iure, hic culpa.</h3>
            </div>
        </div>

    </section>

    <section class="advertising">
        <div class="container">
            <h2>Amazon cta</h2>
        </div>


    </section>

    <section class="why_my_courses">
        <div class="container d-flex flex-wrap">
            <div class="course_features">
                <h3>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente, sint dolor fuga eligendi enim,
                    illum voluptatem nemo ipsa cum, nulla hic libero atque. Hic ducimus minus soluta a culpa labore!
                </h3>
            </div>
            <div class="course_features">
                <h3>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente, sint dolor fuga eligendi enim,
                    illum voluptatem nemo ipsa cum, nulla hic libero atque. Hic ducimus minus soluta a culpa labore!
                </h3>
            </div>
            <div class="course_features">
                <h3>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente, sint dolor fuga eligendi enim,
                    illum voluptatem nemo ipsa cum, nulla hic libero atque. Hic ducimus minus soluta a culpa labore!
                </h3>
            </div>
            <div class="course_features">
                <h3>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente, sint dolor fuga eligendi enim,
                    illum voluptatem nemo ipsa cum, nulla hic libero atque. Hic ducimus minus soluta a culpa labore!
                </h3>
            </div>

        </div>

    </section>

    <section class="advertising">
        <div class="container">
            <h2>Ratings</h2>
        </div>
    </section>

    <section class="what_students_say">

    </section>





</template>

<style lang="scss" scoped>
.jumbo {
    background-image: url('../assets/img/slide-1.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    height: 90vh;

    h1 {
        font-size: 3rem;

        span {
            color: #F2B91E;
        }

    }

}

.founder_info {
    height: 50vh;
}

.new_courses {
    height: 100vh;
    background-color: green;

    .courses_container {
        width: 70%;
        margin: auto;
        height: 100%;
        border: 1px dashed black;
        background-color: red;


        .course_card {
            width: calc(100% / 3);
        }
    }
}

.advertising {
    height: 50vh;
    background-color: lightsalmon;
}

.why_my_courses {
    height: 70vh;
    background-color: bisque;

    .course_features {
        width: calc(100% / 2);

    }

}

.what_students_say {
    height: 60vh;
    background-color: blue;
}
</style>