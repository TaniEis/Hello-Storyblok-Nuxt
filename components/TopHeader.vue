<template>
  <header class="top-header util__container">
    <nav class="top-header__col inline-block">
      <ul class="top-header__nav">
        <li :key="index" v-for="(navitem, index) in $store.state.settings.main_navi">
          <nuxt-link class="top-header__link" :to="navitem.link.cached_url">
            {{ navitem.name }}
          </nuxt-link>
        </li>
      </ul>
    </nav>
    <a href="/" class="top-header__col top-header__logo">
      <img src="http://a.storyblok.com/f/42016/1096x313/0353bf6654/logo2.png">
    </a>
    <nav class="top-header__col top-header__second-navi">
      <ul class="top-header__nav top-header__nav--right">
        <li>
          <nuxt-link class="top-header__link" to="/en/blog">English</nuxt-link>
        </li>
        <li>
          <nuxt-link class="top-header__link" to="/he/blog">Hebrew</nuxt-link>
        </li>
      </ul>
    </nav>
  </header>
</template>