<template>

    <div>
        <img src="https://picsum.photos/200/300" alt="">
    </div>

</template>
<script>

export default {
  name : 'JumboComponent'
}
</script>


<style scoped>
    div{
        width: 100%;
    }

    img{
            width: 100%;
            max-height: 400px;
            object-fit: cover;
        }
</style>
