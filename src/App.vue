<template>
<div>
  <div>Hello {{ value }}</div>
  <a href="/.auth/login/aad?post_login_redirect_uri=/api/echo">Log in</a>
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
