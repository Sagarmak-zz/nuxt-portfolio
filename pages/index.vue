index.vue

<template>
  <div class="container mx-auto">
    <div class="page1 home flex items-center justify-center">
      <div class="card hover:shadow-lg transition duration-500 ease-in p-6">
        <img
          class="mx-auto h-48 w-48 rounded-full object-cover shadow-2xl"
          src="../assets/sagar.jpg"
          alt="profile image"
        />
        <div class="content mt-4">
          <h2 class="name text-color-text text-3xl lg:text-5xl font-semibold">
            Sagar Makhija
          </h2>
          <div class="text-color-text text-lg lg:text-2xl">
            Frontend Engineer
          </div>
          <div class="text-background-lighter animation">
            <i class="fas fa-chevron-down"></i>
          </div>
        </div>
      </div>
    </div>
    <div class="page2 about mb-20">
      <div class="me">
        <div
          class="about-title inline-block p-3 rounded text-lg md:text-lg text-accent-text bg-accent-bg"
        >
          /me
        </div>
        <div class="text-color-text md:text-3xl mt-2">
          <div>Hi! 👋</div>
          <div>
            I'm <span class="font-semibold italic underline">Sagar</span> & I
            build things for the <span class="italic">internet</span>
          </div>
        </div>
        <div class="text-color-text text-base md:text-xl mt-2">
          I'm a frontend engineer based out of AMD and BLR with the main focus on crafting
          clean & user‑friendly experiences. I have a passion for web design and
          love to create for web which strives to build immersive and beautiful
          web applications through carefully crafted code and user-centric
          design bringing the ideas to life.
        </div>
      </div>
      <div class="tech mt-6">
        <div
          class="about-title inline-block p-3 rounded text-lg md:text-lg text-accent-text bg-accent-bg"
        >
          /skillset
        </div>
        <div class="text-color-text text-base md:text-xl mt-2">
          <ul class="flex flex-wrap list-inside">
            <li class="w-1/3">JavaScript</li>
            <li class="w-1/3">VueJS</li>
            <li class="w-1/3">Nuxt</li>
            <li class="w-1/3">TypeScript</li>
            <li class="w-1/3">Angular</li>
            <li class="w-1/3">PHP/Laravel</li>
            <li class="w-1/3">NodeJS</li>
            <li class="w-1/3">Git</li>
            <li class="w-1/3">HTML/CSS</li>
          </ul>
        </div>
      </div>
    </div>
    <div class="footer">
      <div
        class="links flex items-center justify-center my-4 text-2xl text-accent"
      >
        <div class="dot bg-accent rounded-full w-1 h-1 mr-2"></div>
        <a
          href="https://www.linkedin.com/in/sagarmak/"
          target="_blank"
          class="icon mx-3 hover:text-teal-300 transition duration-300 ease-in-out"
        >
          <i class="far fa-file-alt"></i>
        </a>
        <a
          href="https://www.linkedin.com/in/sagarmak/"
          target="_blank"
          class="icon mx-3 hover:text-teal-300 transition duration-300 ease-in-out"
        >
          <i class="fab fa-linkedin-in"></i>
        </a>
        <a
          href="mailto:sagar1309@live.com"
          target="_blank"
          class="icon mx-3 hover:text-teal-300 transition duration-300 ease-in-out"
        >
          <i class="far fa-envelope"></i>
        </a>
        <a
          href="https://twitter.com/Sagarmak"
          target="_blank"
          class="icon mx-3 hover:text-teal-300 transition duration-300 ease-in-out"
        >
          <i class="fab fa-twitter"></i>
        </a>
        <a
          href="https://t.me/Sagarmak"
          target="_blank"
          class="icon mx-3 hover:text-teal-300 transition duration-300 ease-in-out"
        >
          <i class="fab fa-telegram-plane"></i>
        </a>
        <div class="dot bg-accent rounded-full w-1 h-1 ml-2"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ["lightTheme"],
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
  text-align: center;
}
.footer {
  min-height: 10vh;
}
ul.flex li {
  list-style-type: circle;
}
.animation {
  animation: in-out 2000ms ease-in-out 0s infinite normal forwards;
}

@keyframes in-out {
  0%,
  100% {
    opacity: 1;
  }
  50% {
    opacity: 0.2;
  }
}
</style>
