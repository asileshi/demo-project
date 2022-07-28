<template>
<dev :key = "t.id" v-for = "t in tasks">

</dev>
</template>
<script>
export default{
    mane:"Tasks",
    props:{
        tasks:array
    }
}
</script>
