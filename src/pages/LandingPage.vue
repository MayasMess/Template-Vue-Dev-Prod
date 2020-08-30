<template>
  <body class="body-style">
    <h1 class="text-style-one"> This is your <b>Vue</b> Frontend</h1>
    <h2 class="text-style-two"> Ready for production</h2>
  </body>
</template>

<script>
export default {

}
</script>

<style>
    .body-style{
        height:100vh;
        width:100vw;
        background:#f6f5f7;
        display:grid;
        overflow:hidden;
    }
    .text-style-one{
        font-size: 3vw;
        text-align:center;
        align-self:end
    }
    .text-style-two{
        font-size: 2vw;
        text-align:center;
    }
</style>