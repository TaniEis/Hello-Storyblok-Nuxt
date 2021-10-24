<template>
  <header class="container mx-auto flex items-center">
    <nav>
      <ul class="list-reset flex justify-between flex-1 md:flex-none items-center">
        <li class="mr-2">
          <nuxt-link
            class="inline-block py-2 px-2 no-underline hover:underline"
            to="/">
            Home
          </nuxt-link>
        </li>
        <li class="mr-2">
          <nuxt-link
            class="inline-block py-2 px-2 no-underline hover:underline"
            to="/articles">
            Blog
          </nuxt-link>
        </li>
      </ul>
    </nav>
    <div class="flex-1">
      <h1 href="/" class="font-extrabold text-3xl md:text-2xl text-center">Hello Storyblok & Nuxt</h1>
    </div>
    <nav>
      <ul class="list-reset flex justify-between flex-1 md:flex-none items-center">
        <li class="mr-2">
          <nuxt-link
            class="inline-block py-2 px-2 no-underline hover:underline"
            to="/">
            English
          </nuxt-link>
        </li>
        <li class="mr-2">
          <nuxt-link
            class="inline-block py-2 px-2 no-underline hover:underline"
            to="/he">
            Hebrew
          </nuxt-link>
        </li>
      </ul>
    </nav>
  </header>
</template>
