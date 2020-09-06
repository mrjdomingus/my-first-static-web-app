<template>
<div>
  <div>Hello {{ value }}</div>
  <a href="/login">Log in</a>
  <a href="/logout">Log out</a>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "World"
    };
  }
};
</script>
