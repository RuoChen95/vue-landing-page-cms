<template>
    <div class="cms">
        <h1 class="title">Landing page</h1>
    </div>
</template>

<script>
  export default {
    name: 'cms',
    props: {},
    data() {
      return {
        data: '',
      };
    },
  };
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less" type="text/less">
    div.cms {
        width: 550px;
        margin: 0 auto;
        h1.title {
            margin: 0 auto;
            font-size: 100px;
            text-align: center;
            font-weight: 100;
            color: rgba(175, 47, 47, 0.15);
        }
    }
</style>
<style lang="less" type="text/less">
    body {
        background-color: #f5f5f5;
        font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
    }
</style>
