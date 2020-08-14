index.vue

<template>
  <div class="container mx-auto">
    <div class="page1 home items-center">
      <div class="card hover:shadow-lg transition duration-500 ease-in p-6">
        <img
          class="mx-auto h-48 w-48 rounded-full object-cover shadow-xl"
          src="../assets/sagar.jpg"
          alt="profile image"
        />
        <div class="content mt-4">
          <h2 class="name text-3xl lg:text-5xl font-semibold dark:text-orange-400">Sagar Makhija</h2>
          <div class="text-lg lg:text-2xl">Frontend Engineer</div>
        </div>
      </div>
    </div>
    <div class="page2 about">
      <div class="me">
        <div class="about-title bg-green-200 w-16 p-3 text-lg text-teal-700">
          /me
        </div>
        <div class="text-xl mt-2">
          Hi, I'm <span class="font-semibold italic underline">Sagar</span>. I'm
          a frontend engineer based out of Ahmedabad and Banglore. I've been
          developing web apps since 2 years mainly in javascript and other
          cutting edge technologies. I also design my own websites for
          small/side projects.
        </div>
      </div>
      <div class="tech mt-6">
        <div class="about-title bg-green-200 w-20 p-3 text-lg text-teal-700">
          /tech
        </div>
        <div class="text-xl mt-2">
          JavaScript | VueJS | Nuxt | TypeScript | Angular | PHP/Laravel |
          NodeJS | Git | HTML/CSS
        </div>
      </div>
    </div>
    <div class="footer">
      <div
        class="links flex content-center justify-center my-4 text-2xl text-teal-400"
      >
        <a
          href="https://www.linkedin.com/in/sagarmak/"
          target="_blank"
          class="icon mx-3 hover:text-teal-700"
        >
          <i class="far fa-file-alt"></i>
        </a>
        <a
          href="https://www.linkedin.com/in/sagarmak/"
          target="_blank"
          class="icon mx-3 hover:text-teal-700"
        >
          <i class="fab fa-linkedin-in"></i>
        </a>
        <a
          href="mailto:sagar1309@live.com"
          target="_blank"
          class="icon mx-3 hover:text-teal-700"
        >
          <i class="far fa-envelope"></i>
        </a>
        <a
          href="https://twitter.com/Sagarmak"
          target="_blank"
          class="icon mx-3 hover:text-teal-700"
        >
          <i class="fab fa-twitter"></i>
        </a>
        <a
          href="https://t.me/Sagarmak"
          target="_blank"
          class="icon mx-3 hover:text-teal-700"
        >
          <i class="fab fa-telegram-plane"></i>
        </a>
      </div>
      <!-- <div>&copy; 2020 - Sagar Makhija</div> -->
    </div>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "Sagar Makhija | Frontend Engineer",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Best place for corny dad jokes"
        }
      ]
    };
  }
};
</script>

<style>
.page1 {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  /* align-items: center; */
  text-align: center;
}
.page2 {
  min-height: 40vh;
}
.footer {
  min-height: 10vh;
}
</style>
