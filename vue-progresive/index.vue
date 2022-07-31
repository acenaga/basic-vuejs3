<template>
    <div>
        <h2> {{ text }}</h2>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Totam corporis a eius harum recusandae officia ex perspiciatis quibusdam quod, eligendi accusamus. Excepturi est sunt dolores atque perferendis consequatur similique dicta.</p>
    </div>
</template>



<script>
export default{
    data(){
        return{
            text: "hola vue"
        }
    },
};
</script>

<style>
    h2{
        color: red;
    }
</style>