<script>


export default {
    name: 'CourseCard',
    data() {
        return {
            courseCardData: [
                {
                    title: 'How to be a DJ? Make Electronic Music',
                    category: 'Electronic',
                    mode: 'Advanced',
                    lectures: '8 lectures',
                    hours: '6 hours',
                    thumb: 'https://github.com/Shelbot77/proj-html-vuejs/blob/b7deb3f746edb81840af76c49f126d2cb28f58ee/src/assets/img/photo-1496307042754-b4aa456c4a2d-370x200.jpeg'
                },
                {
                    title: 'Nvidia and UE4 Technologies Practice',
                    category: 'Nvidia',
                    mode: 'Advanced',
                    lectures: '8 lectures',
                    hours: '6 hours',
                    thumb: 'https://github.com/Shelbot77/proj-html-vuejs/blob/b7deb3f746edb81840af76c49f126d2cb28f58ee/src/assets/img/12345-1-370x200.png'
                },
                {
                    title: 'Fashion Photography from professional',
                    category: 'fashion',
                    mode: 'Advanced',
                    lectures: '6 lectures',
                    hours: '6 hours',
                    thumb: 'https://github.com/Shelbot77/proj-html-vuejs/blob/b7deb3f746edb81840af76c49f126d2cb28f58ee/src/assets/img/photo-1491897554428-130a60dd4757-370x200.jpeg'



                },
                {
                    title: 'Design Instruments for Communication',
                    category: 'Communication',
                    mode: 'Intermediate',
                    lectures: '6 lectures',
                    hours: '6 hours',
                    thumb: 'https://github.com/Shelbot77/proj-html-vuejs/blob/b7deb3f746edb81840af76c49f126d2cb28f58ee/src/assets/img/photo-1416339134316-0e91dc9ded92-370x200.jpeg'
                },
                {
                    title: 'Make your Concept Right and Beautiful',
                    category: 'Art',
                    mode: 'intermediate',
                    lectures: '6 lectures',
                    hours: '6 hours',
                    thumb: '../assets/img/cathryn-lavery-67852-unsplash-370x200.jpg'
                },
                {
                    title: 'Road Bike Manual or How to Be a Champion',
                    category: 'Bicycling',
                    mode: 'Beginner',
                    lectures: '6 lectures',
                    hours: '6 hours',
                    thumb: 'https://github.com/Shelbot77/proj-html-vuejs/blob/b7deb3f746edb81840af76c49f126d2cb28f58ee/src/assets/img/photo-1475452779376-caebfb988090-370x200.jpeg'

                },
            ]
        }
    },


}

</script>

<template>
    <div class="course_card" v-for="card in courseCardData">
        <img :src="card.thumb" alt="">
        <h2>{{ card.category }}</h2>
        <h3>{{ card.title }}</h3>
        <span>{{ card.mode }}</span>





    </div>





</template>

<style lang="scss" scoped>
.course_card {
    width: calc(100% / 3);
    border: 2px dashed green;
    padding: 1rem;


}
</style>