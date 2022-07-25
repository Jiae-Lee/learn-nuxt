<template>
  <div>
    <header class="title">
      <h1>
        <NuxtLink class="logo" to="/">Nuxt Shopping</NuxtLink>
      </h1>
    </header>
    <Nuxt />
  </div>
</template>

<script>
export default {
}
</script>

<style scope>
/* 헤더 관련 스타일 */
header {
  height: 60px;
  display: flex;
  align-items: center;
  padding: 0 0.5rem;
}
.logo {
  font-weight: 900;
}
.logo:visited {
  color: inherit;
}

</style>