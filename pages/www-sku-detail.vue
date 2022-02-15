<template>
<div>{{$route.params}}</div>
</template>

<router>
{
path: '/:slug'
}
</router>

<script>
export default {
  name: "sku-detail"
}
</script>

<style scoped>

</style>
