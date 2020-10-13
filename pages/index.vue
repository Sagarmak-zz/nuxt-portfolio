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
        <div class="text-color-text text-xl md:text-3xl mt-2">
          <div>Hi! 👋</div>
          <div>
            I'm <span class="font-semibold italic underline">Sagar</span> & I
            build things for the <span class="italic">internet</span>
          </div>
        </div>
        <div class="text-color-text text-base md:text-xl mt-2">
          A proficient and passionate Web Developer, more inclined towards
          frontend, set out to build immersive and beautiful web apps through
          carefully crafted code and user-centric design.
        </div>
      </div>
      <div class="tech mt-6">
        <div
          class="about-title inline-block p-3 rounded text-lg md:text-lg text-accent-text bg-accent-bg"
        >
          /skillset
        </div>
        <div class="text-color-text text-base md:text-xl mt-2 flex items-center flex-wrap">
          <span>JavaScript</span>
          <div class="dot bg-accent rounded-full w-1 h-1 mx-2"></div>
          <span>Vue.js</span>
          <div class="dot bg-accent rounded-full w-1 h-1 mx-2"></div>
          <span>Nuxt</span>
          <div class="dot bg-accent rounded-full w-1 h-1 mx-2"></div>
          <span>TypeScript</span>
          <div class="dot bg-accent rounded-full w-1 h-1 mx-2"></div>
          <span>Angular</span>
          <div class="dot bg-accent rounded-full w-1 h-1 mx-2"></div>
          <span>PHP/Laravel</span>
          <div class="dot bg-accent rounded-full w-1 h-1 mx-2"></div>
          <span>NodeJS</span>
          <div class="dot bg-accent rounded-full w-1 h-1 mx-2"></div>
          <span>Git</span>
          <div class="dot bg-accent rounded-full w-1 h-1 mx-2"></div>
          <span>HTML/CSS</span>
        </div>
      </div>
    </div>
    <div class="footer">
      <div
        class="links flex items-center justify-center my-4 text-2xl text-accent"
      >
        <div class="dot bg-accent rounded-full w-1 h-1 mr-2"></div>
        <a
          href="https://drive.google.com/file/d/1RjaUSNimY7T_SQMhmw_dKkNAMNuPoFFb/view?usp=sharing"
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
          hid: "keywords",
          name: "keywords",
          content:
            "sagar, sagar makhija, sagarmak, netlify, frontend engineer, vuejs, javascript, nuxt, portfolio",
        },
        {
          hid: "name",
          name: "name",
          content: "Sagar Makhija | Frontend Engineer",
        },
        {
          hid: "description",
          name: "description",
          content: "Hi👋, I'm Sagar and this is my portfolio site",
        },
        {
          hid: "og:title",
          name: "og:title",
          content: "Sagar Makhija | Frontend Engineer",
        },
        {
          hid: "og:url",
          name: "og:url",
          content: "https://sagarmakhija.netlify.app/",
        },
        {
          hid: "og:description",
          name: "og:description",
          content: "Hi👋, I'm Sagar and this is my portfolio site"
        }
      ],
    };
  },
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
  list-style-type: disc;
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
