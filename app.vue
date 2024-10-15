<script setup lang="ts">
  import '~/assets/css/app.css'
</script>
<template>

  <main>
    <div class="menu">
      <ul>
        <li>
          <NuxtLink to="/">/</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/about">/about</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/contact">/contact</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/users/samit?type=admin&page=1">/users/samit?type=admin&page=1</NuxtLink>
        </li>
      </ul>
    </div>
    <div class="content">
      <NuxtPage />
    </div>
  </main>
  
</template>
