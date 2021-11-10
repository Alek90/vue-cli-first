<template>
    <div class="hero">

        <h2>JUMBOTRON PER VUE CLI</h2>

        <div class="option">

            <p class="left">
                Lorem ipsum dolor sit amet.
            </p>

            <p class="right">
                Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dicta reprehenderit nobis vitae cumque repudiandae nisi est et.
            </p>

        </div>

    </div>
</template>

<script>
export default {
    name: 'Hero'
}
</script>

<style scoped>
.hero{
    width: 570px;
    height: 300px;
    margin:0 auto;
    padding: 35px;
    text-align: center;
    color: whitesmoke;
    background-image: url(https://images.ctfassets.net/nj2caiz7hkjw/5SdA2VBLpKUsAeumA2EsMa/537af179a90aba7a0ce3f823d9d69408/form-with-vuejs.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    border-radius: 25px;
}

h2{
    line-height: 135px;
    text-decoration: underline;
}

.option{
    display: flex;
    justify-content: space-evenly;
}

p{
    line-height: 1.5rem;
}

.left{
    width: 30%;
}

.right{
    width: 55%;
}
</style>