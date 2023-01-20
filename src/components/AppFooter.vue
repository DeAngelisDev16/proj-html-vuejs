<script>

export default {
    name: 'AppFooter',

}


</script>

<template>
    <footer>
        <div class="container d-flex">
            <div class="col-3">
                <h3> About</h3>
                <p>Masterstudy is Education Wordpress theme featured by Lerning Management system (LMS) for online
                    education. <br> Developed by Stylemix Themes.
                </p>
                <i class="fa-brands fa-facebook"></i>
                <i class="fa-brands fa-twitter"></i>
                <i class="fa-brands fa-instagram"></i>




            </div>
            <div class="col-3">
                <h3> contact</h3>
                <p id="address">USA,California 20, First Avenue, California</p>
                <span>Tel.+1 212 458 300 32</span>
                <span>Fax: +1 212 375 2414</span>
                <span id="email">info@masterstudy.com</span>

            </div>
            <div class="col-3">
                <h3> pages</h3>
                <ul class="d-flex flex-wrap">
                    <li><a href="#">Blog</a></li>
                    <li><a href="#">Courses</a> </li>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Membership A...</a></li>
                    <li><a href="#">Shortcodes</a></li>
                    <li><a href="#">Typhograpy</a></li>





                </ul>

            </div>
            <div class="col-3">
                <h3> blog</h3>
                <div class="posts d-flex">
                    <img src="../assets/img/photo-1517520287167-4bbf64a00d66-50x50.jpeg" alt="">
                    <div class="post_title">
                        <h4>Our main target is to "Developing Youself as a Leader"</h4>
                        <span>- August 9,2018</span>
                    </div>
                </div>
                <div class="posts d-flex">
                    <img src="../assets/img/photo-1490376840453-5f616fbebe5b-50x50.jpeg" alt="">
                    <div class="post_title">
                        <h4>Those Other College Expenses You Aren't Thinking About</h4>
                        <span>- June 3,2015</span>
                    </div>
                </div>




            </div>





        </div>

    </footer>



</template>

<style lang="scss" scoped>
footer {

    background-color: #F2B91E;
    padding: 3rem 0;

}

.col-3 {
    width: calc(100% / 4);
    padding: 1rem;

    h3 {
        text-transform: uppercase;
    }

    p {
        line-height: 1.3;
        margin-top: 1.5rem;
    }

    .fa-brands {
        padding: .5rem;
        margin-left: -.6rem;
    }

    #address {
        margin-bottom: 1rem;
        line-height: 1.3;
    }

    span {
        display: block;
    }

    #email {
        margin-top: .5rem;
    }

    ul {
        margin-top: 1.5rem;

        li {
            width: calc(100% / 2);
            padding: .5rem 0;

            a {
                text-decoration: none;
                color: black;
            }

            a:hover {
                color: white;
            }

        }






    }

    .posts {
        margin-top: 1.5rem;

        img {
            width: 70%;
        }

        .post_title {
            padding-left: .8rem;
        }

        .post_title:hover {
            color: white;
            cursor: pointer;
        }
    }


}
</style>