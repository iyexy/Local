<template>
<a class="add" href="/createtopic"><img src="../assets/add.png"></a>
</template>
<script>
export default {
  name: 'addbtn'
}
</script>
<style scoped>
.add {
    width: 25px;
    height: 25px;
    position: fixed;
    bottom: 80px;
    right: 10px;
    border-radius: 50%;
    border: none;
}
.add img {
    width: 25px;
    height: 25px;
}
</style>