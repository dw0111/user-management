<template>
  <nav class="navigation">
    <section class="nav_block">
      <img
        class="nav_logo"
        src="../assets/logo.png"
        alt=""
        width="30"
        height="30"
      >
      <div class="nav_entry">{{userName}}</div>
    </section>
    <section class="nav_block">
      <a
        href="/benutzer"
        class="nav_link"
      >Benutzer</a>
      <a
        href="/teilnahmeerklärung"
        class="nav_link"
      >Teilnahmeerklärung</a>
    </section>
  </nav>
</template>

<script>
export default {
  name: "Navigation",
  props: ["userName"]
};
</script>

<style scoped>
.navigation {
  background-color: orange;
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin: 0;
  padding: 0.8em;
}
.nav_block {
  display: flex;
  gap: 1em;
}

.nav_entry {
  text-justify: center;
}

.nav_link {
  border: 1px solid lightgoldenrodyellow;
  background-color: lightgoldenrodyellow;
  border-radius: 0.3rem;
  padding: 0.5rem;
  text-decoration: none;
  cursor: pointer;
  font-size: 0.8rem;
}

.nav_button {
  border: none;
  background-color: lightgoldenrodyellow;
  border-radius: 0.2rem;
  padding: 0.5rem;
}
</style>
