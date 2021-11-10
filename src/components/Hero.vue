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

            <p class="bottom">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Illum, odio repudiandae nostrum, consequuntur vitae ratione quas mollitia, maxime cupiditate quisquam laudantium quod facere nam ipsa culpa dolores animi modi repellat sunt totam vero quae ex.</p>

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
    width: 750px;
    height: 420px;
    margin:0 auto;
    padding: 50px;
    text-align: center;
    color: whitesmoke;
    background-image: url(https://images.ctfassets.net/nj2caiz7hkjw/5SdA2VBLpKUsAeumA2EsMa/537af179a90aba7a0ce3f823d9d69408/form-with-vuejs.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    border-radius: 25px;
}

h2{
    line-height: 120px;
    text-decoration: underline;
}

.option{
    height: 200px;
    display: flex;
    justify-content: space-evenly;
    align-content: space-between;
    flex-wrap: wrap;
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

.bottom{
    width: 100%;
}
</style>