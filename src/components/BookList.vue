<template>
  <div>
    <h1>{{ title }}</h1>
    <ul>
      <li>Harry Potter: And The Goblet of Fire</li>
      <li>The Great Gatsby</li>
      <li>Can't Hurt Me</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "BookList",

  data() {
    return {
      title: "All Books",
    };
  },
};
</script>

<style>
h1,
h2 {
  font-weight: normal;
}
</style>