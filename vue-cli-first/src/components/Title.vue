<template>
    <div>
        <p>
            {{msg}}
        </p>
    </div>
</template>
<script>
export default {
    name: 'Title',
    props: {
        msg:String,
    }
}
</script>
<style scoped>
div {
    font-size: 2rem;
    color: red;
    left: 50%;
    width: 50vw;
    background-color: blue;
    height: 20vh;
    margin: 0 auto;
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>