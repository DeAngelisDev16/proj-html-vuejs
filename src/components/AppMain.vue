<script>
import LimitedSale from './LimitedSale.vue';
import CourseCard from './CourseCard.vue';

export default {
    name: 'AppMain',
    components: {
        LimitedSale,
        CourseCard,
    },
    data() {
        return {

        }

    }
}


</script>

<template>
    <section class="jumbo d-flex align-center">
        <div class="col-6"></div>
        <div class="col-6">
            <h1>Start your Human <br> <span>Revolution</span> today</h1>
            <p>A wonderful serenity has taken possetion of my entire soul, like <br> these sweet mornings of spring
                which
                I
                enjoy with my whole heart.</p>
        </div>

    </section>


    <section class="founder_info">
        <LimitedSale />
        <div class="container d-flex">
            <div class="col-6">
                <h2>Hey there,my name is <br> John Doe.I'm the founder <br> of the Brain Academy.</h2>
                <img src="../assets/img/sign.jpg" alt="">
            </div>
            <div class="col-6">
                <p>A wonderful serenity has taken possetion of my entire soul, like these sweet <br> mornings of spring
                    which
                    I
                    enjoy with my whole heart. I am alone, and feel the charm of existence in this spot, which was
                    created for the bliss of souls like mine. I am so happy, my dear friend, so absorbed in the
                    exquisite sense of mere tranquil existence,that I neglect my talents. When, while the lovely
                    valley teems with vapour around me,and the meridian sun strikes the upper surface of the
                    impenetrable foliage of my trees, and but a few stray gleams steal into the inner sanctuary.</p>
            </div>

        </div>
    </section>

    <section class="new_courses text-center">
        <h2>New Courses</h2>
        <div class="courses_container d-flex flex-wrap">
            <CourseCard />

        </div>
        <button>load more</button>

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

    .col-6 {
        margin-left: -1rem;
    }

    h1 {
        font-size: 3rem;

        span {
            color: #F2B91E;
        }

    }

    p {
        padding-top: 1rem;
    }

}

.founder_info {
    padding-top: 7rem;
    padding-bottom: 4rem;
    position: relative;

    h2,
    img {
        padding-left: 3.5rem;
    }

    h2 {
        font-size: 2rem;
    }

    img {
        margin-top: 2rem;
        margin-left: 4.5rem;
        width: 40%;

    }
}





.new_courses {
    background-color: #EDF2F5;
    padding: 4rem 0;

    h2 {
        font-size: 2.5rem;
        padding-bottom: 2.5rem;
    }





    .courses_container {
        width: 70%;
        margin: auto;
        height: 100%;




    }

    button {
        padding: .9rem;
        text-transform: uppercase;
        margin-top: 1.5rem;
        border-radius: 1rem;
        background-color: #F2B91E;
        color: #FFFF;

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