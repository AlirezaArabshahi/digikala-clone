<template>
  <nav :class="$style.nav">
    <ul :class="$style['nav-category-list']">
      <li>
        <MegaMenu />
      </li>

      <li>
        <NuxtLink to="/">سوپر مارکت</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/">تخفیف‌ها و پیشنهاد‌ها</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/">دیجی‌کالای من</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/">دیجی‌پلاس</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/">دیجی‌کلاب</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/">دیجی‌پی</NuxtLink>
      </li>
    </ul>
  </nav>
</template>

<style module>
.nav {
  background-color: white;
  box-shadow: 0 2px 4px 0 rgba(113, 113, 113, 5%);
}
.nav-category-list {
  display: flex;
}
.nav-category-list > li {
  /* display: block; */
  list-style: none;
  padding-left: 1rem;
  font-size: 1rem;
}
.nav-category-list > li a {
  color: #616161;
  display: block;
  padding: 7px 12px 8px;
  text-decoration: none;
}

/* .NuxtLogo {
  animation: 1s appear;
  margin: auto;
} */

@keyframes appear {
  0% {
    opacity: 0;
  }
}
</style>
