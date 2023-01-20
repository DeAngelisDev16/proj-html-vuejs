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

    <section class="amazon_advertising">
        <div class="container d-flex align-center">
            <div class="col-6 text-center">
                <h2>Get My Exclusive Investing Book just for $19.50</h2>
                <p>Vestibulum imentum eu urna vel cursus. Anean vehicula quam quam, vitae pellentesque urna <br>
                    elementum
                    cursus.
                </p>
                <a href="#"> <img class="amazon_link" src="../assets/img/amazon.png" alt=""></a>

            </div>
            <div class="col-6 d-flex">
                <img src="../assets/img/book.png" alt="">

            </div>


        </div>


    </section>

    <section class="why_my_courses ">
        <h2>Why my courses?</h2>
        <div class="container d-flex flex-wrap space_between">
            <div class="course_features">
                <div class="card_border d-flex">
                    <i class="fa-solid fa-briefcase"></i>

                    <div>
                        <h3>Entrepreneurship</h3>
                        <p>Vestibulum vitae aliquam nunc. Suspendisse mollis meteus ac tellus egestas pharetra.
                            Suspendisse at viverra purus. Pellentesque nec posuere ligula, eu congue leo. Integer
                            vuluptate tempor arcu. Vestibulum vuluptate.</p>

                    </div>

                </div>
            </div>
            <div class="course_features d-flex">
                <div class="card_border d-flex">
                    <i class="fa-solid fa-rocket"></i>
                    <div>
                        <h3>Accelerated learning</h3>
                        <p>Vestibulum vitae aliquam nunc. Suspendisse mollis meteus ac tellus egestas pharetra.
                            Suspendisse at viverra purus. Pellentesque nec posuere ligula, eu congue leo. Integer
                            vuluptate tempor arcu. Vestibulum vuluptate.</p>

                    </div>

                </div>
            </div>
            <div class="course_features d-flex">
                <div class="card_border d-flex">
                    <i class="fa-solid fa-thumbs-up"></i>
                    <div>
                        <h3>Productivity</h3>
                        <p>Vestibulum vitae aliquam nunc. Suspendisse mollis meteus ac tellus egestas pharetra.
                            Suspendisse at viverra purus. Pellentesque nec posuere ligula, eu congue leo. Integer
                            vuluptate tempor arcu. Vestibulum vuluptate.</p>

                    </div>

                </div>



            </div>
            <div class="course_features d-flex">
                <div class="card_border d-flex">
                    <i class="fa-solid fa-gear"></i>
                    <div>
                        <h3>Life Coaching</h3>
                        <p>Vestibulum vitae aliquam nunc. Suspendisse mollis meteus ac tellus egestas pharetra.
                            Suspendisse at viverra purus. Pellentesque nec posuere ligula, eu congue leo. Integer
                            vuluptate tempor arcu. Vestibulum vuluptate.</p>

                    </div>

                </div>
            </div>



        </div>

    </section>

    <section class="ratings">
        <div class="container d-flex space-evenly align-center">
            <div class="ratings_info">
                <i class="fa-solid fa-user-group"></i>
                <span>3195</span>
                <pre>Online Learner</pre>
            </div>
            <div class="ratings_info">
                <i class="fa-solid fa-film"></i>
                <span>23</span>
                <pre>Video Courses</pre>
            </div>
            <div class="ratings_info">
                <i class="fa-solid fa-image"></i>
                <span>437</span>
                <pre>Sliders & Images</pre>
            </div>
            <div class="ratings_info">
                <i class="fa-solid fa-thumbs-up"></i>
                <span>1440</span>
                <pre>Excellent Reviews</pre>
            </div>



        </div>
    </section>

    <section class="what_students_say text-center">
        <h2>What Student Say</h2>
        <div class="container d-flex justify-center align-center">
            <pre>&LeftArrow;</pre>
            <div class="thumbs">
                <img src="../assets/img/1-100x100.jpg" alt="">
                <img class="active_thumb" src="../assets/img/2-100x100.jpg" alt="">
                <img src="../assets/img/4-100x100.jpg" alt="">


            </div>
            <pre>&RightArrow;</pre>

        </div>
        <h3>Paints of the Future</h3>
        <div class="stars">
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>

        </div>
        <div class="container">
            <p>The response to your MasterStudy has been really overwhelming! Those who participated <br> in the
                workshop are
                spreading the word here on campus and the "buzz" is on. The VP of <br> Instruction wants you to come
                back!
                Her
                goal is to have more faculty trained. She also <br> wants to attend a workshop herself. Our sident told
                me
                Masterstudy needs to be the <br> cornerstone of our success program.</p>


        </div>






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
        line-height: 1.4;
        color: #222222;
        font-weight: 100;
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

.amazon_advertising {
    height: 70vh;
    background-image: url('../assets/img/slider_1-1917x607-1914x606.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;

    img {
        width: 30%;
        position: absolute;
        bottom: 0;
    }

    h2 {
        color: #F2B91E;
        font-size: 2.5rem;
        margin-bottom: 2rem;

    }

    p {
        color: #FFFF;
        font-size: 1.5rem;

    }

    .amazon_link {
        width: 10%;
        margin-bottom: 3rem;
        margin-left: -5rem;

    }






}

.why_my_courses {
    padding: 4rem;

    h2 {
        text-align: center;
        font-size: 2.5rem;
        padding-bottom: 2.5rem;


    }

    .course_features {
        width: calc(100% / 2);
        padding: 1rem;


        .card_border {
            border: 1px thin black;
            padding: 1.54rem;
            border-left: 7px solid #F2B91E;
            box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;

            h3 {
                font-size: 1.5rem;
                margin-bottom: 1rem;
            }
        }





        .fa-solid {
            padding-right: 2rem;
            font-size: 2rem;
            color: #F2B91E;
        }
    }

}

.ratings {
    height: 70vh;
    background-image: url('../assets/img/counter-1919x1101.jpg');
    background-repeat: no-repeat;
    background-size: cover;

    .ratings_info {


        .fa-solid {
            color: #FFFF;
            font-size: 2rem;


        }

        span {
            color: #EAB830;
            font-size: 2rem;
            padding-left: .8rem;




        }

        pre {
            color: #FFFF;
            font-size: 1rem;
            padding-left: 3rem;


        }
    }



}





.what_students_say {

    padding: 4rem 0;

    h2 {
        text-align: center;
        font-size: 2.5rem;
        padding-bottom: 2.5rem;


    }

    h3 {
        margin-top: 1rem;
    }

    .stars {
        color: #EAB830;
        margin-top: .3rem;
    }


    pre {
        font-size: 1.5rem;
        font-weight: 100;
    }

    .thumbs {
        padding: 0 2.5rem;

        img {
            padding: 0 .8rem;
            width: 25%;
            border-radius: 50%;
        }

        .active_thumb {
            width: 30%;

        }
    }

    p {
        margin: 2rem 0;
        line-height: 1.5;
        font-size: 1.2rem;
    }
}
</style>