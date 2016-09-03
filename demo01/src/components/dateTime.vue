<template>
  <div class="dateTime">
    <span>&lt;</span>
    <div>
      {{chooseDate}}
    </div>
    <span>&gt;</span>
  </div>
</template>

<script>
    export default {
        data() {
            return {
                chooseDate: '2016年9月3日'
            }
        },
        methods：{
            
        }
    }
</script>

<style scoped>
    h1 {
        color: #42b983;
    }
</style>