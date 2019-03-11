<template>
  <header class="header">
    <h1>TodoList</h1>
    <div id="nav">
      <router-link to="/">
        Home
      </router-link> |
      <router-link to="/about">
        About
      </router-link> |
      <router-link to="/about2">
        About2
      </router-link>
    </div>
  </header>
</template>


<script>
export default {
  name: "Header"
}
</script>

<style lang="scss" scoped>

    $bgColor: black;
    $textColor: #fff;
    .header {
        background: $bgColor;
        color: $textColor;
        text-align: center;
        padding: 10px;
    }

    .header a {
        color: $textColor;
        padding-right: 5px;
        text-decoration: none;
    }
</style>



