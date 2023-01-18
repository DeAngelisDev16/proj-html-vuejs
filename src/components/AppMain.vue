<script>

export default {
    name: 'AppMain'
}


</script>

<template>
    <section class="jumbo">
        <h2>jumbo section</h2>
    </section>

    <section class="founder_info">
        <div class="container">
            <h2>founder info section</h2>
        </div>
    </section>

    <section class="new_courses">
        <div class="courses_container">
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





</template>

<style lang="scss" scoped>
.jumbo {
    height: 70vh;
    background-color: aqua;
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
        display: flex;
        flex-wrap: wrap;

        .course_card {
            width: calc(100% / 3);
        }
    }
}
</style>