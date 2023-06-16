<template>
  <div>
    <div>user detail</div>
    <div>{{ $route.params.id }}</div>
    <div>{{ $route.query.fname ?? "" }}</div>
  </div>
</template>

<script>
export default {
  name: "user-detail",
  created() {
    console.log(this.$route);
  },
};
</script>

<style></style>
