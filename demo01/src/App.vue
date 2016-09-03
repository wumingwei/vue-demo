<template>
  <div class="container">
    this is  vue demo01!
  </div>
</template>

<script>
    import Hello from './components/Hello'

    export default {
        components: {
            Hello
        }
    }
</script>

<style>
    html {
        height: 100%;
    }
    
    body {
        display: flex;
        align-items: center;
        justify-content: center;
        height: 100%;
    }
    
    .container {
        color: #2c3e50;
        margin-top: -100px;
        max-width: 600px;
        font-family: Source Sans Pro, Helvetica, sans-serif;
        text-align: center;
    }
</style>