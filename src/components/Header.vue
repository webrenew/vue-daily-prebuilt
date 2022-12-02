<template>
  <header class="header-container row">
    <div class="wrapper row">
      <div class="row">
        <img class="logo" alt="Daily logo" src="../assets/logo.png" />
        <h1>Welcome to Dayla</h1>
      </div>
      <div class="row">
        <a
          class="buttonish"
          target="_blank"
          href="https://dayla.io"
          >Home</a
        >
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
body{
  color: #fdfdfd;
  background-color: #0f172a;
}
.header-container {
  background-color: #0f172a;
  border-bottom: 1px solid #64748b;
  padding: 0 24px;
}
h1 {
  font-size: 16px;
  color: #fff;
}
.wrapper {
  max-width: 1200px;
  width: 100%;
  margin: auto;
  padding: 4px 0 4px 24px;
}
.logo {
  width: 111px;
  height: 32.5px;
  margin-right: 24px;
}
.divider {
  background: var(--grey);
  margin: 0 16px;
  display: block;
  height: 32px;
  width: 1px;
}
.icon {
  width: 24px;
}
a.buttonish {
  color: #fff;
  background:#8b5cf6 ;
  border: none;
  padding: 8px 16px;
  border-radius: .5rem;
  font-size: 1rem;
  line-height: 1;
  font-weight: regular;
  cursor: pointer;
  text-decoration: none;
}
a.buttonish:active {
  background: #121212;
}
</style>
