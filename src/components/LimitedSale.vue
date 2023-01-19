<script>


export default {
    name: 'LimitedSale',

}

</script>

<template>
    <div class="discount">
        <h2><span>Limited Sale:</span>All courses with 55% off</h2>
        <input type="email" size="55" placeholder="Enter your email">
        <button>Subscribe</button>

    </div>



</template>

<style lang="scss" scoped>
.discount {
    width: 75%;
    height: 170px;
    background-color: #F2B91E;
    position: absolute;
    bottom: 85%;
    left: 15%;
    padding: 2rem;
    border-radius: 1rem;

    span {
        color: white;
        padding-right: .3rem;

    }

    input,
    button {
        margin-top: 1.5rem;
        border-radius: 2rem;
        height: 2.5rem;



    }

    button {
        margin-left: -3.5rem;
        padding: .5rem;
        background-color: #2D4649;
        color: white;




    }

    input {
        padding: .5rem;
    }





}
</style>
