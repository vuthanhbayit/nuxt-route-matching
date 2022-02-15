<template>
<div>noi dung {{$route.params}}</div>
</template>

<router>
{
path: '/noi-dung-:slug'
}
</router>

<script>
export default {
  name: "noi-dung-slug"
}
</script>

<style scoped>

</style>
