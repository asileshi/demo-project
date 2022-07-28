<template>
<button @click = "temp" :style = "{background:color}" 
class = "btn">{{text}}</button>
</template>
<script>
export default{
    name :"Button",
    props:{
        text:String,
        color:String,
    },
    methods:{
        temp(){
            console.log('the task was added sucessfully')
        }
    }
  
}
</script>
