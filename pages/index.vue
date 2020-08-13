index.vue

<template>
  <div class="container">
    <div class="page1 home">
      <div class="card hover:shadow-lg transition duration-500 ease-in p-6">
        <img
          class="mx-auto h-48 w-48 rounded-full object-cover shadow-xl"
          src="../assets/sagar.jpg"
          alt="profile image"
        />
        <div class="content mt-4">
          <h2 class="name text-5xl font-semibold">Sagar Makhija</h2>
          <div class="text-2xl">Frontend Engineer</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.container {
  margin: 0 auto;
}
.page1 {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.page2 {
  min-height: 40vh;
}
.footer {
  border: solid 1px black;
  min-height: 10vh;
}
</style>
